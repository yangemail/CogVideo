# 贡献指南

本项目可能还存在很多不完善的内容。 我们期待您在以下方面与我们共建仓库, 如果您完成了上述工作并愿意PR和分享到社区，在通过审核后，我们将在项目首页感谢您的贡献。

## 模型算法

- 模型量化推理支持 (Int4,Int8等量化工程)
- 模型多卡推理支持 / 模型推理并发工程
- 非 CUDA 架构 推理设备支持

## 模型工程 / 模型二次开发

- 模型微调示例 / 最佳提示词实践
- 视频超分/插帧，用于美化视频生成效果。
- 任何模型周边工具
- 任何使用CogVideoX开源模型制作的最小完整开源项目

## 代码规范

良好的代码风格是一种艺术，我们已经为项目准备好了`pyproject.toml`配置文件，用于规范代码风格。您可以按照以下规范梳理代码:

1. 安装`ruff`工具

```shell
pip install ruff
```

接着，运行`ruff`工具

```shell
ruff check tools sat inference
```

检查代码风格，如果有问题，您可以通过`ruff formate`命令自动修复。

```shell
ruff formate tools sat inference
```

如果您的代码符合规范，应该不会出现任何的错误。

## 命名规范

- 请使用英文命名，不要使用拼音或者其他语言命名。所有的注释均使用英文。
- 请严格遵循 PEP8 规范，使用下划线分割单词。请勿使用 a,b,c 这样的命名。