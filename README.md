# \# Embodied AI Assessment: VLA/VLN \& Safety

# 

# 本项目为具身智能 (Embodied AI) 考核任务的代码库，主要侧重于视觉语言导航大模型 (VLA/VLN) 的部署、评估以及物理仿真环境的迁移。

# 

# > 💡 详细的开发日志、实验可视化与踩坑记录，请参阅我的 \[飞书开发文档]https://jcnfpy47hqel.feishu.cn/wiki/EClTwJrmxi2G8Dk5qoRcy6Nbn5d

# \## 🎯 考核核心任务

# 

# 1\. NaVILA-Bench 部署与评估\*\*：在 MP3D 场景下复现模型 eval 流程。

# 2\. 仿真环境迁移探索\*\*：尝试将 Habitat 格式的 3D 场景导入 NVIDIA Isaac Sim 5.1.0。

# 3\. UAV-VLN 基准测试设计\*\*：基于 `IndoorUAV` 探索无人机视觉语言导航的 benchmark。

# 4\. 文献调研与具身安全\*\*：梳理 Loco-manipulation 与 VLA 发展脉络，思考安全护栏机制。

# 

# \## 📂 仓库目录结构

# 

# \- `configs/`: 实验运行配置文件 (如 NaVILA 测评的 yaml 参数修改)。

# \- `scripts/`: 数据预处理与自动化评测脚本。

# \- `results/`: 关键实验指标记录与 log 输出。

# \- `assets/`: README 展示所需的相关截图或媒体文件。

# 

# \## 🛠️ 环境依赖

# 

# \* OS:Ubuntu 22.04 LTS

# \* Python: >= 3.8

# \* CUDA: >= 12.1

# 

# \## 🔄 核心改动与 Commit 规范说明

# 

# 本仓库的 commit 记录遵循常规的语义化标准，主要前缀包括：

# \* `feat:` 新增功能或脚本

# \* `fix:` 修复配置错误或 bug

# \* `docs:` 更新 README 或相关说明

# \* `chore:` 调整依赖或无关紧要的杂项

# 

# \---

# \*Developer: Zichen Li  | Date: 2026-05-17

