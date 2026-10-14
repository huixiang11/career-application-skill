# 简历与求职实战 Skill

面向校招、实习和转岗求职的中文 AI 助手 Skill：搜索真实岗位、核验资格和投递入口、按 JD 修改简历、撰写求职文案、模拟面试与复盘。

## 功能

- 搜索岗位：扩展职位同义词，查官网与公开招聘渠道，核对届别、地点和截止时间。
- 评估匹配：区分硬条件、可迁移经历和待确认项，不编造录用概率。
- 定制材料：基于使用者的真实经历优化简历、自我评价和邮件。
- 面试准备：逐题模拟，利用可读取的录音或文字复盘，不捏造项目细节。
- 跟进投递：按需维护岗位状态，区分填表、提交成功、面试和 Offer。

这是给支持 Skill 的 AI 助手使用的指令包，并非独立运行的软件或全平台爬虫。实时搜岗需要宿主提供联网搜索或浏览器；文档导出和录音处理取决于宿主工具。Offer岛等其他 Skill 为可选补充，不是必装依赖。

## 安装

将本仓库链接发给支持安装 Skill 的 AI 助手，并说：

> 请安装这个仓库中的 career-application Skill，保留整个文件夹以及 references 和 agents 子目录。

也可使用 GitHub 的 **Code → Download ZIP** 下载，解压后将 `career-application` 文件夹放入所用工具的技能目录。不要只复制 SKILL.md，否则会缺失搜索模块。

## 使用示例

```text
使用 career-application，根据我的简历、毕业届别和目标城市搜索岗位，给出资格要求、在招状态和官网投递链接。

使用 career-application，对照这份 JD 优化简历，不添加未经确认的经历或数字。

使用 career-application，按这个岗位模拟面试，一次问一个问题。
```

首次使用时提供自己的简历或背景、目标地区、招聘类型和岗位方向；没有确定的条件可以留空。

## 文件

```text
career-application/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── job-discovery.md
    ├── china-campus.md
    └── sources.md
```

## 个人资料与使用边界

本仓库为通用分享版，不含候选人的简历、联系方式、账号凭据或真实经历案例。请勿将自己的简历、密钥、录音或投递记录提交到公开仓库。生成求职文案不等于发送邮件，搜索岗位不等于完成投递；外部提交遵循使用者明确授权。

招聘状态可能变化，结果应注明核验时间，提交前以招聘方公告和系统为准。

## 方法来源

参考了 Resume Tailoring、Job Search Skills、Resume Career Toolkit、CareerSail、JobSpy 和 AI Job Search CN 的部分公开方法，并独立重写为中文工作流。具体阅读来源和取舍见 [sources.md](career-application/references/sources.md)。未复制或捆绑上游程序。
