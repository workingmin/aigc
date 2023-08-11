# AIGC

<style>
  h1 {
    counter-reset: h2
  }
  h2 {
    counter-reset: h3
  }
  h3 {
    counter-reset: h4
  }
  h2:before {
    counter-increment: h2;
    content: counter(h2) ". "
  }
  h3:before {
    counter-increment: h3;
    content: counter(h2) "." counter(h3) ". "
  }
  h4:before {
    counter-increment: h4;
    content: counter(h2) "." counter(h3) "." counter(h4) ". "
  }
</style>

> Artificial Intelligence Generated Content
> 人工智能生成内容

[TOC]

<br>

## 发展历史沿革

+ ![png](resources/AIGC发展历程.png "AIGC 发展历程")

<br>

## 三大前沿能力

+ ![png](resources/AICG的三大前沿能力.png "AICG 三大前沿能力")

+ $$\begin{gather*}
    \text{AIGC技术演化出三大前沿能力}
    \begin{dcases}
    \text{智能数字内容孪生能力}
    \begin{dcases}
    \text{智能增强技术}
    \begin{dcases}
    \text{生成复原有缺陷的音频数据} \\
    \text{修复并增强受损的视觉内容} \\
    \cdots
    \end{dcases} \\
    \text{智能转译技术}
    \begin{dcases}
    \text{给定语音信号进行字幕合成} \\
    \text{依据文字进行语音生成} \\
    \cdots
    \end{dcases}
    \end{dcases} \\
    \text{智能数字内容编辑能力}
    \begin{dcases}
    \text{语义理解}
    \begin{dcases}
    \text{分离音频数据的人声信号和背景音} \\
    \text{图片、视频剪辑} \\
    \text{文本摘要生成} \\
    \cdots
    \end{dcases} \\
    \text{属性控制}
    \begin{dcases}
    \text{智能图像编辑} \\
    \text{文本情感改写} \\
    \text{智能调音} \\
    \cdots
    \end{dcases}
    \end{dcases} \\
    \text{智能数字内容创作能力}
    \begin{dcases}
    \text{作画} \\
    \text{旋律创作} \\
    \text{文本写作} \\
    \text{诗词创作} \\
    \cdots
    \end{dcases}
    \end{dcases}
    \end{gather*}$$

<br>

## 技术和产业生态

### 技术积累融合

+ $$\begin{gather*}
    \begin{drcases}
    \text{GAN} \\
    \text{Diffusion} \\
    \text{Transformer} \\
    \text{CLIP} \\
    \cdots
    \end{drcases}
    \text{预训练模型} \to \text{AIGC}
    \end{gather*}$$
  + | 模型 | 提出时间 | 模型描述 |
    | --- | --- | --- |
    | 生成对抗网络（Generative Adversarial Network, GAN） | 2014年 | 基于对抗的生成—鉴别（Generator-Discriminator）模型对。 |
    | 扩散模型（Diffusion Model） | 2015年 | 扩散模型有两个过程，分别为扩散过程和逆扩散过程。在前向扩散阶段对图像逐步施加噪声，直至图像被破坏变成完成的高斯噪声，然后在逆向阶段学习从高斯噪声还原为原始图像的过程。<br>经过训练，该模型可以应用这些去噪方法，从随机输入中合成新的“干净”数据。 |
    | Transformer | 2017年 | 一种基于自注意力机制的神经网络模型，最初用来完成不同语言之间的文本翻译任务，主题包括Encoder和Decoder部分，分别负责对源语言文本进行编码和将编码信息转换为目标语言文本。 |
    | 跨模态深度学习模型（Contrastive Language-Image Pre-Training, CLIP） | 2021年 | 1、进行自然语言理解和计算机视觉分析；<br>2、使用已经标记好的“文字—图像”训练数据。一方面对文字进行模型训练。一方面对另一个模型的训练，不断调整两个模型的内部参数，使得模型分别输出的文字特征和图像特征值并确认匹配。 |

<br>

+ 国外主要的AIGC预训练模型
  + | | 预训练模型 | 应用 | 领域 |
    | --- | --- | --- | ---|
    | 谷歌 | BERT<br>LaMDA<br>PaLM<br>Imagen<br>Parti | 语言理解与生成<br>对话系统<br>语言理解与生成、推理、代码生成<br>语言理解与图像生成<br>语言理解与图像生成 | NLP<br>NLP<br>NLP<br>多模态<br>多模态 |
    | 微软 | Florence<br>Turing-NLG | 视觉识别<br>语言理解、生成 | CV<br>NLP |
    | Facebook | OPT-175B<br>M2M-100 | 语言模型<br>100种语言互译 | NLP<br>NLP |
    | Deep Mind | Gato<br>Gopher<br>AlphaCode | 多面手的智能体<br>语言理解与生成<br>代码生成 | 多模态<br>NLP<br>NLP |
    | Open AI | GPT3<br>CLIP&DALL-E<br>Codex<br>ChatGPT | 语言理解与生成、推理等<br>图像生成、跨模态检索<br>代码生成<br>语言理解与生成、推理等 | NLP<br>多模态<br>NLP<br>NLP |
    | 英伟达 | Megatron-Turing NLG | 语言理解与生成、推理 | NLP |
    | Stability AI | Stable Diffusion | 语言理解与图像生成 | 多模态 |

<br>

+ 国内各大厂ChatGPT技术布局及应用场景
  + ![webp](resources/国内各大厂ChatGPT技术布局及应用场景.webp "国内各大厂ChatGPT技术布局及应用场景") 

<br>

## 应用场景

+ ![png](resources/AIGC应用视图.png "AIGC 应用视图")

<br>

### 各行业领域

+ 传媒
  + $$\begin{align*}
      \text{采编环节} &
      \begin{dcases}
      \text{采访录音语音转写} \\
      \text{智能新闻写作} \\
      \text{智能视频剪辑}
      \begin{dcases}
      \text{视频字幕生成} \\
      \text{视频锦集} \\
      \text{视频拆条} \\
      \text{视频超分}
      \end{dcases}
      \end{dcases} \\
      \text{传播环节} &
      \begin{drcases}
      \begin{dcases}
      \text{实时语音} \\
      \text{人物动画}
      \end{dcases}
      \end{drcases}
      \text{智能合成主播}
      \end{align*}$$

<br>

+ 电商
  + $$\begin{align*}
      & \text{商品三维模型} \\
      & \text{虚拟主播} \\
      & \text{虚拟货场}
      \end{align*}$$

<br>

+ 影视
  + $$\begin{align*}
      & \text{剧本创作} \\
      & \text{合成人脸} \\
      & \text{合成声音} \\
      & \text{合成虚拟物理场景} \\
      & \text{修复还原影视图像} \\
      & \text{影视预告片生成} \\
      & \text{影视内容从二维向三维自动转制}
      \end{align*}$$

<br>

+ 娱乐
  + $$\begin{align*}
      & \text{趣味性图像或音视频生成} \\
      & \text{打造虚拟偶像} \\
      & \text{开发个人用户数字化身}
      \end{align*}$$

<br>

+ 教育
  + $$\begin{align*}
      & \text{制作历史人物} \\
      & \text{合成逼真的虚拟教师}
      \end{align*}$$

<br>

+ 金融
  + $$\begin{align*}
      & \text{自动化生产金融咨询、产品介绍} \\
      & \text{视听双通道的虚拟数字人客服}
      \end{align*}$$

<br>

+ 医疗
  + $$\begin{align*}
      & \text{改善医学图像质量} \\
      & \text{录入电子病历} \\
      & \text{为失声者合成语言音频} \\
      & \text{为残疾者合成肢体投影} \\
      & \text{为心理疾病患者合成无攻击感的医护陪伴}
      \end{align*}$$

<br>

+ 工业
  + $$\begin{align*}
      & \text{自动化工程设计中的任务} \\
      & \text{生成衍生设计} \\
      & \text{动态模拟} \\
      & \text{创建工厂、工业设备和生产线等的数字孪生系统}
      \end{align*}$$

<br>

### 应用工具

+ [AIGC导航](https://www.aigc.cn/)
+ AI办公工具
  + | 应用 | 功能 | 网址链接 |
    | --- | --- | --- |
    | 爱设计PPT | 一款AI驱动的PPT在线生成器。 | <https://www.isheji.com/> |
    | GPTBots.AI | 极光（Aurora Mobile，纳斯达克股票代码：JG）旗下的AI产品，让企业及个人开发者能快速创建自己的AI Bots | <https://www.gptbots.ai/> |
    | WPS AI-体验官申请 | 智能办公助手 | <https://ai.wps.cn/> |
    | 协码啦 AI | AI图片+文字+文档 一站式AI集成平台 | <https://ai.xiemala.com/> |
    | 通义听悟 | 全文概要、章节速览、发言总结等高阶AI功能，并获赠使用权益。 | <https://tingwu.aliyun.com/> |
    | 集智魔方AI BOX | 创建属于自己的AI应用平台 | <https://www.chatbox.cool/#/home> |
    | 壹伴助手 | 长文写作、短文生成、排版、修图、找素材和回消息 | <https://yiban.io/> |
    | ChatPPT | 参照你的语义对话生成完整的PPT文档，指令支持个性化生成与编辑诉求 | <https://chat-ppt.com/> |
    | SQLkiller | AI数据分析助手-SQL生成、修正，Excel公式生成 | <https://www.sqlkiller.com/> |
    | 微软爱写作 | 微软开发的一款在线写作平台 | <https://aimwriting.mtutor.engkoo.com/> |
    | ChartAI | 解决数据可视化中存在的例如数据过多、数据难以理解、图表编制时间长等问题 | <https://chartai.io/zh> |
    | ChatExcel | ChatExcel帮你处理Excel表格，上传你的文件，输入你的需求，AI自动就帮主你处理。 | <https://chatexcel.com/> |
    | excelformulabot | 在人工智能的帮助下，几秒钟内免费将文本指令转换为Excel公式。在几秒钟内精通Excel。 | <https://formulabot.com/> |
    | Chatbase | 只要上传一个pdf文件，就可以得到一个基于GPT的聊天机器人的链接，它可以回答上面的任何问题。 | <https://www.chatbase.co/> |
    | TreeMind树图 | AI生成导图，提升学习及工作效率。 | <https://shutu.cn/> |
    | 多墨智能 | AI一键生成工作文档，流程图，思维导图 | <https://duomosmart.com/> |

<br>

## 参考文献

> [人工智能生成内容（AIGC）白皮书（2022年） 中国信息通信研究院,京东探索研究院 2022年9月](http://www.caict.ac.cn/sytj/202209/t20220913_408835.htm)
> [腾讯研究院AIGC发展趋势报告2023](https://research.tencent.com/report?id=AJJ)
> [国内各大厂ChatGPT技术布局及应用场景](https://zhuanlan.zhihu.com/p/621901693)