# EduBot —— 多模态智能模拟面试评测系统

[![HTML](https://img.shields.io/badge/HTML-5-orange)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.5-brightgreen)](https://spring.io/projects/spring-boot)
[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-4FC08D)](https://vuejs.org)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

**EduBot** 是基于 Spring Boot 2.5 + Vue.js 构建的企业级面试模拟与评测系统，采用前后端分离架构，支持模块化开发和灵活扩展。系统集成了多模态 AI 能力，为高校学生提供沉浸式的面试训练体验。

> 更多详情请查看 [Gitee 仓库](https://gitee.com/okok11223/job-interview)

---

## 核心功能

### 多岗位面试场景模拟
- 支持人工智能、大数据、物联网、产品经理等技术岗位
- 提供技术问答、项目经历追问、场景模拟题等差异化题库
- 支持自由练习、限时模拟、专项训练等多种面试模式

### 多维度智能评测
- **语音分析**：评估语言流畅度、语速、停顿等指标
- **视频分析**：检测微表情、肢体语言、眼神交流等表现
- **文本分析**：评估专业知识匹配度、逻辑性、完整性等
- **综合评分**：5 项核心能力雷达图评分

### 智能反馈与学习推荐
- 可视化能力雷达图与详细分析报告
- 突出薄弱环节定位与改进建议
- 定制化学习资源推荐与进步趋势跟踪

## 技术栈

### 前端
- Vue.js 3 + Element Plus
- ECharts 可视化
- WebRTC

### 后端
- Spring Boot 2.5.15
- MySQL + Redis
- WebSocket / REST API
- JWT 认证

### AI
- ASR 语音识别
- CV 表情与行为分析
- NLP 语义评分

## 快速开始

### 后端
```bash
cd backend
mvn spring-boot:run
```

### 前端
```bash
cd frontend
npm install
npm run dev
```

### 配置
1. 修改 `application.yml` 中的数据库连接配置
2. 配置 AI 服务 API 密钥（语音识别 / 视觉分析 / NLP）

## 许可证

本项目仅供学习研究使用。
