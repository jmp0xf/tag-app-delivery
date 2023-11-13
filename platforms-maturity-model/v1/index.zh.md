#### Characteristics:

* Capabilities are treated as managed services with well-defined SLAs and SLOs.
* Platform teams have well-defined processes for gathering feedback, prioritizing enhancements, and planning releases.
* Continuous delivery pipelines are used to automate the deployment of capabilities and features.
* Platform teams have a clear understanding of the impact of changes on users and take steps to minimize disruption.
* Capabilities are continuously monitored and optimized for performance, reliability, and security.

#### Example Scenarios:

* A platform team releases a new version of a database service with improved performance and additional features. The upgrade process is automated and transparent to users, with no downtime or disruption.
* Platform teams proactively monitor the usage and performance of their capabilities and make optimizations to improve efficiency and reliability.

{{< /tab >}}
{{< tab tabName="Measurement">}}

<h4 style="color:gray;padding-bottom:10px;padding-top:20px"><i>What is the process for gathering and incorporating feedback and learning?</i></h4>

Measurement is the process of collecting feedback and data to evaluate the effectiveness and impact of platform capabilities. It involves understanding the needs and satisfaction of users, identifying areas for improvement, and using data to drive decision-making and prioritization.

At each level of maturity, the measurement process becomes more systematic, consistent, and data-driven. This enables platform teams to make informed decisions, iterate on their capabilities, and continuously improve the value they provide to users.

### Level 1, Provisional — Ad hoc

Measurement of platform capabilities is ad hoc and inconsistent. There is no formal process for collecting feedback or measuring user satisfaction. Feedback is often anecdotal and based on individual experiences or conversations. There is little to no data available to evaluate the impact or effectiveness of platform capabilities.

#### Characteristics:

* Feedback is collected on an ad hoc basis, often through informal conversations or meetings.
* There is no formal process for analyzing or incorporating feedback into platform improvements.
* User satisfaction is not measured or tracked systematically.
* There is no data available to evaluate the impact or effectiveness of platform capabilities.

#### Example Scenarios:

* A platform team receives occasional feedback from users during casual conversations or meetings.
* User satisfaction with platform capabilities is not measured or tracked.

### Level 2, Operationalized — Consistent collection

Measurement of platform capabilities is more consistent and structured. There is a formal process for collecting feedback and measuring user satisfaction. Feedback is collected through surveys, interviews, or other structured methods. The platform team analyzes the feedback and incorporates it into their improvement plans. User satisfaction is measured and tracked, although the process may not be fully automated or integrated with other systems.

#### Characteristics:

* Feedback is collected through surveys, interviews, or other structured methods.
* The platform team analyzes the feedback and identifies areas for improvement.
* User satisfaction is measured and tracked, although the process may not be fully automated or integrated with other systems.
* The platform team uses the feedback and data to prioritize improvements and make informed decisions.

#### Example Scenarios:

* A platform team sends out regular surveys to users to gather feedback on their satisfaction and identify areas for improvement.
* User satisfaction scores are tracked and reviewed by the platform team to identify trends and prioritize improvements.

### Level 3, Scalable — Insights

Measurement of platform capabilities is systematic and data-driven. Feedback is collected through a variety of channels, including surveys, interviews, usage analytics, and user support interactions. The platform team uses data analysis techniques to gain insights into user needs, pain points, and satisfaction. User satisfaction is measured and tracked in a systematic and automated way. The platform team uses the insights and data to drive decision-making, prioritize improvements, and iterate on their capabilities.

#### Characteristics:

* Feedback is collected through a variety of channels, including surveys, interviews, usage analytics, and user support interactions.
* Data analysis techniques, such as segmentation and correlation analysis, are used to gain insights into user needs, pain points, and satisfaction.
* User satisfaction is measured and tracked in a systematic and automated way.
* The platform team uses the insights and data to drive decision-making, prioritize improvements, and iterate on their capabilities.

#### Example Scenarios:

* A platform team collects feedback through surveys, usage analytics, and user support interactions.
* Data analysis techniques are used to identify patterns and trends in user feedback and behavior.
* User satisfaction scores are tracked and reviewed on a regular basis, and improvements are prioritized based on the insights gained from the data.

### Level 4, Optimizing — Quantitative and qualitative

Measurement of platform capabilities is comprehensive and combines both quantitative and qualitative data. Feedback is collected through a variety of channels, including surveys, interviews, usage analytics, user support interactions, and user forums. Advanced data analysis techniques, such as predictive modeling and sentiment analysis, are used to gain deeper insights into user needs, pain points, and satisfaction. User satisfaction is measured and tracked in a systematic, automated, and real-time manner. The platform team uses the quantitative and qualitative data to drive continuous improvement, make data-driven decisions, and optimize their capabilities.

#### Characteristics:

* Feedback is collected through a variety of channels, including surveys, interviews, usage analytics, user support interactions, and user forums.
* Advanced data analysis techniques, such as predictive modeling and sentiment analysis, are used to gain deeper insights into user needs, pain points, and satisfaction.
* User satisfaction is measured and tracked in a systematic, automated, and real-time manner.
* The platform team uses the quantitative and qualitative data to drive continuous improvement, make data-driven decisions, and optimize their capabilities.

#### Example Scenarios:

* A platform team collects feedback through surveys, interviews, usage analytics, user support interactions, and user forums.
* Advanced data analysis techniques, such as predictive modeling and sentiment analysis, are used to gain deeper insights into user needs, pain points, and satisfaction.
* Real-time dashboards and reports provide up-to-date information on user satisfaction and platform performance.
* The platform team uses the data to identify areas for improvement, prioritize enhancements, and optimize their capabilities.

{{< /tab >}}
{{< /tabs >}}
</div>

## Conclusion

This maturity model provides a framework for organizations to reflect on their platform engineering practices and identify opportunities for improvement. By evaluating their current level of maturity in each aspect, organizations can set goals and develop strategies to advance to higher levels. It is important to note that each aspect can be evaluated and evolved independently, but they are also interrelated and may require minimum levels in other aspects to improve in one. The ultimate goal is to develop a mature platform engineering discipline and create platforms that deliver value and enable the organization to achieve its goals.

平台能力提供商承担了维护的大部分责任，但有一个明确的合同 -“共享责任模型”，描述了用户的责任，使双方能够基本上自主运作。

#### 特点：

* 共享所有权模型清楚地定义了谁负责平台及其能力以及用户的期望。
* 团队脚本化执行升级和任何回滚策略，以降低风险和影响。

#### 示例场景：

* 虚拟机的用户不需要管理与版本升级有关的任何事情。他们唯一的要求是在交付流程中有一个代表性的冒烟测试阶段。然后，他们被要求将其应用程序声明为对完全强化的升级具有较低的风险容忍度，或对成为早期采用者具有较高的容忍度。然后，虚拟机能力会管理升级的自动发布，包括在冒烟测试或金丝雀发布失败后的回滚。

{{< /tab >}}
{{< tab tabName="测量">}}

<h4 style="color:gray;padding-bottom:10px;padding-top:20px"><i>如何收集和整合反馈和学习的过程是什么？</i></h4>

通过对用户的明确和隐含反馈做出反应，组织可以提高用户满意度并确保长期的平台可持续性。组织必须在创新和满足用户需求之间取得平衡，以保持平台的相关性。随着技术和用户偏好的变化，灵活和响应这些变化的平台将脱颖而出。定期审查和完善反馈机制可以进一步优化平台开发并提高用户参与度。

### Level 1，临时 - 临时性

为每个平台和能力以自定义方式（如果有的话）收集使用和满意度指标。结果和成功的衡量标准在能力之间没有一致性，因此无法收集相应的见解。用户反馈和平台使用的仪器化可能不会被收集，或者如果收集了，那么它将是非正式的。决策是基于传闻要求和不完整的数据做出的。

#### 特点：

* 对于衡量平台成功没有经验或意见
* 使用熟悉的工具收集常见指标，但意图和预见性有限
* 依赖少量数据
* 难以获得用户参与 - 用户认为他们的反馈不被考虑
* 如果使用调查，问题在每次运行之间会发生变化，无法追踪进展

#### 示例场景：

* 平台技术负责人希望通过在下一个季度计划中添加关键主题来改善与用户的协作。他们决定对用户想要看到的内容进行调查。回应非常多，这令人兴奋，但也导致了组织和回应所有想法的困难。虽然一些想法影响了季度计划，但用户并不认为他们的想法被接受，并且不太愿意回答下一个调查。
* 软件交付能力的团队希望自动捕获更多的数据，因此他们寻找易于收集的机会，例如CI中的测试失败。然而，并非每个团队都使用相同的CI自动化，因此该数据仅适用于Java应用程序，即使一些团队已经开始使用Scala编写服务。

### Level 2，操作化 - 一致的收集

在这个级别的组织中，有一个明确的目标是验证平台产品是否满足内部用户市场的需求。重视可行的、结构化的用户反馈收集。可能会指定专门的团队或个人来收集反馈，以确保更一致的方法。反馈渠道，如调查或用户论坛，是标准化的，并且反馈被分类和优先级排序。除了用户反馈外，还有一种期望用户体验被仪器化以生成随时间变化的使用数据。

在将反馈转化为可行任务方面仍然存在挑战。虽然组织可能有越来越多的用户数据存储库，但可能需要帮助有效地理解和整合这些反馈到平台路线图中。很难确保用户看到由他们的反馈驱动的实质性变化。

#### 特点：

* 数据收集是大多数重要计划会议或能力实施的讨论内容。
* 可能无法对验证成功的确切衡量标准达成一致。
* 可以衡量平台功能的成功，例如通过衡量用户采用率或节省的用户时间。

#### 示例场景：

* 一个平台团队将他们的20%时间分配给用户定义的功能，他们根据调查和其他访谈技术进行识别。他们的调查结果被收集到一个工具中，该工具可以进行额外的投票和评论以进一步细化优先级。在实施过程中，请求的用户被邀请在早期设计和实施中进行合作。一旦实施完成，会发布公告，确保请求的用户知道新功能并在采用中得到支持。
* 关注软件交付能力的团队希望自动捕获更多的数据，包括从提交到生产的周期时间，他们通过构建工具自动化了这一过程。他们了解周期时间可以包括其他活动，如PR审查，但目前尚未包括在内。

### Level 3，可扩展 - 洞察力

在这个阶段，强大而标准的反馈机制已经存在，数据以精心设计的方式收集，以产生特定的战略洞察和行动。首先确定期望的结果和成果，然后选择标准指标来表示朝着这些结果的进展。可以使用行业框架和标准来从行业研究中受益，了解特定行为的影响。

专门的团队或工具被用于收集和审查反馈，并总结可行的洞察。建立了平台产品与用户之间的共生关系。反馈被视为指导平台运营和路线图的战略资产。可能会设立定期的反馈审查会议，跨职能团队共同讨论和制定基于用户洞察的策略。

#### 特点：

* 在交付任何新的平台功能之前，团队讨论如何评估他们的工作结果。
* 组织在衡量平台倡议的成功方面达成了广泛的一致。
* 产品经理或专门的团队成员推动持续的、一致的反馈收集和分析过程。
* 组织已经建立了度量和目标，以观察和追踪成功的指标。

#### 示例场景：

* 组织一直在跟踪构建时间和交付时间。然而，现在他们意识到，虽然易于收集，但这些指标本身并不能完整地反映软件交付的情况。基于此，团队实施了服务可靠性和稳定性的测量。

### Level 4，优化 - 定量和定性

反馈和测量已经深入融入组织的文化中。整个组织，从高层管理人员到全体工程师，都认识到数据收集和产品演进的反馈的价值。数据的民主化，各方利益相关者，包括平台用户和业务领导者，积极参与到识别平台改进假设、在设计过程中提供反馈以及在交付后测量影响的过程中。在规划平台倡议时，所有这些测量都被考虑在内。

不仅利用标准框架，而且还理解从多个角度进行测量可以创建更全面的画面。投资于理解定性指标如何随着定量指标的改善而变化。专注于识别能够预测支持用户需求、减轻他们的挑战并紧跟行业趋势和业务需求的功能的领先指标。

#### 特点：

* 平台团队不断寻求改进他们关注的指标和数据收集方式的方法。
* 组织熟悉并重视[古德哈特定律](https://en.wikipedia.org/wiki/Goodhart%27s_law)：“当一个度量成为目标时，它就不再是一个好的度量。”
* 持续评估度量和遥测数据的真实洞察力和价值。
* 有良好的度量数据管理支持，例如管理数据湖和洞察力的标准平台能力。
* 鼓励跨部门合作，避免数据孤岛并实现有效的反馈循环。

#### 示例场景：

* 随着时间的推移，组织收集到的数据表明构建时间增加了15%以上。这引发了开发人员的负面体验，一旦触发，即使构建时间降低到原始时间以下，开发人员的不满情绪也会持续较长时间。这一发现促使构建团队设定并遵守服务水平目标（SLO），在引发与用户的负面循环之前实现早期识别和改进。

{{< /tab >}}
{{< /tabs >}}
</div>

</br>

---
## 结论

平台及其维护者为敏捷数字产品开发提供了基础。它们提供了一系列一致的能力，使软件开发和交付更加高效。这个成熟度模型为您的平台工程之旅提供了一个地图。