# 你好，我是 @yousizaitianqiong

我关注 **视觉大模型私有化部署、AI 工作流与可复现工程**，也持续维护 Codex 桌宠和科学计算项目；重视清晰的许可边界和可以验证的项目交付。

## 当前重点

- 维护已发布的 Codex 桌宠项目 `yukie-head-pet`，持续改进安装体验、动画质量与兼容性。
- 完善相场方法相关科学计算代码的构建、复现与异构计算适配。
- 整理企业内网双模型视觉道路监测项目的脱敏 Demo，覆盖 Dify Workflow DSL、FastAPI、FFmpeg 视频抽帧和 OpenAI 兼容接口。
- 通过范围明确的 Issue、Pull Request 和代码审查参与开源协作。

## 简历项目索引

| 项目 | 技术方向 | 可公开内容 |
| --- | --- | --- |
| [蜀道云控双模型视觉道路监测系统](https://github.com/yousizaitianqiong/vision-dual-model-workflow) | Qwen3-VL、SenseNova-SI、vLLM、FastAPI、Dify、FFmpeg | 蜀道云控算法负责人项目经历；上线前完成租用服务器冒烟测试与准确率检验，验证后迁移至双 RTX A5000 离线环境正式投用；仓库仅提供脱敏 Demo |
| [`多晶石墨烯 PFC 数值模拟与超算加速工具链`](https://github.com/yousizaitianqiong/polygr-pfc) | C11、FFTW、OpenMP、MPI、CUDA、科学可视化 | 公开 fork 中的求解、后处理、构建与验证工作；不公开科研所内部作业参数 |
| [`高原眼病智能筛查平台`](projects/plateau-retina-screening.md) | RETFound、Adapter / PEFT、长尾分类、异步推理 | 脱敏架构、个人贡献和汇总指标；不公开私有数据、权重、服务配置或论文稿件 |
| [`处处闻啼鸟 - 鸟鸣声识别与应用平台`](projects/bird-audio-platform.md) | HuBERT、音频处理、Flask、地图与众包标注 | 脱敏技术档案与贡献边界；不转载团队源码、数据库、凭据、权重或音频素材 |
| [`Codex Dream Skin 跨平台主题适配`](https://github.com/yousizaitianqiong/Zeyin-Melody-Codex-Dream-Skin) | JavaScript、CSS、PowerShell、Node.js、回归验证 | 公开 fork、个人提交记录、跨平台主题包与版本适配 |
| [`Yukie Head Pet`](https://github.com/yousizaitianqiong/yukie-head-pet) | HTML、CSS、JavaScript、Python、PowerShell、GitHub Actions | 原创开源桌宠、浏览器 Demo、确定性打包、双平台 CI 与 v1.0.0 Release |

## 项目与贡献

| 项目 | 性质与技术 | 当前状态 |
| --- | --- | --- |
| [vision-dual-model-workflow](https://github.com/yousizaitianqiong/vision-dual-model-workflow) | 脱敏原创 Demo；FastAPI、FFmpeg、Dify Workflow DSL、OpenAI 兼容 Mock、Docker 与测试 | 提供图片 JPEG 规范化、视频最多 8 帧均匀抽取、双模型工作流和 CI；不包含企业数据、模型权重或生产配置 |
| [`yukie-head-pet`](https://github.com/yousizaitianqiong/yukie-head-pet) | 原创旗舰项目；使用 Python、PowerShell 和精灵图工具制作 Codex 桌宠 | [`v1.0.0`](https://github.com/yousizaitianqiong/yukie-head-pet/releases/tag/v1.0.0) 已发布；Linux/Windows CI、可复现打包、隔离安装和素材许可边界均已验证 |
| [PyGMT PR #4835](https://github.com/GenericMappingTools/pygmt/pull/4835) | 参与 [`GenericMappingTools/pygmt`](https://github.com/GenericMappingTools/pygmt) 的 Python API 维护 | 单文件弃用参数清理已由上游维护者合并；提交前通过 GMT 6.7.0 focused 测试、ruff 和秘密扫描 |
| [Bilibili-Evolved PR #5743](https://github.com/the1812/Bilibili-Evolved/pull/5743) | 修复播放器临时加速污染倍速切换记忆 | 已由上游合并；补充类型、Lint、构建和 diff 检查记录 |
| [Qwen3-VL PR #2119](https://github.com/QwenLM/Qwen3-VL/pull/2119) | 修复 qwen-vl-utils 项目链接元数据 | 已提交并等待上游处理；包含 TOML、构建、元数据和秘密扫描验证 |
| [LAMMPS PR #5172](https://github.com/lammps/lammps/pull/5172) | KSPACE energy-only 路径性能优化与回归测试 | 已提交阶段性实现；包含 CMake/Make、MPI、聚焦测试和格式检查记录 |
| [`polygr-pfc`](https://github.com/yousizaitianqiong/polygr-pfc) | [`abhpc/polygr-pfc`](https://github.com/abhpc/polygr-pfc) 的 fork；围绕 C、CUDA、Make 与 Shell 开展科学计算和工具链工作 | 贡献工作保留在 fork 中；不将上游代码声明为原创项目 |
| [`melody-chibi-trial`](https://github.com/yousizaitianqiong/melody-chibi-trial) | [`C26H52/melody-chibi-trial`](https://github.com/C26H52/melody-chibi-trial) 的 fork；使用 Python 改进 Codex 桌宠资源与打包 | 改进已提交为上游 [`PR #2`](https://github.com/C26H52/melody-chibi-trial/pull/2)，目前等待维护者审阅 |

## 可验证的技术方向

- **Python**：资源验证、桌宠打包与自动化工具。
- **C / CUDA / Make**：相场方法相关科学计算代码与构建流程。
- **视觉大模型与 AI 应用**：Qwen3-VL、SenseNova-SI、vLLM、FastAPI、Dify、FFmpeg、多模态文件处理。
- **PowerShell / Shell**：Windows 安装、构建和发布辅助脚本。
- **开源工程**：可复现步骤、最小测试、Release 资产和许可证边界。

医学 AI 与团队项目只公开脱敏技术档案；私有数据、模型权重、服务配置、团队源码和未发表稿件均不发布。

## 联系与协作

与具体项目有关的问题，欢迎在对应仓库提交 Issue。其他开源协作可通过 GitHub 联系我：[@yousizaitianqiong](https://github.com/yousizaitianqiong)。
