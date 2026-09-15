# 你好，我是 @yousizaitianqiong

我关注 **Applied Vision AI / Multimodal Systems**，也持续维护 Codex 桌宠和科学计算项目；重视可复现构建、清晰的许可边界和可以验证的工程交付。

Qwen3-VL · vLLM · FastAPI · structured outputs  
Dify workflow design · deterministic video preprocessing  
Python · C/CUDA · reproducible evaluation

## Current focus

- 应用视觉 AI、多模态推理、结构化结果和可复现评估。
- 整理脱敏的视觉道路监测工作流，连接媒体预处理、模型适配、证据整理和 HTTP API。
- 维护可复现的 Python/C 工具、测试、CI 和跨平台发布流程。
- 通过范围明确的 Issue、Pull Request 和代码审查参与开源协作。

## Verified experience

| 项目 | 技术与工程范围 | 状态 |
| --- | --- | --- |
| 蜀道云控视觉道路监测系统（脱敏经历） | Qwen3-VL-8B-Instruct、vLLM、FastAPI、Docker、结构化输出；双 GPU 私有推理、离线依赖治理、API 鉴权与合成输入验证 | 已验证的工程经历；不公开业务数据、部署配置或内部地址 |
| [vision-dual-model-workflow](https://github.com/yousizaitianqiong/vision-dual-model-workflow) | FastAPI、FFmpeg、Dify Workflow DSL、OpenAI-compatible Mock、合成媒体和自动化测试 | 公开脱敏 Demo；只验证媒体链路、协议边界和工作流接口，不代表真实模型效果 |
| [Yukie Head Pet](https://github.com/yousizaitianqiong/yukie-head-pet) | Python、PowerShell、精灵图工具、GitHub Actions | 原创项目；[v1.0.0](https://github.com/yousizaitianqiong/yukie-head-pet/releases/tag/v1.0.0) 已发布 |

## In validation

- Qwen 初筛 + 第二模型复核：复核模型、接口协议和授权边界仍在确认。
- Dify 工作流：公开 Demo 提供脱敏 DSL；实际业务编排仍需独立验证。
- 视频均匀抽帧：公开 Demo 已测试 `max_frames<=8`；真实链路的媒体样本和稳定性仍在验证。
- 租用 GPU 服务器冒烟与标注评估：只使用授权、脱敏或合成样本，尚未发布可复核性能指标。

## Open-source contributions

| 贡献 | 类型 | 当前状态 |
| --- | --- | --- |
| [PyGMT PR #4835](https://github.com/GenericMappingTools/pygmt/pull/4835) | Python API 维护与弃用参数清理 | 已由上游维护者合并 |
| [Bilibili-Evolved PR #5743](https://github.com/the1812/Bilibili-Evolved/pull/5743) | 播放器临时倍速状态修复 | 已由上游合并 |
| [Qwen3-VL PR #2119](https://github.com/QwenLM/Qwen3-VL/pull/2119) | 修复 qwen-vl-utils 项目链接元数据 | OPEN，等待上游处理；不涉及模型权重或推理代码 |
| [Codex Dream Skin PR #356](https://github.com/Fei-Away/Codex-Dream-Skin/pull/356) | 跨平台 CDP 响应边界与安全校验 | OPEN，等待维护者 Review |

## Selected projects

- [polygr-pfc](https://github.com/yousizaitianqiong/polygr-pfc)：上游项目的 fork，围绕 C、CUDA、Make、MPI 和可复现数值验证开展贡献；不将上游代码声明为原创。
- [mcd-mcp-ai-ordering-course](https://github.com/yousizaitianqiong/mcd-mcp-ai-ordering-course)：React/TypeScript、Node/TypeScript 和 Mock MCP 的课程项目，包含显式确认和测试边界。
- [Zeyin-Melody-Skin-for-Codex](https://github.com/yousizaitianqiong/Zeyin-Melody-Skin-for-Codex)：独立历史的派生主题项目，保留第三方素材和 Windows-only 边界。

## Skills

- **Python / FastAPI / vLLM**：应用服务、视觉模型适配、结构化输出和接口验证。
- **多模态工程**：Qwen3-VL、图像/短视频预处理、确定性抽帧和 Mock 协议测试。
- **Dify workflow design**：HTTP API、条件分支、脱敏 DSL 和业务流程编排。
- **C / CUDA / Make / MPI**：科学计算、构建流程和异构计算验证。
- **PowerShell / Shell / CI**：安装、构建、发布和跨平台回归测试。

医学 AI 与团队项目仅保留脱敏技术档案：[医学筛查协作记录](projects/plateau-retina-screening.md)、[鸟鸣平台协作记录](projects/bird-audio-platform.md)。个人主页和公开 Demo 不包含内网地址、账号、凭据、模型权重、真实道路媒体、线上配置或未经证实的性能指标。

## 联系与协作

与具体项目有关的问题，欢迎在对应仓库提交 Issue。其他开源协作可通过 GitHub 联系我：[@yousizaitianqiong](https://github.com/yousizaitianqiong)。
