# InterviewCoach - AI 面试训练系统

## 目录结构

```
InterviewCoach/
├── CLAUDE.md                    # AI 教练行为协议（核心）
├── README.md                    # 本文件
├── personal/
│   └── profile.md              # 你的简历 + 目标 JD（必填）
├── progress/
│   └── interview-tracker.md    # 各轮次评分追踪（唯一真相）
└── sessions/
    └── YYYY-MM-DD/
        └── session-notes.md    # 每次练习的复盘报告
```

## 快速开始

### 第一步：填写个人档案
编辑 `personal/profile.md`：
- 粘贴你的简历（核心内容即可）
- 粘贴目标岗位的 JD
- AI 会自动分析匹配度和考察点

### 第二步：启动练习
用 Claude Code 打开此目录：
```bash
cd InterviewCoach
claude
```

然后说：
> "我要练习一面，目标岗位是 [XX]"

或者（使用 OpenClaw）：
> "进入面试练习模式，练习一面"

### 第三步：面试练习
- AI 会模拟真实面试官提问
- 每个问题回答完会有即时点评
- 说"结束练习"触发复盘报告生成

### 第四步：查看进步
- 复盘报告自动保存在 `sessions/` 目录
- `interview-tracker.md` 追踪跨次评分变化
- 每次练习都能看到和上次的对比

---

## 三轮面试说明

| 轮次 | 面试官 | 核心考察 | 重点准备 |
|------|--------|---------|---------|
| **一面（业务面）** | 直属 leader 或同级资深 | 简历真实性、岗位理解、专业能力 | 项目 STAR 法则、JD 关键词 |
| **二面（Leader面）** | 大老板或跨部门 | 思维方式、方法论、协作、潜力 | 结构化表达、跨岗位视角 |
| **HR面** | HR | 文化适配、稳定性、薪资 | 离职原因、职业规划、价值观 |

---

## 与 Investing_Study 的设计对比

| 元素 | Investing_Study | InterviewCoach |
|------|----------------|----------------|
| 行为协议 | CLAUDE.md（学习模式）| CLAUDE.md（面试模式）|
| 进度追踪 | progress/tracker.md | progress/interview-tracker.md |
| 会话记录 | sessions/日期/session-notes.md | sessions/日期/session-notes.md |
| 个人背景 | personal/财务档案 | personal/简历+JD |
| AI 知识来源 | 训练数据（书本内容）| 训练数据（面试技巧）+ 你的简历/JD |
