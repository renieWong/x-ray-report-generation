# x-ray-report-generation (paper & code)
_________________________________________________________________________________
# Contrastive Learning
* 1.[**Under Review for MIDL 2022**]Representative Image Feature Extraction via Contrastive Learning Pretraining for Chest X-ray Report Generation[[pdf]]
 
原因：一般预训练1.需要使用不同领域的数据集2.不能学习特定于医学领域的一般视觉表示

优点：1.不需要额外的数据集和元信息(模型中的关键字?)2引导网络专注于编码肺区域内的视觉特征

做法：对比学习预训练视觉编码器，肺分割作数据增强

<img width="439" alt="image" src="https://user-images.githubusercontent.com/102885188/227195040-be1b5ecb-1e80-48c6-87a0-9948698a2026.png">


*2.[**arxiv 2022**]Contrastive Attention for Automatic Chest X-ray Report Generation[[pdf]](https://arxiv.org/pdf/2106.06965.pdf)

![image](https://user-images.githubusercontent.com/102885188/227205907-177c207d-88dc-43b2-afef-712525a932f2.png)

![image](https://user-images.githubusercontent.com/102885188/227206075-9357436c-e5c4-4e2b-b8b2-ff94460353b4.png)


