

# 工作方式


## 商业模式画布

- **客户细分**：我们的客户是谁、谁又是最重要的
- **价值主张**：相对于其他同类产品，我们有什么优势
- **客户关系**：用户和商家、用户和用户、商家和商家、商家和系统等之间的关系
- **渠道通路**：和用户、商家的沟通渠道是否高效
- **关键业务**：核心产品解决什么问题
- **核心资源**：我们有什么优势是别人没有的
- **重要合作**：有哪些上下游、周边伙伴需要协作，如何协作
- **收入来源**：如何从用户、商家身上获取收入，并让业务可持续发展
- **成本结构**：核心业务的任何环节需要花费多少

## 业务与技术

- 业务推动技术
- 技术促进业务
- 有些业务场景是现实中存在的（购买），需要技术去支持它
- 有些业务场景是虚拟化出来的（搜索引擎），需要技术结合可行业务做工程化思考
- 没有谁一定要压过谁，大家最终的目标都是为了使得我们的用户有一个舒服的体验，用户用的不爽，就会用脚投票


## 管理者

- **做成一件事，领导的功劳会占到 50% ~ 80%，相反做坏了一件事，领导的责任也是同等**
- 当组织赋予你权力的时候，如何使用权利至关重要，你所做的任何决策都会影响到上上下下
    - 大到公司战略，小到人员任务指派，眼光与执行力都在这些细节中得以体现
- 一个好的管理者是怎样的我不清楚，但是垃圾的大体就是这样的
    - 没有信用
    - 推卸责任
    - 好大喜功
    - 打压人才
    - 狂妄自大，只打嘴炮，无执行力

## 研发团队与公司发展

- 配合公司的发展而变化团队重心，使得每个时期的业务场景都能为用户提供优秀的体验
- 初创期
    - 开发产品原型
    - 积累决策数据
    - 提供灵活性，适应需求变化
    - 培养人才
- 发展期
    - 适配流量增长
    - 支撑业务发展
    - 培养和招募人才
- 规模期
    - 稳健与突破（创新）


## 沟通方式（非常非常非常重要）

- 面对面沟通
- 腾讯企业邮箱
- 企业微信 IM
    - 要把企业微信里面相关功能用起来，不能让信息太分散
- **注意消息在传递过程中的衰减情况**
- **注意信息爆炸**


## 思考问题方式

- [五个为什么（5 Whys）](https://www.jianshu.com/p/0676fbfe0d6c)

```
如下示例解释的就是五问法的基本过程：

［1-WHY］为什么大楼要每天冲洗呢？因为大厦每天被大量鸟粪弄脏；
［2-WHY］为什么这栋大厦有那么多的鸟粪? 因为大厦周围聚了特别多的燕子；
［3-WHY］为什么燕子专喜欢聚在这里？因为建筑物上有燕子最喜欢吃的飞虫；
［4-WHY］为什么这里飞虫多?因为飞虫在这里繁殖得特别快,
［5-WHY］为什么飞虫在这里繁殖得特别快？因为这里的尘埃最宜飞虫繁殖。

在实际应用当中，有可能将这种提问进一步扩展到六问、七问，甚至是更多的“为什么”。
这么做很可能是合乎实际情况的，因为“五个为什么”之中所说的“五”并非一成不变的真理；
反而，这个“五”字实际上说的就是，五次反复提出为什么，一般来说足以找出根本原因。

真正的关键所在就是，鼓励解决问题的人要努力避开主观或自负的假设和逻辑陷阱，从结果着手，沿着因果关系链条，顺藤摸瓜，穿越不同的抽象层面，直至找出原有问题的根本原因。
简而言之，就是鼓励解决问题的人要有“打破砂锅问到底”的精神。
```


## 项目流程（路线）

- 需求 + 原型 > 系统设计 + UI > 评审 > 接口 Mock > 前后端并行开发 > 联调 > 测试 > 预发布验收 > 上线 > 运营 > 数据分析 > 需求 + 原型
- 需求
    - 明确利益关系，特别是多方利益
        - 多方利益的情况，尽可能先与每个利益方单独沟通，遇到矛盾需要再沟通和划分利益优先级
        - 多个利益方一起沟通很容易得到更多需求，不易于需求把控
        - 对于 **信息透明化** 的点，需要大家自行把控
    - 持续有效的沟通
    - 调研、写需求、画原型
    - 划分需求优先级，明确迭代周期
        - 明确迭代周期， 需求溢出砍需求，但不能调整时间，因为其他部门的配合在定下时间的时候已经开始了。
    - 标出不确定域
    - 客户需求确认
    - **召集：需求评审**
- 项目核心负责人
    - 系统设计
    - 细化主要开发任务（TAPD）
    - **召集：估算扑克**
- 前端开发
    - 细化前端需求任务（TAPD）
    - 根据需求和原型实施前端组件
    - 前后端联调
    - 冒烟测试，确保主流程
    - 主流浏览器性能调优
    - **召集：代码评审**
- 后端开发
    - 细化后端需求任务（TAPD）
    - 根据需求、原型、系统设计说明书开发功能
    - 监控埋点
    - 前后端联调
    - 冒烟测试，确保主流程
    - 单元测试（优先保证主流程：新增 + 删除 + 单个查询 + 分页查询的单元测试）
    - 微基准测试
    - 接口压力测试
    - 测试人员测试出的功能：必须写单元测试
    - **召集：代码评审、SQL 审查**
- 测试开发
    - 细化测试需求任务（TAPD）
    - 接口自动化测试用例（优先保证主流程）
    - UI 自动化测试用例（优先保证主流程）
    - Bug 回归测试
    - 压力测试
    - **召集：测试报告分析和反馈**
- 运维部署
    - 根据系统设计说明书，预先调研部署结构，部署脚本，网络评估，系统监控
    - 自动化部署环境准备
    - 自动化测试环境准备
    - 压力测试环境准备
    - 灰度发布（尽可能采用随机样本）
    - **召集：监控报告分析和反馈**
    - 升级回滚设计（很多场景回滚难度大，优先做好灰度发布）
        - 开关设计的回滚
        - 整个环境回滚
        - 回滚脚本设计
        - 数据库补丁回滚设计



## TAPD

- 看板
- 需求（故事）
- 迭代
- 缺陷


## 看板（电子看板）

- 待讨论
- 待规划
- 待开发：优先级高、中、低
- 待测试：优先级高、中、低
- 带验收
- 待发布


## Code Review

- 规范是无法检测代码质量的，周期性的 Review 还是有意义的
- 一般来新人，初期都要进行 Review，并反复强调我们相关规范，同时也可以根据新人的反馈情况来优化规范
- 一开始就没设计好的代码，随着时间推移，技术债务会越来越明显，扩展性差，一有变动就需要大改，整体迭代周期风险变高，期间可能还要修复线上数据，类型循环之后基本就很难再凝聚起团队的力量


## 输出

- 产品输出
    - 思维导图
    - 活动图（不要用普通流程图）
    - 原型
    - 操作指引
- 后端输出
    - 系统架构（架构设计图）
    - UML 模型（核心流程时序图、用例图）
    - 数据库模型
    - Swagger
    - 接口文档（Markdown）
- 前端输出
    - YAPI
    - BFF 接口文档（Markdown）


## 团队常见问题（尽可能避免）

- 目标不明确
- 人员不稳定
    - 增加人手并不能百分百增加效率，除非是有计划的调整，不会影响到现有团队成员的进度。
- 工位不集中（借调）
- 有各类原因的干扰
- 多种不同类型的需求并发一起处理
- 需求不够细化
- 团队角色模糊
- 需求变更
    - 无法避免的事实，它也是让软件不断退化的主要原因
    - 尽可能 **持续有效的沟通** 是避免不断返工的最好办法之一
    - 变更发生得越早，风险越小
- 测试工作在开发结束后有大量堆积
- 每个工程师在沟通能力、技能水平、主动性、服从性、一致性、责任心上都有着巨大差异，每个人都是需要特殊对待。
- 与外部沟通不顺畅
    - 上游协作：客户
    - 下游协作：运维
    - 交叉协作：其他开发团队


## 上线跟踪

- **如果是自己的业务方，上线后前两天，产品经理需要到业务方办公地点收集上线使用情况和业务方的反馈**
- 刚上线的阶段是修改 Bug 的最佳时机，错过了成本就是很大的

## 复盘

- 原本的计划，哪些做了，哪些没做
- 已经做的，进度怎样，效果如何
- 用户反馈，系统稳定性，扩展性

