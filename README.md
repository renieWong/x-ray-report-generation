# x-ray-report-generation (paper & code)
_________________________________________________________________________________
# Contrastive Learning
* 1.[**Under Review for MIDL 2022**]Representative Image Feature Extraction via Contrastive Learning Pretraining for Chest X-ray Report Generation
 
原因：一般预训练1.需要使用不同领域的数据集2.不能学习特定于医学领域的一般视觉表示
优点：1.不需要额外的数据集和元信息(模型中的关键字?)2引导网络专注于编码肺区域内的视觉特征
做法：对比学习预训练视觉编码器，肺分割作数据增强
<img width="439" alt="image" src="https://user-images.githubusercontent.com/102885188/227195040-be1b5ecb-1e80-48c6-87a0-9948698a2026.png">


*2.[**Pattern Recognition Letters**] Two-stream collaborative network for multi-label chest X-ray Image classification with lung segmentation[pdf](https://reader.elsevier.com/reader/sd/pii/S0167865520301380?token=0A9D19797703EA83DF61513C5FCD582B4BDC3248DAE20E35742F4FD349367D097F85AE73BC0D5E2D27B2404902D54410&originRegion=us-east-1&originCreation=20230323122650)

