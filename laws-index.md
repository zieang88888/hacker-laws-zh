# 全量定律索引 · hacker-laws-zh

> 本索引共 **69 条**：定律 Laws **48** 条 + 原则 Principles **21** 条。
> 每条给出：**中文译名 · 英文原名 · 一句话核心 · 源 README 锚点**。
> 锚点跳转至源仓库 [`dwmkerr/hacker-laws`](https://github.com/dwmkerr/hacker-laws) `main` 分支 README 的对应小节。

源 README 基地址：`https://github.com/dwmkerr/hacker-laws/blob/main/README.md`

---

## 一、定律 Laws（48 条）

| # | 中文译名 | 英文原名 | 一句话核心 | 源锚点 |
| --- | --- | --- | --- | --- |
| 1 | 90–9–1 法则（1% 规则） | 90–9–1 Principle (1% Rule) | 网络社区里 90% 只看、9% 改、1% 创造内容。 | [#9091-principle-1-rule](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#9091-principle-1-rule) |
| 2 | 90–90 法则 | 90–90 Rule | 前 90% 的代码花前 90% 的时间，剩下 10% 再花后 90% 的时间。 | [#9090-rule](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#9090-rule) |
| 3 | 阿姆达尔定律 | Amdahl's Law | 并行加速的上限，被那段无法并行的串行部分锁死。 | [#amdahls-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#amdahls-law) |
| 4 | 破窗理论 | The Broken Windows Theory | 一处烂代码不修，会引来更多烂代码，质量逐步崩塌。 | [#the-broken-windows-theory](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-broken-windows-theory) |
| 5 | 布鲁克定律 | Brooks' Law | 给已经延期的项目加人，只会让它更延期。 | [#brooks-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#brooks-law) |
| 6 | CAP 定理（布鲁尔定理） | CAP Theorem (Brewer's Theorem) | 分布式存储在一致性、可用性、分区容忍三者中最多选其二。 | [#cap-theorem-brewers-theorem](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#cap-theorem-brewers-theorem) |
| 7 | 克拉克三定律 | Clarke's three laws | 任何足够先进的技术，都与魔法无异。 | [#clarkes-three-laws](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#clarkes-three-laws) |
| 8 | 康威定律 | Conway's Law | 系统的架构，会复制产出它的组织的沟通结构。 | [#conways-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#conways-law) |
| 9 | 坎宁安定律 | Cunningham's Law | 想在网上得到正确答案，最快的办法是先发一个错误答案。 | [#cunninghams-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#cunninghams-law) |
| 10 | 邓巴数 | Dunbar's Number | 人脑只能稳定维持约 150 人的社会关系，超出就要靠制度。 | [#dunbars-number](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#dunbars-number) |
| 11 | 达克效应 | The Dunning-Kruger Effect | 能力越弱的人越容易高估自己，刚入门反而最自信。 | [#the-dunning-kruger-effect](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-dunning-kruger-effect) |
| 12 | 菲茨定律 | Fitts' Law | 移向目标的时间，与距离成正比、与目标大小成反比。 | [#fitts-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#fitts-law) |
| 13 | 盖尔定律 | Gall's Law | 能跑的复杂系统，都是从能跑的简单系统演化来的。 | [#galls-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#galls-law) |
| 14 | 古德哈特定律 | Goodhart's Law | 当一个度量变成目标，它就不再是好度量。 | [#goodharts-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#goodharts-law) |
| 15 | 汉隆剃刀 | Hanlon's Razor | 能用愚蠢解释的，绝不归因于恶意。 | [#hanlons-razor](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#hanlons-razor) |
| 16 | 希克定律 | Hick's Law (Hick-Hyman Law) | 决策时间随可选项数量的对数增长，选项越多选得越慢。 | [#hicks-law-hick-hyman-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#hicks-law-hick-hyman-law) |
| 17 | 霍夫斯塔特定律 | Hofstadter's Law | 做事总比你想的久，哪怕你已经把这条定律算进去了。 | [#hofstadters-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#hofstadters-law) |
| 18 | 赫特伯定律 | Hutber's Law | 所谓"改进"，往往意味着别处的恶化。 | [#hutbers-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#hutbers-law) |
| 19 | 炒作周期与阿马拉定律 | The Hype Cycle & Amara's Law | 我们总高估技术的短期效果、低估它的长期影响。 | [#the-hype-cycle--amaras-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-hype-cycle--amaras-law) |
| 20 | 海勒姆定律（隐式接口定律） | Hyrum's Law | 只要用户够多，你接口文档没承诺的行为也会被人依赖。 | [#hyrums-law-the-law-of-implicit-interfaces](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#hyrums-law-the-law-of-implicit-interfaces) |
| 21 | 杰文斯悖论 | Jevons' Paradox | 效率提升往往不减少、反而增加资源的总消耗。 | [#jevons-paradox](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#jevons-paradox) |
| 22 | 输入-处理-输出（IPO） | Input-Process-Output (IPO) | 再复杂的系统，也能拆成输入、处理、输出三段。 | [#input-process-output-ipo](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#input-process-output-ipo) |
| 23 | 克尼汉定律 | Kernighan's Law | 调试比写代码难一倍，所以写得越"聪明"越调不动。 | [#kernighans-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#kernighans-law) |
| 24 | 库米定律 | Koomey's Law | 同样计算量所需的电量，约每 1.5~2.5 年减半。 | [#koomeys-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#koomeys-law) |
| 25 | 林纳斯定律 | Linus's Law | 只要有足够多的眼睛，所有 bug 都浅显。 | [#linuss-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#linuss-law) |
| 26 | 梅特卡夫定律 | Metcalfe's Law | 网络的价值约等于用户数的平方。 | [#metcalfes-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#metcalfes-law) |
| 27 | 摩尔定律 | Moore's Law | 集成电路上的晶体管数约每两年翻一番。 | [#moores-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#moores-law) |
| 28 | 墨菲定律 / Sod 定律 | Murphy's Law / Sod's Law | 凡是可能出错的，终将出错（且挑最糟的时机）。 | [#murphys-law--sods-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#murphys-law--sods-law) |
| 29 | 奥卡姆剃刀 | Occam's Razor | 多个可行解中，假设最少、最简单的那个最可能对。 | [#occams-razor](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#occams-razor) |
| 30 | 帕金森定律 | Parkinson's Law | 工作会自动膨胀，填满你给它的所有时间。 | [#parkinsons-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#parkinsons-law) |
| 31 | 过早优化效应 | Premature Optimization Effect | 过早的优化是万恶之源——先确定真的需要再优化。 | [#premature-optimization-effect](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#premature-optimization-effect) |
| 32 | 帕特定律 | Putt's Law | 技术被两种人主导：懂技术却不管理、管理者却不懂技术。 | [#putts-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#putts-law) |
| 33 | 里德定律 | Reed's Law | 大型网络（尤其社交）的效用随规模呈指数增长。 | [#reeds-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#reeds-law) |
| 34 | 苦涩的教训 | The Bitter Lesson | 靠算力与规模的通用方法，长期看总能赢过精心设计的人工套路。 | [#the-bitter-lesson](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-bitter-lesson) |
| 35 | 林格曼效应 | The Ringelmann Effect | 人越多，单个人的平均产出越低（社会惰化+协调成本）。 | [#the-ringelmann-effect](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-ringelmann-effect) |
| 36 | 复杂度守恒定律（特斯勒定律） | The Law of Conservation of Complexity | 系统里有些复杂度消不掉，只能从代码转移给用户。 | [#the-law-of-conservation-of-complexity-teslers-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-law-of-conservation-of-complexity-teslers-law) |
| 37 | 迪米特定律（最少知识原则） | The Law of Demeter | 模块只该和它的直接朋友说话，别碰"陌生人"。 | [#the-law-of-demeter](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-law-of-demeter) |
| 38 | 漏抽象定律 | The Law of Leaky Abstractions | 所有 nontrivial 的抽象，在某种程度上都会"漏水"。 | [#the-law-of-leaky-abstractions](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-law-of-leaky-abstractions) |
| 39 | 工具定律（马斯洛锤子） | The Law of the Instrument | 手里只有锤子，看什么都像钉子——别过度依赖熟悉的工具。 | [#the-law-of-the-instrument](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-law-of-the-instrument) |
| 40 | 琐碎定律（自行车棚效应） | The Law of Triviality | 团队会把最多时间花在最琐碎、最好讨论的小事上。 | [#the-law-of-triviality](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-law-of-triviality) |
| 41 | Unix 哲学 | The Unix Philosophy | 每个程序只做好一件事，靠组合小工具搭出大系统。 | [#the-unix-philosophy](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-unix-philosophy) |
| 42 | 童子军军规 | The Scout Rule | 永远把代码留给比你发现时更干净一点。 | [#the-scout-rule](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-scout-rule) |
| 43 | 第二系统效应 | The Second-System Effect | 成功的第一系统之后，往往会做出一个过度设计的臃肿第二版。 | [#the-second-system-effect](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-second-system-effect) |
| 44 | Spotify 模型 | The Spotify Model | 团队围绕特性而非技术来组织（部落/公会/分会）。 | [#the-spotify-model](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-spotify-model) |
| 45 | 两个披萨规则 | The Two Pizza Rule | 一个团队如果两个披萨都喂不饱，那就太大了。 | [#the-two-pizza-rule](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-two-pizza-rule) |
| 46 | 特怀曼定律 | Twyman's law | 数据越反常、越"漂亮"，越可能是错误或被操纵过。 | [#twymans-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#twymans-law) |
| 47 | 瓦德勒定律 | Wadler's Law | 语言设计里花在某特性上的时间与其位置成 2 的幂次——注释语法最吵。 | [#wadlers-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#wadlers-law) |
| 48 | 惠顿定律 | Wheaton's Law | 别当傻逼。 | [#wheatons-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#wheatons-law) |

## 二、原则 Principles（21 条）

| # | 中文译名 | 英文原名 | 一句话核心 | 源锚点 |
| --- | --- | --- | --- | --- |
| 1 | 所有模型都是错的（博克斯定律） | All Models Are Wrong | 所有模型都不精确，但有些有用——别追求完美模型。 | [#all-models-are-wrong-george-boxs-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#all-models-are-wrong-george-boxs-law) |
| 2 | 切斯特顿栅栏 | Chesterton's Fence | 没搞懂现有代码为什么存在之前，别急着删它。 | [#chestertons-fence](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#chestertons-fence) |
| 3 | 克霍夫原理 | Kerckhoffs's principle | 假设对手完全知道你的系统设计，只要密钥保密就仍安全。 | [#kerckhoffss-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#kerckhoffss-principle) |
| 4 | 死海效应 | The Dead Sea Effect | 越能干的工程师越容易跳槽，留下的往往是能力较弱者。 | [#the-dead-sea-effect](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-dead-sea-effect) |
| 5 | 迪尔伯特原理 | The Dilbert Principle | 公司倾向把不胜任者升到管理层，以减小他们的破坏面。 | [#the-dilbert-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-dilbert-principle) |
| 6 | 帕累托原则（80/20 法则） | The Pareto Principle | 多数结果来自少数投入：20% 的原因造成 80% 的后果。 | [#the-pareto-principle-the-8020-rule](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-pareto-principle-the-8020-rule) |
| 7 | 希尔基原理 | The Shirky Principle | 机构会拼命维护那个它自己被造出来要解决的问题。 | [#the-shirky-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-shirky-principle) |
| 8 | 随机鹦鹉 | The Stochastic Parrot | 大模型只是在概率地拼接文本，听起来自信不等于真懂。 | [#the-stochastic-parrot](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-stochastic-parrot) |
| 9 | 彼得原理 | The Peter Principle | 人会一直被晋升，直到升到自己力不从心的位置。 | [#the-peter-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-peter-principle) |
| 10 | 健壮性原则（波斯特尔定律） | The Robustness Principle | 对自己发出的要保守，对接受别人的输入要宽容。 | [#the-robustness-principle-postels-law](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-robustness-principle-postels-law) |
| 11 | SOLID | SOLID | 面向对象设计五大原则（单一职责/开闭/里氏替换/接口隔离/依赖反转）的合称。 | [#solid](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#solid) |
| 12 | 单一职责原则 | The Single Responsibility Principle | 一个模块/类应该只有一个被改变的理由。 | [#the-single-responsibility-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-single-responsibility-principle) |
| 13 | 开闭原则 | The Open/Closed Principle | 对扩展开放，对修改关闭。 | [#the-openclosed-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-openclosed-principle) |
| 14 | 里氏替换原则 | The Liskov Substitution Principle | 子类型必须能在不破坏系统的前提下替换父类型。 | [#the-liskov-substitution-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-liskov-substitution-principle) |
| 15 | 接口隔离原则 | The Interface Segregation Principle | 不该强迫客户端依赖它用不到的方法。 | [#the-interface-segregation-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-interface-segregation-principle) |
| 16 | 依赖反转原则 | The Dependency Inversion Principle | 高层模块不应依赖低层细节，二者都应依赖抽象。 | [#the-dependency-inversion-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-dependency-inversion-principle) |
| 17 | DRY 原则 | The DRY Principle | 系统里每一条知识都该有唯一、明确、权威的表达。 | [#the-dry-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-dry-principle) |
| 18 | KISS 原则 | The KISS principle | 保持简单、傻瓜化——简单的系统通常更耐用。 | [#the-kiss-principle](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-kiss-principle) |
| 19 | YAGNI | YAGNI | 永远只在真正需要时实现，别为"以后可能用到"写代码。 | [#yagni](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#yagni) |
| 20 | 分布式计算谬误 | The Fallacies of Distributed Computing | 那八条"想当然"——网络可靠、延迟为零、带宽无限……迟早翻车。 | [#the-fallacies-of-distributed-computing](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-fallacies-of-distributed-computing) |
| 21 | 最小惊讶原则 | The Principle of Least Astonishment | 设计应符合用户的经验、预期与心智模型，别"惊吓"用户。 | [#the-principle-of-least-astonishment](https://github.com/dwmkerr/hacker-laws/blob/main/README.md#the-principle-of-least-astonishment) |

---

*统计口径：以源 README 正文实际出现的 `### ` 三级标题为准（不依赖页面顶部 TOC）。合计 48 + 21 = **69 条**。*
