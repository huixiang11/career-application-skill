# GitHub 学习与设计记录

检索与阅读日期：2026-10-14。阅读的是以下分支的在线文件，不宣称固定到某个 commit；再次更新时重新核对原文件。这里保留方法来源，不复制上游全文、模板或脚本。新 Skill 用中文重新组织，并加入国内校招场景。

| 实际阅读的文件 | 采用的思路 | 未采用或改写之处 |
|---|---|---|
| [varunr89 / resume-tailoring](https://github.com/varunr89/resume-tailoring-skill/blob/master/skills/resume-tailoring/SKILL.md) | 汇集已有经历、对照岗位、追问缺口、保留事实来源 | 不照搬大量阶段审批、任职名称重命名、精确匹配百分比和强制多格式产物 |
| [sameergdogg / job-analyzer](https://github.com/sameergdogg/job-search-skills/blob/main/job-analyzer/SKILL.md) | 做有依据的匹配判断，用少量高价值改写替换堆砌 | 去除 Google Drive 前提；邮件和文档按用户需求生成 |
| [sameergdogg / job-crawler](https://github.com/sameergdogg/job-search-skills/blob/main/job-crawler/SKILL.md) | 先筛条件，再读职责，识别可迁移经验；使用公开招聘数据 | 不固化海外 ATS 接口或主观权重，不为凑数量推荐不符条件的职位 |
| [jirawatp / resume-section-guide](https://github.com/jirawatp/resume-career-toolkit/blob/master/skills/resume-section-guide/SKILL.md) | 简历结构随阶段调整，每个模块服务于目标岗位 | 不强制每条带数字；不一律删除 Office；不沿用美国 GPA 阈值 |

本地设计补充：毕业届别与公告年份区分、专业名称和学科门类核验、党员条件、部门介绍与具体招聘岗位区分、录音真实性、问卷证据边界、提交回执与重复发送防护。

## 岗位搜索增强（2026-10-14）

- 阅读 [CareerSail / SKILL.md](https://github.com/genius916/CareerSail/blob/main/SKILL.md)：吸收进入对应届次门户、提取 JD 直链及岗位池记录的思路。不采用强制安装飞书工具、自动同步外部公司库、忽略用户城市硬限制或“100%真实”的保证；申请按钮也不是有效性充分条件。
- 阅读 [JobSpy / README](https://github.com/speedyapply/JobSpy/blob/main/README.md)：借鉴不同来源统一字段、区分来源链接与直接链接、薪资来源与单位、缺失字段留空。项目偏多平台聚合，不能据此声称已支持 BOSS、国聘或国内央国企官网。本次未安装或运行该项目。
- 检索并阅读 [ai-job-search-cn 的项目介绍](https://github.com/youngledo/ai-job-search-cn)：参考中国渠道单独处理、公开检索与手动 JD 补全的思路；其 search-queries.md 本次未成功读取，不宣称复用了具体配置。
- 延用前述 sameergdogg/job-crawler 中先筛硬条件再读实际职责的思路；新模块不采用固定主观匹配权重。

以上均为方法学习与独立重写，不复制执行上游安装指令。成果是本地 Skill 的岗位搜索流程增强，不是独立爬虫、后台监控或招聘网站全量覆盖服务。

这不是对上游代码或说明文件的重新分发；未运行上游脚本，未将简历上传至上述仓库或服务。

## 维护时的行为检查

- 给出只有集团简介和旧年份公告的线索：应输出待核实入口，不能包装为当前在招。
- 候选人政治面貌未知，岗位要求中共党员：应保留条件，不能判定满足。
- 候选人收集反馈问卷并报告受访者的偏好：可写调研与偏好反馈，不应生成留存、转化或因果增长数据。
- 同一项目旧简历写原型，用户明确说现已上线：采纳更正但不捏造用户规模。
- 请求只优化自我评价：直接交付文案，不启动整套搜索与网申。
- 已授权投递但提交超时：查应聘记录或回执，不盲目再次提交。
