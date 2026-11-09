<div align="center">

<h1>JOO<sub>随手记 · Field Notes</sub></h1>

<p>代码、实验，还有一点好奇心<br />Code, experiments, and a little curiosity.</p>

<br />

<img src="https://raw.githubusercontent.com/JOO5216/huahua-codex-pet/main/assets/previews/waving.gif" width="88" alt="花花挥手打招呼" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3000&pause=1600&color=84965B&center=true&vCenter=true&width=680&height=48&lines=Hi%2C+I%27m+JOO.+Welcome+to+my+workspace.;Exploring+AI%2C+data+and+visual+computing.;Small+tools.+Real+problems.+Work+in+progress.)](https://github.com/JOO5216)

**管理科学与工程 · Management Science & Engineering**  
本科管理科背景 → 研究生工科背景  
Undergraduate studies in Management → Graduate studies in Engineering

![AI+](https://img.shields.io/badge/AI%2B-4F7E99?style=flat)
![Data Governance](https://img.shields.io/badge/Data_Governance-B27C2A?style=flat)
![Data Science](https://img.shields.io/badge/Data_Science-816C9D?style=flat)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-42847C?style=flat)
![Digital Humans](https://img.shields.io/badge/Digital_Humans-748931?style=flat)

[![Projects](https://img.shields.io/badge/EXPLORE-Projects-4F7E99?style=flat&labelColor=283024)](#02--selected-projects)
[![Toolbox](https://img.shields.io/badge/OPEN-Toolbox-B27C2A?style=flat&labelColor=283024)](#03--toolbox)
[![Digital Garden](https://img.shields.io/badge/VISIT-Digital_Garden-816C9D?style=flat&labelColor=283024)](https://joo5216.github.io/JOO5216/)
[![GitHub](https://img.shields.io/badge/FIND_ME-GitHub-748931?style=flat&labelColor=283024&logo=github)](https://github.com/JOO5216)

</div>

---

## 🍃 01 / 关于我 · About me

你好，我是 **JOO**，专业是管理科学与工程，本科为管理科背景，研究生为工科背景。主要关注 **AI+、数据治理、数据科学、大数据决策、计算机视觉和数字人**。

最近在做简历填写助手、媒体数据采集和视觉质检工具。我喜欢从具体的问题出发，把想法做成可以使用的小工具。这里记录项目进展、遇到的问题，也放一些因为有趣而做的小东西，比如花花桌宠。

Hi, I'm **JOO**. My field is **Management Science and Engineering**, with an undergraduate background in management and a graduate background in engineering. My interests include **AI applications, data governance, data science, big-data-driven decision-making, computer vision, and digital humans**.

Recently, I've been working on a résumé assistant, media data collection scripts, and visual quality-checking tools. I enjoy starting with a practical problem and turning an idea into something usable. This space collects my projects, progress, and things I'm still figuring out—with room for playful side projects like Huahua, my desktop companion.

> **☕ 工作台上 / On my desk**  
> 简历与浏览器自动化 · 媒体数据采集 · 视觉质量检查  
> Résumé & browser automation · Media data collection · Visual quality checks  
> **🌱 番外 / Side quest** — 给工作台添一只叫「花花」的桌宠。  
> A desktop companion named Huahua, just for a little company.

<a id="02--selected-projects"></a>

## 📚 02 / 项目记录 · Selected projects

### 📝 01 — 简历填写助手 / Resume Copilot

[![Repository](https://img.shields.io/badge/VIEW_REPO-resume-4F581B?style=flat&logo=github&labelColor=283024)](https://github.com/JOO5216/resume)
![Browser Extension](https://img.shields.io/badge/Browser_Extension-A95A4A?style=flat)
![Local LLM](https://img.shields.io/badge/Local_LLM-42847C?style=flat)
![Human in the Loop](https://img.shields.io/badge/Human_in_the_Loop-748931?style=flat)

<img src="https://raw.githubusercontent.com/JOO5216/resume/main/assets/icons/icon-128.png" width="64" alt="简历助手图标" />


**把整理简历、对应网页字段和重复填写这几件事，放进一个浏览器侧栏。**

支持从 PDF、DOCX 和 TXT 提取文字，借助 AI 整理简历，再将经历对应到网页字段。填写前可以检查预览、调整来源和勾选范围；最终提交仍由使用者完成。

- **流程：** 文字提取 → 简历草稿 → 字段对应 → 核对后填写。
- **实现：** Chrome / Edge 扩展，本机 Qwen 模型与 llama.cpp，可处理多段经历和部分复杂控件。
- **当前进展与范围：** 已有扩展与本机模型流程验证；真实招聘网站做过只读识别，实际填写兼容性仍需逐站验证。

**A browser sidebar for organizing résumés, matching form fields, and reducing repetitive typing.**

The extension extracts text from PDF, DOCX, and TXT files, uses AI to organize résumé information, and maps experience entries to web form fields. Users can review the preview, adjust data sources, and select fields before filling. The final application submission remains manual.

- **Workflow:** Text extraction → Résumé draft → Field mapping → Review and fill.
- **Implementation:** A Chrome / Edge extension with local Qwen inference through llama.cpp, supporting multiple experience entries and selected complex controls.
- **Current scope:** The extension and local-model workflow have been tested. Checks on real recruitment sites have been read-only; actual filling compatibility still needs site-by-site validation.

<details>
<summary>查看功能流程 / Inside the project</summary>

![简历填写助手功能流程](https://raw.githubusercontent.com/JOO5216/resume/main/docs/%E6%8F%92%E4%BB%B6%E5%8A%9F%E8%83%BD%E6%B5%81%E7%A8%8B.svg)

</details>

### 🔍 02 — 媒体采集与视觉质检 / Visual Data QC

[![Repository](https://img.shields.io/badge/VIEW_REPO-media--cv--qc-4F581B?style=flat&logo=github&labelColor=283024)](https://github.com/JOO5216/tt-ins-yt-media-cv-qc)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-4F7E99?style=flat)
![OCR](https://img.shields.io/badge/OCR-B27C2A?style=flat)
![VLM](https://img.shields.io/badge/VLM-816C9D?style=flat)
![Data Quality](https://img.shields.io/badge/Data_Quality-A95A4A?style=flat)

**采集之后，继续检查素材的规格，以及画面里需要留意的内容。**

从 TikTok 博主发现与封面采集出发，结合人脸检测、OCR 和视觉语言模型做图片初筛；本地视频工具则检查编码、尺寸、帧率、时长和抽样帧中的人脸尺寸。

- **流程：** 内容发现 → 封面采集 → 图片初筛；另提供本地视频检查入口。
- **实现：** Python、Playwright、FFmpeg / FFprobe、InsightFace、YuNet、SmolVLM。
- **当前进展与范围：** 机器初筛辅助人工检查；抽样通过不代表全片合格。目前不包含 Instagram / YouTube 专用采集器。

**After collection, check media specifications and flag visual details that need a closer look.**

The toolkit covers TikTok creator discovery and cover-image collection, with face detection, OCR, and a vision-language model for preliminary image screening. Separate local-video tools inspect codecs, dimensions, frame rates, duration, and face sizes in sampled frames.

- **Workflow:** Content discovery → Cover collection → Image screening, with separate entry points for local-video checks.
- **Implementation:** Python, Playwright, FFmpeg / FFprobe, InsightFace, YuNet, and SmolVLM.
- **Current scope:** Automated screening supports human review. Passing sampled-frame checks does not establish that an entire video meets requirements. There are currently no dedicated Instagram or YouTube collectors.

<a id="03--toolbox"></a>

## 🧰 03 / 技术工具箱 · Toolbox

<p align="center">
<img src="https://skillicons.dev/icons?i=python,js,html,css,sqlite,git&theme=light&perline=6" alt="Python JavaScript HTML CSS SQLite Git" />
</p>

**💻 项目里的语言与存储 / Languages & Storage**

![Python](https://img.shields.io/badge/Python-816C9D?style=flat&logo=python&logoColor=F2F0E6)
![JavaScript](https://img.shields.io/badge/JavaScript-A95A4A?style=flat&logo=javascript&logoColor=F2F0E6)
![HTML](https://img.shields.io/badge/HTML-42847C?style=flat&logo=html5&logoColor=F2F0E6)
![CSS](https://img.shields.io/badge/CSS-748931?style=flat&logo=css&logoColor=F2F0E6)
![SQLite](https://img.shields.io/badge/SQLite-4F7E99?style=flat&logo=sqlite&logoColor=F2F0E6)

**🧠 模型与视觉工具 / AI & Visual Computing**

![Qwen](https://img.shields.io/badge/Qwen-B27C2A?style=flat)
![llama.cpp](https://img.shields.io/badge/llama.cpp-816C9D?style=flat)
![SmolVLM](https://img.shields.io/badge/SmolVLM-A95A4A?style=flat)
![InsightFace](https://img.shields.io/badge/InsightFace-42847C?style=flat)
![YuNet](https://img.shields.io/badge/YuNet-748931?style=flat)
![OCR](https://img.shields.io/badge/OCR-4F7E99?style=flat)

**⚙️ 自动化与媒体处理 / Automation & Media**

![Playwright](https://img.shields.io/badge/Playwright-B27C2A?style=flat)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-816C9D?style=flat&logo=googlechrome&logoColor=F2F0E6)
![FFmpeg](https://img.shields.io/badge/FFmpeg-A95A4A?style=flat&logo=ffmpeg&logoColor=F2F0E6)
![Git](https://img.shields.io/badge/Git-42847C?style=flat&logo=git&logoColor=F2F0E6)
![PowerShell](https://img.shields.io/badge/PowerShell-748931?style=flat)
![Codex](https://img.shields.io/badge/Codex-4F7E99?style=flat)

<sub>这里列的是现有项目涉及的技术和工具；上方的方向标签则是我关注和探索的领域。<br />These are technologies and tools used in the existing projects. The direction badges above describe my areas of interest and exploration.</sub>

## 🌼 04 / 番外：花花 · Side quest: Huahua

[![Huahua](https://img.shields.io/badge/MEET-HUAHUA-B27C2A?style=flat&labelColor=283024)](https://github.com/JOO5216/huahua-codex-pet)
![Creative Coding](https://img.shields.io/badge/Creative_Coding-816C9D?style=flat)
![Sprite Animation](https://img.shields.io/badge/Sprite_Animation-A95A4A?style=flat)

<p align="center">
<img src="https://raw.githubusercontent.com/JOO5216/huahua-codex-pet/main/assets/previews/idle.gif" width="112" alt="花花：待机" />
<img src="https://raw.githubusercontent.com/JOO5216/huahua-codex-pet/main/assets/previews/review.gif" width="112" alt="花花：检查结果" />
<img src="https://raw.githubusercontent.com/JOO5216/huahua-codex-pet/main/assets/previews/jumping.gif" width="112" alt="花花：跳跃" />
</p>

<p align="center"><sub>☕ 陪伴 / Just here &nbsp; · &nbsp; 🔎 检查 / Reviewing &nbsp; · &nbsp; ✨ 小小进展 / Little wins</sub></p>

工作台上也留一点好玩的东西。

花花是一只 Codex 动画桌宠，会眨眼、跑动、挥手，也会在等待输入、执行任务和检查结果时切换动作。她还会跟着鼠标转动视线。

A little room on the desk for something playful.

Huahua is an animated Codex desktop companion. She blinks, runs, waves, and changes her actions while waiting for input, executing tasks, or reviewing results. Her gaze also follows the mouse pointer.

<details>
<summary>展开动作预览 / Meet Huahua</summary>

![花花动作预览](https://raw.githubusercontent.com/JOO5216/huahua-codex-pet/main/assets/previews/action-sheet.png)

</details>

---

<div align="center">

**继续探索，继续动手**  
有些问题还没解决，有些想法刚刚开始。

**Still exploring. Still building.**  
Some questions remain open. Some ideas are just getting started.

[![All Projects](https://img.shields.io/badge/ALL_PROJECTS-JOO5216-4F581B?style=flat&logo=github&labelColor=283024)](https://github.com/JOO5216?tab=repositories)
[![Garden](https://img.shields.io/badge/PERSONAL_SPACE-Digital_Garden-748931?style=flat&labelColor=283024)](https://joo5216.github.io/JOO5216/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:283024,55:4B5320,100:708238&height=100&section=footer&animation=twinkling" width="100%" alt="Olive green footer" />

</div>
