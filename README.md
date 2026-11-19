# 你好，我是 @yousizaitianqiong

我关注**应用视觉 AI、多模态系统和科学计算**，也维护 Codex 桌宠。重视可复现构建、清晰的许可边界和可验证的交付。

[个人作品集](https://yousizaitianqiong.github.io/) · [公开项目](#公开项目) · [开源贡献](#开源贡献)

## 公开项目

- **双模型视觉工作流 Demo** 使用 FastAPI、FFmpeg 和 Dify。用合成媒体和 Mock 接口验证预处理、HTTP 接口和工作流编排。[项目仓库](https://github.com/yousizaitianqiong/vision-dual-model-workflow)
- **Yukie Head Pet** 是为 Codex 制作的原创动画桌宠，提供 Python 打包和 PowerShell 安装工具。[项目仓库](https://github.com/yousizaitianqiong/yukie-head-pet) · [v1.0.0 发布](https://github.com/yousizaitianqiong/yukie-head-pet/releases/tag/v1.0.0)

## 开源贡献

- **IOR** · 修复 MPI-IO 合并传输并支持中断，修正未完成重复测量时的统计汇总。[已合并 #561](https://github.com/hpc/ior/pull/561) · [已合并 #550](https://github.com/hpc/ior/pull/550)
- **hypre** · 修复初始化前调用 `HYPRE_Finalize` 的行为。[已合并 #1621](https://github.com/hypre-space/hypre/pull/1621)
- **MFEM** · 修复 `ParSubMesh` 中旋转共享面的朝向处理。[已合并 #5518](https://github.com/mfem/mfem/pull/5518)

<a href="https://ghfind.com/u/yousizaitianqiong?ref=badge">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ghfind.com/api/card/mini/yousizaitianqiong?theme=dark&amp;lang=zh" />
    <img src="https://ghfind.com/api/card/mini/yousizaitianqiong?theme=light&amp;lang=zh" alt="ghfind 评分卡，查看 @yousizaitianqiong 的评分详情" width="440" />
  </picture>
</a>

<details>
<summary>更多开源贡献</summary>

**已合并**

- **PyGMT** · 移除 `Figure.velo` 中已弃用的参数。[PR #4835](https://github.com/GenericMappingTools/pygmt/pull/4835)
- **Bilibili-Evolved** · 修复临时加速影响倍速记忆的问题。[PR #5743](https://github.com/the1812/Bilibili-Evolved/pull/5743)
- **48tools** · 新增 SNH48 MCP 只读服务包。[PR #170](https://github.com/duan602728596/48tools/pull/170)
- **Codex Dream Skin** · 让 Windows 校验识别并报告横向溢出。[PR #386](https://github.com/Fei-Away/Codex-Dream-Skin/pull/386)

**等待上游处理**

- **Qwen3-VL** · 修复 `qwen-vl-utils` 的项目链接元数据。[PR #2119](https://github.com/QwenLM/Qwen3-VL/pull/2119)
- **Codex Dream Skin** · 限制回环 CDP 的 JSON 响应解析边界。[PR #356](https://github.com/Fei-Away/Codex-Dream-Skin/pull/356)

</details>

## 工程与研究经历

- **视觉道路监测（脱敏经历）** · 使用 Qwen3-VL-8B-Instruct、vLLM、FastAPI 和 Docker 实现双 GPU 私有推理。处理离线依赖，并用合成输入验证 API 鉴权和结构化输出。
- **科学计算实习（脱敏经历）** · 使用 Slurm 提交 GPU/HIP 仿真作业。完成大规模网格计算、CPU/HIP 一致性检查与输出审查。
- **医学影像模型训练** · 参与 RETFound、Adapter/PEFT 眼底图像分类模型训练与异步推理联调。相关论文共同一作在投。[脱敏技术档案](projects/plateau-retina-screening.md)
- **鸟鸣音频分类** · 参与 HuBERT 实验和识别流程联调。以第二作者发表 IEEE ECCST 2025 论文。[论文](https://doi.org/10.1109/ECCST68196.2025.11441174) · [脱敏技术档案](projects/bird-audio-platform.md)

## 正在验证

- 道路监测的第二模型选择、复核接口和授权范围仍在确认。实际业务的 Dify 编排和真实媒体链路稳定性仍待验证。公开 Demo 已验证 `max_frames <= 8` 的均匀抽帧。
- 梳理 vLLM 的连续批处理、PagedAttention、KV Cache 和推测解码。相关加速效果仍待实测。
- 整理 GPU/HIP 仿真和 RETFound/PEFT 训练的公开技术记录。GPU 冒烟测试与标注评估使用授权、脱敏或合成样本。尚未发布可复核的性能指标。

## 其他项目

- **polygr-pfc** 是相场方法项目的 fork。贡献涉及 C、CUDA、Make、MPI 和可复现数值验证。[仓库](https://github.com/yousizaitianqiong/polygr-pfc)
- **mcd-mcp-ai-ordering-course** 是课程项目。使用 React、Node.js、TypeScript 和 Mock MCP，涵盖显式确认与集成验收。[仓库](https://github.com/yousizaitianqiong/mcd-mcp-ai-ordering-course)
- **Zeyin-Melody-Skin-for-Codex** 是具有独立提交历史的派生主题，面向 Windows，并保留第三方素材声明。[仓库](https://github.com/yousizaitianqiong/Zeyin-Melody-Skin-for-Codex)

## 技术栈

- **应用 AI** · Python、Qwen3-VL、vLLM、FastAPI、Dify、RETFound/PEFT
- **科学计算** · C、FFTW、OpenMP、Slurm、HIP
- **工程交付** · PowerShell、Shell、GitHub Actions

## 联系与协作

项目问题欢迎在对应仓库提交 Issue。其他开源协作可通过 GitHub 联系我。[@yousizaitianqiong](https://github.com/yousizaitianqiong)
