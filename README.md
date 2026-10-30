# 你好，我是 zongemory-spec

这里记录我的个人学习与项目实践：从可直接体验的产品，到可复现的检索、Agent 安全和身份认证实验。

关注 **产品交付、数据权限、结果可解释性与验证证据**。项目使用 AI 辅助开发，保留来源、实现边界和可复现步骤；不将课程原型描述为生产级系统。

## 重点项目

| 项目 | 做了什么 | 体验与证据 |
| --- | --- | --- |
| [我们的恋爱日记](https://github.com/zongemory-spec/couple_diary) | 从独立双人部署演进为邮箱注册、邀请绑定与多小屋隔离，包含回忆、心愿和见面计划 | [在线体验](https://couple-diary-v02.pages.dev/) · [反馈与验收](https://github.com/zongemory-spec/couple_diary/blob/main/docs/FEEDBACK.md) |
| [Enterprise RAG Agent](https://github.com/zongemory-spec/enterprise-rag-agent) | 授权检索、BM25、有界查询改写、多轮澄清与评测门禁；区分默认离线和可选真实模型能力 | [演示路线](https://github.com/zongemory-spec/enterprise-rag-agent/blob/main/docs/SHOWCASE.md) · [评测报告](https://github.com/zongemory-spec/enterprise-rag-agent/blob/main/reports/v4.2-dev.md) |
| [Agent Security Lab](https://github.com/zongemory-spec/agent-security-lab) | 服务端工具与对象鉴权、独立审批、单次消费和记忆隔离；用合成场景验证权限边界 | [审批演示](https://github.com/zongemory-spec/agent-security-lab/blob/main/docs/APPROVAL_DEMO.md) · [实验结果](https://github.com/zongemory-spec/agent-security-lab/blob/main/docs/SECURITY_RESULTS.md) |
| [击键动力学认证](https://github.com/zongemory-spec/keystroke-authentication) | 固定文本事件采集、31 维时序特征、马氏距离与个人阈值，保留合成验证和真人评测的区别 | [实验方法](https://github.com/zongemory-spec/keystroke-authentication/blob/main/docs/EXPERIMENT.md) · [合成报告](https://github.com/zongemory-spec/keystroke-authentication/blob/main/reports/showcase-evidence.json) |

## 其他课程实践

- [SM2 / SM3 Signature Lab](https://github.com/zongemory-spec/sm2-sm3-signature-system)：原文字节签名、显式旧版兼容、已知向量与 OpenSSL 双向验签。
- [SQL 拼接教学模拟器](https://github.com/zongemory-spec/sql-injection-learning-demo)：用本地虚构档案演示拼接查询与选定绕过模式，不连接真实 SQL 数据库。
- [智能错题本](https://github.com/zongemory-spec/intelligent-error-book)：本地错题管理、间隔复习与无 Key 预设解析演示，不冒充实时 AI 或 OCR。

## 项目中的技术实践

- **应用与界面**：Python、JavaScript / TypeScript、React、FastAPI、Flask、Tkinter。
- **数据与部署**：PostgreSQL、SQLite、Supabase、Cloudflare Pages。
- **检索与 Agent**：BM25、可选向量与混合检索、LangChain / LangGraph、Function Calling。
- **验证方式**：自动化回归、合成案例、独立实现对照、真实服务分项验收。

每个项目的运行步骤、测试证据与已知限制都放在对应仓库。欢迎围绕具体实现、复现步骤和设计取舍交流。
