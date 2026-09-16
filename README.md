# 👋 你好呀！我是 **RyaoVen** 🌟  
![访客量](https://komarev.com/ghpvc/?username=RyaoVen&color=ff69b4&style=flat-square)  
*(正在构建 Ven 生态...)*  

## 📌 **关于我** 📌  
- **坐标**：中国·开封 🌆  
- **学校**：河南大学 软件学院 · 软件工程（2024 级）🎓  
- **求职意向**：Go/Java 后端 · 全栈 · AI 应用开发实习 🚀（每周 4-5 天，可连续 4 个月+）  
- **技术方向**：Go 后端 + React 全栈 + Agent 基础设施（MCP / LLM 网关 / Harness）🤖  
- **邮箱**：ryaoven@163.com 📧  

## 🏭 **Ven 生态 · Ven 厂牌** 🏭  
> 我在自建一整套围绕 Agent 的个人生态：**业务侧全面 MCP 化、模型入口有网关、终端之上有 Harness、开发流程由 Agent 工作流驱动**——每个项目既是独立作品，也是生态的一环。

| 项目 📚 | 一句话 📝 | 状态 🚦 | 技术栈 👨‍💻 |
|---------|-----------|---------|------------|
| [ven-blog](https://github.com/RyaoVen/ven-blog) | 自研框架驱动的全栈博客，**已上线持续迭代**：插件系统 + docs 插件 + MCP 工具网关（14 action）+ AI 内容审核 worker（三态判定/失败安全） | 🟢 运行中 | Go · React 19 · MySQL · Redis · LLM |
| [VenHybird](https://github.com/RyaoVen/ven_hybird) | 自研 Go+Node 混合渲染框架：事件驱动 ISR、SSE 实时推送、机制性杜绝 hydration mismatch | 🟢 开源 | Go · Node.js · React 19 · SSE |
| **VenGateway** | LLM 聚合网关：多渠道路由/熔断重试、SSE 流式转发、冻结-结算计费（Lua 原子）、多级限流、跨协议统一 IR | 🔨 核心链路已通 | Go · Fiber · PostgreSQL · Redis |
| **VenWarehouse** | 智能仓储系统（项目带教）：单据流转 + 行锁库存不超卖（自动化并发实验）+ 治理模块（指标→规则告警→LLM 建议人在环），规划 MCP Server 让 Agent 对话式操作仓储 | 🔨 M1 已验收 · M2 进行中 | Spring Boot · Vue 3 · PostgreSQL |
| **VenNote** | AI Native 个人知识库：md 文件唯一真源 + SQLite FTS5 索引，**MCP 双模接入（20 tools）**、人机分级写权限、hooks 事件引擎 | 🔨 MVP | Electron · React · TypeScript |
| **VenHarness** | 「一切皆 Tool」的 Agent Harness 实验内核：微内核 8 工具、PGS 权限分级（G0-G4）、银行流水级审计、结构化沙箱执行 | 🔨 MVP · 48/48 测试 | TypeScript · MCP |
| **VenDevFlow** | Agent 驱动开发工作流：issue→plan→impl→review→pr→ship 六阶段 skill 链 + 五道人工确认门，全程 GitCode 工单/PR 留痕 | 🟢 日常在用 | ZCode Skill · GitCode API |

> 🗃️ 私有项目按里程碑逐步开源；dev 平台在 [GitCode](https://gitcode.com/liaoyutianyuan)，稳定后的完整版本会同步发布到 GitHub。

## 🔥 **我的技术栈** 🔥  
### 💻 **前端**  
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)  
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![HTML5/CSS3](https://img.shields.io/badge/HTML5·CSS3-E34F26?style=flat-square&logo=html5&logoColor=white)  
- 熟悉 React / Next.js，理解 SSR / SPA 渲染与水合机制；了解 Vue.js，Electron 桌面端实践

### 🛠️ **后端**  
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Fiber](https://img.shields.io/badge/Fiber-00ACC1?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)  
- 熟悉 Go（Fiber / fasthttp）与 Java（Spring Boot），Node.js 全栈；RESTful API 设计、JWT/Key 程序化鉴权

### 🤖 **AI / Agent**  
![MCP](https://img.shields.io/badge/MCP-协议接入-8A2BE2?style=flat-square) ![LLM](https://img.shields.io/badge/LLM-应用集成-FF6F00?style=flat-square&logo=openai&logoColor=white)  
- MCP 工具网关与 MCP Server 落地（工具鉴权/审计/分级权限）；LLM 应用（内容审核 worker、结构化输出、失败安全设计）
- Agent 工作流工程化：多 agent 开发流程、工具调用分发、评测驱动迭代

### 🗄️ **数据与工程化**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)  
- MySQL / PostgreSQL / Redis 使用与缓存设计；了解 Docker 容器化；GitHub Actions CI 实践

## 📊 **我的数据看板** 📊  
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=RyaoVen&theme=tokyonight&show_icons=true&count_private=true)  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RyaoVen&theme=vue&layout=compact&langs_count=6)  

### 🎯 **GitHub 等级评分**  
![GitHub Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RyaoVen&theme=github)  

## ✨ **生活碎片** ✨  
- **兴趣爱好**：编程 🖥️、摄影 📷、旅行 🌍  
- **座右铭**：Don't stop here , it isn't the end. 🍎  
- **近期目标**：拿到后端 / 全栈 / AI 应用实习 offer，把 Ven 生态逐步开源 💼  

如果我的项目对你有帮助，欢迎点个 ⭐ 支持一下！ 😊  
</br>  
*Last updated: 2026-09-17*  
