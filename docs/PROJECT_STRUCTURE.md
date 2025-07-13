# 项目结构

本文档描述了MindCub3r项目的目录结构和主要文件的用途。

## 根目录

```
lego_cube/
├── .github/                    # GitHub相关配置
├── cn/                         # 中文版相关文件
├── docs/                       # 项目文档
├── .gitignore                  # Git忽略文件配置
├── CHANGELOG.md                # 版本历史记录
├── CODE_OF_CONDUCT.md          # 行为准则
├── CONTRIBUTING.md             # 贡献指南
├── InstallMC3-v2p2.rbf         # 安装程序
├── LICENSE                     # 许可证文件
├── mc3solver-v2p2.rtf          # 解魔方算法程序
├── MindCub3r-v1p0.pdf          # 构建指南PDF
├── MindCub3r-v2p2.ev3          # 英文版EV3程序
└── README.md                   # 项目主要说明文档
```

## .github目录

包含GitHub相关的配置文件，用于规范问题报告和拉取请求的格式。

```
.github/
├── ISSUE_TEMPLATE/             # 问题报告模板
│   ├── bug_report.md           # 错误报告模板
│   └── feature_request.md      # 功能请求模板
└── PULL_REQUEST_TEMPLATE.md    # 拉取请求模板
```

## cn目录

包含中文版相关的文件。

```
cn/
├── MindCub3r-v2p2-CN.ev3       # 中文版EV3程序
└── README.md                   # 中文版说明文档
```

## docs目录

包含项目的详细文档。

```
docs/
├── build_guide/                # 构建指南
│   ├── README.md               # 构建指南概述
│   ├── home_edition.md         # 家庭版构建指南
│   └── education_edition.md    # 教育版构建指南
├── images/                     # 文档图片
└── PROJECT_STRUCTURE.md        # 本文档
```

## 主要文件说明

### 程序文件

- **MindCub3r-v2p2.ev3**: 英文版EV3程序，用于控制机器人解魔方
- **cn/MindCub3r-v2p2-CN.ev3**: 中文版EV3程序，提供中文界面和语音提示
- **InstallMC3-v2p2.rbf**: 安装程序，用于初始化EV3
- **mc3solver-v2p2.rtf**: 解魔方算法程序，包含解魔方的核心算法

### 文档文件

- **README.md**: 项目的主要说明文档，提供项目概述和基本使用指南
- **CHANGELOG.md**: 记录项目的版本历史和变更内容
- **CONTRIBUTING.md**: 提供项目贡献指南
- **CODE_OF_CONDUCT.md**: 项目行为准则
- **LICENSE**: MIT许可证文件
- **MindCub3r-v1p0.pdf**: 详细的构建指南PDF文档

### 配置文件

- **.gitignore**: 配置Git忽略的文件和目录
- **.github/**: GitHub相关配置文件 