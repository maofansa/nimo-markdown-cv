---
layout: cv
title: Wode "YU" Ziyue
phone:
  text: 15067127048
email:
  url: mailto:alex.yualex@outlook.com
  text: alex.yualex@outlook.com
homepage:
  url: https://github.com/maofansa
  text: github.com/maofansa
---

# 俞子跃

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## 教育经历

### **香港理工大学** `2022.8 - 2024.3`

```
香港
```

- 数据科学和分析理学硕士
- 相关课程：深度学习，高维数据分析，优化方法

### **西南大学** `2018.9 - 2022.6`

```
重庆
```

- 计算机科学与技术工学学士
- 相关课程：数据库原理及应用，数据结构，算法分析与设计


---

## 项目经历

### **股票价格预测** ([CODE](https://www.jianguoyun.com/p/DVw55fQQqaS2Bxi60fwEIAA)) `2023.3`

使用来自雅虎金融的OHLCV数据，计算生成30个技术因子。我对数据进行**小波变换**去噪，并**归一化**到[0.1, 0.9]。训练多层**LSTM**模型，预测股票价格。最终MAPE为0.025。

### **香港赛马预测** ([PDF](https://www.jianguoyun.com/p/DS5wKuoQqaS2BxiPz_wEIAA)) `2022.11`

_EDA_<br>





---

## 获奖

### 美国大学生数学建模竞赛 Meritorious Winner ([PDF](https://www.jianguoyun.com/p/DQnTzoYQqaS2Bxj4zfwEIAA)) `COMPA, 2021` 

_模型构建， R语言程序实现_<br>

选题是高等教育体系评估，数据从各国统计年鉴、统计局和教育部门网站收集。使用多元线性回归补全缺失值。对于高等教育评估模型，我们选择了TOPSIS法，通过计算评估对象与最优/最差解决方案之间的距离得到评分。我们使用了熵值法，确定每个指标的权重， 然后对数据进行正向化，归一化进行无量纲处理。为了解决TOPSIS法的评价局限在当前评估的国家内的问题，我们以某国的数据作为基准，实现了分数差距和最终评分差距之间的映射，使模型具有更广的适用性。最后使用各指标的权重和得分对某一国的高等教育体系提供了改进建议和基于新冠疫情下影响的定量分析。

### 全国大学生数学建模竞赛 重庆赛区二等奖 ([PDF](https://www.jianguoyun.com/p/DVhWIiAQqaS2BxjzzfwEIAA)) `中国工业与应用数学会, 2020` 

_模型构建，R语言程序实现_<br>

选题是银行对中小微企业的信贷决策问题。对于有过往信贷记录的企业，我们通过违约记录和信用评级，得到了基于信誉评级的违约概率的Logit模 型。对于无信贷记录的企业，我们挖掘了企业财务数据，建立起二次判别分析模型用以评价企业的信誉评级，实现了“财务数据-信誉评级-违约概率”三者之间的转换。最后根据已知的贷款利率和客户流失率的关系，给出了银行利润最大化的信贷策略。

<!-- ### Footer

Last updated: March 2023 -->
