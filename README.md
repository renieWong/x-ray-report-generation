# x-ray-report-generation (paper & code)
_________________________________________________________________________________
# Contrastive Learning
* 1.[**MIDL(CCF-A)2022(under review)**] Representative Image Feature Extraction via Contrastive Learning Pretraining for Chest X-ray Report Generation[[pdf]](https://arxiv.org/pdf/2209.01604.pdf)
 
**原因** ：一般预训练1.需要使用不同领域的、有噪声的数据集2.不能学习特定于医学领域的一般视觉表示

**优点**：1.不需要额外的数据集和元信息(模型中的关键字?)2引导网络专注于编码肺区域内的视觉特征

**做法**：对比学习预训练视觉编码器，肺分割作数据增强, 使用的增强技术是随机调整大小裁剪和随机水平翻转。 MeSH标签的F1分数来评估肺分割是否能更准确

**缺点**：编码器不能利用整个图像中的特征，所生成的描述的整体性能会略有下降

**启发**：其他器官分割联合使用

![image](https://user-images.githubusercontent.com/102885188/227221294-d5912c7d-0d64-40fc-97d1-4a041b20204b.png)


* 2.[**arxiv 2022**] Contrastive Attention for Automatic Chest X-ray Report Generation[[pdf]](https://arxiv.org/pdf/2106.06965.pdf)

![image](https://user-images.githubusercontent.com/102885188/227205907-177c207d-88dc-43b2-afef-712525a932f2.png)

![image](https://user-images.githubusercontent.com/102885188/227206075-9357436c-e5c4-4e2b-b8b2-ff94460353b4.png)


* 3.[**ICCV2019**] Align, Attend and Locate: Chest X-ray Diagnosis via Contrast Induced Attention Network with Limited Supervision [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_Align_Attend_and_Locate_Chest_X-Ray_Diagnosis_via_Contrast_Induced_ICCV_2019_paper.pdf)
