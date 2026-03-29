# MVP Idea Generator Skill Pack

![MVP Idea Generator Banner](assets/banner.png)

一个从Reddit挖掘真实痛点并生成可落地的MVP方案的技能包。帮助独立开发者、SaaS创始人、跨境创业者和AI工具开发者快速验证产品创意，设计最小可行产品。

## 功能特性

- **垂直社区定位** - 自动发现高价值、高活跃度的Reddit Subreddit
- **痛点嗅探** - 从社区讨论中提取真实、高频的用户需求
- **MVP生成** - 设计单一核心功能、7天可构建的最小可行产品方案
- **验证文案** - 生成符合Reddit社区规范的验证帖模板
- **商业评分** - 客观评估项目的商业可行性（5维度评分系统）

## 安装

### 从GitHub克隆
```bash
git clone https://github.com/ange-web3/mvp-skills.git
cd mvp-skills
```

### 安装到OpenCode
将技能包复制到OpenCode的技能目录：
```bash
cp -r skills/* ~/.config/opencode/skills/
```

或者使用符号链接（推荐，便于开发）：
```bash
ln -s $(pwd)/skills/* ~/.config/opencode/skills/
```

### 验证安装
重启OpenCode，检查技能是否可用：
```
请列出所有可用的技能
```
你应该能看到 `mvp-idea-generator` 技能。

## 使用示例

### 基本使用
当用户提到产品创意验证、市场痛点分析或MVP设计时，技能会自动触发。

**示例1: AI写作工具创意验证**
```
用户输入: "我想做一个AI工具，但不知道做什么方向"
技能执行: 
1. 定位写作相关Subreddit
2. 发现"小说家需要角色一致性检查工具"的高频痛点
3. 设计"Character Consistency Checker" MVP
4. 生成验证帖草稿
5. 输出商业可行性评分（38/50，建议尝试）
```

**示例2: 跨境电商工具创意**
```
用户输入: "跨境电商卖家有什么痛点?"
技能执行:
1. 定位电商Subreddit
2. 发现"多平台库存同步困难"痛点
3. 设计"Simple Inventory Sync" MVP
4. 生成问题验证帖
5. 输出评分（32/50，建议细分市场）
```

## 技能包内容

### 主要技能
- **mvp-idea-generator** - MVP创意生成器，包含完整的五阶段工作流程

### 参考文档
- [社区定位指南](skills/mvp-idea-generator/references/subreddit-discovery-guide.md)
- [痛点分析框架](skills/mvp-idea-generator/references/pain-point-analysis-framework.md)
- [MVP设计原则](skills/mvp-idea-generator/references/mvp-design-principles.md)
- [商业化评分表](skills/mvp-idea-generator/references/commercial-scoring-rubric.md)

### 输出资产
- [验证帖模板](skills/mvp-idea-generator/assets/validation-post-templates.md)

## 工作流程

1. **垂直社区定位** - 找到高质量的目标Subreddit
2. **痛点嗅探** - 从社区讨论中提取真实需求
3. **MVP生成** - 设计7天可构建的最小可行产品
4. **验证文案** - 生成Reddit合规的验证帖
5. **商业化评分** - 评估项目可行性（50分制）

## 贡献指南

欢迎贡献！请遵循以下步骤：

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建 Pull Request

### 开发新技能
1. 在 `skills/` 目录下创建新的技能文件夹
2. 遵循技能包结构：
   ```
   your-skill/
   ├── SKILL.md          # 技能描述和指令
   ├── references/       # 参考文档（可选）
   └── assets/           # 输出资产（可选）
   ```
3. 更新本README的技能列表

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 联系方式

- Email: qson8888@gmail.com

## 致谢

- 感谢所有提供反馈和建议的独立开发者
- 感谢Reddit社区提供的真实用户痛点数据