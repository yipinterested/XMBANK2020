# 厦门国际银行金融数创杯2020小结
## 大赛简介
本次比赛由厦门国际银行联合厦门大学数据挖掘研究中心和DataCastle联手创办，比赛地址：https://www.dcjingsai.com/v2/cmptDetail.html?id=439
### 背景
随着科技发展，银行陆续打造了线上线下、丰富多样的客户触点，来满足客户日常业务办理、渠道交易等客户需求。面对着大量的客户，银行需要更全面、准确地洞察客户需求。在实际业务开展过程中，需要发掘客户流失情况，对客户的资金变动情况预判；提前/及时针对客户进行营销，减少银行资金流失。本次竞赛提供实际业务场景中的客户行为和资产信息为建模对象，一方面希望能借此展现各参赛选手的数据挖掘实战能力，另一方面需要选手在复赛中结合建模的结果提出相应的营销解决方案，充分体现数据分析的价值。
### 数据
本次比赛由的训练集为第三第四季度的用户数据，测试集为次年第一季度的用户数据。每个数据集包含了如下数据表：
  * aum数据：即用户的资产数据（定期活期理财基金等）
  * 存款数据（存款产品和数量等）
  * 重大事件数据（开户贷款逾期等）
  * 用户行为数据（转出转入等）
此处不一一列举每个数据集的字段，有兴趣的可以在官网查看。

### 评分标准
本次任务为三分类任务，-1表示下降，0代表维稳，1代表上升，评估指标使用kappa值，这次比赛是我第一次接触到kappa值
kappa的计算是基于混淆矩阵的，具体计算方法如下：



