# gpu-pde-solver
使用AMD GPU和HIP编程模型加速偏微分方程（PDE）的数值求解。本项目以热传导方程和拉普拉斯方程为例，实现了从CPU到GPU的有限差分求解器移植，并对比了加速性能。
## 项目目标
- 学习基于AMD ROCm的GPU异构计算
- 实现常见PDE的GPU并行求解（有限差分法）
- 验证AMD MI300X在科学计算场景中的加速效果
## 技术栈
- **硬件**: AMD MI300X (192GB HBM3)
- **平台**: AMD Developer Cloud (DigitalOcean GPU Droplet)
- **软件**: ROCm 6.4+, HIP, C++, g++
- **分析工具**: rocprof, hipcc
