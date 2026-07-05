# SES - Shiyu Engineering Standard

SES（Shiyu Engineering Standard）是一套面向控制系统工程的个人工程标准、知识库与模板体系。

它的长期目标是沉淀一个可持续维护的 Engineering Brain，用于支撑 UUV、USV、PLC 自动化控制系统以及相关软件、通信、文档和调试工作。

## Mission

> Build an Engineering Brain.

## 当前版本

当前阶段：SES v0.1 Foundation

本阶段重点不是完成某一个具体系统，而是建立稳定的工程知识库结构、基础规范和协作方式。

## 覆盖领域

- UUV：大型无人潜航器相关控制系统工程。
- USV：无人船导航、航迹、避障与运动控制。
- PLC：工业自动化控制系统、SCADA、历史数据与现场调试。
- Communication：工业通信、设备协议、网络与数据链路。
- Control Algorithms：PID、LOS、路径跟踪、状态估计与工程化控制算法。
- Software：C#、Python、工具链、仿真、测试与数据处理。
- Documents：工程文档、方案、调试记录、测试报告。
- Drawings：系统图、控制框图、IO 图、通信拓扑图。
- AI：AI 协作规范、提示词、代码生成与审查流程。

## 工程原则

- Engineering First
- Reliability First
- Maintainability First
- Scalability First
- Safety First

核心判断标准：

> 工程可实施性 > 理论最优

## 目录结构

```text
SES/
├── README.md
├── AGENTS.md
├── LICENSE
├── CHANGELOG.md
├── PROJECT_CONTEXT.md
├── ENGINEERING_PRINCIPLES.md
├── DEVELOPMENT_WORKFLOW.md
├── CODING_STANDARD.md
├── DOCUMENT_STANDARD.md
├── DRAWING_STANDARD.md
├── 00-Core/
├── 01-UUV/
├── 02-USV/
├── 03-PLC/
├── 04-Communication/
├── 05-ControlAlgorithms/
├── 06-Software/
├── 07-Documents/
├── 08-Drawings/
├── 09-Templates/
└── 10-AI/
```

## 使用方式

1. 新工程启动前，先阅读 `PROJECT_CONTEXT.md` 和 `ENGINEERING_PRINCIPLES.md`。
2. 编写代码前，参考 `CODING_STANDARD.md`。
3. 输出文档前，参考 `DOCUMENT_STANDARD.md`。
4. 绘制系统图、控制框图、IO 图、通信图前，参考 `DRAWING_STANDARD.md`。
5. 与 AI 协作时，参考 `AGENTS.md` 和 `10-AI/`。

## 维护策略

SES 应持续迭代。每一次真实工程中的设计决策、调试经验、失败案例、复盘结论，都应被沉淀到对应目录中。
