# 如何玩

## 角色扮演：如何进行

本指南将教您如何与DreamGen角色扮演系统进行基本互动。

## 场景

场景代表了一些故事背景/情节以及一组你可以互动的角色。例如：

- **"佛罗多在夏尔"** — 一个生活片段场景，你扮演佛罗多，与来自夏尔的其他角色互动。
- **"揭开黑暗谜团"** — 一个场景，你扮演侦探，调查一些黑暗的谜团。
- **"你和你的可爱女友"** ― 一个场景，你扮演自己，与一个代表你女友的角色互动。

## 查找场景

您可以在 [角色扮演](https://dreamgen.com/app/rp) 页面浏览场景。

## 创建场景

要创建您自己的场景，请参阅我们的[专门的场景创建指南](/role-play/create)。  
您还可以复制和调整现有场景，这也是学习场景创建艺术的好方法。  
只需找到您想要复制和调整的场景，点击垂直省略号按钮，然后选择“复制”。

## 开始一个场景

要开始一个场景，请点击场景卡片或页面上的“开始聊天”按钮。

![场景卡片](https://dreamgen.com/_next/static/media/scenario_card.c806958f.png)

之后，您将进入“设置”屏幕，在这里您可以自定义您的角色。具体来说：

- **名称：** 您角色的名称。这将在场景的提示和互动中使用。尽量保持简短，不要使用特殊字符和空格。
- **描述：** 您角色的简短描述。这将在场景的提示中使用，以告知模型有关您的信息。您应该包括您希望模型牢记并遵循的关于您自己的信息。这些可以是身体或心理特征，或者您角色的喜好和厌恶。

## 互动

互动是您或AI采取的行动。互动分为三种类型：
每个场景以几个互动开始，用于设置场景并介绍角色。

### 消息

消息是来自角色或用户（您）的单个对话片段。
它可能包含直接引用，也可能包含对角色动作或思想的描述。
例如：

![Interaction Message](https://dreamgen.com/_next/static/media/interaction_message.a7ac5155.png)

### 文本

文本是角色扮演故事中的一个普通部分，并不归属于任何角色。它通常用于描述场景、提供背景等。例如：

![Interaction Text](https://dreamgen.com/_next/static/media/interaction_text.9f8022db.png)

### 指令

指令是一种特殊的交互方式，用于引导模型。它可以用于将模型引导向某些结果，即使这些结果通常不是模型的特征。某些具体的使用案例包括：

- **方向:** "萨曼莎决定亲吻杰克的脸颊"。
- **时间跳跃:** "故事快进到几天后，杰克和萨曼莎在约会"。

例如：

![交互指令](https://dreamgen.com/_next/static/media/interaction_instruction.3b172d42.png)

### Sticky Interactions

当一个交互被标记为“sticky”时，在我们决定在遇到令牌限制时要修剪哪些交互和保留哪些交互时，它将被优先考虑。对于指令交互，“sticky”还意味着即使您在[设置](/model-settings)中选择“仅保留最后一条指令”，它也不会被移除。

## 互动编辑器

### 输入

此输入允许您向场景中添加另一个互动。您可以使用顶部菜单中的三种互动类型中的任何一种：

![Instruction Input](https://dreamgen.com/_next/static/media/interaction_input.eb6bf996.png)

当您选择“消息”时，您还可以通过点击左侧的头像选择消息来自哪个角色（包括您自己）。这意味着您可以模仿场景中的任何角色，从而给予您很大的创作自由。

![Instruction Input Select Character](https://dreamgen.com/_next/static/media/interaction_input_select_character.8fdd984b.png)

您还可以（针对任何类型的互动）通过选择强制特定角色的消息来影响回复。请点击底部的“No forced reply”选择对话框：

![Instruction Input Forced Reply](https://dreamgen.com/_next/static/media/interaction_input_forced_reply.0eee1547.png)

### 发送与继续

如您所见，在右下角有两个按钮：“发送”和“继续”。它们的功能如下：

#### 发送

将您指定的交互发送给模型，并等待模型生成回复。

#### 继续

不向模型发送任何新的交互，而是请求模型从上一个交互继续。

这在某些情况下很有用，例如当模型的最后一次交互被截断时（例如，由于达到最大输出令牌限制，或因为您进行了编辑）。

另一个可能的应用是当您希望模型为您编写整个场景（包括您的消息），而无需您提供任何输入。为此，您还需要调整一些设置（见下文）。

**注意：** 有时当您点击“继续”时，可能不会收到任何回复。这可能是因为模型已判断轮到您了。对此有几种解决方法：

1. 让模型为您进行一次交互。在[设置](/model-settings)中取消选择“在用户消息之前停止”。
2. 强制模型为特定角色进行交互。点击底部的“无强制回复”按钮，选择您希望模型以其回复的角色。
3. 再试一次，或更改最后一次交互。模型不是确定性的，有时您可以再试一次并获得好运。

### 编辑现有交互

您可以编辑或删除任何现有的交互。只需点击您想要编辑或删除的交互右上角的铅笔按钮（或者，双击或长按该交互）：

![Interaction Edit](https://dreamgen.com/_next/static/media/interaction_edit.45df652a.png)

之后，该交互将变为可编辑状态，您可以根据需要进行更改或删除：

![Interaction Edit Bar](https://dreamgen.com/_next/static/media/interaction_edit_bar.3fc8ea5c.png)

## 设置

查看我们的完整 [模型设置指南](/model-settings)。有几个特定于角色扮演的设置：
**超过限制修剪交互**、**“在 N 次交互后停止”**、**“在用户消息前停止”**、**“显示隐藏交互”**，在 [本节](/model-settings#role-play) 中进行了描述。

**超过限制修剪交互** 默认选中，如果交互超过令牌限制，则会移除交互，首先删除非粘性的旧交互。

**“在用户消息前停止”** 默认选中，确保模型不会以您的名义发送消息。
如果您取消选中，它将允许模型为您生成消息，这有时也会非常有趣。

**“显示隐藏交互”** 默认未选中。选中后，它将显示标记为“隐藏”的交互。