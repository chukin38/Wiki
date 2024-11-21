如何写好一篇wikimd
2024-09-11 10:12 由 陈潮日 00838469 创建，于2024-11-16 21:11 由 刘梦醒 00573904最后修改。
1. 引言
Wiki是一种协作式的知识共享平台，它允许用户共同创建、编辑和维护内容。技术类型的Wiki专注于记录和分享技术知识，包括编程语言、软件工具、开发框架、关键技术实现、问题定位总结等等。

wiki 最重要的是要有逻辑，以图文为主，请大家不要在主目录里随意的加入日常视频讲解、特性串讲等，这些辅助资料可以归档到附件中

2.怎么写
写好一篇Wiki不仅需要准确的信息，还需要清晰的结构和易于理解的表达。

一篇好的Wiki通常有以下这些特征：

通俗易懂，假设受众无基础知识，能让更多读者更容易理解文章承载的知识和经验；
逻辑清晰，一般采用总分总结构，能让读者更好的理解文章所传递的知识重点内容；
示例解释，能提升文章的实用性，对所学的知识点可以直接通过例子进行实践应用；
图文并茂，能勾起读者的阅读欲，帮助读者更好地理解和记忆文章所传递的信息；
来龙去脉，讲清实现背后的原因，能让大家更好的这些知识使用在什么场景中使用；
参考信息，能提升文章的信任度，帮助读者更全面理解文章中提到的技术或知识点。
以下是一些关键步骤和建议，帮助你撰写一篇高质量的Wiki。

2.1 明确目标和受众
在开始写作之前，明确你的Wiki文章的目标和预期受众。这将帮助你决定内容的深度和广度。例如，如果你是为初学者编写关于Python的文章，你可能需要从基础概念开始，而如果是为有经验的开发者，你可以深入讨论特定的高级特性。

读者的掌握水平可能层次不齐，要对读者能力范围进行假定

这样可以使每次讲解更加聚焦更加高效。例如：讲数据库架构，就默认读者熟悉通用的术语如2PL、MVCC，但各个产品的模块组织不同，需要介绍；讲关系代数，就默认具备集合论基本知识，在此基础上进一步介绍关系代数运算。

要让每个层次的读者都要有所收获

如果说一次Wiki的思维演讲在40min，可以粗略地划分四个阶段：
第一个10min，讲给刚入行的萌新听，让他们提起聆听的兴趣，对未来有信心。
第二个10min，讲给新手开发，让他们了解全景与框架，解释一些基本概念，扫清术语的绊脚石。
第三个10min，讲给资深骨干，让他们对业务的掌握更加深入，对架构分层与机制实现具备清晰的认识。
第四个10min，是讲给假想的友商，触摸业界前沿并秀出自己的核心竞争力。

这是倡导，不是强制要求，并不是说每个Wiki都要这样安排，但是如果这样安排一定可以深入浅出地讲解，让所有读者受益。

反应在Wiki上，可以用背景/简介来引入，然后再逐步展开描述。

2.2 明确主题和标题
对于Wiki主题的选择要慎重。

每个Wiki不应该过于冗长，每篇帖子需要明确一个具体的主题。主题的选取与细致程度密切相关，例如主题选择为openGauss就只能进行产品框架与模块的说明，没法在这篇帖子中进行代码级别的详细说明。主题选择为openGauss的锁就可以对代码细节与各个锁的差异也进行详细说明。

选好主题后写文章的时候一定要紧扣主题，与主题无关的代码、概念都不应该重点描述，否则会让读者产生误解。

所以Wiki一定是来自思考总结，但是并非所有的思考总结都适合发Wiki。

建议多阅读自己创建的Wiki，如果写的东西连自己都不愿意多看一眼，别人是更加难以读完的。

根据团队的特点，推荐的主题有如下几类：

领域知识总结类，如开发人员所在责任田的关键技术和关键流程梳理；
问题定位总结类，如典型问题、疑难问题的总结，定位三板斧总结等；
业界技术介绍类，如友商的架构或关键技术介绍、单个技术点实现介绍等；
论文学习分享类，如三大顶会SIGMOD、VLDB、ICDE，经典/最新论文分享等；
业务场景介绍类，如银行系统、企业IT系统、政企系统等业务特点介绍等；
效率提升分享类，如设计、编码和调试等方面工具脚本，笔记工具等；
另外，选择一个好的标题也很重要，标题也标题应该简洁、具体，并且能够准确反映文章的内容。一个好的标题可以吸引读者的注意力，并帮助他们在搜索时快速找到你的Wiki。

2.3 使用清晰的结构
Wiki应该有一个清晰的结构，使得读者可以轻松地导航和理解内容。通常，一个好的结构包括：

​引言​：简要介绍主题和文章的目的。
​概念解释​：定义关键术语和概念。
​步骤和指南​：提供详细的步骤和指南，帮助读者完成任务。
​示例代码​：提供示例代码，帮助读者理解如何应用概念。
​常见问题解答​：回答可能的疑问和问题。
​参考资料​：列出用于撰写文章的参考资料。
2.4 使用清晰的语言和格式
​简洁明了​：避免使用复杂的术语和冗长的句子。使用简单、直接的语言。
​格式化​：使用标题、列表、表格和代码块来组织内容，使其更易于阅读。
​代码高亮​：如果包含代码，使用代码高亮来区分不同的代码元素。
关于Wiki格式，推荐使用markdown语言，通过编码的方式来定义文章格式

markdown练习网站：链接

2.5 提供示例和案例研究
示例和案例研究可以帮助读者更好地理解概念。确保示例是相关的，并且能够清楚地展示如何应用技术。

比如：

在介绍工具命令、脚本、API使用时，应该给出对应的使用示例，类似STL的vector example 链接
在介绍代码坏味道时，建议给出好坏代码示例，参考 高斯部十大低级编码问题
2.6 协作开发和定期更新
Wiki不是一个静止的帖子，而是随着代码变动、知识内容需要同步更新的动态帖子。知识是共享的才有价值，如果帖子归属于个人，那只是blog，不是Wiki。

并且不要只提意见，请同步给出建议。

私下和同事们交流，偶尔会听到大家对代码架构的吐槽、对版本管理流程的不理解、对某篇博文观点的不认可。大千世界，百家争鸣，由于每个人的理解能力不一样，观点不一致是极其正常的。作为一个团队成员，不仅需要提出这些意见，还应该给出改进建议。跟帖、评论、私信、批注等任何方式都可以。Wiki可以及时修改。

2.7 验证信息的准确性
技术信息变化迅速，确保你提供的信息是最新的。引用可靠的来源，并在可能的情况下，提供链接到官方文档或权威资源。

3. 总结
写好一篇Wiki，清晰的结构和易于理解的表达，能帮助你撰写一篇高质量的Wiki。

拥有一颗爱学习爱分享、持之以恒的心，你的写作技能、表达技巧也就在在这份热爱中持续提升和完善。

邀请大家一起完善本Wiki，共同进步！