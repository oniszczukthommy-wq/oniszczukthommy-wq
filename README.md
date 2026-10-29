# Hi, I'm Yuanhang Zhou (周远航) 👋

AI Product Manager building local-first AI tools and agents — from PRD and user research all the way to a runnable demo.
I focus on Agent product design, human-in-the-loop decision flows, and shipping small, opinionated products end to end.

📕 [Xiaohongshu](https://www.xiaohongshu.com/user/profile/5cd98bab0000000010005b08) · ✉️ oniszczukthommy@gmail.com · 📍 Open to AI PM / FDE roles (Singapore)

---

## 🚀 Featured Projects

### Runnable Demos（可本地跑起来的产品原型）

🔭 **[film-shot-agent](https://github.com/oniszczukthommy-wq/film-shot-agent)** — *Cinematic shot & line search agent*
A personal agent that finds frames and lines with natural language: faceted search on palette / brightness / color temperature, subtitle context aligned to the timeline, one-click MP4 / GIF clip export, and an annotated reference board. FastAPI + SQLite + ffmpeg, 58 offline tests; all footage under CC BY 3.0.
> 影视镜头与台词检索 Agent：一句话找画面、找台词、切片导出、收参考板；规则驱动，Agent 每一步的检索调用与耗时都摊开在 trace 面板里。

🕵️ **[night-shift-ai-detective](https://github.com/oniszczukthommy-wq/night-shift-ai-detective)** — *夜班档案 · 狐狸警官*
A third-person browser detective game with a DeepSeek case generator: schema-validated JSON cases (3 / 4 / 6 NPCs, 4 physical clues, uniquely solvable), NPCs holding only partial facts with possible lies, evidence cross-checking and case submission. Three.js + Node, paired with a 32 KB PRD.
> AI 探案游戏：先写 PRD 再做可玩 Demo；案件生成器带人数 / 物证 / 凶手在场 / 线索指向关系校验，NPC 只收到自身事实与对话历史。

### Product Design & Systems（产品设计与工作台）

🎵 **[Osmanthus](https://github.com/oniszczukthommy-wq/Osmanthus)** — *音乐与 MV 创作工作台*
Two connected studios under one local entry. Music side: idea → editable lyrics → two song versions → stem preview → score export. MV side: free canvas, storyboard clips, material upload, subtitles and MP4 export. Local-first; large media stored in Releases with checksum verification.
> AI 音乐 + MV 一体化工作台：想法 → 歌词确认 → 双版本歌曲 → 分轨试听 → MV 分镜画布剪辑导出。

🧰 **[blue-pm-workbench](https://github.com/oniszczukthommy-wq/blue-pm-workbench)** — *Blue PM 工作台*
A local PM cockpit: multi-source web teardown → requirement interview → human-confirmed PRD versions → technical plan → development task board; every AI edit shows a diff before it is saved. Built on the open-source agent-blueprint (MIT); personal extensions are listed in [PERSONAL_EXTENSIONS.md](https://github.com/oniszczukthommy-wq/blue-pm-workbench/blob/main/PERSONAL_EXTENSIONS.md).
> 面向个人的 PM 工作台：产品拆解、需求访谈、PRD 版本管理、技术方案与任务看板走同一条流程。

### Frontend & Landing

🌌 **[astronavi-landing](https://github.com/oniszczukthommy-wq/astronavi-landing)** — 天文通 APP 官网落地页
Single-file cinematic landing page: Three.js parallax star field, meteors, interactive solar system, procedural moon phase, GSAP scroll narrative, `prefers-reduced-motion` fallback. [Live preview](https://hcn4pc1ewda5.doubaoapps.com/app/app_17etd2u5kmk).

---

## ✍️ Writing

Notes on AI products and model capabilities, from a product lens:

- [Jev爆火背后：AI模型正在从"什么都能聊"走向"只做一件事"](https://mp.weixin.qq.com/s/QUxastjphzBssuFruJr6sg)
- [降本不是口号：Haiku 5.5 让「子 Agent 批量跑」第一次算得过来](https://mp.weixin.qq.com/s/ZgMWDtMdYGFYiIBSBTWsIw)
- [我试了一圈 Personal Agent，发现离"私人助手"还很远](https://mp.weixin.qq.com/s/Sh5ovTCxbSKS5OEx1J-vDw)
- [GPT-6.1 Sol Ultrafast：OpenAI 第一次为"等待"明码标价](https://mp.weixin.qq.com/s/DuEMzBfzs7_CtYghjG_kMA)
- [以后用 AI 会越来越便宜？把这半个月串起来看](https://mp.weixin.qq.com/s/fDG-FzectUcqSNrbTZhkSA)
- [上下文窗口都 100 万了，为什么还要"管"它？](https://mp.weixin.qq.com/s/4PUOSkDSiCv7efrppSAfdQ)
- [Meta 发新模型：不比聪明了，开始比"记得住你"](https://mp.weixin.qq.com/s/HRU1zZ16ghBhEl00FeZS_Q)
- [美团把 Agent 评测讲透了：你缺的不是更强的模型](https://mp.weixin.qq.com/s/HqG0J7VP1I0YfnmvGIMklw)
- [DeepSeek 又掀桌：不涨价、开源、还白送搜索 API](https://mp.weixin.qq.com/s/rZJbuQYhuMimzu5kRQGdTQ)
- [48 小时内，DeepSeek 和 MiniMax 把"平替"两个字撕碎了](https://mp.weixin.qq.com/s/VuIUx3TnMq3rTwCHrp10Yg)

---

## Toolbox

- **Product**: PRD writing, requirement interviews, competitive teardown research, user journey design, acceptance criteria
- **Build**: Python · FastAPI · SQLite · Node.js · Three.js · FFmpeg · DeepSeek / DashScope / Qwen APIs · prompt & agent design · uv / pnpm
- **Principles**: local-first; human confirmation before AI writes anything permanent; deterministic guardrails over model self-control

## About

- AI Product Manager in training toward AI PM / Forward Deployed Engineer roles
- I care that an idea becomes something a reviewer can actually run and judge
- Open to AI PM / FDE opportunities in Singapore
