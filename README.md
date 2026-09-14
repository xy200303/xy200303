<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=gradient&text=XiaoYun&fontSize=72&fontAlignY=38&desc=Code%20%7C%20Learn%20%7C%20Share&descAlignY=60&descSize=24&animation=fadeIn" alt="XiaoYun Banner" />
</p>

<p align="center">
  <img width="780" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&pause=1200&center=true&vCenter=true&width=780&lines=Welcome+to+my+GitHub+profile" alt="Typing Intro" />
</p>

<h1 align="center">极客小云 | XiaoYun</h1>

<p align="center">
  热爱编程、持续学习，也乐于把过程整理成可见的作品。<br />
  这里记录我的项目实践、开发轨迹、技术积累，以及一点点长期主义。
</p>

<p align="center">
  <a href="https://github.com/xy200303"><img src="https://img.shields.io/badge/GitHub-xy200303-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <a href="https://space.bilibili.com/319065773?spm_id_from=333.1007.0.0"><img src="https://img.shields.io/badge/Bilibili-_极客小云_-FB7299?style=for-the-badge&logo=bilibili&logoColor=white" alt="Bilibili" /></a>
  <a href="https://blog.csdn.net/m0_73370855?type=blog"><img src="https://img.shields.io/badge/CSDN-技术博客-FC5531?style=for-the-badge" alt="CSDN" /></a>
  <a href="https://orcid.org/0009-0008-4777-304X"><img src="https://img.shields.io/badge/ORCID-0009--0008--4777--304X-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID" /></a>
</p>

<p align="center">
  <a href="https://hub.docker.com/u/xy200303"><img src="https://img.shields.io/badge/Docker%20Hub-xy200303-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Hub" /></a>
  <a href="https://www.npmjs.com/~dev_xiaoyun"><img src="https://img.shields.io/badge/npm-dev__xiaoyun-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm" /></a>
  <a href="https://pypi.org/user/xiaoyun2003/"><img src="https://img.shields.io/badge/PyPI-xiaoyun2003-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="PyPI" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=xy200303&label=Profile+Views&color=0e75b6&style=flat" alt="Profile Views" />
</p>

---

## 关于我

- 主要使用 `Python`、`Go`、`TypeScript`、`Java`，关注 AI 编程工具、LLM 推理与训练基础设施、GPU Kernel、图像处理和安全工程。
- 习惯从 Issue、PR 和可复现测试出发解决问题，再把实现沉淀为项目、工具或文档。
- 当前重点参与 AI Agent、GPU/编译器基础设施和可视化产品方向的开源实践。

## 开源贡献与项目亮点

> 以下内容根据 GitHub 公开提交与 Pull Request 整理，PR 状态截至 2026-09-14。

### 已合并的 Pull Requests

| 项目 | PR | 简介 |
| :--- | :--- | :--- |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | [#10790 Fix fp8 block dequant fallback on pre-sm89 GPUs](https://github.com/unslothai/unsloth/pull/10790) | 修复低于 `sm89` 架构的 GPU 执行 FP8 block dequant 时错误进入不支持的 Triton Kernel，恢复 PyTorch fallback |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | [#10797 Clear the metadata directory cache before scanning installed records](https://github.com/unslothai/unsloth/pull/10797) | 清理安装元数据目录缓存，使同一进程内新增或损坏的 `*.dist-info` 能被安装校验及时发现 |
| [fla-org/flash-linear-attention](https://github.com/fla-org/flash-linear-attention) | [#1111 Restore backend dispatch under `torch.compiler.disable`](https://github.com/fla-org/flash-linear-attention/pull/1111) | 修正装饰器顺序，避免 `torch.compiler.disable` 丢失 KDA backend dispatch |
| [Tencent/tdesign-common](https://github.com/Tencent/tdesign-common) | [#2639 fix(Button): 修复自定义 SVG 图标与文字的间距](https://github.com/Tencent/tdesign-common/pull/2639) | 为普通 SVG 图标补齐 Button 图标与文本之间的间距，并通过项目测试 |
| [superdoc/docx-editor](https://github.com/superdoc/docx-editor) | [#3616 fix(super-editor): support nested content controls](https://github.com/superdoc/docx-editor/pull/3616) | 修复 Word `w:sdt` 嵌套 content controls 的 DOCX 导入问题 |
| [superdoc/docx-editor](https://github.com/superdoc/docx-editor) | [#3641 fix(super-editor): rethrow export docx errors](https://github.com/superdoc/docx-editor/pull/3641) | `Editor.exportDocx()` 失败时正确把错误抛给调用方，并补充回归测试 |
| [stepfun-ai/Step-Realtime-CLI](https://github.com/stepfun-ai/Step-Realtime-CLI) | [#18 Fix smart compaction abort handling](https://github.com/stepfun-ai/Step-Realtime-CLI/pull/18) | 修复 smart compaction 中止处理，用户中断不再被误判为可恢复的压缩失败 |
| [insistence/RuoYi-Vue3-FastAPI](https://github.com/insistence/RuoYi-Vue3-FastAPI) | [#82 perf: 优化项目启动速度](https://github.com/insistence/RuoYi-Vue3-FastAPI/pull/82) | 启动连通性检查改用国内可达 DNS，路由扫描跳过 `.git`、`venv` 等目录 |

### 被官方采纳

- ![credit](https://img.shields.io/badge/-credit-0969DA?style=flat-square) **[fix(approval): close three shell-obfuscation denylist bypasses](https://github.com/NousResearch/hermes-agent/pull/56184)** — [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)  
  我在 [#40663](https://github.com/NousResearch/hermes-agent/pull/40663) 中提出的 shell word 级变体扫描与去混淆方案（识别 `$(echo rm)` 这类绕过，同时避免误报参数里的 `rm`），被维护者整合进该综合修复，并标注 Class 1 credit 为 `@xy200303 (#40663)`。
- ![credit](https://img.shields.io/badge/-credit-0969DA?style=flat-square) **[fix(skills): block path traversal via skill_view name argument](https://github.com/NousResearch/hermes-agent/pull/40566)** — [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)  
  我在 [#40521](https://github.com/NousResearch/hermes-agent/pull/40521) 中报告并修复了 `skill_view` `name` 参数的路径穿越漏洞；维护者复用现有 traversal 辅助函数收紧后在 #40566 合并，并明确标注 "Salvaged from #40521 (@xy200303)"。
- ![release](https://img.shields.io/badge/-release-2EA043?style=flat-square) **[Compare View feature](https://github.com/CVHub520/X-AnyLabeling/releases/tag/v3.3.7)** — [CVHub520/X-AnyLabeling v3.3.7](https://github.com/CVHub520/X-AnyLabeling/releases/tag/v3.3.7)  
  多模态图像对比显示功能被纳入官方 Release，可用于红外/可见光融合、mask preview、超分等场景。
- ![adopted](https://img.shields.io/badge/-adopted-D4A017?style=flat-square) **[Clear existing lint warnings](https://github.com/stepfun-ai/Step-Realtime-CLI/pull/15)** — [stepfun-ai/Step-Realtime-CLI](https://github.com/stepfun-ai/Step-Realtime-CLI)  
  维护者确认该修复比官方落地的 [#10](https://github.com/stepfun-ai/Step-Realtime-CLI/pull/10) 早一个月，四个文件中两个与官方修复完全一致、两个仅差循环变量名，关闭时明确致谢并说明"并非 PR 本身有问题"。

### 近期 Pull Requests

- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[TileLang #3205](https://github.com/tile-ai/tilelang/pull/3205)**、**[#3206](https://github.com/tile-ai/tilelang/pull/3206)**、**[#3207](https://github.com/tile-ai/tilelang/pull/3207)** — 修复 `T.clamp` 的 NaN 传播、CUDA Kernel 中 host-only assert，以及输出参数位于动态 shape 输入之前时的 JIT 分配错误。
- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[Flash Linear Attention #1239](https://github.com/fla-org/flash-linear-attention/pull/1239)**、**[#1242](https://github.com/fla-org/flash-linear-attention/pull/1242)**、**[#1244](https://github.com/fla-org/flash-linear-attention/pull/1244)** — 修复 chunk-state Kernel 的 CUDA 网格上限问题，以及 KDA/GDN-2 `safe_gate` 对未来 token 的数值依赖。
- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[FlashKDA #27](https://github.com/MoonshotAI/FlashKDA/pull/27)**、**[#28](https://github.com/MoonshotAI/FlashKDA/pull/28)** — 增加可微分 CPU KDA backend 与完整 CUDA 训练路径，覆盖前向、反向和研究验证场景。
- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[Unsloth #10796](https://github.com/unslothai/unsloth/pull/10796)** — 为 GPU inference smoke test 的 Hub 下载增加超时边界，避免慢连接阻塞整个测试套件。
- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[Kimi Code #2498](https://github.com/MoonshotAI/kimi-code/pull/2498)**、**[#2499](https://github.com/MoonshotAI/kimi-code/pull/2499)** — 修复不可达阈值导致的自动压缩循环，并为无工具进展的 goal continuation 增加退避策略。
- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[ncnn #6844](https://github.com/Tencent/ncnn/pull/6844)**、**[#6845](https://github.com/Tencent/ncnn/pull/6845)** — 修复非整数缩放插值与 light mode 下外部 `Mat` 的处理问题，并补充回归测试。
- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[Tencent Hunyuan Hy3 #53](https://github.com/Tencent-Hunyuan/Hy3/pull/53)**、**[#103](https://github.com/Tencent-Hunyuan/Hy3/pull/103)** — 提交数据分析 MCP Server 与混元多模型驱动的 ArchAgent 空间设计工作台。
- ![open](https://img.shields.io/badge/-open-1F883D?style=flat-square) **[ollama #16717](https://github.com/ollama/ollama/pull/16717)** — 保留多模态解析中的嵌套文件路径。

GitHub 公开搜索当前记录有 40 个开放 PR，覆盖 MoonshotAI、Tencent、NousResearch、Unsloth、TileLang、Flash Linear Attention 等项目。

### 工作亮点

- **AI 基础设施与 GPU Kernel**：围绕 Flash Linear Attention、FlashKDA 和 TileLang，持续处理 CUDA 训练路径、Triton backend dispatch、动态 shape、Kernel 代码生成和门控注意力数值正确性问题。
- **稳定性与工程质量**：在 Unsloth、Kimi Code、Step-Realtime-CLI、ncnn 等项目中补充 fallback、缓存失效、超时、中止传播、退避和回归测试，重点解决“异常被吞掉”或“测试无限等待”类问题。
- **安全与平台治理**：迭代 [Fenx 合规监控平台](https://github.com/xy200303/login-intercept-tool)，完成 JWT 双令牌、登录 IP 记录管理、管理员与任务权限控制、外连配置和元数据缓存等能力。
- **色彩计算与可视化**：完成 [shise-engine](https://github.com/xy200303/shise-engine) 与 [拾色·东方](https://github.com/xy200303/shise-dongfang) 的 OKLCH 色阶引擎、传统色检索、WCAG/APCA 对比、3D 星图和器物展示。

### Issues

- ![issue](https://img.shields.io/badge/-issue-F85149?style=flat-square) **[RootModel unions 反序列化问题反馈](https://github.com/langchain-ai/langchain/issues/38137)** — [langchain-ai/langchain](https://github.com/langchain-ai/langchain)
- ![issue](https://img.shields.io/badge/-issue-F85149?style=flat-square) **[VS Code terminal input freezes when pasting escaped single-line JSON](https://github.com/openai/codex/issues/27405)** — [openai/codex](https://github.com/openai/codex)

### 最近更新的项目

- [Fenx 合规监控平台](https://github.com/xy200303/login-intercept-tool) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
  面向登录 IP 记录、账号与任务管理的轻量合规监控平台，采用 Go、PostgreSQL、JWT 双令牌和 Docker Compose 部署。
- [拾色 · 东方](https://github.com/xy200303/shise-dongfang) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
  537 只中国传统色主题馆，集成 OKLCH 色阶、图片取色、配色实验室、TDesign Token 沙盒、3D 星图和器物展示。
- [拾色引擎 shise-engine](https://github.com/xy200303/shise-engine) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
  基于 OKLCH 的感知均匀色阶与 TDesign Design Token 生成引擎，已发布 `v1.2.0`，支持作为 npm/git 依赖使用。
- [ArchAgent](https://github.com/xy200303/ArchAgent) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
  混元多模型驱动的对话式空间设计工作台，从自然语言或参考图片出发，完成设计决策、3D 资产生成、可编辑场景搭建与多格式导出。
- [Spec Kimi](https://github.com/xy200303/spec-kimi-code) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
  基于 Kimi Code CLI 的 spec-driven 分支，将自然语言开发流程转换为可追踪的规格驱动工作流，已发布 `spec-kimi` `1.0.1`。
- [AetherVectorLab/dev-mesh](https://github.com/AetherVectorLab/dev-mesh) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
  给 AI 编程助手使用的 local-first 项目知识层，通过 MCP 提供项目知识检索、经验沉淀、本地缓存与可选团队同步。
- [OpenTrans](https://github.com/xy200303/OpenTrans) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)  
  多协议 LLM 请求体/响应体/流式事件转换 SDK，用于 OpenAI、Claude、Gemini 等协议适配。
- [AiCodeAudit](https://github.com/xy200303/AiCodeAudit) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)  
  基于大模型的代码安全审计工具，支持命令行与 Streamlit Web 界面。
- [image_registration_tool](https://github.com/xy200303/image_registration_tool) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)  
  基于 PyQt6 的红外图像和可见光图像手动配准、批量处理工具。
- [ComfyUiApi](https://github.com/xy200303/ComfyUiApi) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)  
  调用 ComfyUI API 的 Python 客户端库。
- [SafeGate](https://github.com/xy200303/SafeGate) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)  
  可配置的 IP 风控网关/反向代理防火墙，面向域名映射、真实 IP 透传、接口风控拦截、JSON 请求体转换与访问日志审计。
- [spec-coding-mcp](https://github.com/xy200303/spec-coding-mcp) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)  
  给 Codex、Claude Code、OpenCode 等编程工具提供本地规格上下文的 MCP 项目。

## GitHub 总览

<table>
  <tr>
    <td width="42%" valign="top">
      <img src="https://github-readme-stats-pi-pied-31.vercel.app/api?username=xy200303&theme=transparent&show_icons=true&hide_border=true&show=reviews&hide_title=true&number_format=long&include_all_commits=true" alt="Profile Stats" width="100%" />
      <br />
      <img src="https://github-readme-streak-stats-six-peach.vercel.app?user=xy200303&theme=transparent&hide_border=true&locale=zh_Hans&date_format=%5BY.%5Dn.j" alt="Streak Stats" width="100%" />
      <br />
      <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=xy200303&layout=compact&hide=powershell" alt="Top Languages" width="100%" />
      <br />
      <img src="https://github-stats-extended.vercel.app/api/wakatime?username=@xiaoyun&layout=compact&hide_border=true" alt="WakaTime Stats" width="100%" />
      <a href="https://ghfind.com/u/xy200303?ref=badge"><img src="https://ghfind.com/api/card/xy200303?theme=light&variant=contrib&qr=1" alt="GitHub Roast" width="600" /></a>
    </td>
    <td width="58%" valign="top">
      <img src="./github-metrics.svg" alt="GitHub Metrics" width="100%" />
    </td>
  </tr>
</table>

<p align="center">
  <img width="900" src="https://github-readme-activity-graph.vercel.app/graph?username=xy200303&theme=github-compact&hide_border=true&area=true&custom_title=Activity%20Graph" alt="Activity Graph" />
</p>

## 常用技术

<p align="center">
  <img width="820" height="32" src="https://go-skill-icons.vercel.app/api/icons?i=py,html,css,golang,java,git,huggingface&titles=true" alt="Skill Icons" />
</p>

<details>
  <summary><strong>展开查看详细技术标签</strong></summary>
  <br />

  **编程语言**

  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
  ![C](https://img.shields.io/badge/C-5C6BC0?style=flat-square&logo=c&logoColor=white)
  ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
  ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

  **前端与标记**

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
  ![JSON](https://img.shields.io/badge/JSON-222222?style=flat-square&logo=json&logoColor=white)
  ![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

  **系统与数据库**

  ![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
  ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
  ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
  ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
  ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

  **其他工具与兴趣**

  ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
  ![Minecraft](https://img.shields.io/badge/Minecraft-3C9A1A?style=flat-square&logo=minecraft&logoColor=white)
  ![Genshin](https://img.shields.io/badge/Genshin-6C63FF?style=flat-square)
</details>

## 更多信息

- 哔哩哔哩：[_极客小云_](https://space.bilibili.com/319065773?spm_id_from=333.1007.0.0)
- CSDN：[极客小云](https://blog.csdn.net/m0_73370855?type=blog)
- ORCID：[0009-0008-4777-304X](https://orcid.org/0009-0008-4777-304X)
- Docker Hub：[xy200303](https://hub.docker.com/u/xy200303)
- npm：[dev_xiaoyun](https://www.npmjs.com/~dev_xiaoyun)
- PyPI：[xiaoyun2003](https://pypi.org/user/xiaoyun2003/)
