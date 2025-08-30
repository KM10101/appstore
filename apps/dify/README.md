# Dify

Dify 是一个开源的 LLM 应用开发平台，它的直观界面结合了 AI 工作流、RAG 管道、Agent 功能、模型管理、可观测性功能等，让您快速从原型到生产。

## 功能特性

- **工作流编排**: 在画布上构建和测试强大的AI工作流，利用企业级LLM的全部功能
- **全面的模型支持**: 与数百个专有/开源LLM以及数十个推理提供商和自托管解决方案无缝集成
- **提示IDE**: 用于制作提示、比较模型性能以及为基于聊天的应用程序添加文本转语音等其他功能的直观界面
- **RAG管道**: 广泛的RAG功能，涵盖从文档接收到检索的所有内容，支持从PDF、PPT和其他常见文档格式中提取文本
- **Agent功能**: 您可以基于LLM函数调用或ReAct定义Agent，并为Agent添加预构建或自定义工具
- **LLMOps**: 监视和分析应用程序日志和性能，使用生产数据持续改进提示、数据集和模型
- **后端即服务**: 所有Dify的功能都带有相应的API，因此您可以轻松将Dify集成到自己的业务逻辑中

## 系统要求

- CPU >= 2 Core
- RAM >= 4 GiB
- Docker 19.03 或更高版本
- Docker Compose 1.28 或更高版本


## 环境变量

- `PANEL_APP_PORT_HTTP`: Web访问端口，默认40080
- `DATABASE_PASSWORD`: 数据库密码
- `SECRET_KEY`: 应用密钥
- `REDIS_PASSWORD`: Redis密码


## 升级说明

升级时，由于插件安装等数据是放在volumes目录下的，所以需要把数据迁移到新的目录下。


## 技术支持

- 官方网站：https://dify.ai
- 官方文档：https://docs.dify.ai
- GitHub：https://github.com/langgenius/dify
- 社区讨论：https://github.com/langgenius/dify/discussions

## 注意事项

1. 首次启动需要进行初始化配置
2. 建议定期备份数据
3. 请根据实际需求调整资源配置
4. 确保防火墙开放对应端口