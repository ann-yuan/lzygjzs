# 2023 CCL24-Eval      手语数字人翻译质量评测

## 主题 ： 小语种自然语言处理

### 评测组织者
* 姚登峰教授（tjtdengfeng@buu.edu.cn），北京联合大学/清华大学  
* 仰国维副研究员，河南财经政法大学/中国聋人协会手语研究与推广委员会  
* 金澎教授，乐山师范学院特殊教育语言智能四川省哲学社会科学重点实验室
* 陈毅东副教授，厦门大学
* 徐聪主任，中国聋人协会手语研究与推广委员会
* 王海旭研究员，青海广播电视台/中国盲文手语研究应用中心
* 陈斌博士，株洲手之声信息科技有限公司
* 吴力权副秘书长，深圳市信息无障碍研究会
* 沈刚副主任，中国聋人协会手语研究与推广委员会
* 陈华铭副主任，中国聋人协会手语研究与推广委员会
* 刘春达，北京手语研究会
* 丁艳丽，北京联合大学国家语言文字推广基地
* 胡可，北京联合大学
* 陈澜，深圳市联谛信息无障碍有限责任公司

### 联系人及联系方式
* 赵源（1398396428@qq.com），北京联合大学硕士生
* 张睿诠，厦门大学硕士生
* 刘振宇，北京联合大学硕士生    

  

## 1.任务内容  
&emsp;&emsp;CCL（China National Conference on Computational Linguistics）为中国计算语言学大会，会议组织单位为中国中文信息学会。CCL是全国最权威、最具影响力、规模最大的NLP会议之一，它聚焦于中国境内各类语言的智能计算和信息处理，为研讨和传播计算语言学最新学术和技术成果提供了广泛的高层次交流平台。

&emsp;&emsp;随着科技的进步，手语数字人（Sign Language Avatars）已经成为促进聋人群体与社会沟通的重要工具。手语数字人通过模拟手语动作，为聋人提供实时的翻译服务，有助于打破语言障碍，提升聋人群体的社会参与度。为了确保手语数字人能够提供准确、自然且易于理解的手语翻译，对其翻译质量进行评测至关重要。本次评测旨在评测手语数字人将汉语翻译成中国手语方面的自然性和准确性，确保手语数字人能够符合手语语法规则，并且能够被聋人群体所理解和接受。

&emsp;&emsp;由于手语为小语种，语料库规模有限，因此本次评测将不设自动评测环节，全部采取人工评测的方式进行。由中国聋人协会手语研究与推广委员会认证的精通中国手语的聋人和专业手语翻译人员组成的评测者对手语数字人的翻译结果进行人工评测。

&emsp;&emsp;鉴于各参赛队伍均已拥有自主产权的手语语料库（欢迎各参赛队伍提供语料，本评测团队和中国聋人协会手语研究与推广委员会审核后将一起公布），此次评测提供的语料库仅作为参考，以确保评测的全面性和公正性，此次评测提供的语料库规模至少为500个左右手语句子，涵盖100~200个手势，场景主要为服务行业，后期将根据合作单位标注进度逐步增加，2024年3月15日正式公布其规模和内容。

## 2.评测数据  
#### 数据提供：
手语语料库以及对应的真人手语演示集合：  
&emsp;&emsp;在本次评测语料库中，我们会选择特定场景的语料，并提供相应的书面语文本及其对应的手语转写文本作为参考示例。这些参考示例包括词性标注和手势级别的标注。此外，评测还将提供参考示例的手语视频演示，特别注意其中的表情变化。

&emsp;&emsp;（注：标记为❶❷的是词目相同但词义不同的常用词；标记为①②的是词目和词义相同，但手语动作有差异的常用词。其他手语内容的参考资料包括《国家通用手语常用词表》和《国家通用手语词典》APP等相关资料。）

* &emsp;例1：  
&emsp;书面语：女儿可能生病了，快带她去医院。  
&emsp;手语转写文本：  
&emsp;&emsp;词级标注：  
&emsp;&emsp;&emsp;女儿②/病/可能②，带❶/医院/速度  
&emsp;&emsp;手势级标注：  
&emsp;&emsp;&emsp;女-矮/病/可能②【疑问】，带❶/医生-家/速度

![Image text](https://github.com/ann-yuan/lzygjzs/blob/main/1.png)

&emsp;&emsp;上面图例是心理活动波长，类似于“渐变”的表情变化过程。

&emsp;&emsp;解读：y上半轴表示正面情绪作用，y下半轴表示负面情绪作用；x右半轴表示正常表情，k斜率表示手势动作快慢。


![Image text](https://github.com/ann-yuan/lzygjzs/blob/main/table1.png)

&emsp;手语演示：  
&emsp;&emsp;![image](https://github.com/ann-yuan/lzygjzs/blob/main/video1.gif)

* &emsp;例2：  
&emsp;书面语：为了赢得比赛，儿子一直在专心训练。  
&emsp;手语转写文本：  
&emsp;&emsp;词级标注：  
&emsp;&emsp;&emsp;为/比赛/赢②，儿子②/专心/训练/一直  
&emsp;&emsp;手势级标注：  
&emsp;&emsp;&emsp;为/比较/胜利②，男-矮/认真【眼睛同时向下看】-心/练习/一直

![Image text](https://github.com/ann-yuan/lzygjzs/blob/main/2.png)

&emsp;&emsp;上面图例是心理活动波长，类似于“渐变”的表情变化过程。

&emsp;&emsp;解读：y上半轴表示正面情绪作用，y下半轴表示负面情绪作用；x右半轴表示正常表情，k斜率表示手势动作快慢。


![Image text](https://github.com/ann-yuan/lzygjzs/blob/main/table2.png)

&emsp;手语演示：  
&emsp;&emsp;![image](https://github.com/ann-yuan/lzygjzs/blob/main/video2.gif)


## 3.评价标准   
&emsp;&emsp;评测将以手语语法的准确性、表达的自然性和可读性以及是否满足聋人理解为主要标准，综合考虑手势清晰度、流畅性、与汉语原文的语义一致性等。具体包括：

&emsp;&emsp; 1、手语语法准确性：

&emsp;&emsp; 词序和结构：检查翻译是否遵循中国手语的词序规则，例如，汉语的主谓宾结构在手语中可能需要调整为更符合手语习惯的顺序。

&emsp;&emsp; 手势形态：评测手势是否正确，是否使用了恰当的手指位置、手掌方向和手部运动。

&emsp;&emsp; 语法标记：手语中有许多语法标记，如时态、否定、疑问等，需要确保这些标记在翻译中得到正确表达。


&emsp;&emsp; 2、自然性：

&emsp;&emsp; 流畅性：翻译过程中的手势是否连贯，是否模仿了自然手语的流畅性，避免生硬的断续。

&emsp;&emsp; 表达习惯：评测翻译是否符合聋人群体的日常表达习惯，包括常用的手语短语和惯用表达。

&emsp;&emsp; 非言语元素：考虑面部表情、身体姿态和空间布局等非言语元素是否自然地融入翻译中。


&emsp;&emsp; 3、可读性：

&emsp;&emsp; 清晰度：手势是否清晰可见，是否容易被理解，避免模糊不清的动作。

&emsp;&emsp; 一致性：确保同一概念或词汇在不同句子中的手势表达保持一致，便于理解和记忆。

&emsp;&emsp; 适应性：评测翻译是否考虑到不同语境下可能需要的调整，以提高可读性。


&emsp;&emsp; 4、文化敏感性：

&emsp;&emsp; 文化差异：翻译是否考虑到文化差异，避免直译可能带来的文化误解或不恰当的表达。

&emsp;&emsp; 社会语境：评测翻译是否考虑了社会语境，如礼貌用语、行业术语等，以确保在特定社会环境中的适宜性。

&emsp;&emsp; 情感色彩：检查翻译是否能够准确传达原文的情感色彩，如讽刺、幽默等。

&emsp;&emsp; 在进行评测时，评测者需要具备深厚的中国手语知识和文化背景，以便准确地判断翻译是否符合上述标准。此外，评测过程中的反馈对于手语数字人技术的改进和优化至关重要。


### 3.1 &emsp;手语语法准确性 
#### 3.1.1 &emsp;计算方法  
&emsp;&emsp;本次评测标准完全依赖人工打分，用于评估手语数字人在手语语法准确性方面的表现。评测的内容包括手语数字人是否遵循中国手语的词序规则，手势的准确性，以及语法标记在翻译中是否得到正确表达。本项的总得分是去掉一个最高分和一个最低分，剩下所有评分的算术平均值，具体的计算公式如下：

![Image text](https://github.com/ann-yuan/lzygjzs/blob/main/gs1.png)

&emsp;&emsp;式中：  
&emsp;&emsp; \$n\$ ——&emsp;评价人员数量；  
&emsp;&emsp; \$x_i\$ ——&emsp;第位评价人员对结果数据的打分。  

&emsp;&emsp;手语语法准确性得分表如下表所示：  
| 分数 | 评分标准 |
| --- | --- |
| 0 | 完全不遵循手语语序的习惯，完全不符合手语五要素的标准，无体现出时态、否定、疑问等的语法标记 |
| 60-79 | 部分语序遵循手语语序的习惯，部分语序符合手语五要素的标准，部分语序能体现出时态、否定、疑问等的语法标记 |
| 80-99 | 大多数语序遵循手语语序的习惯，大多数语序符合手语五要素的标准，大多数语序能体现出时态、否定、疑问等的语法标记 |
| 100 | 完全遵循手语语序的习惯，完全符合手语五要素的标准，完全能体现出时态、否定、疑问等的语法标记 |  

#### 3.1.2&emsp;测试方法  
&emsp;&emsp;评测人员为精通中国手语的聋人以及专业的手语翻译人员，将评测人员分为中老年组(50岁以上)和青壮年组(50 岁以下)，每组又各分为男性组和女性组，共4组，每组3至5名成员，对测试结果进行观看，并按得分标准进行整体评测。  

#### 3.1.3&emsp;权重系数  
&emsp;&emsp;手语语法准确性得分=分数x0.25  

### 3.2 &emsp;自然性
#### 3.2.1 &emsp;计算方法  
&emsp;&emsp;本次评测标准完全依赖人工打分，以评估手语数字人在自然性方面的表现。这包括评估手势的连贯性、翻译是否符合聋人群体的日常表达习惯，以及面部表情、身体姿态和空间布局等非言语元素是否自然地融入翻译中。本项的总得分是去掉一个最高分和一个最低分，剩下所有评分的算术平均值，其计算方法与评估手语语法准确性的方法一致：

&emsp;&emsp;自然性得分表如下表所示：  
| 分数 | 评分标准 |
| --- | --- |
| 0 | 目标语言完全不连贯，完全不流畅，完全生硬，完全不符合聋人的日常表达习惯，全程没有出现表情、体态、空间位置、运动轨迹等 |
| 60-79 | 部分目标语言有连贯，有一定的流畅，有一定的生硬，部分符合聋人的日常表达习惯，部分体现出出现表情、体态、空间位置、运动轨迹等 |
| 80-99 | 大多数目标语言有连贯，大多数能流畅，大多数不生硬，大多数符合聋人的日常表达习惯，大多数能体现出出现表情、体态、空间位置、运动轨迹等 |
| 100 | 目标语言完全连贯，完全流畅，无生硬，完全符合聋人的日常表达习惯，全程能体现出出现表情、体态、空间位置、运动轨迹等 |  

#### 3.2.2&emsp;测试方法  
&emsp;&emsp;评测人员为精通中国手语的聋人以及专业的手语翻译人员，将评测人员分为中老年组(50岁以上)和青壮年组(50 岁以下)，每组又各分为男性组和女性组，共4组，每组3至5名成员，对测试结果进行观看，并按得分标准进行整体评测。  

#### 3.2.3&emsp;权重系数  
&emsp;&emsp;自然性得分=分数x0.25

### 3.3 &emsp;可读性
#### 3.3.1 &emsp;计算方法  
&emsp;&emsp;本次评测标准完全由人工进行打分，以评估手语数字人在清晰度、一致性和适应性方面的表现。本项的总得分是去掉一个最高分和一个最低分，剩下所有评分的算术平均值，其计算方法与评估手语语法准确性时所采用的方法一致：

&emsp;&emsp;可读性得分表如下表所示：  
| 分数 | 评分标准 |
| --- | --- |
| 0 | 目标语言中的手势完全不清晰，动作模糊，难以理解，对同一概念或词汇的手势表达在不同句子中完全不一致，导致理解和记忆困难，目标语言完全没有考虑不同语境下的适应性，无法提高可读性。 |
| 60-79 | 目标语言中的手势部分清晰，有些动作可能略显模糊，但大体上可被理解，对同一概念或词汇的手势表达在不同句子中大多数情况下保持一致，但偶尔存在一致性问题，目标语言部分考虑了不同语境下的适应性，但在某些情况下仍有改进空间。 |
| 80-99 | 目标语言中的手势大多数情况下非常清晰，易于理解，只有极少数动作略有不清晰，对同一概念或词汇的手势表达在不同句子中几乎始终保持一致，有助于理解和记忆，目标语言在大多数情况下考虑了不同语境下的适应性，有效地提高了可读性。 |
| 100 | 目标语言中的手势完全清晰，易于理解，没有任何模糊不清的动作，对同一概念或词汇的手势表达在所有句子中始终保持完全一致，极大地促进了理解和记忆，目标语言完全考虑了不同语境下的适应性，极大地提高了可读性。|  

#### 3.3.2&emsp;测试方法  
&emsp;&emsp;评测人员为精通中国手语的聋人以及专业的手语翻译人员，将评测人员分为中老年组(50岁以上)和青壮年组(50 岁以下)，每组又各分为男性组和女性组，共4组，每组3至5名成员，对测试结果进行观看，并按得分标准进行整体评测。  

#### 3.3.3&emsp;权重系数  
&emsp;&emsp;可读性得分=分数x0.25

### 3.4 &emsp;文化敏感性
#### 3.4.1 &emsp;计算方法  
&emsp;&emsp;本次评测标准完全由人工进行打分，旨在评估手语数字人在文化敏感性方面的表现。评测内容包括翻译时是否考虑了文化差异、社会语境的适应性，以及是否能够准确传达原文的情感色彩。本项的总得分是去掉一个最高分和一个最低分，剩下所有评分的算术平均值，其计算方法与评估手语语法准确性时所使用的方法一致：

&emsp;&emsp;文化敏感性得分表如下表所示：  
| 分数 | 评分标准 |
| --- | --- |
| 0 | 目标语言完全不考虑文化差异，南北方以及不同地方的手语文化完全不能被接受，没有用到礼貌用语、行业术语等社会环境的专业手语，不能准确传达出情感色彩。如讽刺、幽默等。 |
| 60-79 | 目标语言部分考虑文化差异，南北方以及不同地方的手语文化部分能被接受，部分用到礼貌用语、行业术语等社会环境的专业手语，部分准确传达出情感色彩，如讽刺、幽默等。 |
| 80-99 | 目标语言大多数考虑文化差异，南北方以及不同地方的手语文化大多数能被接受，大多数用到礼貌用语、行业术语等社会环境的专业手语，大多数能准确传达出情感色彩。如讽刺、幽默等。 |
| 100 | 目标语言完全考虑文化差异，南北方以及不同地方的手语文化完全能被接受，全部用到礼貌用语、行业术语等社会环境的专业手语，完全准确传达出情感色彩，如讽刺、幽默等。|  

#### 3.4.2&emsp;测试方法  
&emsp;&emsp;评测人员为精通中国手语的聋人以及专业的手语翻译人员，将评测人员分为中老年组(50岁以上)和青壮年组(50 岁以下)，每组又各分为男性组和女性组，共4组，每组3至5名成员，对测试结果进行观看，并按得分标准进行整体评测。  

#### 3.4.3&emsp;权重系数  
&emsp;&emsp;文化敏感性得分=分数x0.25

### 3.5&emsp;综合评价方法  
&emsp;&emsp;手语数字人翻译质量的评定包括四个主要指标：手语语法准确性、自然性、可读性和文化敏感性。每个单项指标的满分为100分。综合得分通过计算单项指标得分和各自的权重系数的加权和来确定，其满分也为100分。评测主要反映了手语数字人在表达理解方面的手语语法准确性和文化敏感性，同时侧重于其自然性和可读性。每个单项指标的权重占整体评测结果的25%。单项指标权重系数如下。
| 指标类型 | 指标名称 | 权重系数 | 占比 |
| --- | --- | --- | --- |
| 翻译质量评测 | 手语语法准确性 | 0.25 | 25% |
| 翻译质量评测 | 自然性 | 0.25 | 25% |
| 翻译质量评测 | 可读性 | 0.25 | 25% |
| 翻译质量评测 | 文化敏感性 | 0.25 | 25% |

## 4.评测赛程 
* 开放报名：2024年1月1日  
* 公布手语语料库等以及评测方法：2024年3月15日  
* 报名截止： 2024年3月15日
* 参赛队提交系统接口：2024年4月15日
* 组织者返回评测结果：2024年5月25日 
* 参赛队提交评测任务技术报告用于审稿：2024年5月31日
* 评测论文录用通知：2024年6月25日
* CCL 2024评测研讨会：2024年7月25-28日

### 任务大致流程：
报名完成的参赛队伍请邮箱联系本次评测联系人（1398396428@qq.com），以获取本次评测提供的手语语料库（需提前签署语料库保密协议及版权声明书），参赛队伍可以使用自带的手语语料库，也可以使用本次评测提供的手语语料库，最终提交评测任务技术报告和系统接口及其使用说明书。本次评测将通过系统接口来测评参赛队伍的手语数字人，并录制最终生成的手语视频，评测联系人提交给评测者来完成本次评测。
(注：本次评测所提供的手语语料库只用于训练，不能同时作为测试)

## 5.奖项设置  
本届评测将设置一、二、三等奖，由中国中文信息学会为获奖队伍颁发荣誉证书。

## 6.撰写技术报告
报告可由中文或英文撰写。  
报告统一使用CCL 2024的论文模板。  
报告正文不得超过4页，参考文献页数不限。  
报告应至少包含以下四个部分：模型介绍、评测结果、结果分析与讨论和参考文献。  

## 7.报名提交方式及申请本次评测语料使用权
点击报名链接填写报名表 https://f.kdocs.cn/g/aYC93cfz/    进行报名，我们会发送邮件确认您已经参赛，如需要本次评测提供的语料库，请参赛队伍需自行向评测联系人申请本次评测语料使用权，并签署保密协议。
 1)	每支参赛队伍需指派一名联系负责人。
 2)	参赛队伍联系负责人需填写本次评测语料许可协议，扫描后通过E-mail发送给评测联系人（1398396428@qq.com）。
 3)	申请通过后，评测联系人将返回手语语料库给参赛队伍联系负责人，以供参赛队伍使用。该语料数据只可用于本次评测任务，不可有其他任何用途，请尊重手语者的隐私。
 4)	本次评测语料库的知识产权按其版权分别归属北京联合大学、乐山师范学院、厦门大学、青海广播电视台、株洲手之声信息科技有限公司所有。
