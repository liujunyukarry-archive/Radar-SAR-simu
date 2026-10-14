# 仓库使用指南 / Repository Guide

这是 MATLAB 的雷达与合成孔径雷达（Synthetic Aperture Radar，SAR）仿真项目。**原始 README、作者署名、联系方式和 LICENSE 保持不变**；本文件只是补充文件导航，不表示已取得或改变原作归属。

## 源码入口

| 文件 | 内容 |
| --- | --- |
| `lfmPulseCompression.m` | 线性调频（LFM）脉冲压缩仿真 |
| `radarImaging_withDotsTarget.m` | 点目标雷达成像示例 |
| `rect.m` | 点目标示例的辅助函数 |
| `realDataProsessing.m` | 原始雷达数据处理示例（保留原始拼写） |

## 使用建议

打开 MATLAB，先检查各脚本中的路径、输入文件和工具箱调用，再按原 [README.md](README.md) 提供的数据获取说明准备真实数据。点目标案例应与 `rect.m` 放在同一 MATLAB 可搜索路径下。

**未对 MATLAB 版本、数据下载链接或脚本输出做运行验证。** 不应在未经实际比较时重命名函数文件或合并算法，避免破坏调用关系。

## 规范化边界

- 保留原有文件名和许可信息，特别是对外部引用可能有影响的脚本入口。
- 将未来生成的中间图像、结果和大型数据与源码分开管理，并补充复现实验步骤。
- 禁止在 README 中额外公布敏感凭据；已有原作者信息不作归属更改。
