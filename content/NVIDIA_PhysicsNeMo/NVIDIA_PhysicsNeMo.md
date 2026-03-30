# NVIDIA_PhysicsNeMo框架
## 1.概述
NVIDIA PhysicsNeMo是一个开源深度学习框架，它使用最先进的SciML方法构建、训练、微调和推理物理AI模型，用于AI4science和工程领域。

| 成分 | 描述 |
|---|---|
| `physicsnemo.models` | 一系列经过优化、可定制且易于使用的模型架构，例如神经算子、图神经网络、扩散模型、Transformer 模型等等。 |
| `physicsnemo.datapipes` | 经过优化且可扩展的内置数据管道，可精细处理点云、网格等工程和科学数据结构。 |
| `physicsnemo.distributed` | 基于分布式计算子模块构建，使用 `torch.distributed` 只需几个步骤即可实现并行训练。 |
| `physicsnemo.curator` | 用于简化和加速工程数据集数据整理过程的子模块。 |
| `physicsnemo.sym.geometry` | 一个用于处理深度学习训练几何体的子模块，使用构造实体几何建模和 STL 格式的 CAD 文件。 |
| `physicsnemo.sym.eq` | 一个用于在深度学习训练中使用偏微分方程的子模块，其中包含几种常用方程的实现方式以及简单的自定义方法。 |

## 2.入门
### 2.1系统要求
+ Ubuntu 24.04
+ pip与本地 PyTorch 安装兼容的 NVIDIA 驱动程序
+ Python 版本 >= 3.10
### 2.2安装
我自己用的是PhysicsNeMo与uv，对于开发或运行存储库中的示例，可以使用uv克隆并安装依赖项：
```bash
git clone https://github.com/NVIDIA/physicsnemo.git
cd physicsnemo
uv sync --extra cu13
uv run python -c "import physicsnemo; print('PhysicsNeMo version:', physicsnemo.__version__)"
```
## 3.学习指南
### 3.1训练计划


