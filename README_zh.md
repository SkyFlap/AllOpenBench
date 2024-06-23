# 基准分数文档

欢迎来到基准分数文档项目！该项目旨在记录和组织各种模型在不同基准上的分数。所有文件均为 Markdown 格式，以确保易读性和可维护性。

## 目录

- [基准分数文档](#基准分数文档)
  - [目录](#目录)
  - [项目概述](#项目概述)
  - [目录结构](#目录结构)
    - [目录详情](#目录详情)
  - [使用方法](#使用方法)
  - [贡献](#贡献)
  - [许可证](#许可证)

## 项目概述

本项目旨在将不同模型在各种基准上的分数整合到一个结构良好的存储库中。每个基准和模型都有专门的文件来提供详细信息和分数。

## 目录结构

```plaintext
benchmark-scores/
├── README.md
├── benchmarks/
│   ├── benchmark1/
│   │   ├── overview.md
│   │   ├── model1.md
│   │   ├── model2.md
│   │   └── ...
│   ├── benchmark2/
│   │   ├── overview.md
│   │   ├── model1.md
│   │   ├── model2.md
│   │   └── ...
│   └── ...
├── models/
│   ├── model1.md
│   ├── model2.md
│   └── ...
└── summary/
    ├── all_benchmarks.md
    ├── benchmark1_summary.md
    ├── benchmark2_summary.md
    └── ...
```

### 目录详情

- **benchmarks/**: 包含每个基准的目录。每个目录包括：
  - `overview.md`: 基准的一般描述和方法。
  - 各个模型的分数文件（例如，`model1.md`，`model2.md`）。

- **models/**: 包含每个模型的文件，提供详细信息，如作者、版本、应用领域和描述。

- **summary/**: 包含摘要文件：
  - `all_benchmarks.md`: 所有基准和模型分数的概述。
  - 各个基准的摘要文件（例如，`benchmark1_summary.md`，`benchmark2_summary.md`）。

## 使用方法

使用此文档：

1. 浏览 `benchmarks/` 目录以查找特定基准的详细信息和各模型的分数。
2. 查看 `models/` 目录以获取每个模型的详细信息。
3. 参考 `summary/` 目录以获取基准和模型的概述和比较分析。

## 贡献

我们欢迎贡献！如果您想要贡献：

1. Fork 这个存储库。
2. 创建一个新分支（`git checkout -b feature-branch`）。
3. 提交您的更改（`git commit -am 'Add new feature'`）。
4. 推送到分支（`git push origin feature-branch`）。
5. 创建一个新的 Pull Request。

请确保您的贡献与现有文件结构和命名约定保持一致。

## 许可证

本项目使用 MIT 许可证。有关更多详情，请参阅 [LICENSE](LICENSE) 文件。