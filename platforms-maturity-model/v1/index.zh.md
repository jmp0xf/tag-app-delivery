## 引言

CNCF最初的[平台定义白皮书](https://tag-app-delivery.cncf.io/whitepapers/platforms/)描述了云计算内部平台是什么，以及它们承诺为企业带来的价值。但是，要实现这些价值，组织必须反思并有意识地追求对它们有影响的成果和实践，同时要记住，每个组织都依赖于为其自身定制的内部平台——即使这个平台只是关于如何使用第三方服务的文档。这个成熟度模型为这种反思提供了一个框架，并为任何组织识别改进机会。

## 什么是平台工程？

受到DevOps所承诺的跨职能合作的启发，平台和平台工程在企业中作为这种合作的明确形式出现了。平台策划并呈现共同的能力、框架和体验。在这个工作组及相关出版物的背景下，重点是促进和加速[内部用户](https://tag-app-delivery.cncf.io/wgs/platforms/glossary/#platform-users)如产品和应用团队工作的平台。

[**平台工程**](https://tag-app-delivery.cncf.io/wgs/platforms/glossary/#platform-engineering)是规划和提供这类计算平台给开发者和用户的实践，并包括平台及其能力的所有部分——它们的人员、流程、政策和技术；以及推动它们的期望商业成果。

请先阅读[CNCF平台定义白皮书](https://tag-app-delivery.cncf.io/whitepapers/platforms/)以获得完整的背景信息。

## 如何使用这个模型

随着平台工程在过去几年中的日益突出，一些模式变得明显。通过将这些模式和观察结果组织成一个渐进的成熟度模型，我们旨在引导[平台团队](https://tag-app-delivery.cncf.io/wgs/platforms/glossary/#platform-teams)认识到他们可能面临的挑战和目标机会。每个方面都由不同团队和组织在该方面的不同级别的特征连续体描述。我们希望读者能在模型中找到自己，并识别相邻级别的机会。

值得注意的是，每增加一个成熟度级别都伴随着对资金和人员时间的更大要求。因此，达到最高级别本身不应该是一个目标。每个级别描述了在该阶段应出现的特质。读者必须考虑他们的组织和当前的背景是否会从这些特质中受益，鉴于所需的投资。

请记住，每个方面都是独立评估和演进的。然而，像任何社会技术系统一样，这些方面是复杂且相互关联的。因此，你可能会发现，为了在一个方面改进，你也必须在另一个方面达到最低级别。

同样重要的是要认识到，平台的实现因组织而异。确保评估你的团队整体云原生转型的当前状态。一个极好的评估资源是[云原生成熟度模型](https://maturitymodel.cncf.io/)。

最后，这个模型鼓励组织通过有意规划来成熟他们的平台工程学科和由此产生的平台。这样的规划和纪律本身就是成熟平台开发和持续演进的要求。

总的来说，请记住，将你的组织映射到一个模型中是为了捕捉当前状态，以_促进_渐进式迭代和改进。[Martin Fowler](https://martinfowler.com/bliki/MaturityModel.html)说得好：“成熟度模型评估的真正结果不是你处于哪个级别，而是你需要工作的事项清单以改进。你当前的级别只是为了确定下一步需要获取的技能清单的中间工作。”本着这种精神，寻找模型中的自己，然后识别相邻级别的机会。

## 这项工作背后的背景

了解文档编写背景的价值是很重要的。以下部分概述了模型背后的一些背景，以及对你，读者的一些期望。

### 预期受众

每位读者都带着独特的背景，并将从这个模型中获得独特的学习。以下是我们考虑的一些人物角色，以及他们可能参与这个模型的动机：

* **CTO、技术副总裁和技术总监**：领导者寻求制定数字化转型和提高开发者生产力的路径
* **工程经理**：寻求授权工程师以更少的开销和更高效率提供价值的团体和个人
* **企业架构师**：寻求在技术问题上采取以价值和解决方案为导向的视角的个人
* **平台工程师和平台产品经理**：寻求为平台构建者和平台用户构建最佳体验的团队和人员
* **产品供应商和项目维护者**：希望设计工具并传达信息以使用户能够成功使用平台和能力的组织和工程师
* **应用和产品开发者**：希望更详细了解他们可能对内部平台有何期望的平台用户

### 理解级别

这个模型并不是要将一个组织或平台团队完全归类为“1级”或“4级”。每个方面应该独立于其他方面考虑；每个级别的特征代表了该方面内的一个连续体，但不一定与同一级别的其他方面耦合。更重要的是，许多组织会看到他们的团队和工作中适用多个级别的特征。这是因为没有任何级别本质上是好是坏，只是与团队的目标相关。

每个级别的标签旨在反映平台工程在你的组织中的影响。当你认识到你的组织处于给定级别时，你将洞察到随后级别的机会。较低编号的级别包括更多的战术解决方案，而较高编号的级别则更加战略性。

这产生了一个与其他数字产品开发类似的潜在平台开发和成熟过程：首先识别问题和对新解决方案的需求，接下来开发最小可行产品作为假设的解决方案，第三迭代以更好地解决问题并确保适合你的客户，最后扩展和优化产品以解决许多团队和用户的问题。

与[CNCF云原生成熟度模型](https://maturitymodel.cncf.io/)类似，这个模型强调，成功的商业成果只能通过平衡人员、流程和政策以及技术来实现。值得注意的是，这个模型引入了一些通常不完全在单个内部团队的职权范围内的方面，而是需要跨工程部门甚至更广泛的组织合作。

### 但它似乎不适合

这完全没问题！所有组织和团队都有特定于它们的动态和参数。

请记住，这篇论文的目标不是规定一个固定的公式，而是提供一个你可以应用于你的情况的框架。每一个字可能都不适合你，但我们希望内容能激发你对自己的平台之旅进行反思，取其精华，去其糟粕。

这个模型的目标是提供一个工具，帮助指导平台工程从业者、利益相关者和其他感兴趣的方在他们的旅程中。平台设计和实现不是一门精确的科学，而是取决于个别项目、组织以及特定的时间和地点的需求。

## 模型表格

[模型表格的内容未提供，无法翻译。]

| 方面 | 描述 | 临时性 | 运营化 | 可扩展性 | 优化型 |
|:---|:---|:---|:---|:---|:---|
| [投资](#investment-model-detail) | 平台能力的人员和资金是如何分配的？ | 自愿或临时 | 专职团队 | 作为产品 | 启用生态系统 |
| [采纳](#adoption-model-detail) | 用户是如何发现和使用内部平台及其能力的？ | 零散 | 外在推动 | 内在吸引 | 参与式 |
| [接口](#interfaces-model-detail) | 用户如何与平台能力进行交互和使用？ | 定制流程 | 标准工具 | 自助服务解决方案 | 集成服务 |
| [运营](#operations-model-detail) | 平台及其能力是如何规划、优先级排序、开发和维护的？ | 应需求 | 中心跟踪 | 中心启用 | 管理服务 |
| [测量](#measurement-model-detail) | 收集和整合反馈及学习的过程是什么？ | 临时 | 持续收集 | 洞察 | 定量和定性 |

## 投资模型详解

#### *平台能力的人员和资金是如何分配的？*

投资于平台和平台工程是将预算和人员分配用于构建和维护共同能力的过程。通常，倡议被描述为自下而上的有机构建，或者通过自上而下的倡议推动。无论哪种情况，持续投入努力的能力都是推动高影响工作的关键。这个方面捕捉了投资的规模和广度如何影响平台成功。

### 1级，临时性 — 自愿或临时

个别能力可能存在，以提供常见或关键功能的共同基础。这些能力是出于必要而构建和维护的，而不是有计划和有意资助的。

这些能力是由临时或自愿分配的人员构建和维护的；没有有意分配给它们的中央资金或人员。它们依赖于用户当前的战术需求。

#### 特点：

* "敲门"或"飞虎"队伍是为了应对紧急需求而组建的。这些团队寿命短暂，没有被分配或授予时间来提供长期规划和支持。
* 迁移、改进或增强通常被视为"好有"的工作项，并依赖于"研究"或"黑客日"的努力。
* 在处理新需求（如紧急安全补丁）时，可能会引入流程改进或自动化，但没有支持以可重用或可持续的方式构建解决方案。
* 员工抱怨疲劳和挫败感，因为他们在核心角色之外的工作量太大。

#### 示例场景：

* 有一个特定的员工被视为测试环境专家。虽然这名员工意图好，但他们尝试在有限的投资下启用更好的测试环境，这增加了风险，因为没有维护他们的解决方案，也没有共享的理解如何排查破损的测试环境。
* 当管理层没有对收入产生特性的压力时，鼓励工程师投资于能力改进。这通常转化为一些冲刺的最后几天，他们优先自动化和改进他们的CI/CD管道的部分。这些改进通常是突发的，因为可能有几个月的冲刺过于充满，不允许时间在这些旁边的事业上。

### 2级，运营化 — 专职团队

预算和人员被分配用于持久的人员和资源支持。被分配的人员负责提供一套常用的能力，以加速软件交付。这些团队通常专注于满足反应性技术需求。他们可能被称为DevOps、工程使能、开发者体验（DevEx或DevX）、共享工具、卓越中心，甚至是平台。他们由中央资助，并被视为成本中心；他们对直接价值流和应用团队的影响没有被衡量。在这个层面上，很难映射平台团队对组织及其价值流的影响，这可能使得持续和继续资助这样的团队变得困难。

#### 特点：

* 团队几乎全由技术通才组成。
* 团队预算可能包括与他们工作相关的基础设施成本，这常常是预算对话中的一个关键点。
* 待办事项涵盖多种技术，导致频繁和大规模的上下文切换。
* 这个团队通常是第一个填补尚未被解决的空白，即使不在团队声明的范围内。这个团队对没有所有者的资源承担所有权。
* 被分配的人员很少有时间或经验进行客户研究来验证他们的设计或实现。

#### 示例场景：

* 应用开发者提出他们的应用程序构建时间过长的问题。一个中心化团队被任务减少50%的构建时间。他们通过加倍CI运行器的大小和数量来解决这个问题，因为他们离软件太远，无法单独改进应用程序构建。这为他们的中心化团队创造了预算问题，因为生产力增益与这种增加的基础设施成本无法直接衡量。

### 3级，可扩展性 — 作为产品

对内部平台及其能力的投资类似于对企业外部产品和价值流的投资：基于它们预期为客户提供的价值。产品管理和用户体验被明确考虑并投资。可能使用收费返还系统来反映平台对其客户自己的直接价值流和产品的影响。企业使用数据驱动的绩效指标和反馈循环，将资金和人员分配给适当的倡议。平台团队最终可以优化业务本身，并有助于提高盈利能力。

#### 特点：

* 平台团队配备了内部服务或技术团队中不常见的角色，例如产品管理和用户体验。
* 团队在组织内部公开路线图，指示交付的价值和高层次的特性目标。
* 特性在设计、交付和部署后都会测试实现质量和用户体验。
* 特性移除是对话的关键部分，目标是拥有一套受到良好支持、使用频繁的能力套件，而不是可能无法维护的庞大资产。

#### 示例场景：

* 来自平台使用度量的数据指导了将资金和人员分配给最有影响力的倡议的决策。

### 4级，优化型 — 启用生态系统

平台团队找到了提高全组织效率和效果的方法，超越了基本能力。核心平台维护者有意图优化新产品的上市时间，降低企业的整体成本，为新服务启用高效的治理和合规性，快速轻松地扩展工作负载，以及其他横跨要求。这些核心维护者专注于使能力专家无缝集成他们的需求和产品到现有和新的平台部分。此外，组织将专业领域（如安全、性能、质量）的人员和资源集中起来，通过提供的平台框架，引入高级特性，使产品团队能够加速遵循公司目标，而不依赖于中心化团队的待办事项清单。

#### 特点：

* 使能力专家扩展平台能力和引入新能力成为优先事项。
* 组织可以集中专家，使他们的知识和支持通过平台能力传播。

#### 示例场景：

* 市场营销与平台构建者合作，引入一致的用户跟踪，以将市场营销努力归因于产品结果。
* 自动化倡议将数据库配置的人工时间减少了30分钟每个实例，每年节省1000万美元。

## 采纳模型详解



#### *用户如何发现并使用内部平台及其功能？*

采用不仅描述了一个组织如何以及使用平台功能的程度，还包括了他们这样做的动机。在早期阶段，许多目标用户可能并没有意识到他们正在使用一个平台，而是将他们的工具视为来自各种内部来源的临时功能集合。这可能会成熟为一组始终如一地管理并呈现给用户的功能 — 也就是说，一个或多个平台。随着功能变得更加精细和易于发现，推动平台使用的动力通常会从外部动机（如强制或激励措施）转变为用户自主选择平台功能，理想情况下甚至会将他们自己的努力投入到更广泛的平台生态系统中。

<figure align="center">
<img src="assets/adoption-curve.jpg" width=600px />
<br/>
<figcaption align="center" padding="50px">
<em>一个展示平台采用常见增长模式的图表。这展示了通常由平台构建者主导的缓慢起步。一旦平台为用户提供足够的价值，增长将更多地由用户拉动，导致采用曲线变得更陡峭。</em>
</figcaption>
</figure>
</br>
</br>

### 第1级，临时 — 零散

共享平台和功能的采用是零星且不一致的。没有全组织范围内的策略或指导来选择和整合所需的后端服务和技术。个别团队可能会利用平台实践来改进自己的流程，但组织内部没有协调努力或标准化。这种采用水平的特点是缺乏一致的方法和认为外部工具比内部提供的工具更有效的观念。

#### 特点：

* 一次性的工具、服务和功能由组织内的各个团队和部门管理和使用。
* 提供商管理的（即“云”）服务被不一致地采用和使用，没有标准的实践和政策，因为内部配置难以找到或使用。
* 应用和服务团队通过传言和偶然的交谈而非通过更集中的流程偶然发现工具和功能。
* 组件和功能的协调和重用仅由最终用户（应用团队）推动，如果有的话。
* 产品团队各自维护自己的脚本或工具来部署他们的应用程序。

#### 示例场景：

* 一个银行服务需要一个数据库。一个开发者从另一个团队的朋友那里得知，他们可以申请一个AWS账户并设置一个RDS数据库。从另一个团队那里，他们找到了一个Terraform脚本来配置那个数据库。对于监控，他们临时使用CloudWatch；他们从AWS控制台手动复制秘密到Hashicorp Vault的一个实例，然后运行Terraform脚本。

### 第2级，运营化 — 外在推动

组织认识到共享平台和功能的价值，并努力鼓励和培养它们。内部指令激励甚至要求在某些用例中使用共享平台服务。一些产品团队比其他团队更多地使用平台功能；功能覆盖了组织中的典型用例，但不包括不寻常的用例；并且将这些异常添加到公共平台中很困难。

用户发现功能以及如何使用它们的一致性不佳；产品团队上的用户可能不会发现支持的功能，除非平台团队将他们引导到那里。

#### 特点：

* 一定程度的外部推动导致使用平台功能，例如：
  * 个人评审等激励措施
  * 生产发布或获得资金等强制要求
* 平台功能的利用是零散的 — 用户可能利用一个功能，但可能不知道或不感兴趣采用其他可用的功能。
* 用户学习如何使用平台功能的动机不高，严重依赖与提供者通过办公时间或帮助台等论坛的合作。
* 鼓励平台用户加入非正式的实践社区来分享问题和解决方案，但参与可能有限。

#### 示例场景：

* 一个工程组织决定使用一个标准的部署工具，并指示所有团队使用它。围绕该标准建立了新的流程（发布说明的沟通等）。团队被指示停止使用其他类型的部署脚本，改用通用工具。对于一些团队来说，这很困难，因为他们的需求没有得到新流程的满足，但他们不理解或不允许扩展它。

### 第3级，可扩展 — 内在吸引

产品和服务团队选择使用平台及其功能，因为它们在减轻产品团队的认知负担的同时提供了更高质量的支持服务方面提供了明确的价值。文档和人性化的界面使产品团队用户能够快速配置和使用平台功能。用户选择内部平台实现而不是其他替代方案，例如自己开发功能或雇用提供商。

#### 特点：

* 平台采用是自我维持的 —— 主要的采用驱动力不是外部的推动或激励措施，而是这些平台提供的价值本身吸引用户使用它们。
* 在使用和欣赏一个或某些平台功能后，用户会寻找其他功能，并发现跨功能的体验是相似的。人们期望一个单独的功能不是孤立的，而是更大平台功能集中的一个特性。
* 平台团队通过收集用户反馈、分享路线图并维护与用户对话的开放论坛来鼓励平台的自然采用。
* 应用和产品团队足够重视平台功能，以至于愿意为它们付费，例如通过计费回收系统。
* 用户可以通过开放论坛和共享路线图分享反馈并了解即将推出的功能。
* 自助服务门户、黄金路径模板和其他文档使得快速使用成为可能。

#### 示例场景：

* 一个应用团队之前成功请求了一个新数据库。他们的流程易于理解，几乎不需要等待时间。此外，关键功能如备份和监控使团队能够在没有问题的情况下将使用推进到生产。这种经验意味着，当团队后来需要一个队列时，他们的第一反应是检查内部平台选项。虽然他们最初打算使用特定的队列技术，但最终他们选择使用内部提供的技术，因为他们知道这个解决方案将如何为他们的组织提供良好的集成。

### 第4级，优化 — 参与性

产品团队的用户通过加入生态系统并为其做出贡献，进一步投资于平台功能。一些贡献改进和修复现有功能；其他贡献引入新功能和特性以解决新的用例。定义了流程和服务，使用户能够识别需求并在多个产品和平台团队之间协调贡献。新功能通过一致的界面和门户发布，并具有完整的文档和标准版本。

#### 特点：

* 应用/服务团队的用户被授权为平台功能贡献修复、特性和反馈。
* 战略性地利用外部项目和标准以降低维护成本，加速新功能交付，并最有效地使用组织人力。
* 新功能和增强功能通过问题板和拉取请求异步协调。文档和清单使贡献者能够自主开发。
* 开发者倡导者和内部大使建立和支持一个内部用户社区，将平台所有权扩展到应用和服务团队的贡献者。
* 组织内的领导和个人贡献者都将使用平台功能视为最佳工作方式。
* 平台工程师参与产品团队的规划，了解需求并建议相关的现有功能。

#### 示例场景：

* 一个团队想要一个备选的备份计划。在提议将其作为一般性提供后，由于重用性很低，它被认为是低优先级。提议团队选择将他们的解决方案集成到平台框架中，并使其可供组织使用。最初它是一个alpha版本的提供，但一旦满足所有运营要求，就可以提升为核心平台功能。

## 接口模型详细信息

#### *用户如何与平台功能进行交互和使用？*

平台提供的接口影响用户如何与这些平台产品进行交互，以配置、管理和观察功能。接口可以包括工单系统、项目模板和图形门户，以及可自动化的API和命令行（CLI）工具。

接口的关键特性包括在关键用户旅程（如初始请求、维护或事故分类）期间的可发现性和用户友好性。这里的成熟度更高反映了更集成、一致、自动化和支持的接口。

### 第1级，临时 — 定制流程

存在一系列不同的流程来配置不同的功能和服务，但没有考虑接口的一致性。定制的量身定做的流程满足个人或团队的即时需求，并依赖于手动干预，即使提供者使用了一些自动化实施脚本。

如何请求这些解决方案的知识是通过人传人分享的。请求服务的流程缺乏标准化和一致性。配置和使用平台服务可能需要能力提供者的深度支持。

缺乏中央要求和标准使得这个级别适用于公司尚未识别和记录期望的情况。对于处于早期阶段的公司或平台努力的团队来说，这可以特别有效。在这些环境中，团队被赋予自由以根据他们的需求发展流程和功能，允许他们更快地交付，并仅在以后必要时支付标准化的代价。

#### 特点：

* 用户交互不是讨论的关键话题，设计和交付新功能时很少（如果有的话）测试交互。
* 功能主要通过手动请求提供，尽管提供者可以选择自动化部分或全部必要的活动来处理用户请求。
* 表面上“简单”的请求因找不到正确的流程而变得复杂。
* 有时候一个流程看似得到批准，但当涉及到不同部门或团队时，用户会遇到问题。

#### 示例场景：

* 一个应用团队想要对他们的新变更进行性能测试。为此，他们需要一个包含足够测试数据的隔离环境来获得准确的性能读数。上次他们有这个请求时，一个前同事能够获得一个环境的访问权限，但他们已经离开了，没有人知道如何重新创建它。最终，他们联系到基础设施团队的一名工程师，他能够在几天内为他们提供一个环境。
* 一个处于产品开发探索阶段的团队使用定制流程来配置新的云服务，而不需要验证他们的解决方案是否值得进一步投资。

### 第二级，运营化 — 标准工具

存在一致的、标准的接口用于配置和观察平台和功能，并满足广泛的需求。用户能够识别哪些功能是可用的，并能够请求他们需要的功能。

提供“铺好的道路”或“黄金路径”，以文档和模板的形式。这些资源定义了如何使用符合标准和经过测试的模式来配置和管理典型功能。虽然一些用户能够独立使用这些解决方案，但这些解决方案通常仍然需要深入的领域专业知识，因此维护者的支持仍然至关重要。

#### 特点：

* 技术解决方案是针对其问题领域的内置工具，而不总是用户熟悉的工具。
* 有投资在一个共同的路径上；然而，一旦偏离这条路径，就会很快发现很少有定制选项，因为重点是构建单一选项。
* 鉴于标准化，非正式的内部小组能够形成并聚集起来，分享良好的实践并克服共同的问题。
* 随着团队采用模板、定制它们，然后无法将更改合并到中央团队中，功能实现可能会发生偏移。

#### 示例场景：

* 一个中央团队策划了一个Terraform模块、Kubernetes控制器和CRD的库，用于配置不同类型的基础设施。
* 一个共享位置包括跨组织的解决方案的全面文档。

### 第三级，可扩展 — 自助服务解决方案

解决方案以一种赋予用户自主权并且维护者几乎不需要支持的方式提供。组织鼓励并使解决方案能够提供一致的接口，使用户体验的可发现性和可移植性从一个功能转移到另一个功能。虽然是自助服务，但解决方案确实需要团队意识和实施。为了改善这种体验，可能会有一个指导性和简化的内部语言，使用户能够更快地采用和整合平台功能。这产生了以用户为中心的、可自助服务的、一致的功能集合。

#### 特点：

* 解决方案以“一键”实现的形式提供，使团队能够从功能中受益，而不需要了解它们是如何配置的。
* 虽然解决方案易于创建，但可能没有在第二天及以后的解决方案管理中构建太多的可用性。
* 仍然存在可用解决方案的狭窄路径，使得有独特需求的用户不确定如何继续。

#### 示例场景：

* 提供了一个API，它抽象了数据库的创建和维护，并为用户提供了利用该平台功能所需的任何信息，例如连接字符串、存放秘密数据的位置和带有可观察性数据的仪表板。

### 第四级，优化 — 托管服务

平台功能透明地集成到团队已经用来进行工作的工具和流程中。一些功能，如可观察性或部署服务的身份管理，是自动配置的。当用户遇到提供的服务的边界时，有机会超越自动化解决方案并根据需要定制，而不离开内部产品，因为平台功能被视为构建块。这些构建块被用来构建透明和自动的组合，以满足更高级别的用例，同时在必要时启用更深层次的定制。

#### 特点：

* 明确哪些功能对组织有区别，哪些没有，允许内部团队只在他们无法利用行业标准的地方投资定制解决方案。
* 虽然功能以一致的方式呈现，但没有一种使用功能的方式。有些最适合作为CLI工具在脚本中使用，而其他的则受益于集成到用户在编辑器和IDE中编写代码的地方。
* 通过关注软件开发和发布的流程，扩展了单个功能的价值，从而专注于如何将功能组合成更高级别的产品。
* 虽然功能通常以包的形式提供，但超级用户被赋能以分解这些更高级别的产品，以便在需要时进行优化。

#### 示例场景：

* 每个工作负载中都注入了可观察性代理，所有应用程序前都放置了OIDC代理。
* 默认情况下，每个新项目都会在任务运行器（管道）中获得一个空间和一个运行时环境（K8s命名空间），但项目可以选择其他选项，如无服务器运行时。
* 用户在Service Now门户的目录中选择“配置数据库”。自动化配置了一个RDS数据库，并向用户发送了一个URL和获取凭证的位置。

## 运营模型详细信息

#### *平台及其功能是如何规划、优先级排序、开发和维护的？*

平台的运营意味着在其整个生命周期内运行和支持其功能及其特性，包括接受新请求、初次发布、升级和扩展、持续维护和运营、用户支持，甚至是废弃和终止。组织及其平台团队选择要创建和维护的平台和功能，并可以优先考虑最有价值和影响力的举措。

值得注意的是，提供一个功能的大部分工作是在其初次发布之后进行的 — 提供无缝升级、新的和改进的功能、运营支持以及最终用户的启用和教育。因此，一个有影响力、有价值的平台将提前规划，并管理他们的平台，以实现长期可持续的运营和可靠性。

### 第一级，临时 — 按需求

平台和功能是基于临时的产品团队请求和需求，以反应性的方式开发、发布和更新的。产品团队本身甚至可能需要规划和构建他们所需的功能。

那些构建新功能的团队，无论是专门的中央团队还是满足自己需求的应用团队，都只是非正式地负责支持其他使用它的人。他们不被期望积极维护它，且很少有流程存在来审核产品的质量。在这个级别，实现通常被忽视，直到发现安全漏洞、一个错误阻止使用，或者出现新的需求，此时可能会迅速实施另一个反应性计划。

#### 特点：

* 功能是为了满足个别应用团队的迫切需求而创建的。
* 重点是核心功能的初始交付；没有为持续维护和可持续性制定计划。
* 功能实现通常已过时，等待更新。
* 为了应对突然出现的高影响力变更，如发现漏洞，引入了工作量的突然增加。
* 变更可能导致计划内和计划外的停机。
* 每次升级都是以定制的方式完成的，需要时间和研究来为每次升级设计流程。

#### 示例场景：

* 宣布了Log4Shell安全漏洞，组织组建了一个专门团队来调查组织可能存在的漏洞并启动补丁。一旦团队确定了影响，他们必须与许多不同的团队手拉手合作，因为每个团队都以不同的方式管理他们的服务器和升级流程。即使这项工作被认为已经完成，也很难有信心不会发现更多的实例。

### 第二级，运营化 — 中央跟踪

平台和功能在中央记录和可发现，并且至少轻度定义了规划和管理功能生命周期的流程。每项服务和功能的责任和所有权都有文档记录。不同功能的生命周期管理流程因其所有者和优先级而异。一个中央团队维护或能够按需生成一个后备能力清单，以提供当前功能的维护状态。这使组织能够跟踪能力提供和升级要求的进展。

#### 特点：

* 应用团队根据需要创建新功能以满足迫切需求。
* 中央团队提供了一个跨组织可用的共享服务注册表。
* 应用了松散的标准，例如要求可自动化的API和使用文档，到功能上。
* 使用基础设施即代码来更容易地追踪部署的服务。
* 通过服务清单启用了对PCI DSS或HIPPA等合规法规的审计。
* 迁移和升级工作被跟踪在燃尽图上，使组织能够跟踪合规率和完成时间。
* 跟踪并不表明支持水平；通常在这个阶段的升级仍然是手动和定制的。

#### 示例场景：

* PostgreSQL 11将在年底前停止服务。组织知道哪些数据库需要升级，并正在安排每个团队的待办事项清单上的工作以完成。

### 第三级，可扩展 — 中央启用

平台和能力不仅要在中央注册，还要由中央进行统筹。平台团队负责了解组织的广泛需求，并相应地优先处理平台和基础设施团队的工作。负责某项能力的人不仅要从技术上维护它，还要为将该能力与组织周围的其他相关服务集成提供标准用户体验，确保安全可靠的使用，甚至提供可观察性。

存在创建和发展新能力的标准流程，使组织中的任何人都能贡献出符合预期的解决方案。平台能力和特性的持续交付流程支持定期的推出和回滚。大的变更计划和协调，就像面向客户的产品变更一样。

#### 特点：

* 应用团队在创建服务之前，首先向平台团队请求服务。
* 新服务必须遵循标准实践，如标准接口、文档和治理。
* 升级流程在各个版本和服务之间都有记录且一致。
* 如果能力提供者不管理升级，他们会提供工具和支持，以便用户受到的影响最小。

#### 示例场景：

* 组织即将升级到RHEL 9。在此过程中，每个应用团队都需要验证他们的软件是否继续工作。为了使这一测试阶段成为可能，中央计算团队为每个团队设置了测试环境，配备了正确的软件和操作系统版本。

### 第4级，优化 — 管理服务

每项能力的生命周期都以标准化、自动化的方式进行管理。能力、特性和更新持续交付，不影响用户。平台提供者引发的任何大变更都包括现有用户的迁移计划，以及明确的责任和时间表。

平台能力提供者承担了维护的大部分责任，但有一个明确的合同 —— 一个“共享责任模型” —— 描述了用户的责任，使双方能够基本上自主运作。

#### 特点：

* 共享所有权模型清晰定义了谁对平台及其能力负责，以及用户的期望是什么。
* 团队编写了执行升级和任何回滚策略的脚本，以保持风险和影响低。

#### 示例场景：

* 虚拟机的用户不需要管理与版本升级相关的任何事务。他们唯一的要求是在交付管道中有一个包含代表性烟雾测试的阶段。然后，他们被要求声明他们的应用程序对风险的容忍度较低，以便等待一个完全加固的升级，或者容忍度较高以成为早期采用者。然后虚拟机能力管理自动发布升级，包括在烟雾测试或金丝雀发布失败后的回滚。

## 测量模型详细信息

#### *收集和整合反馈和学习的过程是什么？*

通过对用户的明确和隐含反馈做出反应，组织可以提高用户满意度并确保平台的长期可持续性。组织必须平衡创新和满足用户需求，以保持平台的相关性。随着技术和用户偏好的变化，那些敏捷并能响应这些变化的平台将脱颖而出。定期回顾和完善反馈机制可以进一步优化平台开发并提高用户参与度。

### 第1级，临时 — 临时性

如果有的话，平台和能力的使用和满意度指标是以定制的方式收集的。成功的结果和衡量标准在各个能力之间不一致，因此相应的洞察也没有收集到。可能没有收集用户反馈和平台使用的仪表化数据，或者如果有，也是非正式的。决策是基于轶事性要求和不完整数据做出的。

#### 特点：

* 没有关于如何衡量平台成功的经验或意见
* 使用熟悉的工具以有限的意图和思考收集常见指标
* 依赖少量数据
* 难以获得用户参与 — 用户认为他们的反馈不被考虑
* 如果使用调查，问题在每次运行之间都会改变，无法追踪进展

#### 示例场景：

* 一个平台技术负责人希望通过在下一个季度计划中添加关键话题来改善与用户的协作。他们决定进行一项调查，了解用户想看到什么。反应热烈，这很令人兴奋，但也导致难以组织和响应所有的想法。虽然一些想法影响了季度计划，但用户没有看到他们的想法被接受，因此不太愿意回答下一次调查。
* 团队希望自动捕获更多数据，因此他们寻找易于收集的机会，例如CI中的测试失败。然而，并不是每个团队都使用相同的CI自动化，所以数据只适用于Java应用程序，尽管有些团队已经转向用Scala编写他们的服务。

### 第2级，运营化 — 一致性收集

在这个级别的组织有一个明确的目标，以验证平台产品满足其内部用户市场的需求。重视可操作的、结构化的用户反馈收集。可能会指定专门的团队或个人来收集反馈，确保更一致的方法。反馈渠道，如调查或用户论坛，是标准化的，反馈被分类和优先排序。除了用户反馈，还期望用户体验被仪表化，以便随着时间的推移生成使用数据。

将反馈转化为可操作任务仍然存在挑战。虽然用户数据的存储库在增长，但组织可能需要帮助有效地理解和将这些反馈整合到平台路线图中。可能很难确保用户看到由他们的反馈驱动的实际变化。

#### 特点：

* 数据收集作为大多数主要规划会议或能力实施的一部分进行讨论。
* 可能没有就确切要测量什么以验证成功达成一致。
* 可以衡量平台特性的成功，例如通过衡量用户采用或节省的用户时间。

#### 示例场景：

* 一个平台团队将他们20%的时间分配给用户定义的特性，他们根据调查和其他访谈技巧确定这些特性。他们的发现被收集到一个工具中，该工具支持额外的投票和评论，以进一步细化优先级。在实施过程中，请求用户被邀请合作早期设计和实施。一旦实施，会有公告确保请求用户了解新特性并在采用它们时得到支持。
* 专注于软件交付能力的团队希望自动捕获更多数据，包括他们通过从提交到生产的构建工具自动化的周期时间。大家都明白，周期时间可能包括其他活动，如PR审查，但目前还没有包括。

### 第3级，可扩展 — 洞察

虽然已经存在健全的标准反馈机制，但在这个阶段，数据以精心设计的方式收集，以产生特定的战略洞察和行动。确定了期望的结果和成果，然后选择标准指标来指示朝这些成果的进展。可能会使用行业框架和标准，以从行业研究中受益，了解某些行为的影响。

专门的团队或工具被用来收集和审查反馈，并总结可操作的洞察。建立了平台产品和用户之间的互惠关系。反馈被视为指导平台运营和路线图的战略资产。可能会设立定期的反馈审查会议，跨职能团队聚在一起，根据用户洞察进行讨论和策略制定。

#### 特点：

* 在交付任何新的平台特性之前，团队会讨论如何评估他们工作的成果。
* 组织在衡量平台倡议成功的指标上有广泛的一致性。
* [产品经理](https://tag-app-delivery.cncf.io/wgs/platforms/glossary/#platform-product-managers)或专门的团队成员推动持续且一致的反馈收集和分析过程。
* 组织已经建立了指标和目标，以观察和指向以指示成功。

#### 示例场景：

* 组织一直在跟踪构建时间和领先时间。然而，现在他们意识到，虽然易于收集，但这些指标本身并不能提供软件交付的完整画面。考虑到这一点，团队实施了服务可靠性和稳定性的测量。

### 第4级，优化 — 定量和定性

反馈和测量深度融入组织文化。从高层执行官到全组织的工程师，整个组织都认识到数据收集和产品演进反馈的价值。数据民主化，各种利益相关者，包括平台用户和业务领导者，都积极参与确定平台改进的假设，提供设计过程中的反馈，然后在交付后测量影响。所有这些测量都在规划平台倡议时考虑。

不仅利用了标准框架，而且还理解从多个角度测量可以创建更全面的画面。投资于了解定性指标如何随着定量指标的改进而变化。重点是识别领先指标，这可以预测支持用户需求的特性，减轻他们的挑战，并领先于行业趋势和业务要求。

#### 特点：

* 平台团队不断寻求改进他们关注的指标和收集数据的方式。
* 组织熟悉并对[古德哈特法则](https://en.wikipedia.org/wiki/Goodhart%27s_law)敏感：“当一个度量变成目标时，它就不再是一个好的度量。”
* 收集的指标和遥测数据不断评估以获得真正的洞察和价值。
* 指标数据管理得到良好支持，例如标准平台能力管理数据湖并得出洞察。
* 鼓励跨部门合作，避免数据孤岛，实现有效的反馈循环。

#### 示例场景：

随着时间的推移，该组织收集的数据显示构建时间增加了超过15%。这导致了开发者体验的负面影响，一旦触发，即使构建时间降低到原来的水平以下，开发者的挫败感也会持续更长时间。这一洞察促使构建团队设定并坚持遵守服务水平目标（SLO），这使得他们能够在触发用户的负面循环之前，及早识别问题并进行改进。

---
## 结论

平台及其维护者为敏捷数字产品开发提供了基础。它们提供了一套一致的能力集合，使得软件开发和交付更加高效。这个成熟度模型为您的平台工程之旅提供了一张地图。