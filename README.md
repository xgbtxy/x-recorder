# x-recorder · X 推文记录师

从 X（Twitter）推文里摘有价值的关键点，做成可检索的记录库。

**硬规则：每一条记录必须有可点开的出处链接（优先 X status；已批 TG 频道可用消息链接并标明平台）。没有可核对出处的不入库。**

和 `project-collect` 的分工：

| | x-recorder | project-collect |
|--|------------|-----------------|
| 粒度 | 一条推文 / 一条线索 | 一个项目条目 |
| 必填 | X 链接 | 仓库或项目页 |
| 内容 | VPN、网安工具、AI 资源等「发现」 | 经整理的项目短档 |

## 分类目录

- [`records/security-tools/`](./records/security-tools/) — 网络安全 / 逆向 / 攻防工具
- [`records/vpn-proxy/`](./records/vpn-proxy/) — VPN / 代理 / 网络访问相关（优先：网速向「机场/订阅」公开测速与评测；开源客户端仍收；不写绕过教程）
- [`records/ai-resources/`](./records/ai-resources/) — 模型、Agent、提示、数据集、AI 工具
- [`records/other/`](./records/other/) — 暂不好归类但有价值的（含低价卡网/优惠渠道线索，标题可标 `[低价]`）
- 低价线草稿目录：[`drafts/deals/`](./drafts/deals/)

新条目用 [`templates/record.md`](./templates/record.md)。

运维与审推纪律见 [`docs/OPS.md`](./docs/OPS.md)（草稿目录、专员边界、审计清单、建小弟标准）。

## 索引

| 标题 | 分类 | 状态 | 来源 X |
|------|------|------|--------|
| ASC 介绍帖（Agent 反编译 / Arsenal 叙事） | security-tools | 已核（主张未全证） | https://x.com/MGAldys4/status/2098541143474749913 |
| JADX-AI-MCP | security-tools | 已核 | https://x.com/zinja_coder/status/2085396884273914160 |
| BurpNinja | security-tools | 已核 | https://x.com/altafpasha_h/status/2093771074391732639 |
| Claude+MCP×JADX/IDA 案例 | security-tools | 已核 | https://x.com/taidh_/status/2072863860625989984 |
| apktool-mcp-server | security-tools | 已核 | https://x.com/zinja_coder/status/1923636620420350411 |
| Beerus Framework（Android） | security-tools | 已核 | https://x.com/ptdbugs/status/2095187404860616908 |
| frida-ssl-bypass | security-tools | 已核 | https://x.com/Jayson_security/status/2101324384786845903 |
| Perenio App Analysis | security-tools | 已核 | https://x.com/ereksonas/status/2102823621412413778 |
| Android-Pentesting-Skill | security-tools | 已核 | https://x.com/Dinosn/status/2051858764312023244 |
| android-reverse-engineering-skill | security-tools | 已核 | https://x.com/Dinosn/status/2030635793442558363 |
| renef-skills | security-tools | 已核 | https://x.com/Dinosn/status/2070800787542864054 |
| ASC 实战叙事（作者自述 root） | security-tools | 已核（主张未全证） | https://x.com/MGAldys4/status/2100144298029449331 |
| reverse-skill 推荐 | security-tools / ai-resources | 已核 | https://x.com/bigaiguy/status/2102329454173602054 |
| ToCode · Agent 逆向导出源码 | ai-resources（兼 security-tools） | 已核 | https://x.com/buzz3r_/status/2063486884806832200 |
| T3MP3ST · Agent 红队 harness | security-tools（兼 ai-resources） | 已核 | https://x.com/elder_plinius/status/2073579120135664102 |
| Maigret 0.6.6（TG） | security-tools | 已核 | https://t.me/offensiveosint/193 |
| Matkap（JADX MCP × 恶意 TG bot 狩猎） | security-tools | 已核 | https://x.com/0x6rss/status/2092295504533012775 |
| kahlo-mcp（Frida MCP · Android Agent） | security-tools | 已核 | https://x.com/tom_doerr/status/2035619264120467536 |
| Awesome-LLM4Cybersecurity（TG） | ai-resources | 已核 | https://t.me/tsecrecord/1557 |
| NLA on open models：Anthropic × Neuronped | ai-resources | 已核 | https://x.com/AnthropicAI/status/2052435460220211397 |
| skills CLI：跨 Agent 安装 Skill 包（类 npm） | ai-resources | 已核 | https://x.com/rauchg/status/2012345679721771474 |
| Cursor `/orchestrate`：递归派生多 Agent 的官方 Sk | ai-resources | 已核 | https://x.com/cursor_ai/status/2052432778743210127 |
| Cursor Agent Skills：SKILL.md 扩展 Agent 能力 | ai-resources | 已核 | https://x.com/cursor_ai/status/2014753596223770841 |
| HyperFrames：可 `npx skills add` 的 HTML→MP | ai-resources | 已核 | https://x.com/HeyGen/status/2044827454460871072 |
| HTML Explainer：本地 HTML→MP4 Skill 流水线 | ai-resources | 已核 | https://x.com/QingQ77/status/2103499013391593718 |
| Claude Code /simplify 与 /batch Skills | ai-resources | 已核 | https://x.com/bcherny/status/2027534984534544489 |
| FineWeb 预训练数据集 | ai-resources | 已核 | https://x.com/gui_penedo/status/1781953413938557276 |
| Google Workspace CLI + Agent Skills | ai-resources | 已核 | https://x.com/addyosmani/status/2029372736267805081 |
| last30days Agent Skill | ai-resources | 已核 | https://x.com/mvanhorn/status/2092629365045559547 |
| OpenClaw 2.0 | ai-resources | 已核 | https://x.com/openclaw/status/2094266903204434431 |
| Omnigent meta-harness | ai-resources | 已核 | https://x.com/omnigent_ai/status/2100610102013071364 |
| Cloudflare API MCP（Code Mode） | ai-resources | 已核 | https://x.com/Jilles/status/2094833926879560031 |
| datasette-mcp | ai-resources | 已核 | https://x.com/simonw/status/2102916558712705427 |
| funes 本地 Agent 记忆 | ai-resources | 已核 | https://x.com/lancedb/status/2102079650839306613 |
| Claude Code 支持 AGENTS.md | ai-resources | 已核 | https://x.com/trq212/status/2101009392611278961 |
| SmolDataEnvs RL 数据集 | ai-resources | 已核 | https://x.com/adithya_s_k/status/2103181855214432556 |
| LensVLM-9B（Apple） | ai-resources | 已核 | https://x.com/victormustar/status/2102824162511503669 |
| FLUX 3 Action | ai-resources | 已核 | https://x.com/bfl_ai/status/2102816874782241174 |
| Pruna-Qwen-Image-2.1 | ai-resources | 已核 | https://x.com/PrunaAI/status/2103152549809311816 |
| Claude Marketplace | ai-resources | 已核 | https://x.com/claudeai/status/2102840851538080172 |
| The Stack v3 代码预训练数据集 | ai-resources | 已核 | https://x.com/anton_lozhkov/status/2080254608639701222 |
| Harbor Agent eval harness | ai-resources | 已核 | https://x.com/alexgshaw/status/2100296774955237438 |
| Context7 Search 文档 grounding | ai-resources | 已核 | https://x.com/Context7AI/status/2102508908095123767 |
| Playwright MCP / CLI | ai-resources | 已核 | https://x.com/playwrightweb/status/2101099626401067367 |
| llama.cpp v0.5.0 | ai-resources | 已核 | https://x.com/ggml_org/status/2102864024358776969 |
| OpenCode 开源 Coding Agent | ai-resources | 已核 | https://x.com/opencode/status/2077148766092558570 |
| Firecrawl MCP | ai-resources | 已核 | https://x.com/firecrawl/status/2066918976689754148 |
| ElevenLabs MCP | ai-resources | 已核 | https://x.com/ElevenLabs/status/1909300782673101265 |
| browse.sh Browserbase Skills | ai-resources | 已核 | https://x.com/browserbase/status/2056404332824944970 |
| Cline SDK | ai-resources | 已核 | https://x.com/cline/status/2054580767779700775 |
| NVIDIA-Verified Agent Skills | ai-resources | 已核 | https://x.com/NVIDIAAI/status/2087887993025843391 |
| Crush 终端 Coding Agent | ai-resources | 已核 | https://x.com/charmcli/status/1985374223783621051 |
| Goose AAIF 本机 Agent | ai-resources | 已核 | https://x.com/goose_oss/status/2062310564660224145 |
| Notion MCP | ai-resources | 已核 | https://x.com/NotionHQ/status/2095923091134206448 |
| Linear MCP Inbox | ai-resources | 已核 | https://x.com/linear/status/2102431323889775037 |
| X Hosted MCP | ai-resources | 已核 | https://x.com/XDevelopers/status/2071752389183647758 |
| Supabase Agent Skills | ai-resources | 已核 | https://x.com/supabase/status/2014375032261156943 |
| Graphify Skill/MCP | ai-resources | 已核 | https://x.com/safishamsii/status/2102396664577192252 |
| Jules Tools CLI | ai-resources | 已核 | https://x.com/julesagent/status/1973812188977508755 |
| GitHub Remote MCP GA | ai-resources | 已核 | https://x.com/GHchangelog/status/1963634192010379338 |
| Chrome DevTools MCP | ai-resources | 已核 | https://x.com/ChromiumDev/status/1970505063064825994 |
| Vercel MCP | ai-resources | 已核 | https://x.com/vercel_dev/status/1954190678596157824 |
| Hugging Face MCP | ai-resources | 已核 | https://x.com/reach_vb/status/1942247029515735263 |
| Agent Plugins（OpenAI） | ai-resources | 已核 | https://x.com/OpenAIDevs/status/2085398373511918022 |
| next-devtools-mcp | ai-resources | 已核 | https://x.com/gao_jude/status/1982942366727372843 |
| mini-SWE-agent | ai-resources | 已核 | https://x.com/KLieret/status/1948375289014173791 |
| Stripe MCP | ai-resources | 已核 | https://x.com/StripeDev/status/1892685153987592526 |
| GitHub Copilot Agent Skills | ai-resources | 已核 | https://x.com/github/status/2003229314112770052 |
| ChatGPT MCP Tools | ai-resources | 已核 | https://x.com/OpenAIDevs/status/1965807401745207708 |
| Replit Agent MCP | ai-resources | 已核 | https://x.com/Replit/status/1998085186513473803 |
| Figma MCP（use_figma + Skills） | ai-resources | 已核 | https://x.com/figma/status/2036434766661296602 |
| Prisma MCP | ai-resources | 已核 | https://x.com/prisma/status/1905590716480585815 |
| Scenario GameDev OS Skills | ai-resources | 已核 | https://x.com/Scenario_gg/status/2103460573895659982 |
| Cua Driver MCP + Skill | ai-resources | 已核 | https://x.com/trycua/status/2103498682532253734 |
| Datadog MCP Server（Code Execution GA） | ai-resources | 已核 | https://x.com/datadoghq/status/2102849508073685485 |
| Datadog Pup CLI（Agent 向） | ai-resources | 已核 | https://x.com/daisuke/status/2024506290421260366 |
| Sentry MCP Server Monitoring | ai-resources | 已核 | https://x.com/sentry/status/1970911516716306813 |
| Claude Opus 5.5 | ai-resources | 已核 | https://x.com/claudeai/status/2102435511222890900 |
| Perplexity Portable Computer（本地 Agent） | ai-resources | 已核 | https://x.com/perplexity_ai/status/2103161414919872628 |
| Grafana MCP + gcx CLI | ai-resources | 已核 | https://x.com/grafana/status/2082162797366935823 |
| New Relic AI MCP Server | ai-resources | 已核 | https://x.com/newrelic/status/1990876449075515478 |
| PagerDuty MCP Server | ai-resources | 已核 | https://x.com/pagerduty/status/2099963502710440067 |
| Chronosphere MCP Server（GA） | ai-resources | 已核 | https://x.com/chronosphereio/status/1988645524417790169 |
| Zed Delta（公测） | ai-resources | 已核 | https://x.com/zeddotdev/status/2100223348563194123 |
| JetBrains Air | ai-resources | 已核 | https://x.com/kskrygan/status/2102349426857578994 |
| OpenHands Agent Canvas | ai-resources | 已核 | https://x.com/OpenHandsDev/status/2095598358853284115 |
| Pi coding agent（Earendil） | ai-resources | 已核 | https://x.com/badlogicgames/status/2100248057413558600 |
| Hermes Agent（Nous） | ai-resources | 已核 | https://x.com/NousResearch/status/2068056504125563317 |
| Remotion Skills 2.0 | ai-resources | 已核 | https://x.com/Remotion/status/2089295038932996194 |
| mattpocock/skills v1.3（cooking） | ai-resources | 已核 | https://x.com/mattpocockuk/status/2103038241578397823 |
| Qwen-Image-2.1（基座） | ai-resources | 已核 | https://x.com/Alibaba_Qwen/status/2101659302792679789 |
| DeepSeek-V4 Preview（开源） | ai-resources | 已核 | https://x.com/deepseek_ai/status/2047516922263285776 |
| Marketing Skills（第三方包） | ai-resources | 已核 | https://x.com/coreyhainesco/status/2092344373908550142 |
| Skills CLI ← Notion 源 | ai-resources | 已核 | https://x.com/vercel_dev/status/2100635727331811669 |
| transitions.dev Skills | ai-resources | 已核 | https://x.com/Jakubantalik/status/2077790361993236496 |
| Gemma 4（开源） | ai-resources | 已核 | https://x.com/GoogleDeepMind/status/2039735446628925907 |
| Muse Glimmer 30B（本地 Agent） | ai-resources | 已核 | https://x.com/AIatMeta/status/2086757844544811485 |
| career-ops Skills | ai-resources | 已核 | https://x.com/santifer/status/2041403685696053741 |
| Archify Skills | ai-resources | 已核 | https://x.com/midudev/status/2094425974406320207 |
| Impeccable Skills | ai-resources | 已核 | https://x.com/ivanleomk/status/2041371674248147047 |
| ECC（Everything Claude Code） | ai-resources | 已核 | https://x.com/nicos_ai/status/2060766377670013188 |
| vercel-labs/agent-skills | ai-resources | 已核 | https://x.com/rauchg/status/2011179888976544134 |
| anthropics/skills | ai-resources | 已核 | https://x.com/alexalbert__/status/1978877498411880550 |
| Taste Skill | ai-resources | 已核 | https://x.com/LexnLin/status/2100842256630534283 |
| ui-ux-pro-max | ai-resources | 已核 | https://x.com/Voxyz_ai/status/2071928115052335364 |
| Caveman Skills | ai-resources | 已核 | https://x.com/tetumemo/status/2045102005908332881 |
| SWE-Bench Pro V2 | ai-resources | 已核 | https://x.com/scale_AI/status/2102451007041282353 |
| τ2/τ³-bench（Sierra） | ai-resources | 已核 | https://x.com/SierraPlatform/status/1932464265207889974 |
| Terminal-Bench 4.0 | ai-resources | 已核 | https://x.com/terminalbench/status/2093593947654533349 |
| Neon MCP | ai-resources | 已核 | https://x.com/neondatabase/status/2097411958152855717 |
| MongoDB Atlas Managed MCP | ai-resources | 已核 | https://x.com/MongoDB/status/2098082804793798845 |
| Airtable MCP | ai-resources | 已核 | https://x.com/airtable/status/2103483184931369312 |
| VQ-bench（向量量化评测） | ai-resources | 已核 | https://x.com/pinecone/status/2102416782971769178 |
| SWE-Serve（NVIDIA 推理服务 Agent 榜） | ai-resources | 已核 | https://x.com/JiantaoJ/status/2102885056327090418 |
| MLPerf Training v6.1 后训练 | ai-resources | 已核 | https://x.com/MLCommons/status/2103137660885774720 |
| MentalHealthBench（OpenAI） | ai-resources | 已核 | https://x.com/OpenAI/status/2102837574092161102 |
| Atlassian Rovo MCP | ai-resources | 已核 | https://x.com/Atlassian/status/2031067692182941991 |
| Salesforce DX MCP | ai-resources | 已核 | https://x.com/SalesforceDevs/status/1937587282619331071 |
| PayPal Remote MCP | ai-resources | 已核 | https://x.com/paypaldev/status/1925212212618252419 |
| MCPMark（MCP 压力测试评测） | ai-resources | 已核 | https://x.com/qizhex1/status/1960029790305763567 |
| Square MCP | ai-resources | 已核 | https://x.com/jack/status/1915942871792029770 |
| GitLab MCP 19.4 | ai-resources | 已核 | https://x.com/gitlab/status/2101008794184528304 |
| Auth0 MCP | ai-resources | 已核 | https://x.com/auth0/status/2103127841114038462 |
| Webflow MCP | ai-resources | 已核 | https://x.com/webflow/status/2102109983433470157 |
| PlanetScale MCP | ai-resources | 已核 | https://x.com/PlanetScale/status/2027074286394167793 |
| Twilio MCP + Skills | ai-resources | 已核 | https://x.com/twilio/status/2052466530751766749 |
| Fastly MCP | ai-resources | 已核 | https://x.com/fastly/status/1952460057641095332 |
| Dropbox Dash MCP | ai-resources | 已核 | https://x.com/Dropbox/status/1981393384460910606 |
| Box MCP | ai-resources | 已核 | https://x.com/Box/status/2092286094427787588 |
| HubSpot MCP | ai-resources | 已核 | https://x.com/HubSpotDev/status/1919845598779396160 |
| Shopify Dev MCP | ai-resources | 已核 | https://x.com/ShopifyDevs/status/1978855962829009211 |
| Slack MCP | ai-resources | 已核 | https://x.com/SlackHQ/status/2024948072212505008 |
| Firebase MCP | ai-resources | 已核 | https://x.com/Firebase/status/1975939244863390099 |
| Databricks Genie One MCP | ai-resources | 已核 | https://x.com/databricks/status/2102454273376202780 |
| Qwen3-Coder + Qwen Code CLI | ai-resources | 已核 | https://x.com/Alibaba_Qwen/status/1947766835023335516 |
| Qwen3-Omni（全模态开源） | ai-resources | 已核 | https://x.com/Alibaba_Qwen/status/1970181599133344172 |
| gpt-oss 120B/20B（开源权重） | ai-resources | 已核 | https://x.com/ArtificialAnlys/status/1952887733803991070 |
| Kimi K2 Thinking（开源权重） | ai-resources | 已核 | https://x.com/ArtificialAnlys/status/1986541785511043536 |
| Mistral 3 族（开源权重） | ai-resources | 已核 | https://x.com/MistralAI/status/1995872766177018340 |
| Ollama × MLX（Apple Silicon） | ai-resources | 已核 | https://x.com/ollama/status/2038835449012351197 |
| vLLM v0.28.0 | ai-resources | 已核 | https://x.com/vllm_project/status/2092789782464315594 |
| EXO 1.0（本地集群） | ai-resources | 已核 | https://x.com/exolabs/status/2001817749744476256 |
| SGLang v0.5.15 | ai-resources | 已核 | https://x.com/sgl_project/status/2075721488456654861 |
| LMDeploy v0.10.0 | ai-resources | 已核 | https://x.com/intern_lm/status/1965752368190070887 |
| LFM2.5-2.6B（端侧开源） | ai-resources | 已核 | https://x.com/liquidai/status/2084640701669613906 |
| GLM-5.3（开源权重） | ai-resources | 已核 | https://x.com/Zai_org/status/2093354097122455713 |
| K2 Horizon（IFM 六模型族） | ai-resources | 已核 | https://x.com/IFM_AI/status/2095497035806113861 |
| Command A+（Cohere 开源） | ai-resources | 已核 | https://x.com/cohere/status/2057120818551734589 |
| Intern-S2-Preview | ai-resources | 已核 | https://x.com/intern_lm/status/2055146106799976798 |
| Elastic Agent Skills | ai-resources | 已核 | https://x.com/elastic/status/2052040690796777781 |
| BFCL V4 Agentic | ai-resources | 已核 | https://x.com/shishirpatil_/status/1946020561626546176 |
| North Mini Code（Cohere） | ai-resources | 已核 | https://x.com/cohere/status/2064378058329526556 |
| Cosmos 3（Physical AI） | ai-resources | 已核 | https://x.com/NVIDIAAI/status/2061308434629132553 |
| Inkling-Small | ai-resources | 已核 | https://x.com/thinkymachines/status/2082885869426631032 |
| Lark CLI Skills | ai-resources | 已核 | https://x.com/Larksuite/status/2038789640346624457 |
| MLE-bench | ai-resources | 已核 | https://x.com/OpenAI/status/1844429536353714427 |
| MiMo-V2.6（小米开源） | ai-resources | 已核 | https://x.com/XiaomiMiMo/status/2102138582324625780 |
| Olmo 3（Ai2 全开源） | ai-resources | 已核 | https://x.com/allen_ai/status/1991507983881379896 |
| Prisma Skills | ai-resources | 已核 | https://x.com/prisma/status/2028772644322242899 |
| Azure Skills | ai-resources | 已核 | https://x.com/Azure/status/2052856062840074294 |
| GameDevBench | ai-resources | 已核 | https://x.com/iamwaynechi/status/2022357146478764127 |
| NeoMME（多模态编码器） | ai-resources | 已核 | https://x.com/hcompany_ai/status/2098040121547182154 |
| DeepSWE | ai-resources | 已核 | https://x.com/serenaa_ge/status/2059308218564890875 |
| Obsidian Skills | ai-resources | 已核 | https://x.com/kepano/status/2008578873903206895 |
| SkillsBench 1.1 | ai-resources | 已核 | https://x.com/xdotli/status/2067006779255619912 |
| WeMM-Embedding | ai-resources | 已核 | https://x.com/TencentAI_News/status/2095873481917505558 |
| Toolathlon | ai-resources | 已核 | https://x.com/junxian_he/status/1983834164727312391 |
| Stitch Skills | ai-resources | 已核 | https://x.com/stitchbygoogle/status/2034332847893574080 |
| Qwen3-VL-Embedding | ai-resources | 已核 | https://x.com/Alibaba_Qwen/status/2009264754917863924 |
| InternVL-U | ai-resources | 已核 | https://x.com/intern_lm/status/2032294588715843913 |
| HunyuanImage 3.0 | ai-resources | 已核 | https://x.com/TencentHunyuan/status/1972137010707288459 |
| LHTB（长程终端评测） | ai-resources | 已核 | https://x.com/rosinality/status/2076572455854825894 |
| Qwen3.5-397B-A17B | ai-resources | 已核 | https://x.com/Alibaba_Qwen/status/2023331062433153103 |
| AliceAI-Foundation-80B | ai-resources | 已核 | https://x.com/yandexcom/status/2102050970939383810 |
| Kimi K3 | ai-resources | 已核 | https://x.com/Kimi_Moonshot/status/2081760186235289764 |
| dbt Agent Skills | ai-resources | 已核 | https://x.com/getdbt/status/2019501979395817790 |
| Nex-N2.5 | ai-resources | 已核 | https://x.com/NexEcosystem/status/2097341149405151287 |
| MiniMax-M3 | ai-resources | 已核 | https://x.com/MiniMax_AI/status/2065436935188058208 |
| terraform-skill | ai-resources | 已核 | https://x.com/antonbabenko/status/2012917839745659170 |
| AutomationBench-AA | ai-resources | 已核 | https://x.com/ArtificialAnlys/status/2074194764510208230 |
| AgencyBench | ai-resources | 已核 | https://x.com/rohanpaul_ai/status/2014934941226692747 |
| LongCat-2.0 | ai-resources | 已核 | https://x.com/Meituan_LongCat/status/2071783587205308721 |
| LTX-2.5 | ai-resources | 已核 | https://x.com/ltx_io/status/2087255203489755243 |
| DolphinBench | ai-resources | 已核 | https://x.com/mem0ai/status/2102438126941876590 |
| AWS Agent Toolkit Skills | ai-resources | 已核 | https://x.com/awscloud/status/2070568410887414167 |
| jina-embeddings-v5-omni | ai-resources | 已核 | https://x.com/JinaAI_/status/2054226262047301933 |
| Nemotron 3.5 Lightning | ai-resources | 已核 | https://x.com/NVIDIAAI/status/2087162151995629926 |
| jina-ocr-v1 | ai-resources | 已核 | https://x.com/JinaAI_/status/2100617174985638364 |
| jina-reranker-v3.5 | ai-resources | 已核 | https://x.com/JinaAI_/status/2084288559435903485 |
| Granite 4.2 | ai-resources | 已核 | https://x.com/IBMResearch/status/2092304349665833410 |
| Nemotron 3 Embed | ai-resources | 已核 | https://x.com/NVIDIAAI/status/2077786069840318800 |
| PP-OCRv6 | ai-resources | 已核 | https://x.com/PaddlePaddle/status/2065299834756902995 |
| Laguna S 2.1 | ai-resources | 已核 | https://x.com/poolsideai/status/2079613777343848465 |
| LFM2.5-VL-3B | ai-resources | 已核 | https://x.com/liquidai/status/2087539876929441983 |
| North Small Translate | ai-resources | 已核 | https://x.com/cohere/status/2098081558087270736 |
| MiniCPM5-2B | ai-resources | 已核 | https://x.com/OpenBMB/status/2096970974247956501 |
| Atria Dawn Preview | ai-resources | 已核 | https://x.com/OpenBMB/status/2099498690092355897 |
| HLE-Diamond | ai-resources | 已核 | https://x.com/CAIS/status/2102787839964729431 |
| Nemotron 3 Diarization | ai-resources | 已核 | https://x.com/NVIDIAAI/status/2102775666366435450 |
| AuK | ai-resources | 已核 | https://x.com/TencentHunyuan/status/2097996926876795197 |
| EvolveScaler | ai-resources | 已核 | https://x.com/TencentHunyuan/status/2099748549281939558 |
| GameHorizon Suite | ai-resources | 已核 | https://x.com/HuggingPapers/status/2102314047878345185 |
| Cohere Megakernel | ai-resources | 已核 | https://x.com/cohere/status/2097410772355666393 |
| Mixture-of-Kittens (MoK) | ai-resources | 已核 | https://x.com/cursor_ai/status/2084670806613737919 |
| NASA-IBM Lunar Foundation Model | ai-resources | 已核 | https://x.com/IBMNews/status/2098018859840082162 |
| Salesforce Connect adapter skill | ai-resources | 已核 | https://x.com/SalesforceDevs/status/2102080476957614405 |
| Dynamo AIPerf | ai-resources | 已核 | https://x.com/NVIDIAAI/status/2101077927408623623 |
| MiniMax Code CLI | ai-resources | 已核 | https://x.com/MiniMax_AI/status/2100930515058753830 |
| Qwen Intelligence | ai-resources | 已核 | https://x.com/Alibaba_Qwen/status/2102727405198876753 |
| LFM2.5-VL-3B-DSpark | ai-resources | 已核 | https://x.com/liquidai/status/2103131179100819783 |
| shadcn/lint | ai-resources | 已核 | https://x.com/shadcn/status/2099534231114314145 |
| Azure Container Apps Sandboxes | ai-resources | 已核 | https://x.com/Azure/status/2103514866770215048 |
| LongevityBench + LFM2 Longevity | ai-resources | 已核 | https://x.com/liquidai/status/2100608105444684181 |
| Terminal-Bench-Science 0.1 | ai-resources | 已核 | https://x.com/ArtificialAnlys/status/2103265956479070260 |
| Decision Index 0.1 | ai-resources | 已核 | https://x.com/multimodalart/status/2102296665331999098 |
| E-Commerce Bench | ai-resources | 已核 | https://x.com/Alibaba_Qwen/status/2095476249556853100 |
| MiniMax H3 | ai-resources | 已核 | https://x.com/MiniMax_AI/status/2099381310733328784 |
| Cultivar | ai-resources | 已核 | https://x.com/pinecone/status/2101325527457968417 |
| Jev | ai-resources | 已核 | https://x.com/typesafeai/status/2101786156572823624 |
| READY | ai-resources | 已核 | https://x.com/fdesouza/status/2095455647923937310 |
| ROK-FORTRESS | ai-resources | 已核 | https://x.com/scale_AI/status/2100982540152815644 |
| Agora-2 | ai-resources | 已核 | https://x.com/odysseyml/status/2103146841378586820 |
| Agents API | ai-resources | 已核 | https://x.com/OpenAIDevs/status/2098130570048045453 |
| Desert Ant Labs | ai-resources | 已核 | https://x.com/desertantlabs/status/2097337888669139285 |
| Ling-3.0-flash-VL | ai-resources | 已核 | https://x.com/AntLingAGI/status/2095935971556782372 |
| DeepSeek-V4.1-Flash | ai-resources | 已核 | https://x.com/deepseek_ai/status/2097930608790167907 |
| Hy4 preview | ai-resources | 已核 | https://x.com/TencentAI_News/status/2093232936434954659 |
| Gemini 3.8 Flash TTS | ai-resources | 已核 | https://x.com/GoogleDeepMind/status/2102781530867126505 |
| GPT-6 Sol / Luna | ai-resources | 已核 | https://x.com/OpenAIDevs/status/2102461432684282061 |
| WorldCrafter | ai-resources | 已核 | https://x.com/TencentAI_News/status/2102678781605691676 |
| Pipette | ai-resources | 已核 | https://x.com/liquidai/status/2091906366428598284 |
| visual-pr Skill | ai-resources | 已核 | https://x.com/dexhorthy/status/2100558413314859118 |
| CUDA Rust | ai-resources | 已核 | https://x.com/NVIDIAHPCDev/status/2100261772355907936 |
| Transformers GGUF/Metal | ai-resources | 已核 | https://x.com/ggerganov/status/2102382619845410978 |
| PageIndex | ai-resources | 已核 | https://x.com/simplifyinAI/status/2080468063548543454 |
| Ming-Image-0.1-Design | ai-resources | 已核 | https://x.com/TheInclusionAI/status/2102631831120097486 |
| BrowserSkill | ai-resources | 已核 | https://x.com/TencentAI_News/status/2100143086429217278 |
| CubeSandbox | ai-resources | 已核 | https://x.com/TencentAI_News/status/2099445261185765528 |
| Claude biomolecular uplifts | ai-resources | 已核 | https://x.com/AnthropicAI/status/2100701581109072332 |
| ZCode | ai-resources | 已核 | https://x.com/zRdianjiao/status/2101837445927141736 |
| Mercury 2.5 | ai-resources | 已核 | https://x.com/_inception_ai/status/2097365772289151417 |
| Ling-3.0-flash-Fin | ai-resources | 已核 | https://x.com/AntLingAGI/status/2093022087069958492 |
| Step Code | ai-resources | 已核 | https://x.com/StepFun_ai/status/2102433493410345273 |
| Step 5 Preview | ai-resources | 已核 | https://x.com/StepFun_ai/status/2101510462685003786 |
| onPanda | ai-resources | 已核 | https://x.com/StepFun_ai/status/2102454115473510643 |
| LongCat-2.5-Preview | ai-resources | 已核 | https://x.com/Meituan_LongCat/status/2103488918788411728 |
| Kimi Browser Extension | ai-resources | 已核 | https://x.com/Kimi_Moonshot/status/2102372557190230244 |
| State of agent skills | ai-resources | 已核 | https://x.com/vercel/status/2103541839399907424 |
| LLaDA-Image | ai-resources | 已核 | https://x.com/TheInclusionAI/status/2095696902004293744 |
| PanelWise | ai-resources | 已核 | https://x.com/TheInclusionAI/status/2091851247259443627 |
| sing-box 1.14.0（TG） | vpn-proxy | 已核 | https://t.me/yapnc/495 |
| Hiddify：多平台开源代理客户端（App Store / GPLv3 宣称） | vpn-proxy | 已核 | https://x.com/hiddify_com/status/1852014812051406910 |
| Hiddify 1.5.2：官方发版帖（含 GitHub Releases 入口） | vpn-proxy | 已核 | https://x.com/hiddify_com/status/1810758424881496232 |
| Clash Verge Rev：Tauri 桌面代理 GUI（GitHub 热榜转发） | vpn-proxy | 已核 | https://x.com/kodemarket01/status/2062195599626101043 |
| AmneziaVPN 5.0.3：开源 VPN 客户端版本更新 | vpn-proxy | 已核 | https://x.com/AmneziaVPN/status/2102447556433186967 |
| 3m-ui：Mihomo 服务端 Web 管理面板 | vpn-proxy | 已核 | https://x.com/Flowers_hurt/status/2102965119017976096 |
| 七喜机场 · 海豚快速评测（TG） | vpn-proxy | 已核 | https://t.me/haitun_channel/2469 |
| AWS 海外中转异常观察（TG） | vpn-proxy | 已核 | https://t.me/jichangtj/1203 |
| 比特冲刺 DASHBIT · SpeedCentre（TG） | vpn-proxy | 已核 | https://t.me/speedcentre/14115 |
| Free Proxy Airport 自动测速（X） | vpn-proxy | 已核 | https://x.com/tyiiopple/status/2100729531850227787 |
| AWS 海外中转异常观察（X·jichangtj） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2098410173245337604 |
| AWS 中转「测速正常、带载超时」机制分析（X） | vpn-proxy | 已核 | https://x.com/divid_lu49394/status/2098490860354871669 |
| 安徽校园网海外中转异常 + 证书风险（X） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2099301546723013039 |
| AnyTLS：IPv4 秒墙、IPv6 正常（X） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2057736251818840249 |
| 闽苏浙 TLS/SNI 与 AnyTLS 阻断观察（X） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2082487380078960822 |
| 移动蜂窝 TCP 超时 vs Hy2/IPv6（X） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2047663760660373788 |
| @jichangtj 2026 评测/测速索引（X） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2076920947072975302 |
| Clash「经典回归」辨伪（jichangtj→Fndroid） | vpn-proxy | 已核 | https://x.com/jichangtj/status/2098964330473836682 |
| [低价] 86中转停服大陆 IP（TG） | other | 已核 | https://t.me/api86channel/12 |
| [低价] 86中转 GPT 号池风控×sub2api（TG） | other | 已核 | https://t.me/api86channel/25 |
| [低价] AIPricedb 比价监控入口（TG） | other | 已核 | https://t.me/aipricedb |
| [低价] 86中转日抛 PLUS 号池失效（TG） | other | 已核 | https://t.me/api86channel/7 |
| [低价] 86中转 Codex 号池崩溃（TG） | other | 已核 | https://t.me/api86channel/10 |
| [低价] 86中转 Claude Max 分组维护（TG） | other | 已核 | https://t.me/api86channel/21 |
| [低价] 86中转模型关停与 Claude 死号（TG） | other | 已核 | https://t.me/api86channel/8 |
| [低价] 86中转称 Codex 官方故障（TG） | other | 已核 | https://t.me/api86channel/22 |
| [低价] TG 号铺 mrnf / @TG_MRNF（风险观察） | other | 已核 | https://tg.mrnf.de/ |
| [低价] TG堂号铺 shop.tgtown.com（风险观察） | other | 已核 | https://shop.tgtown.com/ |
| [低价] Dapally TG 号铺（风险观察） | other | 已核 | https://www.dapally.com/ |
| [低价] telegramhao 号铺（风险观察） | other | 已核 | https://telegramhao.com/ |
| [低价] 土豆 AI 聚合 TG 目录 2dou（观察） | other | 已核 | https://2dou.org/telegram |
| [低价] TG目录网 tgmulu（观察） | other | 已核 | https://www.tgmulu.com/ |
| [低价] @lowpriceking_bot 比价（观察） | other | 已核 | https://t.me/lowpriceking_bot |
| [低价] @pikabaobot 开卡充值（高风险观察） | other | 已核 | https://t.me/pikabaobot |
| [低价] @afaka_bot 发卡（高风险观察） | other | 已核 | https://t.me/afaka_bot |
| [低价] OpenPrice AI 比价（观察） | other | 已核 | https://www.openprice.cc/ |
| [低价] PriceAI 比价雷达（观察） | other | 已核 | https://priceai.cc/ |
| [低价] TelegramNav 目录（观察） | other | 已核 | https://telegramnav.github.io/ |
| [低价] DragonSIM TG 批发（风险观察） | other | 已核 | https://dragonsim.net/en/telegram-account-wholesale/ |
| [低价] AccsMarket TG 目录（风险观察） | other | 已核 | https://www.accsmarket.com/en/catalog/telegram |
| [低价] MixAcc TG 账号页（风险观察） | other | 已核 | https://mixacc.com/products/telegram-accounts/ |
| [低价] tg.cool 搜索目录（观察） | other | 已核 | https://tg.cool/ |
| [低价] TGStat 目录统计（观察） | other | 已核 | https://tgstat.com/ |
| [低价·bot] @FKfc8888bot 发卡（观察） | other | 已核 | https://t.me/FKfc8888bot |
| [低价·bot] @niu444_bot 号铺（观察） | other | 已核 | https://t.me/niu444_bot |
| [低价·bot] @BuyYourPremiumBot（观察） | other | 已核 | https://t.me/BuyYourPremiumBot |
| [低价·bot] @faka 会员群发卡（观察） | other | 已核 | https://t.me/faka |
| [低价·bot] @gptnocard_bot Plus 升级（观察） | other | 已核 | https://t.me/gptnocard_bot |
| [低价·bot] @WarzoneShopBot（观察） | other | 已核 | https://t.me/WarzoneShopBot |
| [低价·bot] @Gemini_shop_robot（观察） | other | 已核 | https://t.me/Gemini_shop_robot |
| [低价·bot] @AiSubShop_bot（观察） | other | 已核 | https://t.me/AiSubShop_bot |
| [低价·bot] @EliteMethodsStoreBot EM Store（风险观察） | other | 已核 | https://t.me/EliteMethodsStoreBot |
| [低价·bot] @scammersdeathbot EM Escrow（风险观察） | other | 已核 | https://t.me/scammersdeathbot |
| [低价·bot] @nomorescammersbot EM 举报入口（风险观察） | other | 已核 | https://t.me/nomorescammersbot |
| [低价·bot] @VouchersShopBot 闪购（风险观察） | other | 已核 | https://t.me/VouchersShopBot |
| [低价·bot] @Prime_Gadget_Store_bot（风险观察） | other | 已核 | https://t.me/Prime_Gadget_Store_bot |
| [低价·bot] @ExcaliburTechBot（风险观察） | other | 已核 | https://t.me/ExcaliburTechBot |
| [低价·bot] @TrustedShopingbot Claude Gift（风险观察） | other | 已核 | https://t.me/TrustedShopingbot |
| [低价·bot] @AithSubscriptions_bot Adobe/Duolingo（风险观察） | other | 已核 | https://t.me/AithSubscriptions_bot |
| [低价·bot] @VaultXStorebot 数字商品店（风险观察） | other | 已核 | https://t.me/VaultXStorebot |
| [低价·bot] @mangoshopglobal_bot API Codex（风险观察） | other | 已核 | https://t.me/mangoshopglobal_bot |
| [低价·bot] @lhiestore_bot ChatGPT Plus（风险观察） | other | 已核 | https://t.me/lhiestore_bot |
| [低价·bot] @storeBatmanBot Apple Pay 话术（风险观察） | other | 已核 | https://t.me/storeBatmanBot |
| [低价·bot] @BuyCardOffical_bot 礼品卡/eSIM（风险观察） | other | 已核 | https://t.me/BuyCardOffical_bot |
| [低价·bot] @WantToPayBot 虚拟卡（风险观察） | other | 已核 | https://t.me/WantToPayBot |
| [低价·bot] @redotpay_bot 加密支付（风险观察） | other | 已核 | https://t.me/redotpay_bot |
| [低价·bot] @kise1223chatbot 86客服（风险观察） | other | 已核 | https://t.me/kise1223chatbot |
| [低价·bot] @toolswala_bot LIVE PRODUCTS（风险观察） | other | 已核 | https://t.me/toolswala_bot |
| [低价·bot·价目] @crassus_market_bot 订阅价目（风险观察） | other/em-shop | 已核 | https://t.me/crassus_market_bot |
| [低价·bot·价目] @AIVerseXBot 多品促销价（风险观察） | other/em-shop | 已核 | https://t.me/AIVerseXBot |
| [低价·bot·价目] @Pixora_Tunisie_bot 成交播报价（风险观察） | other/em-shop | 已核 | https://t.me/Pixora_Tunisie_bot |
| [低价·bot·价目] @RichAIStoreBot 批发样例价（风险观察） | other/em-shop | 已核 | https://t.me/RichAIStoreBot |
| [低价·bot·价目] @canvora24bot 公开价目表（风险观察） | other/em-shop | 已核 | https://t.me/canvora24bot |
| [低价·bot·价目] @geminiprosub_bot 库存长表（风险观察） | other/em-shop | 已核 | https://t.me/geminiprosub_bot |
| [低价·bot·价目] @Shop_Ayham_bot Gemini 标价偏弱（风险观察） | other/em-shop | 已核 | https://t.me/Shop_Ayham_bot |
| [低价·bot·价目] @ver_pixel_bot STOCK 价目（风险观察） | other/em-shop | 已核 | https://t.me/ver_pixel_bot |
| [低价·bot·价目] @u_pebot 卢布网页价目（风险观察） | other/em-shop | 已核 | https://t.me/u_pebot |
| [低价·bot·价目] @novastore_ai_bot 波斯语价目（风险观察） | other/em-shop | 已核 | https://t.me/novastore_ai_bot |
| [低价·bot·价目] @Veriyferbot 多品美元价目（风险观察） | other/em-shop | 已核 | https://t.me/Veriyferbot |
| [低价·bot·价目] @Cp669912_bot 人民币代充价目（风险观察） | other/em-shop | 已核 | https://t.me/Cp669912_bot |
| [低价·bot·价目] @nevakeystore_bot CORE 价目（风险观察） | other/em-shop | 已核 | https://t.me/nevakeystore_bot |
| [低价·bot·价目] @Chatgpt_aboutshopBot  تومان价目（风险观察） | other/em-shop | 已核 | https://t.me/Chatgpt_aboutshopBot |
| [低价·bot·价目] @Substor_bot 卢布价目（风险观察） | other/em-shop | 已核 | https://t.me/Substor_bot |
| [低价·bot·价目] @SubscriptionDotCheap_bot 站内目录（风险观察） | other/em-shop | 已核 | https://t.me/SubscriptionDotCheap_bot |
| [低价·bot·价目] @parsgptbot تومان价目（风险观察） | other/em-shop | 已核 | https://t.me/parsgptbot |
| [低价·bot·价目] @taynikstore_bot 站内 API 多品价目（风险观察） | other/em-shop | 已核 | https://t.me/taynikstore_bot |
| [低价·bot·价目] @storeluma_bot 论坛卢布价目（风险观察） | other/em-shop | 已核 | https://t.me/storeluma_bot |
| [低价·bot·价目] @ZykoLand_bot 论坛卢布价目（风险观察） | other/em-shop | 已核 | https://t.me/ZykoLand_bot |
| [低价·bot·价目] @Premium_Shop_bot 论坛卢布价目（风险观察） | other/em-shop | 已核 | https://t.me/Premium_Shop_bot |

| [低价·群] @chatgptplusbuysell 买卖群（风险观察） | other/tg-catalog | 已核 | https://t.me/chatgptplusbuysell |
| [低价·群] @gemini12pro 讨论群（风险观察） | other/tg-catalog | 已核 | https://t.me/gemini12pro |
| [低价·群] @Geminivip1 公益Plus交流（风险观察） | other/tg-catalog | 已核 | https://t.me/Geminivip1 |
| [低价·bot] @SSkyGPTbot 公益升级（风险观察） | other/tg-catalog | 已核 | https://t.me/SSkyGPTbot |
| [低价·bot·价目] @JeroAccountsBot EM群价目（风险观察） | other/em-shop | 已核 | https://t.me/JeroAccountsBot |
| [低价·群] @elitemethodchat EM Chat（风险观察） | other/tg-catalog | 已核 | https://t.me/elitemethodchat |
| [低价·群] @aipricedb 比价交流（风险观察） | other/tg-catalog | 已核 | https://t.me/aipricedb |
| [低价·群] @with_ai_homes AI原住民交流（风险观察） | other/tg-catalog | 已核 | https://t.me/with_ai_homes |
| [低价·群] @geminichatgroup 中转API交流（风险观察） | other/tg-catalog | 已核 | https://t.me/geminichatgroup |
| [低价·群] @priceaicc PriceAI交流（风险观察） | other/tg-catalog | 已核 | https://t.me/priceaicc |
| [低价·bot] @gemini12pro_bot Pixel Helper（风险观察） | other/tg-catalog | 已核 | https://t.me/gemini12pro_bot |
| Sub2API 开源合租中转网关 | ai-resources | 已核 | https://github.com/Wei-Shaw/sub2api |


> 注：硬规则优先 X 链接；已批 TG 频道来源可用 Telegram 消息链接入库，并在条目中标明平台。

## 跟盯清单

- Telegram：[`watchlists/tg-channels.md`](./watchlists/tg-channels.md)（已审公开频道；不擅自发帖）

## 工作方式（给人 / 给助手）

1. 在 X 搜关键词或跟账号，打开具体帖子。
2. 判断是否有价值（可复用工具、可跟进资源、可验证方法）。
3. 复制帖子链接 → 按模板新建 `records/<分类>/<短名>.md`。
4. 更新本 README 索引表。
5. 夸大、未证实的声称写进「风险 / 待核实」，不删帖源。

## 不收什么

- 无 X 链接的二手转述
- 纯营销无实质入口
- 违法操作教程式细节（只记公开工具名与官方入口）
