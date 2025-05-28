# Code Prompt Engineering

这是一个专注于 AI 编程助手的 prompt 工程项目，旨在优化和增强 AI 编程助手的能力和交互体验。

## 项目结构

```
.
├── Cursor/                 # Cursor AI 编程助手配置
│   └── frontend/
│       ├── global-cn.md   # 中文全局配置
│       └── global.md      # 英文全局配置
└── RooCode/               # RooCode AI 编程助手配置
    ├── PromptEnhance.md   # Prompt 增强工具
    └── frontend/
        └── role.md        # 角色定义配置
```

## 主要功能

### Cursor AI 编程助手

Cursor 部分包含了针对 Cursor AI 编程助手的全局配置，提供了中英文两个版本：
- `global.md`: 英文版全局配置
- `global-cn.md`: 中文版全局配置

这些配置文件定义了 AI 助手的基本行为、能力范围和交互方式。

### RooCode AI 编程助手

RooCode 部分包含了 RooCode AI 编程助手的核心配置：
- `role.md`: 定义了 RooCode 作为专业高级软件工程师的角色特征和能力范围
- `PromptEnhance.md`: 提供了一个 prompt 增强工具，用于优化用户输入的 prompt

## 使用说明

1. **Cursor 配置使用**
   - 选择合适的语言版本（中文/英文）
   - 将对应的全局配置应用到 Cursor AI 编程助手

2. **RooCode 配置使用**
   - 使用 `role.md` 中的配置来初始化 RooCode AI 编程助手
   - 使用 `PromptEnhance.md` 来优化和增强现有的 prompts

## 许可证

本项目采用 MIT 许可证。详情请参见 [LICENSE](LICENSE) 文件。
