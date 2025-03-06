
# 多智能体强化学习的无人机协同系统

基于先进的强化学习算法，实现多无人机协同作业的智能控制系统。本系统提供了完整的无人机管理、任务规划、实时监控和数据分析功能。

## 系统特点

- 实时多机协同控制
- 智能路径规划
- 自适应任务分配
- 多角色权限管理
- 实时数据监控和分析
- 应急管理和故障处理

## 系统架构

系统采用模块化设计，主要包含以下功能模块：

### 1. 用户认证模块 (`login.html`)
- 多角色登录系统（管理员、操作员、观察者）
- 安全的身份验证
- 记住登录状态功能

### 2. 系统仪表盘 (`dashboard.html`)
- 系统概览和关键指标
- 无人机状态实时监控
- 快速导航到各功能模块

### 3. 无人机管理 (`drone-management.html`)
- 无人机状态监控
- 设备管理和维护
- 电池状态监控
- 设备注册和配置

### 4. 任务管理模块
- 训练任务管理 (`training-task.html`)
- 任务规划系统 (`mission-planning.html`)
- 部署管理 (`deployment-management.html`)

### 5. 监控和分析模块
- 实时监控 (`real-time-monitoring.html`)
- 数据分析 (`data-analysis.html`)
- 模型评估 (`model-evaluation.html`)

### 6. 系统配置和管理
- 系统配置 (`system-configuration.html`)
- 仿真测试 (`simulation-testing.html`)
- 应急管理 (`emergency-management.html`)

### 7. 训练环境 (`training-environment.html`)
- 强化学习训练环境配置
- 算法开发接口 (`algorithm-development.html`)
- 模型训练和优化

## 页面导航关系

```
login.html
└── dashboard.html
    ├── drone-management.html
    ├── real-time-monitoring.html
    ├── mission-planning.html
    │   └── deployment-management.html
    ├── data-analysis.html
    │   └── model-evaluation.html
    ├── training-task.html
    │   ├── training-environment.html
    │   └── algorithm-development.html
    ├── system-configuration.html
    │   ├── simulation-testing.html
    │   └── emergency-management.html
```

## 用户角色和权限

1. 系统管理员 (Admin)
   - 完整的系统访问权限
   - 系统配置和管理
   - 用户权限管理

2. 操作员 (Operator)
   - 无人机操控权限
   - 任务执行和监控
   - 数据分析权限

3. 观察者 (Observer)
   - 系统监控权限
   - 数据查看权限
   - 无操作权限

## 技术栈

- 前端：HTML5, TailwindCSS, JavaScript
- 实时数据更新：WebSocket
- UI组件：SweetAlert2
- 可视化：自定义图表组件

## 开发指南

### 环境要求
- 现代浏览器（支持ES6+）
- 网络连接（用于加载CDN资源）

### 本地开发
1. 克隆代码库
2. 使用本地服务器运行项目
3. 默认开发账号：
   - 管理员：admin/admin123
   - 操作员：operator/operator123
   - 观察者：observer/observer123

## 版本信息

当前版本：v2.1.0 
>>>>>>> 22a2344 (2025-3-6 完成前端模板)
