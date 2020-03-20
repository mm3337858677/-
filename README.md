本文主题内容： 

**1.翻译了[Tips for Getting Started Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/)的原则** 

**2.以[星巴克官网](https://www.starbucks.com.cn/)为例分析点评** 

----

# ✍编写Web可访问性
在[入门提示中](http://https://www.w3.org/WAI/tips/)

***************************************

### 摘要
此页面介绍了一些基本注意事项，以帮助您开始编写残障人士更容易访问的Web内容。这些技巧是帮助您满足Web Content Accessibility Guidelines（WCAG）要求的很好的实践。遵循相关WCAG要求的链接，“理解”文档中的详细背景，教程指南，用户案例等。



#### 页面的内容
*  **提供内容丰富，独特的页面标题** 
* **使用标题表达含义和结构**
* **让链接文字有意义**
* **为图像编写有意义的文本替代(以防当图像失效时)**
* **为多媒体创建文字记录和字幕**
* **提供明确的指引**
* **保持内容简洁明了**

----


### 提供有用的信息，独特的页面标题

对于每个网页，请使用简短的标题，来描述页面内容并将其与其他页面区分开。页面标题通常与页面的主要标题相同。将独特且最相关的信息放在首位；例如，将页面名称放在组织名称之前。对于属于多步骤过程的页面，请在页面标题中包括当前步骤。


####  示例：页面标题

#### ☑ 主页标题
![主页标题](https://images.gitee.com/uploads/images/2020/0318/154724_a284a9d0_4864777.png "主页主题.png")

#### ☑页面名称后跟组织名称

![页面名称后跟组织名称](https://images.gitee.com/uploads/images/2020/0318/154757_323cd4f4_4864777.png "页面名称后跟组织名称.png")

#### ☑页面名称，包括流程中的步骤

![页面名称，包括流程中的步骤](https://images.gitee.com/uploads/images/2020/0318/154816_1a142478_4864777.png "页面名称，包括流程中的步骤.png")
----

#### 更多信息
 * WCAG
    * [标题为2.4.2的页面](https://www.w3.org/WAI/WCAG21/quickref/#page-titled)（[了解2.4.2](https://www.w3.org/WAI/WCAG21/Understanding/page-titled)）

----

### 使内容丰富，独特的页面标题
使用短标题将相关段落分组，并清楚地描述各节。好的标题能提供内容的大纲。

#### 示例：使用标题来组织内容
❌标题不足

![标题不足](https://images.gitee.com/uploads/images/2020/0318/160538_85d15622_4864777.png "headings-poor.png")

✅使用标题和副标题

![使用标题和副标题](https://images.gitee.com/uploads/images/2020/0318/160613_9c742414_4864777.png "headings-good.png")

更多信息

*  **WCAG** 
    * [标题和标签2.4.6](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)（[理解2.4.6](https://www.w3.org/WAI/WCAG21/Understanding/headings-and-labels)）
    * [本节标题2.4.10](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)（[了解2.4.10](https://www.w3.org/WAI/WCAG21/Understanding/section-headings)）
    * [本节标题2.4.10](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)（[了解1.3.1](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships)）

*   **用户的故事** 
    * [屏幕阅读器用户如何使用标题导航](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)

----

### 使链接文字有意义
编写链接文本，以描述链接目标的内容。避免使用容易引起歧义的链接文本，例如“单击此处”或“阅读更多”。指示有关链接目标的相关信息，例如文档类型和大小，例如“建议文档（RTF，20MB）”。

#### 示例：使用链接文本描述目标页面
❌无信息
有关设备独立性的更多信息，[请单击此处]()。


✅ 有意义的信息
阅读[有关设备独立性]()的[更多信息]()。

更多信息

*  **WCAG** 
    * [链接目的（在上下文中）2.4.4](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-in-context)（[理解2.4.4](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-in-context)）
    * [链接目的（仅链接）2.4.9](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-link-only)  （[理解2.4.9](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-link-only)）

----

### 为图像编写有意义的文本替代
对于每个图像，编写提供图像信息或功能的替代文本。对于纯装饰性图像，无需编写替代文本。

#### 示例：使用替代文本传达重要信息
❌没有信息

![正在为手机充电](https://images.gitee.com/uploads/images/2020/0318/162303_b698e66e_4864777.png "phone_charging.png")为手机充电：使用随附的电缆和电源适配器将手机连接至电源插座。  **图片的替代文本**：“正在为手机充电” 


✅内容丰富

![输入图片说明](https://images.gitee.com/uploads/images/2020/0318/162421_93a0b3d0_4864777.png "phone_charging (2).png")为手机充电：使用随附的电缆和电源适配器将手机连接至电源插座。  **图片的替代文本** ：“将电缆插入电话的底部边缘。”

更多信息
*  **WCAG** 
    * [非文本内容1.1.1](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)（[理解1.1.1](https://www.w3.org/WAI/WCAG21/Understanding/non-text-content)）
*  **讲解** 
    * [图片](https://www.w3.org/WAI/tutorials/images/)
*  **用户的故事** 
    * [向盲人用户介绍替代文本的价值
](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)
----

创建多媒体文字记录和字幕
对于纯音频内容（例如播客），请提供内容文字记录。对于音频和视频内容（例如培训视频），也提供字幕。在文字记录和字幕中包括对理解内容很重要的语音信息和声音，例如“门吱吱作响”。对于视频字幕，还包括重要视觉内容的描述，例如“ Athan离开房间”。

更多信息
*  **WCAG** 
    * [字幕（预先录制）1.2.2](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)（[理解1.2.2](https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded)）
    * [音频描述或媒体替代（预先录制）](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-or-media-alternative-prerecorded)1.2.3（[了解1.2.3](https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded)）
*  **用户的故事** 
    * [描述字幕如何帮助聋哑学生](https://www.w3.org/WAI/people-use-web/user-stories/#onlinestudent)

----

### 提供明确的指示
确保说明，指导和错误消息足够清晰，易于理解，并避免不必要的专业性、技术性语言。描述输入要求，例如日期格式。

#### 示例：说明传达用户应提供哪些信息

密码至少应包含六个字符，并且至少包含一个数字（0-9）。

密码：![密码框](https://images.gitee.com/uploads/images/2020/0318/163825_1b6bfb53_4864777.png "密码框.png")

#### 示例：错误指示问题所在以及可能的解决方法
1.❗用户名“ superbear”已被使用。

2.❗密码必须至少包含一个数字。

更多信息
 *  **WCAG** 
    * [标签或说明3.3.2](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)（[理解3.3.2](https://www.w3.org/WAI/WCAG21/Understanding/labels-or-instructions)）
*  **用户的故事** 
    * [描述简单的说明，帮助学习有困难的人](https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant)

----

### 保持内容简洁明了
* 根据情况，使用简单的语言和格式。
* 编写简短明了的句子和段落。
* 避免使用不必要的复杂单词和短语。考虑为读者可能不知道的专业术语提供词汇表。
* 首次使用时请缩写。例如，Web内容可访问性指南（WCAG）。
* 考虑为读者可能不知道的术语提供词汇表。
* 适当使用列表格式。
* 考虑使用图像，插图，视频，音频和符号来帮助阐明含义。

#### 示例：让内容易读易懂

❌ **不必要的复杂** 

CPP：万一发生车辆碰撞，公司指派的代表将查清楚所涉及各方财产的损害程度与产生的原因。一旦我们的代表获得我们了解因果关系的信息，我们可能会也可能不会给予适当的赔款补偿。最终的决定可能会出现以下结果之一：索赔未获批准并被拒绝，索赔的状态不明确，在进一步处理之前将需要其他信息，部分索赔已获批准并且减免了赔款。分配和签发，或者索赔已完全批准，并且分配了总索赔赔款。

✅ **更容易理解** 
索赔处理程序（CPP）：如果您发生车祸，我们的公司代表将进行调查。调查结果将确定所有索赔款项。这可能导致：
* 批准的索赔-全额赔款
* 部分批准的索赔-部分赔款
* 未确定的索偿-需要更多信息
* 索赔被拒-不赔款
![理赔流程](https://images.gitee.com/uploads/images/2020/0318/164946_5392df22_4864777.png "clear_text_diagram.png")

更多信息
 *  **WCAG** 
    * [阅读级别3.1.5](https://www.w3.org/WAI/WCAG21/quickref/#reading-level)（[理解3.1.5](https://www.w3.org/WAI/WCAG21/Understanding/reading-level)）
    * [不寻常的单词3.1.3](https://www.w3.org/WAI/WCAG21/quickref/#unusual-words)（[理解3.1.3](https://www.w3.org/WAI/WCAG21/Understanding/unusual-words)）
    * [缩写3.1.4](https://www.w3.org/WAI/WCAG21/quickref/#abbreviations)（[理解3.1.4](https://www.w3.org/WAI/WCAG21/Understanding/abbreviations)）
*  **用户的故事** 
    * [阅读障碍者受益于易于阅读的文本
](https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent)

----

### 🚩 了解有关可用性的更多信息

这些技巧是您需要了解关于Web访问的一些注意事项。以下资源可帮助您了解为什么 可访问性 很重要，以及有关使残障人士更易访问网络的准则。
* [辅助功能简介](https://www.w3.org/WAI/fundamentals/accessibility-intro/) —介绍辅助功能并提供许多有用资源的链接
* [易访问性原则](https://www.w3.org/WAI/fundamentals/accessibility-intro/) -一个介绍WCAG要求
* [残疾人如何使用网络](https://www.w3.org/WAI/people-use-web/) -现实生活中的例子表明了残疾人无障碍获取的重要性
* [如何满足WCAG（快速参考）](https://www.w3.org/WAI/WCAG21/quickref/) -所有WCAG要求和技术的可定制参考


----
----


###  🤖**以[星巴克][1]官网为例的Web可访问性分析点评** 

----
### 1.针对不同的页面提供了不同的页面标题

![home](https://images.gitee.com/uploads/images/2020/0319/222954_103cc6ee_4864777.png "屏幕截图.png")

![register](https://images.gitee.com/uploads/images/2020/0319/223009_97c31331_4864777.png "屏幕截图.png") 

![story](https://images.gitee.com/uploads/images/2020/0319/223043_dc218061_4864777.png "屏幕截图.png")

**页面标题明显的标注出了当前页面的内容，美中不足的是
没有做到步骤细分😑**

----

### 2.在网页内容中使用了主标题与副标题来区分各个区块的内容
![Demo](https://images.gitee.com/uploads/images/2020/0319/222703_7cfd8643_4864777.png "屏幕截图.png")
![Menu](https://images.gitee.com/uploads/images/2020/0319/222730_b6ac341a_4864777.png "屏幕截图.png")

**简洁明了，用户能够很快的理解到想要传达的信息😉**

![colorless](https://images.gitee.com/uploads/images/2020/0319/222801_07caa67c_4864777.png "屏幕截图.png")

**且整体颜色风格为绿色，减轻了色盲障碍的视觉体验影响🧐**

----

### 3.没有使用链接文本描述目标页面
![href-wrong](https://images.gitee.com/uploads/images/2020/0319/222829_8e259c56_4864777.png "屏幕截图.png")

**直接使用了“单击此处”,无文本描述😟**

----

### 4.使用了替代文本传达重要信息
![href](https://images.gitee.com/uploads/images/2020/0319/222849_67aacc38_4864777.png "屏幕截图.png")

**为不同的超链接传送提供了简短的替代文本😀**

----

### 5.指出来用户该填写信息且何种内容
![mind](https://images.gitee.com/uploads/images/2020/0319/222903_1bf3fe7f_4864777.png "屏幕截图.png")

**简洁实用的登录框设计，空间足够大让用户更容易实用😀**

----

### 6.总体的内容设计非常简洁易懂
![story](https://images.gitee.com/uploads/images/2020/0319/222917_72088feb_4864777.png "屏幕截图.png")
**不仅仅设计简洁，而且文字编写也是非常平易近人，不会让用户拥有距离感与陌生感😄**

![story-where](https://images.gitee.com/uploads/images/2020/0319/222929_272e8b22_4864777.png "屏幕截图.png")


  [1]: https://www.starbucks.com.cn/
