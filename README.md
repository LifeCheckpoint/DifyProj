# DifyProj

一些基于 `Dify` 的工作流合集，由于使用了自定义的 LLM API 提供商，如需使用需要将其中的模型替换为可用接口

## 1. 文本分析Flow

**对一段给定的文本，给出有见解的分析**

大致步骤：

1. 针对文本提出研究方向关键词
2. 搜索和回忆关键词相关背景
3. 基于关键词多模型集成讨论
4. 针对讨论作出建设性批判
5. 综合讨论与批判得到最终观点
6. 将所有关键词研究内容整合，重构观点

> [!CAUTION]
> LLM 输出仅供参考，其中可能含有并不存在的学术背景与概念

**Example 1**

> 听好了，十夜，好好听着哦
> 
> 嗯…听着呢，从刚才开始就一直好好听着呢
> 
> 嗯，是啊，十夜的话肯定没问题的吧…虽然我相信你是没问题的…但是我还是希望你能听听这件事
>
> 嗯，嗯…是什么？
> 
> 那个啊，十夜。听好了，十夜…

> 这是一段来自galgame的对话，有人认为作者写得较为啰嗦，但我认为它有着独特的情感。

**OUTPUT**

> ## 最终文本文艺解读
> 
> ### 一、对话的自然性与情感表达
> 
> 这段对话看似简单，甚至带有一定的重复性，但实际上通过日常化的语言结构和细腻的语气词，构建了一种真实而富有情感张力的对话场景。对话中的重复（如“听好了，十夜”）和语气词（如“嗯…”）并非冗余，而是对日常对话中常见的情感表达方式的精准捕捉。这种设计使得对话更加贴近真实生活，同时也为角色情感的传递提供了细腻的载体。
> 
> **显性层面**：对话呈现出一种自然的交流模式，符合日常对话中常见的确认与回应机制。例如，“嗯…听着呢”不仅是对对方话语的回应，也体现了角色在对话中的参与感。
> 
> **隐性层面**：通过重复和停顿，对话暗示了说话者内心的犹豫与关切。例如，“虽然我相信你是没问题的…但是我还是希望你能听听这件事”展现了说话者既信任对方又希望对方重视的矛盾心理。
> 
> ### 二、角色互动的层次感
> 
> 对话通过角色之间的互动，展现了复杂的情感层次：
> 
> **主动者**：通过祈使句（“听好了”）和假设语气（“肯定没问题的吧”）试图主导对话，但同时也流露出恳求的姿态（“但是我还是希望你能听听这件事”）。
> 
> **回应者**：通过简短的附和（“嗯…听着呢”）表现出被动但专注的态度，体现了对对方话语的尊重与回应。
> 
> 这种互动不仅展现了角色之间的关系，也为后续剧情的发展埋下了伏笔。例如，“那个啊，十夜…”的欲言又止，为对话增添了悬念感，激发了读者（玩家）的好奇心。
> 
> ### 三、重复的叙事功能
> 
> 对话中重复的“十夜”并非简单的啰嗦，而是具有多重叙事功能：
> 
> **角色维度**：通过重复强化了被呼唤者的在场感，使角色更加鲜明。
> 
> **情感维度**：重复的称呼体现了说话者对对方的重视与关切，增强了情感表达的力度。
> 
> **叙事维度**：未说完的“那个啊…”为后续剧情的发展提供了期待感，符合galgame叙事中常见的悬念设置手法。
> 
> ### 四、日常对话中的情感张力
> 
> 文本通过看似琐碎的日常对话，展现了角色之间微妙的情感张力。例如，“虽然我相信你是没问题的…但是我还是希望你能听听这件事”中的转折，不仅体现了说话者的矛盾心理，也为对话增添了情感深度。这种设计使得对话在自然中蕴含了丰富的情感内涵，符合galgame叙事中注重情感表达的特点。
> 
> ### 五、理论运用的适切性
> 
> 通过对话理论的分析，可以更深入地理解文本的情感表达机制：
> 
> **巴赫金的对话理论**：对话中的重复与停顿并非冗余，而是通过语言互动构建了双重情感空间，既展现了显性的日常交流，又暗示了隐性的心理活动。
> 
> **克里斯蒂娃的互文性理论**：对话中的重复与转折在横向轴上形成了意义的补足，而在纵向轴上则与galgame的叙事惯例形成了呼应。
> 
> 这种理论运用并非强行套用，而是基于文本特征的自然延伸，有助于揭示对话中的情感与叙事功能。
> 
> ### 结论
> 
> 该文本通过精心设计的对话结构，将日常对话的自然性与情感表达的深度相结合，展现了角色之间复杂的情感互动。其价值不在于语言的经济性，而在于通过细腻的语言设计，将表层对话转化为角色心理的映射，为后续剧情的发展提供了情感基础。这种设计不仅符合galgame叙事的媒介特性，也为玩家（读者）提供了丰富的诠释空间，体现了互动叙事作品的独特魅力。