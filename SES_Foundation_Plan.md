# SES（Shiyu Engineering Standard）项目规划（Foundation）

## 项目愿景

SES（Shiyu Engineering
Standard）定位为个人控制系统工程标准，是一套长期维护的工程知识库、开发规范和模板体系。

### Mission

> Build an Engineering Brain.

------------------------------------------------------------------------

## 三大领域

1.  UUV（大型无人潜航器）
2.  USV（无人船）
3.  PLC 自动化控制系统

覆盖控制算法、PLC、C#、Python、工业通信、系统图、技术文档、调试经验和 AI
协作。

------------------------------------------------------------------------

## 版本规划

-   SES v0.1 Foundation
-   SES v0.5 Engineering
-   SES v1.0 Professional
-   SES v2.0 Enterprise

------------------------------------------------------------------------

## 推荐目录

``` text
SES/
├── README.md
├── AGENTS.md
├── LICENSE
├── CHANGELOG.md
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

------------------------------------------------------------------------

## 工程理念

-   Engineering First
-   Reliability First
-   Maintainability First
-   Scalability First
-   Safety First

核心原则：

> 工程可实施性 \> 理论最优

------------------------------------------------------------------------

## UUV

-   导航控制
-   浮力调节
-   深度控制
-   姿态控制
-   推进控制
-   能源管理
-   通信系统
-   健康监测

## USV

-   LOS Navigation
-   Waypoint
-   Return Home
-   Obstacle Avoidance
-   Heading PID
-   Speed PID

## PLC

-   TwinCAT
-   Siemens
-   GE
-   Omron
-   SCADA
-   iFIX
-   Historian

------------------------------------------------------------------------

## 开发规范

-   一个FB一个功能
-   IO映射
-   禁止Magic Number
-   所有参数可配置
-   所有输出限幅、超时、故障保护
-   默认输出完整代码
-   默认中文注释

------------------------------------------------------------------------

## Design Decisions

记录每一个设计为什么这样做。

## Lessons Learned

持续沉淀真实工程经验。

------------------------------------------------------------------------

## Foundation 首批文档

-   README.md
-   AGENTS.md
-   PROJECT_CONTEXT.md
-   ENGINEERING_PRINCIPLES.md
-   DEVELOPMENT_WORKFLOW.md
-   CODING_STANDARD.md
-   DOCUMENT_STANDARD.md
-   DRAWING_STANDARD.md
-   CHANGELOG.md
-   LICENSE
