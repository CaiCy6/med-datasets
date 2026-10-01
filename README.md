# 🩺 Medical Datasets · 医学数据集大全（整合版）

> 把**医学影像 / 多模态 / 文本数据集**、**疾病大类公开数据集索引**与**医学分割基准专题**整合到一起，统一分类、补齐链接、**随机排序**，方便一站式检索选型。

> ⚠️ 本仓库**只做索引与导航**，不托管任何数据集原始文件。数据版权归各数据集官方所有，使用前请到官方页面确认许可证（License）。

## 📊 一览

- **影像/多模态/文本数据集：** 431 条（12 个分类）
- **疾病大类数据集：** 23 个疾病大类，**1584** 条记录（每类一文件，见 `disease/`）
- **医学分割基准专题笔记：** 48 篇
- **更新：** 2026-10-01

## 🗂 影像数据集分类导航

| 分类 | 条目数 |
| :--- | ---: |
| 全身 | 12 |
| 头颈部 | 61 |
| 胸部 | 55 |
| 腹部 | 57 |
| 心脏 | 14 |
| 骨头 | 17 |
| 内窥镜 | 35 |
| 眼科 | 57 |
| 皮肤科 | 15 |
| 显微成像 | 39 |
| 多模态数据集 | 44 |
| 文本数据集 | 25 |
| **合计** | **431** |

## 📦 影像数据集总表（已打乱顺序）

> 共 **431** 条，随机排序（不按来源顺序，避免与上游清单雷同）；每条附分类标签与官方链接。

| # | 数据集 | 分类 | 模态 | 说明 | 链接 |
| ---: | :--- | :--- | :--- | :--- | :--- |
| 1 | **CRAG** | 腹部 | 2D | 2D，病理，213例，大肠腺癌分割 | [官网](https://github.com/XiaoyuZHK/CRAG-Dataset_Aug_ToCOCO) |
| 2 | **PleThora** | 胸部 | 3D CT | 3D CT, 402例, 2 类胸膜积液和胸腔分割 | [官网](https://www.cancerimagingarchive.net/analysis-result/plethora/) |
| 3 | **COVID-19 CHEST X-RAY DATABASE** | 胸部 | 2D X-Ray | 2D X-Ray, 3886例, 3类肺炎分类 | [官网](https://www.heywhale.com/mw/dataset/6027caee891f960015c863d7/content) |
| 4 | **MIAS** | 胸部 | 2D X-ray | 2D X-ray，322例，7类乳房病变分类 | [官网](https://www.kaggle.com/datasets/kmader/mias-mammography) |
| 5 | **MICCAI2024 TriALS 2024 Task1** | 胸部 | 3D | 3D，CT，60例，肝脏病变分割 | [官网](https://www.synapse.org/Synapse:syn53285416/wiki/) |
| 6 | **Endoscapes** | 内窥镜 | 2D | 2D，内窥镜，58813例，外科手术场景分割、目标检测和CVS评估研究 | — |
| 7 | **QIN-LungCT-Seg** | 胸部 | 3D | 3D，CT，31例，肺部CT 分割 | [官网](https://www.cancerimagingarchive.net/analysis-result/qin-lungct-seg/) |
| 8 | **REFUGE** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 1200例, 2类青光眼分类, 2类视盘/杯分割 | [官网](https://refuge.grand-challenge.org/) |
| 9 | **ULS** | 全身 | 3D CT | 3D CT, 38842例, 1类全身肿瘤分割 | [官网](https://uls23.grand-challenge.org/) |
| 10 | **LC25000** | 显微成像 | 2D 病理图像 | 2D 病理图像, 25000例, 5类病理图像分类 | [官网](https://github.com/tampapath/lung_colon_image_set) |
| 11 | **CHAOS** | 腹部 | 3D CT&MRI | 3D CT&MRI, 40例, 4类腹部器官分割 | [官网](https://chaos.grand-challenge.org/Combined_Healthy_Abdominal_Organ_Segmentation/) |
| 12 | **Endoscopic Bladder Tissue Classification Dataset** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 1754例, 4类膀胱镜组织分类 | [官网](https://commons.datacite.org/doi.org/10.5281/zenodo.7741475) |
| 13 | **ISLES22** | 头颈部 | 3D MRI | 3D MRI, 400例, 1类中风病变分割 | [官网](https://isles22.grand-challenge.org/) |
| 14 | **SLIVER07** | 腹部 | 3D | 3D，CT，30例，1类肝脏分割 | [官网](https://sliver07.grand-challenge.org/) |
| 15 | **Diabetic Retinopathy Arranged** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 35127例, 5类糖尿病视网膜病变分类 | [官网](https://tianchi.aliyun.com/dataset/93926) |
| 16 | **ANHIR** | 显微成像 | 2D 病理图像 | 2D 病理图像, 481例, 病理图像肺叶、乳腺组织配准 | [官网](https://anhir.grand-challenge.org/Download/) |
| 17 | **MICCAI 2024 CARE-LiQA** | 腹部 | 3D | 3D，MRI，250例，2类肝脏分割和纤维化分期 | [官网](http://zmic.org.cn/care_2024/track3/) |
| 18 | **Chaoyang 病理图像结肠癌诊断** | 显微成像 | 2D | 2D，病理图像，6160例，4类结肠病变 | [官网](https://bupt-ai-cz.github.io/HSA-NRL/) |
| 19 | **Herlev-宫颈涂片** | 显微成像 | 2D | 2D，组织病理学，917例，7类宫颈涂片分类 | [官网](https://mde-lab.aegean.gr/index.php/downloads/) |
| 20 | **ISIC 2017** | 皮肤科 | 2D 皮肤镜图像 | 2D 皮肤镜图像, 2750例, 1类黑色素瘤分割 | [官网](https://challenge.isic-archive.com/data/#2017) |
| 21 | **KiTS19** | 腹部 | 3D CT | 3D CT, 300例, 2类肾脏和肾脏肿瘤分割 | [官网](https://kits19.grand-challenge.org/) |
| 22 | **MICCAI2024 HNTS-MRG Task2** | 头颈部 | 3D | 3D，MRI T2w，150例，原发肿瘤和转移淋巴结分割 | [官网](https://hntsmrg24.grand-challenge.org/overview/) |
| 23 | **IvyGAP-Radiomics** | 头颈部 | 3D MRI | 3D MRI，31例，3类胶质母细胞瘤分割 | [官网](https://www.cancerimagingarchive.net/analysis-result/ivygap-radiomics/) |
| 24 | **ATM22** | 胸部 | 3D CT | 3D CT, 500例, 1类肺气管分割 | [官网](https://atm22.grand-challenge.org/) |
| 25 | **BiDR** | 眼科 | 2D | 2D，眼底照片，2838例，2类糖尿病视网膜病变分类 | [官网](https://www.kaggle.com/datasets/pkdarabi/diagnosis-of-diabetic-retinopathy?resource=download-directory) |
| 26 | **DeSmokeData** | 腹部 | 2D | 2D，Surgical，1类，961例，腹腔镜前列腺手术去雾 | — |
| 27 | **StructSeg2019 Task1 头颈部危及器官分割** | 头颈部 | 3D CT | 3D CT, 50例, 22类头颈部器官分割 | [官网](https://structseg2019.grand-challenge.org/) |
| 28 | **ImageCAS 大规模 CT 血管造影图像冠状动脉分割** | 心脏 | 3D CTA | 3D CTA, 1000例, 1类冠状动脉分割 | [官网](https://github.com/XiaoweiXu/ImageCAS-A-Large-Scale-Dataset-and-Benchmark-for-Coronary-Artery-Segmentation-based-on-CT) |
| 29 | **GlaS** | 显微成像 | 2D 病理图像 | 2D 病理图像, 165例, 1类结直肠腺体组织分割 | [官网](https://warwick.ac.uk/services/gov/calendar/section2/regulations/computing/) |
| 30 | **Br35H** | 头颈部 | 2D | 2D，MRI，3000例，2类脑肿瘤分类 | [官网](https://www.heywhale.com/mw/dataset/61d3e5682d30dc001701f728) |
| 31 | **GEMeX** | 多模态数据集 | VQA | VQA，3960例，胸部X光诊断的大规模、可溯源和可解释的医学VQA基准 | — |
| 32 | **Chest CT-Scan images** | 胸部 | 2D CT | 2D CT, 1000例, 4类肺癌分类 | [官网](https://tianchi.aliyun.com/dataset/93929) |
| 33 | **PDDCA** | 头颈部 | 3D CT | 3D CT, 48例, 9类头颈部器官分割 | [官网](https://www.imagenglab.com/newsite/pddca/) |
| 34 | **DigestPath2019** | 显微成像 | 2D 病理图像 | 2D 病理图像, 250例, 1类消化系统病理分割检测 | [官网](https://digestpath2019.grand-challenge.org/Home/) |
| 35 | **CHASE** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 28例, 1类眼底血管分割 | [官网](https://blogs.kingston.ac.uk/retinal/chasedb1/) |
| 36 | **MICCAI 2024 DIAMOND** | 头颈部 | 2D | 2D，眼底照片，204例，5类中心型糖尿病性黄斑水肿预测 | [官网](https://www.codabench.org/competitions/2333/) |
| 37 | **MSD Lung Tumours** | 胸部 | 3D CT | 3D CT, 96例, 1类肺肿瘤分割 | [官网](http://medicaldecathlon.com/) |
| 38 | **MICCAI 2024 PENGWIN Task1** | 骨头 | 3D | 3D，CT，100例，3 类骶骨髋骨分割 | [官网](https://pengwin.grand-challenge.org/pengwin/) |
| 39 | **NAFLD** | 全身 | 2D | 2D，病理，119828例，16类图像分类的病理学数据集 | [官网](https://osf.io/gqutd/) |
| 40 | **TN3K** | 头颈部 | 2D 超声 | 2D 超声, 3494例, 1类甲状腺结节分割 | [官网](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation) |
| 41 | **ClinicalAgent Bench** | 多模态数据集 | VQA | VQA，14,897例，旨在全面评估医疗智能体的能力 | [官网](https://github.com/smilell/AG-CNN?tab=readme-ov-file) |
| 42 | **MedBench 中文医疗大模型评测开放平台** | 文本数据集 | QA | QA, 30万道题目 | [官网](https://medbench.opencompass.org.cn/) |
| 43 | **Retina** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 601例, 4类白内障青光眼视网膜病分类 | [官网](https://github.com/yiweichen04/retina_dataset) |
| 44 | **Leukemia** | 显微成像 | 2D 显微图像 | 2D 显微图像, 1867 例, 2类白血病细胞分类 | [官网](https://www.kaggle.com/datasets/andrewmvd/leukemia-classification) |
| 45 | **Osteosarcoma Tumor Assessment** | 骨头 | 2D | 2D，病理，1144例，3类手术切除后肿瘤分类 | [官网](https://www.cancerimagingarchive.net/collection/osteosarcoma-tumor-assessment/) |
| 46 | **WORD** | 腹部 | 3D CT | 3D CT, 150例, 16类腹部器官分割 | [官网](https://github.com/HiLab-git/WORD) |
| 47 | **MSD Brain** | 头颈部 | 3D | 3D，mpMR，3484 训练，3类胶质瘤分割 | [官网](http://medicaldecathlon.com/) |
| 48 | **SCARED** | 内窥镜 | 2D | 2D，内窥镜，为内窥镜深度估计研究提供了高质量、标准化的数据基准 | [官网](https://endovissub2019-scared.grand-challenge.org/Home/) |
| 49 | **OCTMNIST** | 头颈部 | 2D | 2D，OCT，4类109309例，用于视网膜疾病的分类 | — |
| 50 | **ML2HP** | 多模态数据集 | 2D | 2D，多模态：RGB+文本，714000例，多视图手势识别 | [官网](https://www.nature.com/articles/s41597-024-03968-9?_gl=1*ikljf0*_up*MQ..&gclid=Cj0KCQjwpvK4BhDUARIsADHt9sTKeJdkTiVgts02Lx7tkFajPSGA9upeXML9AePHRgmojqIZejtL75kaAktZEALw_wcB) |
| 51 | **MED-NODE** | 皮肤科 | 2D 皮肤镜图像 | 2D 皮肤镜图像, 170例, 2类黑色素瘤良恶性分类 | [官网](https://www.cs.rug.nl/~imaging/databases/melanoma_naevi/) |
| 52 | **RHUH-GBM** | 头颈部 | 3D MR | 3D MR，120例，3类胶质母细胞瘤分割 | [官网](https://www.cancerimagingarchive.net/collection/rhuh-gbm/) |
| 53 | **IVDM3Seg** | 骨头 | 3D | 3D，MRI，16例，1类椎间盘分割 | [官网](https://ivdm3seg.weebly.com/) |
| 54 | **MSD Hippocampus** | 头颈部 | 3D MRI | 3D MRI, 394例, 2类脑海马体分割 | [官网](http://medicaldecathlon.com/) |
| 55 | **UW-Madison GI Tract Image Segmentation** | 腹部 | 2D | 2D, MRI, 38496例, 3类胃肠道分割 | [官网](https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation/overview) |
| 56 | **LUNA16** | 胸部 | 3D CT | 3D CT, 888例, 1类肺结节检测 | [官网](https://luna16.grand-challenge.org/Home/) |
| 57 | **PANDA** | 腹部 | 2D | 2D，病理，331例，前列腺癌分类 | [官网](https://gleason2019.grand-challenge.org/Home/) |
| 58 | **CMRxMotion** | 心脏 | 3D MRI | 3D MRI, 360例, 3类左右心室和心肌分割 | [官网](https://www.synapse.org/#!Synapse:syn28503327/wiki/617823) |
| 59 | **MedVidQA 医学视频问答** | 多模态数据集 | VQA | VQA, 899 段视频 | — |
| 60 | **BM-BronchoLC** | 胸部 | 2D | 2D，支气管镜，2921例，解剖标志物和气道病变精确定位识别 | [官网](https://figshare.com/articles/dataset/BM-BronchoLC/24243670) |
| 61 | **OphNet2024** | 眼科 | 2D | 2D，眼科手术，1969例真实眼科手术视频并支持多种识别、定位和预测任务 | [官网](https://www.fc.up.pt/addi/ph2%20database.html) |
| 62 | **CAS2023** | 头颈部 | 3D MRI | 3D MRI, 100例, 1类脑动脉分割 | [官网](https://codalab.lisn.upsaclay.fr/competitions/9804) |
| 63 | **X光手部小关节分类** | 骨头 | 2D | 2D，X Ray，8210例，9类细致观察手部特定骨骼的X光片，来确定个体的骨龄分类 | — |
| 64 | **HCC-TACE-Seg** | 腹部 | 3D | 3D，CT，628例，4类肝、肝癌分割 | [官网](https://www.cancerimagingarchive.net/collection/hcc-tace-seg/) |
| 65 | **RenalCell** | 腹部 | 2D | 2D，pathology，6,39,458例组织类别数，6,25,095例淋巴细胞类别数，肾细胞癌病理图像分类 | — |
| 66 | **MVSeg-3DTEE 2023** | 胸部 | 3D 超声 | 3D 超声, 175例, 2类二尖瓣分割 | [官网](https://www.synapse.org/#!Synapse:syn51186045/wiki/621356) |
| 67 | **BRACS 病理图像乳腺癌亚型分类** | 显微成像 | 2D 病理图像 | 2D 病理图像, 4539 ROIs/547 WSIs, 7类乳腺癌亚型分类 | [官网](https://www.bracs.icar.cnr.it/) |
| 68 | **SCIN** | 皮肤科 | 2D | 2D，dermatology image，10408例，皮肤病理状况在外观和严重程度上分类 | [官网](https://research.google/blog/scin-a-new-resource-for-representative-dermatology-images/) |
| 69 | **FUMPE** | 胸部 | 3D CT | 3D CT, 35例, 1类肺栓塞分割 | [官网](https://figshare.com/collections/FUMPE/4107803/1) |
| 70 | **CORN** | 显微成像 | 2D 显微成像 | 2D 显微成像，1698例, 1类角膜神经分割 | [官网](https://imed.nimte.ac.cn/CORN.html) |
| 71 | **Dental X Ray Computacional Vision Segmentation** | 骨头 | 2D | 2D，X-ray，8188例，牙科X光影像分割 | [官网](https://www.kaggle.com/datasets/henriquerezermosqur/dental-x-ray-computacional-vision-segmentation/data) |
| 72 | **BraTS2023-MET** | 头颈部 | 3D MRI | 3D MRI, 328例, 3类脑转移瘤分割 | [官网](https://www.synapse.org/#!Synapse:syn51156910/wiki/622553) |
| 73 | **cSeg 2022** | 头颈部 | 3D MRI | 3D MRI, 13例, 3类脑组织分割 | [官网](https://tarheels.live/cseg2022/) |
| 74 | **ZuCo** | 头颈部 | 2D | 2D，NLP，146909例，3类阅读时的采样 | [官网](https://osf.io/q3zws/) |
| 75 | **INSTANCE 2022** | 头颈部 | 3D CT | 3D CT, 200例, 1类脑出血分割 | [官网](https://instance.grand-challenge.org/) |
| 76 | **SPPIN** | 腹部 | 3D MRI | 3D MRI, 111例, 1类神经母细胞瘤分割 | [官网](https://sppin.grand-challenge.org/sppin/) |
| 77 | **RJUA-QA** | 腹部 | QA | QA，213例，泌尿专科QA推理数据集 | [官网](https://github.com/alipay/RJU_Ant_QA/) |
| 78 | **ODIR-5K** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 5000例, 8类眼科常见病分类 | [官网](https://odir2019.grand-challenge.org/introduction/) |
| 79 | **StructSeg 2019 Task2 鼻咽癌肿瘤靶区分割** | 头颈部 | 3D CT | 3D CT, 50例, 1类鼻咽癌分割 | [官网](https://structseg2019.grand-challenge.org/) |
| 80 | **ZuCo 2.0** | 多模态数据集 | eeg-to-text | eeg-to-text，提供更全面的生理数据以支持自然语言处理（NLP）和认知科学的研究 | [官网](https://osf.io/2urht/) |
| 81 | **MedicationQA** | 文本数据集 | QA | QA, 674 | [官网](https://github.com/allenai/medicat) |
| 82 | **EIT-1M** | 多模态数据集 | 语义解码 | 语义解码，100万对EEG-图像-文本数据对，适用于EEG信号解码任务 | [官网](https://eit-1m.github.io/EIT-1M/) |
| 83 | **MICCAI 2024 INSTED** | 头颈部 | 3D | 3D，MR，191例，3类中风的分割 | [官网](https://www.codabench.org/competitions/2139/#/pages-tab) |
| 84 | **Mindboggle** | 头颈部 | 3D | 3D，MR，62类，101例，人脑影像分割 | — |
| 85 | **MMMU Health&Medicine** | 多模态数据集 | VQA | VQA, 1752 例 QA 对 | [官网](https://data.mendeley.com/datasets/pc4mb3h8hz/1) |
| 86 | **Colorectal-Liver-Metastases** | 腹部 | 3D | 3D，CT，197例，肝肿瘤分割 | [官网](https://www.cancerimagingarchive.net/collection/colorectal-liver-metastases/) |
| 87 | **EndoMapper** | 内窥镜 | 2D 内窥镜视频 | 2D 内窥镜视频, 59例, 三维重建和VSLAM | [官网](https://www.synapse.org/#!Synapse:syn26707219/wiki/615178) |
| 88 | **CP-CHILD** | 内窥镜 | 2D | 2D，内窥镜，9500例，结肠息肉分类 | [官网](https://www.kaggle.com/datasets/mah) |
| 89 | **TG3K** | 头颈部 | 2D 超声 | 2D 超声, 3585例, 1类甲状腺结节分割 | [官网](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation) |
| 90 | **CPIA** | 全身 | 2D | 2D，pathology，21,427,877例，自监督学习（SSL）预训练数据集 | — |
| 91 | **BraTS21** | 头颈部 | 3D MRI | 3D MRI, 2040例, 3类脑胶质瘤分割 | [官网](https://www.synapse.org/#!Synapse:syn25829067/wiki/610863) |
| 92 | **C3VD 结肠镜三维重建数据集介绍** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 10015例, 三维重建 | [官网](https://durrlab.github.io/C3VD/) |
| 93 | **COVID_CT_COVID-CT** | 胸部 | 2D CT | 2D CT, 746例, 2类肺炎分类 | [官网](https://tianchi.aliyun.com/dataset/106604) |
| 94 | **Cataract-1K** | 眼科 | 2D | 2D，眼科 显微镜，1000例，13种阶段2种异常12种分割 | [官网](https://github.com/Negin-Ghamsarian/Cataract-1K) |
| 95 | **MedMCQA** | 文本数据集 | QA | QA, 193,155 例 QA 对 | [官网](https://medmcqa.github.io/) |
| 96 | **MSD Hepatic Vessel** | 腹部 | 3D CT | 3D CT, 443例, 2类肝脏血管和肝脏肿瘤分割 | [官网](http://medicaldecathlon.com/) |
| 97 | **MICCAI2024-AutoPETIII** | 全身 | 3D | 3D，CT,PET，1614例，优化在多中心、多示踪剂环境下的肿瘤病灶自动分割 | [官网](https://autopet-iii.grand-challenge.org/task/) |
| 98 | **TFDR** | 文本数据集 | text | text，6211例，疾病关系 | — |
| 99 | **Complete Blood Count** | 显微成像 | 2D 血液涂片 | 2D 血液涂片, 360例, 3类血液细胞计数 | [官网](https://github.com/MahmudulAlam/Complete-Blood-Cell-Count-Dataset) |
| 100 | **BCI** | 显微成像 | 2D | 2D，病理图像，4870例，4类将HE图像转换为IHC图像 | [官网](https://bupt-ai-cz.github.io/BCI/) |
| 101 | **Fractured bone detection challenge CT 图像骨折分类** | 骨头 | 3D CT | 3D CT, 5567例, 2类骨折分类 | [官网](https://www.kaggle.com/competitions/fractured-bone-detection-challenge/overview) |
| 102 | **DDTI** | 头颈部 | 2D 超声 | 2D 超声, 637例, 1类甲状腺结节分割 | [官网](http://cimalab.intec.co/applications/thyroid/) |
| 103 | **Malignant Lymphoma Classification** | 显微成像 | 2D 病理切片 | 2D 病理切片, 374例, 3类恶性淋巴瘤分类 | [官网](https://www.kaggle.com/datasets/andrewmvd/malignant-lymphoma-classification) |
| 104 | **Cervix93** | 显微成像 | 2D | 2D，病理，331例，三种不同巴氏试验等级的涂片上的93张EDF图像及其图像堆栈 | [官网](https://github.com/parham-ap/cytology_dataset) |
| 105 | **MultiOrg** | 显微成像 | 2D | 2D，显微镜明场成像，411张完整标注图像，60,000个类器官标注，大规模肺类器官检测 | — |
| 106 | **Corneal Nerve Tortuosity** | 显微成像 | 2D 显微成像 | 2D 显微成像, 30例, 3类角膜神经扭曲程度分类 | [官网](http://bioimlab.dei.unipd.it/Corneal%20Nerve%20Tortuosity%20Data%20Set.htm) |
| 107 | **AGGC** | 腹部 | 2D | 2D，病理，203例，不同Gleason模式的H&E染色全片图像分割· | [官网](https://aggc22.grand-challenge.org/) |
| 108 | **CheXchoNet** | 胸部 | 2D | 2D，Xray，4类，71,589例，单图胸部 X 光影像预测心脏疾病 | — |
| 109 | **STARE** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 20例, 1类眼底血管分割 | [官网](https://cecas.clemson.edu/~ahoover/stare/) |
| 110 | **SEED** | 多模态数据集 | 情绪识别 | 情绪识别，上海交通大学脑与计算科学实验室构建的公开情感数据集，主要用于情感计算和脑机接口领域的研究 | [官网](https://bcmi.sjtu.edu.cn/home/seed/seed.html) |
| 111 | **Hamlyn Endoscopic Video Datasets** | 内窥镜 | 2D | 2D，内窥镜，38例，腹腔镜和内窥镜视频数据 | [官网](https://hamlyn.doc.ic.ac.uk/vision/) |
| 112 | **Augemnted ocular diseases** | 眼科 | AOD)（2D | AOD)（2D，眼底图像，14.8k，7类主要的眼部疾病分类 | [官网](https://www.kaggle.com/datasets/nurmukhammed7/augemnted-ocular-diseases) |
| 113 | **PathText** | 文本数据集 | Caption | Caption，9009例，WSI-文本配对 | [官网](https://github.com/cpystan/Wsi-Caption) |
| 114 | **大规模注释宫颈细胞学图像** | 显微成像 | 2D | 2D，数字细胞学图像，8037例，宫颈癌检测 | — |
| 115 | **Montgomery County CXR Set** | 多模态数据集 | 2D X-Ray | 2D X-Ray, 138例, 2类 CXR 图像异常诊断 | [官网](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#tuberculosis-image-data-sets) |
| 116 | **BrainPTM** | 头颈部 | 3D | 3D，MR-T1，MR-DWI，75例，1类脑白质束路径映射分割 | [官网](https://brainptm-2021.grand-challenge.org/) |
| 117 | **EAD 2019** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 2991例, 7类食管, 结肠,胃, 膀胱, 肝脏分割 | [官网](https://ead2019.grand-challenge.org/EAD2019/) |
| 118 | **KiTS21** | 腹部 | 3D CT | 3D CT, 400例, 3类肾脏和肾脏肿瘤分割 | [官网](https://kits-challenge.org/kits21/) |
| 119 | **TotalSegmentator v2** | 全身 | 3D CT | 3D CT, 1228例, 117类全身器官分割 | [官网](https://github.com/wasserth/TotalSegmentator) |
| 120 | **ChineseEEG** | 多模态数据集 | 语义解码和对齐 | 语义解码和对齐，高密度 EEG（脑电图）数据和同时进行的眼动追踪数据 | [官网](https://github.com/ncclabsustech/Chinese_reading_task_eeg_processing) |
| 121 | **RAVIR** | 眼科 | 2D | 2D，IR，46例，视网膜动脉和静脉的语义分割 | [官网](https://ravir.grand-challenge.org/RAVIR/) |
| 122 | **MOOD2023** | 腹部 | 3D | 3D, CT&MR, 1300例 | [官网](http://medicalood.dkfz.de/web/) |
| 123 | **SegPANDA200** | 腹部 | 2D | 2D，pathology，100960例，前列腺癌分割 | [官网](https://link.springer.com/chapter/10.1007/978-3-031-44917-8_25) |
| 124 | **EMIDEC** | 心脏 | 3D | 3D，DE-MRI，150例，3类评估心肌梗死分割 | [官网](https://emidec.com/) |
| 125 | **ISIC 2020** | 皮肤科 | 2D 皮肤镜图像 | 2D 皮肤镜图像，33126例，2类黑色素瘤良恶性分类 | [官网](https://challenge2020.isic-archive.com/) |
| 126 | **三维下肢肌肉骨骼几何结构** | 全身 | 3D | 3D，下肢，2例，130类肌肉骨骼分割 | [官网](https://digitalcommons.du.edu/visiblehuman/) |
| 127 | **RITE** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 40例, 1类眼底血管分割 | [官网](https://medicine.uiowa.edu/eye/rite-dataset) |
| 128 | **Sinus Surgery Endoscopic Image Datasets** | 内窥镜 | 2D 鼻腔镜 | 2D 鼻腔镜, 9003例, 1类手术器械分割 | [官网](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets?tab=readme-ov-file) |
| 129 | **FUSC2021** | 皮肤科 | 2D | 2D，皮肤镜，1010例，基于图像的伤口分割 | [官网](https://github.com/uwm-bigdata/wound-segmentation/tree/master/data/Foot%20Ulcer%20Segmentation%20Challenge) |
| 130 | **Quilt-1M 视觉-语言组织病理学** | 多模态数据集 | caption | caption, 768826 例 | [官网](https://quilt1m.github.io/) |
| 131 | **CTSpine1K** | 骨头 | 3D CT | 3D CT, 1005例, 25类脊椎分割 | [官网](https://github.com/MIRACLE-Center/CTSpine1K) |
| 132 | **KiPA22** | 腹部 | 3D CTA | 3D CTA, 130例, 4类肾脏，血管和肿瘤分割 | [官网](https://kipa22.grand-challenge.org/) |
| 133 | **CVC-ClinicDB** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 612例, 1类结肠息肉分割 | [官网](https://polyp.grand-challenge.org/CVCClinicDB/) |
| 134 | **SLAKE** | 多模态数据集 | VQA | VQA, 14028 例 QA 对 | [官网](https://www.med-vqa.com/slake/) |
| 135 | **HECKTOR 2022** | 头颈部 | 3D PET-CT | 3D PET-CT, 882例, 2类肿瘤和淋巴结分割 | [官网](https://hecktor.grand-challenge.org/Data/) |
| 136 | **MyoPS 2020** | 心脏 | 3D MRI | 3D MRI, 45例, 5类疤痕、水肿、正常心肌以及左右心室血池分割 | [官网](https://zmiclab.github.io/zxh/0/myops20/) |
| 137 | **MAPLES-DR** | 眼科 | 2D | 2D，眼底照片，198例，12类糖尿病性视网膜病变分割 | [官网](https://www.nature.com/articles/s41597-024-03739-6?_gl=1) |
| 138 | **PubMedQA** | 文本数据集 | QA | QA, 1000 例专家标注 QA 对 | [官网](https://pubmedqa.github.io/) |
| 139 | **Breast Ultrasound Dataset B** | 胸部 | 2D 超声 | 2D 超声, 163例, 1类乳腺病变分割 | [官网](http://www2.docm.mmu.ac.uk/STAFF/M.Yap/dataset.php) |
| 140 | **PromptCBLUE 中文医疗大模型评测基准数据集** | 文本数据集 | QA | QA, 97912例 | [官网](https://www.idpoisson.fr/tcbchallenge/data/) |
| 141 | **MRBrains13** | 头颈部 | 3D | 3D，MR: T1、T1IR、FLAIR，320例，三类脑部分割 | [官网](https://mrbrains13.isi.uu.nl/index.html) |
| 142 | **MM-WHS** | 心脏 | 3D CT/MRI | 3D CT/MRI, 120例, 7类心脏亚结构分割 | [官网](https://zmiclab.github.io/zxh/0/mmwhs/) |
| 143 | **MHIST** | 显微成像 | 2D | 2D，病理图像, 3152例，2类结肠息肉病变分类 | [官网](https://bmirds.github.io/MHIST/) |
| 144 | **AMD-SD** | 眼科 | 2D | 2D，OCT，3049例，5类湿性年龄相关性黄斑变性分割 | [官网](https://www.nature.com/articles/s41597-024-03844-6?_gl=1*b3wq4u*_up*MQ..&gclid=Cj0KCQjw3bm3BhDJARIsAKnHoVXSgcCZ1IVP-iFrZ3UUAyGYcDxTqRoRzajibS9q1F6dA5GEF2xAyw4aAmrcEALw_wcB) |
| 145 | **RibFrac 2020 CT 图像肋骨骨折检测分类** | 骨头 | 3D CT | 3D CT, 660例, 4类肋骨骨折检测分类 | [官网](https://ribfrac.grand-challenge.org/) |
| 146 | **LIMUC** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 11276, 4类胃肠梅奥内窥镜评分分类 | [官网](https://github.com/GorkemP/labeled-images-for-ulcerative-colitis) |
| 147 | **SOPHIE Spitz** | 皮肤科 | 2D | 2D，病理切片，61例，Spitz样肿瘤分类· | [官网](https://www.nature.com/articles/s41597-023-02585-2#ref-CR23) |
| 148 | **KiTS23** | 腹部 | 3D CT | 3D CT, 599例, 3类肾脏和肾脏肿瘤分割 | [官网](https://kits-challenge.org/kits23/) |
| 149 | **CrossMoDA 2023** | 头颈部 | 3D MRI | 3D MRI, 983例, 3类前庭神经瘤和耳蜗分割 | [官网](https://crossmoda-challenge.ml/) |
| 150 | **SegRap 2023** | 头颈部 | 3D CT | 3D CT, 200 例, 45 类头颈部风险器官和 2 类鼻咽癌和相关淋巴结的分割 | [官网](https://segrap2023.grand-challenge.org/) |
| 151 | **QUILT-VQA** | 多模态数据集 | VQA | VQA，1283例，病理图像视觉问答 | [官网](https://quilt-llava.github.io/) |
| 152 | **PathVQA** | 多模态数据集 | VQA | VQA, 32799例 QA 对 | [官网](https://pathvqachallenge.grand-challenge.org/) |
| 153 | **MedDialog-CN** | 文本数据集 | QA | QA, 1.1M 例 QA 对 | [官网](https://github.com/UCSD-AI4H/Medical-Dialogue-System) |
| 154 | **DRHAGIS** | 眼科 | 2D | 2D，眼底彩照，39例，英国糖尿病视网膜病变筛查项目分割 | — |
| 155 | **CAD-Chest** | 多模态数据集 | VQA | VQA, 227,827 例 CXR 报告 | — |
| 156 | **MMIS-2024@ACM MM 2024** | 头颈部 | 4D | 4D，MRI，310例，2类多样化和个性化的大体肿瘤体积分割 | [官网](https://mmis2024.com/) |
| 157 | **AMOS 2022** | 腹部 | 3D CT&MRI | 3D CT&MRI, 600例, 15类腹部器官分割 | [官网](https://amos22.grand-challenge.org/) |
| 158 | **FLARE 2021** | 腹部 | 3D CT | 3D CT, 511例, 4类腹部器官分割 | [官网](https://flare.grand-challenge.org/) |
| 159 | **SegTHOR** | 胸部 | 3D CT | 3D CT, 60例, 4类胸部风险器官分割 | [官网](https://competitions.codalab.org/competitions/21145) |
| 160 | **PMC-VQA** | 多模态数据集 | VQA | VQA, 227K 例 | [官网](https://github.com/xiaoman-zhang/PMC-VQA) |
| 161 | **Huatuo-26M** | 文本数据集 | QA | QA, 26M 例 QA 对 | [官网](https://github.com/FreedomIntelligence/Huatuo-26M) |
| 162 | **ShenNong-TCM-Dataset/EB** | 文本数据集 | QA | QA, 113K 例 QA 对 | [官网](https://github.com/ywjawmw/TCMEB/blob/main/) |
| 163 | **Kvasir-Capsule** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 4741504例, 14类消化道病变分割 | [官网](https://datasets.simula.no/kvasir-capsule/) |
| 164 | **EHRXQA** | 多模态数据集 | image | image, tabular, text，X光，QA，46k个QA，417个QA模板，旨在全面记录患者的健康状况 | — |
| 165 | **MURA** | 骨头 | 2D | 2D，X-ray，40561例，2例肌肉骨骼分类 | [官网](https://stanfordmlgroup.github.io/competitions/mura/) |
| 166 | **HEST-1k** | 多模态数据集 | image-gene | image-gene，1180例，空间转录组学 (ST) 样本 | [官网](https://github.com/mahmoodlab/hest) |
| 167 | **iChallenge-DeepDRiD-Task1** | 眼科 | 2D | 2D，fundus，5类糖尿病视网膜病变分类 | [官网](https://github.com/deepdrdoc/DeepDRiD) |
| 168 | **Multi-Label Retinal Diseases** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 2451例, 20类眼部疾病分类 | [官网](https://data.mendeley.com/datasets/pc4mb3h8hz/1) |
| 169 | **Adrenal-ACC-Ki67-Seg 经过病理证实的肾上腺皮质癌分割** | 腹部 | 3D CT | 3D CT, 57例, 1 类 ACC 分割 | [官网](https://www.cancerimagingarchive.net/collection/adrenal-acc-ki67-seg/) |
| 170 | **Fitzpatrick 17k 皮肤状况和肤色分类** | 皮肤科 | 2D 皮肤镜图像 | 2D 皮肤镜图像, 16577例, 6 类 Fitzpatrick 皮肤类型, 114 种皮肤状况 | [官网](https://github.com/mattgroh/fitzpatrick17k) |
| 171 | **HuBMAP** | 腹部 | 2D | 2D，病理，1类，20例，肾小球的分割 | — |
| 172 | **Web-scraped Skin Image** | 皮肤科 | 2D 皮肤镜图像 | 2D 皮肤镜图像, 804例, 6类皮肤病分类 | [官网](https://www.kaggle.com/datasets/arafathussain/monkeypox-skin-image-dataset-2022) |
| 173 | **Augmented Skin Conditions Image Dataset** | 皮肤科 | 2D | 2D，皮肤镜，2394例，6类·皮肤病变图像分类 | [官网](https://www.kaggle.com/datasets/syedalinaqvi/augmented-skin-conditions-image-dataset) |
| 174 | **BONBID-HIE 2023 新生儿脑缺氧缺血性脑病** | 头颈部 | HIE）的病变分割 (3D MRI | HIE）的病变分割 (3D MRI, 133例, 1类缺血性脑部病变分割 | [官网](https://bonbid-hie2023.grand-challenge.org) |
| 175 | **QUBIQ2021-3D CT** | 腹部 | 2D | 2D, CT, 90例, 2类胰腺胰腺病变分割 | [官网](https://qubiq21.grand-challenge.org/QUBIQ2021/) |
| 176 | **PROMISE12** | 腹部 | 3D | 3D，MR，50例，前列腺分割 | [官网](https://promise12.grand-challenge.org/) |
| 177 | **TotalSegmentator MRI** | 全身 | 3D MR | 3D MR, 298例, 56类全身器官分割 | [官网](https://github.com/wasserth/TotalSegmentator) |
| 178 | **Ultrasound Nerve Segmentation** | 头颈部 | 2D 超声 | 2D 超声, 11143例, 1类颈部神经分割 | [官网](https://kaggle.com/competitions/ultrasound-nerve-segmentation) |
| 179 | **Derm7pt** | 皮肤科 | 2D | 2D，皮肤镜图像，2000例，19类皮肤病 | [官网](https://derm.cs.sfu.ca/Welcome.html) |
| 180 | **MMLU Clinical Topics** | 文本数据集 | QA | QA, 1089 例 QA 对 | — |
| 181 | **ACRIMA 眼底图像青光眼分类** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 705例, 2类青光眼分类 | [官网](https://figshare.com/s/c2d31f850af14c5b5232) |
| 182 | **webMedQA** | 文本数据集 | QA | QA, 63,284 例 QA 对 | [官网](https://github.com/hejunqing/webMedQA/tree/master) |
| 183 | **ToothFairy** | 头颈部 | 3D CBCT | 3D CBCT, 443例, 1类下颌神经分割 | [官网](https://toothfairy.grand-challenge.org/toothfairy/) |
| 184 | **PedCorpus** | 多模态数据集 | QA | QA，270k例，中文儿科医疗问答 | — |
| 185 | **CrossMoDA2021** | 头颈部 | 3D T1-CE | 3D T1-CE, T2-HR，349例，2类肿瘤和耳蜗结构分割 | [官网](https://crossmoda.grand-challenge.org/) |
| 186 | **NuCLS** | 腹部 | 2D | 2D，病理，119828例，胃癌病理图像分类 | [官网](https://www.sciencedirect.com/science/article/abs/pii/S0010482521010015) |
| 187 | **AutoPET** | 全身 | 3D PET-CT | 3D PET-CT, 1214例, 1类全身肿瘤分割 | [官网](https://autopet.grand-challenge.org/) |
| 188 | **HRF-质量评估** | 眼科 | 2D | 2D，Fundus photogr aphy，2类视网膜图像分类 | [官网](https://www5.cs.fau.de/research/data/fundus-images/) |
| 189 | **CMB** | 文本数据集 | QA | QA, 270K 例 QA 对 | [官网](https://github.com/FreedomIntelligence/CMB/tree/main) |
| 190 | **AIROGS** | 眼科 | 2D | 2D，fundus，101442，2类青光眼分类 | [官网](https://airogs.grand-challenge.org/data-and-challenge/) |
| 191 | **SUN Colonoscopy Video** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 158,690例, 1类息肉分割 | [官网](http://amed8k.sundatabase.org/) |
| 192 | **DRAC22** | 眼科 | 2D | 2D，眼底图像，174例，视网膜病变分割 | [官网](https://drac22.grand-challenge.org) |
| 193 | **FLARE 2023** | 腹部 | 3D CT | 3D CT, 4500例, 14类腹部器官和肿瘤分割 | [官网](https://flare22.grand-challenge.org/) |
| 194 | **TotalSegmentator** | 全身 | 3D CT | 3D CT, 1204例, 104类全身器官分割 | [官网](https://github.com/wasserth/TotalSegmentator) |
| 195 | **MIST-HER2** | 胸部 | 2D | 2D，pathology，22688例，4类乳腺癌诊断中至关重要的生物标志物 | [官网](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_61) |
| 196 | **Knee Osteoarthritis Dataset with Severity Grading** | 骨头 | 2D | 2D，X-Ray，9786例，5类膝关节分类 | [官网](https://data.mendeley.com/datasets/56rmx5bjcr/1) |
| 197 | **ICIAR 2018 BACH Task1** | 显微成像 | 2D 组织学图像 | 2D 组织学图像, 400例, 4类乳腺癌分类 | [官网](https://iciar2018-challenge.grand-challenge.org/Dataset/) |
| 198 | **BUSI** | 胸部 | 2D 超声 | 2D 超声, 780例, 3类乳腺肿瘤分类, 1类乳腺肿瘤分割 | [官网](https://scholar.cu.edu.eg/?q=afahmy/pages/dataset) |
| 199 | **DRISHTI-GS** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 101例, 2类视杯视盘分割 | [官网](https://ieeexplore.ieee.org/document/6867807) |
| 200 | **腰骶脊柱MRI** | 骨头 | 3D | 3D，MRI，对脊髓神经根的检测 | [官网](https://figshare.com/collections/An_open-access_lumbosacral_spine_MRI_dataset_with_enhanced_spinal_nerve_root_structure_resolution/7372564) |
| 201 | **ATLAS v2.0** | 头颈部 | ISLES 2022)(3D MRI | ISLES 2022)(3D MRI, 1271例, 1类中风病灶分割 | [官网](http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html) |
| 202 | **ICPR-HEp-2** | 显微成像 | 2D 细胞荧光显微镜图像 | 2D 细胞荧光显微镜图像, 14K, 6类细胞分类 | [官网](https://www.heywhale.com/mw/dataset/5ec3c6883241a100378d5d4a) |
| 203 | **PatchCamelyon** | 显微成像 | 2D 病理图像 | 2D 病理图像, 327,680 例, 2类乳腺癌转移分类 | [官网](https://patchcamelyon.grand-challenge.org/) |
| 204 | **FedSurg 2024** | 腹部 | 2D | 2D，腹腔镜，30例，6类腹腔镜阑尾切除术 | [官网](https://www.synapse.org/Synapse:syn53137385/wiki/625370) |
| 205 | **RANZCR CLiP** | 胸部 | 2D | 2D，X-ray，11类33665个案例，胸部 X 光检查中导管和管路位置的自动检测与分类 | — |
| 206 | **ICIAR 2018 BACH Task2** | 显微成像 | 2D 组织学图像 | 2D 组织学图像, 30例, 3类乳腺癌分割 | [官网](https://iciar2018-challenge.grand-challenge.org/Dataset/) |
| 207 | **PI-CAI** | 腹部 | 3D MR | 3D MR, 1500例, 1类前列腺癌分割 | [官网](https://pi-cai.grand-challenge.org/) |
| 208 | **BioMediTech** | 显微成像 | 2D 细胞成像 | 2D 细胞成像, 1862例, 4类视网膜细胞分类 | [官网](https://figshare.com/s/d6fb591f1beb4f8efa6f) |
| 209 | **疟疾细胞图像** | 显微成像 | 2D 显微图像 | 2D 显微图像, 27558例, 2类疟疾分类 | [官网](https://lhncbc.nlm.nih.gov/LHC-research/LHC-projects/image-processing/malaria-datasheet.html,) |
| 210 | **Eyepacs** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 35126例, 5类糖尿病性视网膜病变分级 | [官网](https://www.eyepacs.com/) |
| 211 | **OCTA-500** | 眼科 | 2D OCT | 2D OCT , 500例, 1类眼底血管分割 | [官网](https://ieee-dataport.org/open-access/octa-500) |
| 212 | **MICCAI2024 HNTS-MRG Task1** | 头颈部 | 3D | 3D，MRI T2w，150例，原发肿瘤和转移淋巴结分割 | [官网](https://hntsmrg24.grand-challenge.org/overview/) |
| 213 | **CBLUE** | 文本数据集 | QA | QA, 195,870例 | — |
| 214 | **EndoVisSub2018-RoboticSceneSegmentation** | 内窥镜 | 2D | 2D，Endoscopy，7274例，机器人外科手术场景分割 | [官网](https://endovissub2018-roboticscenesegmentation.grand-challenge.org/Home/) |
| 215 | **MSD Pancreas Tumour** | 腹部 | 3D CT | 3D CT, 420例, 2类胰腺和胰腺肿瘤分割 | [官网](http://medicaldecathlon.com/) |
| 216 | **SurgToolLoc** | 内窥镜 | 2D | 2D，内窥镜，24695例，14类手术工具的分类和检测 | — |
| 217 | **CMExam** | 文本数据集 | QA | QA, 68K 例 QA 对 | [官网](https://github.com/williamliujl/CMExam/) |
| 218 | **LLD-MMRI2023** | 腹部 | 3D | 3D, MRI, 394例, 肝脏病变检测 | [官网](https://github.com/LMMMEng/LLD-MMRI2023/tree/main?tab=readme-ov-file) |
| 219 | **ASCE** | 眼科 | 2D | 2D，显微镜，385例，角膜内皮自动分割 | — |
| 220 | **Chinese Medical Dialogue Dataset** | 文本数据集 | QA | QA, 792K 例 QA 对 | [官网](https://tianchi.aliyun.com/dataset/90163) |
| 221 | **FLARE 2024 Task1 10000+ CT** | 全身 | 3D | 3D，CT，10000例，1类全身肿瘤分割 | [官网](https://www.codabench.org/competitions/2319) |
| 222 | **PMC-Inline** | 多模态数据集 | caption | caption，11,000,000张图象 | [官网](https://huggingface.co/datasets/chaoyi-wu/PMC-Inline/tree/main) |
| 223 | **CuRIOUS2022 术中超声图像脑肿瘤和切除腔分割** | 头颈部 | 3D Ultrasound | 3D Ultrasound, 23例, 1类脑肿瘤（切除腔）分割 | [官网](https://curious2022.grand-challenge.org) |
| 224 | **MSD Prostate** | 腹部 | 3D MR | 3D MR, 48例, 2类前列腺分割 | [官网](http://medicaldecathlon.com/) |
| 225 | **SegPC21** | 显微成像 | 2D | 2D，显微成像，498例，2类骨髓瘤分割 | [官网](https://segpc-2021.grand-challenge.org/SegPC-2021/) |
| 226 | **PMC-OA** | 多模态数据集 | VQA | VQA, 1.6M QA 对 | [官网](https://weixionglin.github.io/PMC-CLIP/) |
| 227 | **FIVES** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 800例, 1类眼底血管分割 | [官网](https://figshare.com/articles/figure/FIVES_A_Fundus_Image_Dataset_for_AI-based_Vessel_Segmentation/19688169/1) |
| 228 | **EndoSLAM** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 64577例, 三维重建 | [官网](https://github.com/CapsuleEndoscope/EndoSLAM) |
| 229 | **Head CT-hemorrhage** | 头颈部 | 2D CT | 2D CT, 200例, 2类脑出血分类 | [官网](https://www.kaggle.com/datasets/felipekitamura/head-ct-hemorrhage) |
| 230 | **3D-IRCADB** | 腹部 | 3D CT | 3D CT, 22例, 40类腹部器官和肿瘤分割 | [官网](https://www.ircad.fr/research/data-sets/liver-segmentation-3d-ircadb-01/) |
| 231 | **ACPS** | 眼科 | 2D | 2D，光学成像，840例，针对锥体光感受器的自动分割 | [官网](https://people.duke.edu/~sf59/Chiu_BOE_2013_dataset.htm) |
| 232 | **LNQ 2023** | 胸部 | 3D CT | 3D CT, 513例, 1类胸部纵隔淋巴结分割 | [官网](https://lnq2023.grand-challenge.org/lnq2023/) |
| 233 | **MoNuSeg** | 显微成像 | 2D 显微图像 | 2D 显微图像, 53 例, 1类细胞核分割 | [官网](https://monuseg.grand-challenge.org/Home/) |
| 234 | **BTCV Cervix** | 腹部 | 3D CT | 3D CT, 50例, 4类腹部器官分割 | [官网](https://www.synapse.org/#!Synapse:syn3193805/wiki/217790) |
| 235 | **CholecSeg8k** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 8080例, 13类胆囊切除手术语义分割 | [官网](https://www.kaggle.com/datasets/newslab/cholecseg8k) |
| 236 | **L2R-OASIS** | 头颈部 | 3D MRI | 3D MRI, 416例, 35类大脑分割和配准 | [官网](https://learn2reg.grand-challenge.org/Datasets/) |
| 237 | **CoCaHis 结肠癌组织学** | 显微成像 | 2D 病理图像 | 2D 病理图像, 82 例, 2类分割 | [官网](https://cocahis.irb.hr/) |
| 238 | **MSD Colon Cancer** | 腹部 | 3D CT | 3D CT, 190例, 1类结肠肿瘤分割 | [官网](http://medicaldecathlon.com/) |
| 239 | **CMMD** | 胸部 | 2D | 2D，X-ray，5334例，2类乳腺癌分类 | [官网](https://www.cancerimagingarchive.net/collection/cmmd/) |
| 240 | **MICCAI 2024 CARE LAScarQS++** | 心脏 | 3D | 3D，LGE MRI，194例，3类分割左心房腔体和量化左心房疤痕 | [官网](http://zmic.org.cn/care_2024/track4/) |
| 241 | **Ocular Disease Recognition** | 眼科 | 2D | 2D，眼底照片，5k，8种眼部病变分类 | [官网](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k) |
| 242 | **SEED-IV** | 多模态数据集 | 情绪识别 | 情绪识别，相较于原始的 SEED 数据集，SEED-IV 在情绪类别扩展，多模态数据，更精细的特征提取，这些方面进行了提升 | [官网](https://bcmi.sjtu.edu.cn/home/seed/seed.html) |
| 243 | **QIN-PROSTATE-Repeatability** | 腹部 | 3D | 3D，MR，30例，3类前列腺分割 | [官网](https://www.cancerimagingarchive.net/collection/qin-prostate-repeatability/) |
| 244 | **WSI-VQA** | 多模态数据集 | VQA | VQA，977个全切片图像8672个问答对，病理全切片图像视觉问答任务 | [官网](https://github.com/cpystan/WSI-VQA/tree/master) |
| 245 | **m2caiseg** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 307例, 19类腹腔器官和手术器材分割 | [官网](https://www.kaggle.com/datasets/salmanmaq/m2caiseg) |
| 246 | **PH²** | 皮肤科 | 2D 皮肤镜图像 | 2D 皮肤镜图像, 200例, 1类黑色素瘤分割 | [官网](https://www.fc.up.pt/addi/ph2%20database.html) |
| 247 | **ISIC 2024 挑战赛-SLICE-3D** | 皮肤科 | 2D | 2D，皮肤病图像，401059例，皮肤癌检测的人工智能图像分类 | [官网](https://www.kaggle.com/competitions/isic-2024-challenge) |
| 248 | **ISIC-2024** | 皮肤科 | 2D | 2D，皮肤镜，81722例，皮肤镜图像分类 | [官网](https://www.kaggle.com/competitions/isic-2024-challenge) |
| 249 | **Oral Dataset** | 骨头 | 2D | 2D，自然图像，8188例，牙齿状况分类 | — |
| 250 | **STimage-1K4M** | 多模态数据集 | image-gene | image-gene，详细记录了每个空间点的基因表达信息 | [官网](https://github.com/JiawenChenn/STimage-1K4M) |
| 251 | **BraTS18** | 头颈部 | 3D MR | 3D MR，285例，3类脑部肿瘤分割 | [官网](https://www.med.upenn.edu/sbia/brats2018/data.html) |
| 252 | **PAD-UFES-20** | 皮肤科 | 2D 皮肤镜图像 | 2D 皮肤镜图像, 2298例, 6类皮肤病分类 | — |
| 253 | **LNDb** | 胸部 | 3D CT | 3D CT, 294例, 1类肺结节分割 | [官网](https://lndb.grand-challenge.org/) |
| 254 | **IDRID** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 81例, 5类糖尿病视网膜病变分割 | [官网](https://idrid.grand-challenge.org/Home/) |
| 255 | **PanNuke 细胞核实例分割** | 显微成像 | 2D 显微图像 | 2D 显微图像, 7904 例, 6 类细胞核分割 | [官网](https://warwick.ac.uk/fac/sci/dcs/research/tia/data/pannuke) |
| 256 | **CT-ORG** | 全身 | 3D CT | 3D CT, 140例, 6类器官分割 | [官网](https://github.com/bbrister/ctOrganSegmentation) |
| 257 | **C3VD视频** | 腹部 | 2D | 2D，colonoscopy，10015例，筛查性结肠镜检查配准 | [官网](https://durrlab.github.io/C3VD/) |
| 258 | **Breakhis** | 胸部 | 2D | 2D，病理，2类，7909例，乳腺组织切片分类 | — |
| 259 | **LAScarQS 2022** | 心脏 | 3D MRI | 3D MRI, 194例, 2类左心房和左心房疤痕分割 | [官网](https://zmiclab.github.io/projects/lascarqs22/) |
| 260 | **QIBA-VolCT-1B** | 胸部 | 3D | 3D，CT，323例，1类肺部肿瘤分割、病灶尺寸测量 | [官网](https://www.cancerimagingarchive.net/analysis-result/qiba-volct-1b/) |
| 261 | **CTPelvic1K** | 骨头 | 3D CT | 3D CT, 1184例, 4类腰椎、骶骨、左髋和右髋分割 | [官网](https://github.com/MIRACLE-Center/CTPelvic1K) |
| 262 | **MSD Spleen** | 腹部 | 3D CT | 3D CT, 61例, 1类脾脏分割 | [官网](http://medicaldecathlon.com/) |
| 263 | **NEJM-AI Benchmarking 肾脏学医学问答** | 文本数据集 | QA | QA, 858例 | — |
| 264 | **Surgical scene segmentation** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 9156例, 32类手术场景分割 | [官网](https://sisvse.github.io/) |
| 265 | **CheXpert 和CheXpertPlus** | 多模态数据集 | 正侧2面图片 | 正侧2面图片，report，肺部，胸部, 心脏，224K 图像，36M 文本token | [官网](https://stanfordmlgroup.github.io/competitions/chexpert/) |
| 266 | **FLARE 2024 Task3 MRI** | 腹部 | 3D | 3D，MRI，4817例，13种腹部器官分割 | [官网](https://www.codabench.org/competitions/2296) |
| 267 | **LES-AV** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 22例, 1类眼底血管分割 | [官网](https://ignaciorlando.github.io/) |
| 268 | **ORVS** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 49例, 1类眼底血管分割 | [官网](https://github.com/AbdullahSarhan/ICPRVessels) |
| 269 | **MIMIC-Diff-VQA 胸部X光图像差异视觉问答** | 多模态数据集 | VQA | VQA, 164,324 例 | — |
| 270 | **SARAS-ESAD** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 33398例, 21类手术动作识别 | [官网](https://saras-esad.grand-challenge.org) |
| 271 | **StructSeg2019 Task4 肺癌肿瘤靶区分割** | 胸部 | 3D CT | 3D CT, 50例, 1类肺癌靶区分割 | [官网](https://structseg2019.grand-challenge.org/) |
| 272 | **Quilt-Instruct** | 多模态数据集 | VQA | VQA，170131例，病理图像视觉问答 | [官网](https://quilt-llava.github.io/) |
| 273 | **cMedQA v2.0** | 文本数据集 | QA | QA, 108K 例 QA 对 | [官网](https://github.com/zhangsheng93/cMedQA2) |
| 274 | **RIDER-LungCT-Seg** | 胸部 | 3D | 3D，CT，59例，肺部CT影像中癌症分割 | [官网](https://www.cancerimagingarchive.net/analysis-result/rider-lungct-seg/) |
| 275 | **SMILE-UHURA 2023** | 头颈部 | 3D 7T 高分辨率 MRI | 3D 7T 高分辨率 MRI, 14例, 1类脑动脉分割 | [官网](https://www.synapse.org/#!Synapse:syn47164761/wiki/620033) |
| 276 | **TCB Challenge** | 骨头 | 2D | 2D，bone radiograph，174例，2类骨质疏松症分类 | [官网](https://www.idpoisson.fr/tcbchallenge/) |
| 277 | **VQA-RAD** | 多模态数据集 | VQA | VQA, 3515 例 QA 对 | [官网](https://osf.io/89kps/) |
| 278 | **IU-Xray 印度大学胸部X线报告** | 多模态数据集 | RG | RG,7,470 张正侧位胸部X光片, 3955 例对应的报告 | — |
| 279 | **SIIM-FISABIO-RSNA COVID-19** | 胸部 | 2D | 2D，X Ray，7597例，是否存在肺炎的基本判断分类 | [官网](https://www.kaggle.com/competitions/siim-covid19-detection/data) |
| 280 | **FeTA 2022** | 头颈部 | 3D MRI | 3D MRI, 280例, 7类婴儿脑组织分割 | [官网](https://feta.grand-challenge.org/) |
| 281 | **AbdomenAtlas 1.0 Mini 腹部多器官分割** | 腹部 | 3D CT | 3D CT, 5195例, 9类腹部器官分割 | [官网](https://github.com/MrGiovanni/AbdomenAtlas) |
| 282 | **Digital Knee X-ray Images** | 骨头 | 2D X-Ray | 2D X-Ray，1650例，5类膝关节病变分类 | [官网](https://data.mendeley.com/datasets/t9ndx37v5h/1) |
| 283 | **Gleason 2019** | 腹部 | 2D | 2D，病理，331例，6类前列腺癌分类 | [官网](https://gleason2019.grand-challenge.org/Home/) |
| 284 | **iChallenge-ADAM-Task1** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 800例, 2类年龄相关性黄斑变性 (AMD) 分类 | [官网](https://amd.grand-challenge.org/Home/) |
| 285 | **Oral Cancer** | 头颈部 | Lips and Tongue) images（2D | Lips and Tongue) images（2D，病理图像，2类，131例，口腔癌分类 | — |
| 286 | **胸部 X 线成像** | 胸部 | 肺炎） (2D X-Ray | 肺炎） (2D X-Ray, 5856例, 2类肺炎分类 | [官网](https://www.heywhale.com/mw/dataset/62c2ac49913a54a66037f872/file) |
| 287 | **OphNet** | 眼科 | 2D | 2D，眼科，2278例，眼科手术视频分析 | [官网](https://minghu0830.github.io/OphNet-benchmark/) |
| 288 | **Retinal Occlusion Dataset** | 眼科 | 2D | 2D，Fundus， photogr，aphy，4类，281例，视网膜血管阻塞检测和分类 | [官网](https://github.com/yiweichen04/retina_dataset) |
| 289 | **MitoEM2021** | 显微成像 | 3D | 3D，组织病理学，2例，线粒体分割 | [官网](https://mitoem.grand-challenge.org/) |
| 290 | **FetReg 2021 Task1** | 内窥镜 | 2D 胎儿镜 | 2D 胎儿镜, 2718例, 3类血管，胎儿，手术工具分割 | [官网](https://www.synapse.org/#!Synapse:syn25313156) |
| 291 | **UCSF-PDGM** | 头颈部 | 3D MR | 3D MR，501例，4类弥漫性胶质瘤分割 | [官网](https://www.cancerimagingarchive.net/collection/ucsf-pdgm/) |
| 292 | **TDSC-ABUS2023** | 胸部 | 3D 超声 | 3D 超声, 200例, 1类乳腺肿瘤分类分割检测 | [官网](https://tdsc-abus2023.grand-challenge.org/TDSC-ABUS2023/) |
| 293 | **Pancreas-CT 对比增强 CT 健康胰腺分割** | 腹部 | 3D CT | 3D CT, 80例, 1类胰腺分割 | [官网](https://www.cancerimagingarchive.net/collection/pancreas-ct/) |
| 294 | **SEG.A.** | 胸部 | 3D CTA | 3D CTA, 56例, 1类主动脉树分割 | [官网](https://multicenteraorta.grand-challenge.org/) |
| 295 | **ToxoFundus** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 412 例, 2类弓形虫性脉络膜视网膜炎分类 | [官网](https://www.kaggle.com/datasets/nafin59/ocular-toxoplasmosis-fundus-images-dataset) |
| 296 | **SICAPv2 前列腺病理分割数据集** | 显微成像 | 2D 病理图像 | 2D 病理图像, 18783例, 4类前列腺癌分级 | [官网](https://data.mendeley.com/datasets/9xxm58dvs3/1) |
| 297 | **Harvard Glaucoma Detection and Progression** | 眼科 | 2D | 2D，眼底照片,1544例，3类预测青光眼和严重程度 | [官网](https://ophai.hms.harvard.edu/datasets/harvard-gdp1000) |
| 298 | **Retinal OCT-C8** | 眼科 | 2D OCT | 2D OCT, 24000例, 8类视网膜疾病分类 | [官网](https://www.kaggle.com/datasets/obulisainaren/retinal-oct-c8) |
| 299 | **SkinCancer** | 皮肤科 | 2D | 2D，pathology，129,364例，皮肤病理图像分类 | [官网](https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/7QCR8S) |
| 300 | **ISBI 2025 FUGC** | 腹部 | 2D | 2D，超声，890（500可获取）例，宫颈超声图像分割 | — |
| 301 | **视网膜图像质量评估** | 眼科 | 2D | 2D, 眼底图像, 216例, 3类图像质量评估 | — |
| 302 | **SARS-COV-2 Ct-Scan** | 胸部 | 2D CT | 2D CT, 2482例, 2类肺炎分类 | [官网](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset) |
| 303 | **HealthSearchQA** | 文本数据集 | QA | QA, 3173 例 QA 对 | [官网](https://www.nature.com/articles/s41586-023-06291-2) |
| 304 | **Pneumothorax Masks X-Ray** | 胸部 | 2D | 2D，CXR，12047例，胸部X光影像和相应的气胸分割 | [官网](https://www.kaggle.com/datasets/vbookshelf/pneumothorax-chest-xray-images-and-masks/data) |
| 305 | **MICCAI 2023 PSFHS** | 腹部 | 2D | 2D，超声，5101 (4000)例，2类胎儿头部和耻骨联合（FH-PS）分割 | [官网](https://ps-fh-aop-2023.grand-challenge.org/) |
| 306 | **JSIEC** | 眼科 | 2D 眼底图像 | 2D 眼底图像，1000例，39类眼部疾病分类 | [官网](https://www.kaggle.com/datasets/linchundan/fundusimage1000) |
| 307 | **Intel & MobileODT Cervical Cancer Screening** | 内窥镜 | 2D | 2D，宫腔镜，6733例，3类宫颈图像分类 | [官网](https://kaggle.com/competitions/intel-mobileodt-cervical-cancer-screening) |
| 308 | **Chest X-ray PD Dataset** | 胸部 | 2D X-Ray | 2D X-Ray, 4575例, 3类肺炎分类 | [官网](https://data.mendeley.com/datasets/jctsfj2sfn/1) |
| 309 | **WSSS4LUAD** | 胸部 | 2D | 2D，pathology，10211例，肺癌分割 | [官网](https://wsss4luad.grand-challenge.org/WSSS4LUAD/) |
| 310 | **WMH** | 头颈部 | 3D MRI | 3D MRI, 170例, 1类脑白质高强度信号分割 | [官网](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/AECRSD) |
| 311 | **COSMOS2022** | 头颈部 | 3D | 3D，MR，75例，颈动脉血管壁分割 | [官网](https://vessel-wall-segmentation-2022.grand-challenge.org/) |
| 312 | **Corneal Nerve** | 显微成像 | 2D 显微成像 | 2D 显微成像, 90例, 2类角膜异常分类 | [官网](http://bioimlab.dei.unipd.it/Corneal%20Nerve%20Data%20Set.htm) |
| 313 | **CardiacUDA 心脏超声分割数据集** | 心脏 | 2D 超声 | 2D 超声, 992例, 5类心脏结构分割 | [官网](https://github.com/xmed-lab/GraphEcho) |
| 314 | **PALM19** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 1200例, 1类眼底血管分割 | [官网](https://palm.grand-challenge.org/Home/) |
| 315 | **BraTS-TCGA-LGG** | 头颈部 | 3D MRI | 3D MRI, 65例, 3类低级别胶质瘤分割 | [官网](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-lgg/) |
| 316 | **ROSE** | 眼科 | 2D OCT | 2D OCT, 229例, 1类眼底血管分割 | [官网](https://imed.nimte.ac.cn/dataofrose.html) |
| 317 | **DICOM-LIDC-IDRI-Nodules** | 胸部 | 3D | 3D，CT，31例，肺结节的分割 | [官网](https://www.cancerimagingarchive.net/analysis-result/qin-lungct-seg/) |
| 318 | **LungHist700** | 胸部 | 2D | 2D，病理切片，691例，7类肺部恶性肿瘤分类 | [官网](https://www.nature.com/articles/s41597-024-03944-3) |
| 319 | **MedFM Lesion Detection in Colonoscopy Images** | 内窥镜 | Endo)  (2D 内窥镜 | Endo)  (2D 内窥镜, 3865例, 4类结肠病变分类 | — |
| 320 | **BraTS2023-SSA** | 头颈部 | 3D MRI | 3D MRI, 105例, 3类非洲地区脑胶质瘤分割 | [官网](https://www.synapse.org/#!Synapse:syn51156910/wiki/622556) |
| 321 | **VQA-Med** | 多模态数据集 | VQA | VQA, 4200 张图, 15,292 例 QA 对 | — |
| 322 | **ACDC** | 心脏 | 3D MRI | 3D MRI, 150例, 3类左右心室和心肌分割 | [官网](https://www.creatis.insa-lyon.fr/Challenge/acdc/) |
| 323 | **KPIs 2024 肾脏病理学图像分割** | 显微成像 | 2D 病理图像 | 2D 病理图像, 10428 个 patch, 1类肾小球组织分割 | [官网](https://sites.google.com/view/kpis2024) |
| 324 | **AIIB23** | 胸部 | 3D CT | 3D CT, 312例, 1类肺气管分割 | [官网](https://codalab.lisn.upsaclay.fr/competitions/13238) |
| 325 | **RETOUCH** | 眼科 | 3D OCT | 3D OCT, 112例, 3类视网膜液体的分割 | [官网](https://retouch.grand-challenge.org/Home/) |
| 326 | **RIM-ONE DL** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 485例, 2类青光眼分类, 2类视盘和视杯分割 | [官网](https://github.com/miag-ull/rim-one-dl) |
| 327 | **BTCV** | 腹部 | 3D CT | 3D CT, 50例, 13类腹部器官分割 | [官网](https://www.synapse.org/#!Synapse:syn3193805/wiki/) |
| 328 | **DRIVE** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 40例, 1类眼底血管分割 | [官网](https://drive.grand-challenge.org/) |
| 329 | **M&Ms 心脏 CMR 分割** | 心脏 | 3D MR | 3D MR, 375例, 3类左右心室和心肌分割 | — |
| 330 | **Papilledema 眼底图像视神经乳头水肿分类** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 1369例, 3类视神经乳头水肿分类 | [官网](https://osf.io/2w5ce/) |
| 331 | **OmniMedVQA** | 多模态数据集 | VQA | VQA, 127,995 例 | — |
| 332 | **AIDA-E2 共聚焦内窥镜消化道疾病分类数据集** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜，262例，3类消化道疾病分类 | [官网](https://isbi-aida.grand-challenge.org/) |
| 333 | **The Nerthus Dataset** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 5525例, 4类肠道清洁等级分类 | [官网](https://datasets.simula.no/nerthus/) |
| 334 | **Parse 2022** | 胸部 | 3D CT | 3D CT, 200例, 1类肺动脉分割 | [官网](https://parse2022.grand-challenge.org/) |
| 335 | **TN-SCUI2020** | 头颈部 | 2D 超声 | 2D 超声, 4554例, 1类甲状腺结节分割 | [官网](https://tn-scui2020.grand-challenge.org/Home/) |
| 336 | **HuSHeM** | 显微成像 | 2D 显微图像 | 2D 显微图像, 216例, 4类精子分类 | [官网](https://data.mendeley.com/datasets/tt3yj2pf38/3) |
| 337 | **BEH** | 眼科 | Bangladesh Eye Hospital)（2D | Bangladesh Eye Hospital)（2D，眼底照片，634例，青光眼分类 | [官网](https://drive.google.com/file/d/1YdZm-sioiAbTdBRy4oej1q6tZL8Baft7/view) |
| 338 | **NCT-CRC-HE-100K** | 腹部 | 2D pathology | 2D pathology，100,000例，9类结直肠分类 | [官网](https://zenodo.org/records/1214456) |
| 339 | **MSD Cardiac** | 心脏 | 3D MRI | 3D MRI, 30例, 1类左心房分割 | [官网](http://medicaldecathlon.com/) |
| 340 | **MICCAI2024 - EPVS** | 头颈部 | 2D/3D | 2D/3D，MRI，220例，脑部MRI影像中血管周围间隙扩大分割 | [官网](https://www.synapse.org/Synapse:syn54100278/wiki/626542) |
| 341 | **EBBIS-BCC** | 显微成像 | 2D | 2D，病理，58例，乳腺癌细胞分割 | — |
| 342 | **ISPY1-Tumor-SEG-Radiomics** | 胸部 | 3D | 3D，MRI，483例，1类分割肿瘤 | [官网](https://www.cancerimagingarchive.net/analysis-result/ispy1-tumor-seg-radiomics/) |
| 343 | **MICCAI-24 ACOUSLIC** | 腹部 | 3D | 3D，超声，600例，3类盲扫数据进行胎儿生物测量 | [官网](https://acouslic-ai.grand-challenge.org/overview-and-goals/) |
| 344 | **LAG** | 眼科 | 2D | 2D，眼底照片，11760例，青光眼的早期检测与研究分类 | [官网](https://github.com/smilell/AG-CNN?tab=readme-ov-file) |
| 345 | **BraTS2023-MEN** | 头颈部 | 3D MRI | 3D MRI, 1650例, 3类脑膜瘤分割 | [官网](https://www.synapse.org/#!Synapse:syn51156910/wiki/622353) |
| 346 | **MIDOG++** | 胸部 | 2D | 2D，pathology，乳腺癌、肺癌、淋巴肉瘤、神经内分泌肿瘤等分类 | [官网](https://github.com/DeepMicroscopy/MIDOGpp/tree/main) |
| 347 | **VESSEL12** | 胸部 | 3D CT | 3D CT，20例，1类部血管分割 | [官网](https://vessel12.grand-challenge.org/) |
| 348 | **DDXPlus** | 多模态数据集 | 包含鉴别诊断以及非二元症状和前因的大规模数据集 | 包含鉴别诊断以及非二元症状和前因的大规模数据集 | — |
| 349 | **AAPM-RT-MAC** | 头颈部 | 3D MRI | 3D MRI，55例，8类腮腺、下颌下腺、2 级和 3 级淋巴结的轮廓分割 | [官网](https://www.cancerimagingarchive.net/collection/aapm-rt-mac/) |
| 350 | **JSRT** | 胸部 | 2D | 2D，X-ray，1类，247例，胸部X光影像分割 | — |
| 351 | **CoronaHack** | 胸部 | 2D | 2D，CXR，5910例，区别健康个体和患有肺炎的患者的分割分类 | [官网](https://www.kaggle.com/datasets/praveengovi/coronahack-chest-xraydataset/data) |
| 352 | **OCCISC** | 显微成像 | 2D | 2D，显微成像，945例，从重叠的宫颈细胞学图像中提取单个细胞质和细胞核的边界 | [官网](https://cs.adelaide.edu.au/~carneiro/isbi14_challenge/index.html) |
| 353 | **MedMax** | 多模态数据集 | 2D | 2D，VQA/Report Generation/Visual chat/image generation/image captioninig，725k，多任务图文交错数据集 | — |
| 354 | **PitVis** | 内窥镜 | 2D | 2D，内窥镜，120024例，15类内窥镜垂体手术中的工作流程识别 | [官网](https://opencas.dkfz.de/endovis/challenges/2023/) |
| 355 | **OSCC** | 头颈部 | 2D | 2D，病理，1224例，口腔鳞状细胞癌分类 | [官网](https://data.mendeley.com/datasets/ftmp4cvtmb/1) |
| 356 | **DEAP** | 多模态数据集 | 情绪识别 | 情绪识别，通过生理信号的分析来研究人类情感状态 | [官网](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/) |
| 357 | **RP3D-Caption** | 多模态数据集 | caption | caption, 69523 例 image-caption 对 | [官网](https://chaoyi-wu.github.io/RadFM/) |
| 358 | **病理性近视识别和解剖结构标注** | 眼科 | 2D | 2D，眼底彩照，1200例，病理性近视识别和解剖结构标注的开放眼底成像分类/分割 | — |
| 359 | **Bone Marrow Cytomorphology** | 显微成像 | 2D 病理图像 | 2D 病理图像, 171,375 例, 21类骨髓细胞形态学分类 | [官网](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=101941770) |
| 360 | **LDPolypVideo** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 861400帧, 1类息肉检测 | [官网](https://github.com/dashishi/LDPolypVideo-Benchmark) |
| 361 | **PadChest-GR** | 胸部 | 2D | 2D，X-ray，用于生成定位放射学报告 (GRRG) 的双语胸部 X 光数据集 | — |
| 362 | **BIOMEDICA** | 多模态数据集 | VQA | VQA，开源的生物医学图像与文本配对数据集 | — |
| 363 | **MedFMC** | 全身 | 2D | 2D，22349例，X光胸片疾病筛查、病理病变组织筛查、内窥镜图像中的病变检测、新生儿黄疸评估和糖尿病视网膜病变分级 | [官网](https://github.com/wllfore/MedFMC_fewshot_baseline) |
| 364 | **Colonoscopic** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 152例, 3类胃肠病变分类 | [官网](https://www.depeca.uah.es/colonoscopy_dataset/) |
| 365 | **SERV-CT** | 内窥镜 | 2D | 2D，内窥镜，16例，覆盖内窥镜视野大部分区域(>80%)的完整验证集 | [官网](https://www.ucl.ac.uk/interventional-surgical-sciences/weiss-open-research/weiss-open-data-server/serv-ct) |
| 366 | **BraTS2023-PED** | 头颈部 | 3D MRI | 3D MRI, 228例, 3类婴儿脑胶质瘤分割 | [官网](https://www.synapse.org/#!Synapse:syn51156910/wiki/622461) |
| 367 | **ATLAS** | 腹部 | MICCAI2023) (3D CE-MRI | MICCAI2023) (3D CE-MRI, 90例, 2类肝脏和肝脏肿瘤分割 | [官网](https://atlas-challenge.u-bourgogne.fr/dataset) |
| 368 | **Messidor-2** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 1748例, 2类糖尿病视网膜病变分类 | [官网](https://www.adcis.net/en/third-party/messidor2/) |
| 369 | **Med-Halt 医学幻觉测评数据集** | 文本数据集 | QA | QA, 58K | — |
| 370 | **MedICaT** | 多模态数据集 | VQA | VQA, 217060 例 QA 对 | [官网](https://github.com/allenai/medicat) |
| 371 | **Linguistic Meaning** | 多模态数据集 | 语义解码 | 语义解码，功能性磁共振成像（fMRI）和语义向量表示 | [官网](https://osf.io/crwz7/) |
| 372 | **Kvasir-SEG** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 1160例, 1类结肠息肉分割 | [官网](https://github.com/DebeshJha/2020-MediaEval-Medico-polyp-segmentation/tree/master) |
| 373 | **CRASS12** | 胸部 | 2D X-Ray | 2D X-Ray, 284例, 1类锁骨分割 | [官网](https://crass.grand-challenge.org/Details/) |
| 374 | **MICCAI 2024 CARE WHS++** | 心脏 | 3D | 3D，CT/CTA,MRI，206例，1类全心脏分割 | [官网](http://zmic.org.cn/care_2024/track4/) |
| 375 | **RFMiD 2.0** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 3200例, 45类眼部疾病分类 | [官网](https://riadd.grand-challenge.org/Home/) |
| 376 | **LiveQA** | 文本数据集 | QA | QA, 634例 QA 对 | [官网](https://github.com/abachaa/LiveQA_MedicalTask_TREC2017) |
| 377 | **MSseg08** | 头颈部 | 3D | 3D，MRI，51例，1类多发性硬化病变分割 | [官网](http://www.ia.unc.edu/MSseg/index.html) |
| 378 | **MICCAI 2024 LISA 2024 Task2** | 头颈部 | 3D | 3D，MRI，63例，2类海马体分割 | [官网](https://www.synapse.org/Synapse:syn55249552/wiki/) |
| 379 | **PSVFM** | 内窥镜 | 2D | 2D，胎儿镜，483例，胎盘血管分割 | [官网](https://www.ucl.ac.uk/interventional-surgical-sciences/weiss-open-research/weiss-open-data-server/fetoscopy-placenta-data) |
| 380 | **CoNIC2022** | 显微成像 | 2D 病理图像 | 2D 病理图像, 4981例, 7类组织内的细胞核分割 | [官网](https://conic-challenge.grand-challenge.org/) |
| 381 | **FARFUM-RoP** | 眼科 | 2D | 2D，眼底彩照，1533例，早产儿视网膜病变分类 | [官网](https://www.nature.com/articles/s41597-024-03897-7) |
| 382 | **VerSe** | 骨头 | 3D CT | 3D CT, 374例, 26类脊椎分割 | [官网](https://github.com/anjany/verse) |
| 383 | **Cholec80 胆囊切除手术视频数据集** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 370,168例, 14类手术动作类型和器械分类 | [官网](https://github.com/CAMMA-public/TF-Cholec80) |
| 384 | **BraTS-TCGA-GBM** | 头颈部 | 3D MRI | 3D MRI, 102例, 3类多形性胶质母细胞瘤分割 | [官网](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-gbm/) |
| 385 | **CT-RATE 胸部 CT 及其放射学诊断报告** | 多模态数据集 | caption | caption, 47149 例 | [官网](https://huggingface.co/datasets/ibrahimhamamci/CT-RATE) |
| 386 | **ARCH** | 显微成像 | 2D | 2D，病理学图像，11816例，病理图像和相应的文本描述 | [官网](https://warwick.ac.uk/fac/cross_fac/tia/data/arch) |
| 387 | **HRF** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 45例, 1类眼底血管分割 | [官网](https://www5.cs.fau.de/research/data/fundus-images/) |
| 388 | **HVSMR** | 心脏 | 3D | 3D，MR，19例，4类面向3D心血管磁共振影像中心脏解剖结构分割 | [官网](https://segchd.csail.mit.edu/) |
| 389 | **BioASQ-QA** | 文本数据集 | QA | QA, 4719例 | — |
| 390 | **COVIDGR** | 胸部 | 2D X-Ray | 2D X-Ray, 852例, 2类肺炎分类 | [官网](https://github.com/ari-dasci/covidgr) |
| 391 | **CholecT45 Dataset** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 90489例, 128类胆囊切除手术动作识别 | [官网](https://github.com/CAMMA-public/cholect45) |
| 392 | **MICCAI-24 SurgVU24** | 内窥镜 | 2D | 2D，内窥镜，280例，机器人辅助内窥镜手术中的手术器械及手术阶段识别 | [官网](https://surgvu24.grand-challenge.org/) |
| 393 | **AbdomenCT-1K** | 腹部 | 3D CT | 3D CT, 1112例, 4类腹部器官分割 | [官网](https://github.com/JunMa11/AbdomenCT-1K) |
| 394 | **PathMMU** | 多模态数据集 | VQA | VQA，33,428个问答对以及24,067张病理图像 | [官网](https://pathmmu-benchmark.github.io/#/) |
| 395 | **ChestX-Det10** | 胸部 | 2D | 2D，X-ray，10类，3,543例，10种常见的胸部疾病或异常分类 | — |
| 396 | **OCT 2017** | 眼科 | 2D OCT | 2D OCT, 35126例, 4 类眼部疾病分类 | [官网](https://github.com/aishangcengloua/OCT_Classification?tab=readme-ov-file) |
| 397 | **SZ-CXR** | 胸部 | 2D | 2D，X-ray，566例，肺结核诊断的肺部X-ray分类/分割 | [官网](https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen) |
| 398 | **HaN-Seg** | 头颈部 | 3D CT&MRI | 3D CT&MRI, 42例, 30类头颈部风险器官分割 | [官网](https://han-seg2023.grand-challenge.org/) |
| 399 | **PanSegData** | 腹部 | 3D | 3D，MRI，767例，1类胰腺分割 | — |
| 400 | **jsrt-directions X** | 胸部 | 2D | 2D，X-ray，988，4类正确判断X光片的方向 | [官网](http://imgcom.jsrt.or.jp/minijsrtdb/) |
| 401 | **EAV** | 多模态数据集 | 情绪识别 | 情绪识别，涵盖了 30 通道脑电图（EEG）、音频和视频记录数据 | [官网](https://github.com/nubcico/EAV) |
| 402 | **PMC-Patients** | 文本数据集 | IR/CBR | IR/CBR, 167K | — |
| 403 | **FLARE 2022** | 腹部 | 3D CT | 3D CT, 2300例, 13类腹部器官分割 | [官网](https://flare22.grand-challenge.org/Dataset/) |
| 404 | **LiTS** | 腹部 | 3D CT | 3D CT, 201例, 2类肝脏和肝脏肿瘤分割 | [官网](https://competitions.codalab.org/competitions/17094) |
| 405 | **OLIVES** | 眼科 | 2D | 2D，眼底彩照，412例，糖尿病视网膜病分类 | [官网](https://github.com/olivesgatech/OLIVES_Dataset) |
| 406 | **COVID-19-CT SCAN IMAGES** | 胸部 | 2D CT | 2D CT, 1400例, 2类肺炎分类 | [官网](https://tianchi.aliyun.com/dataset/93666) |
| 407 | **Kidney Stone Images with Bounding Box Annotations** | 腹部 | 2D | 2D，CT，1300例，检测方法识别肾结石 | [官网](https://www.kaggle.com/datasets/safurahajiheidari/kidney-stone-images) |
| 408 | **Medical-CXR-VQA** | 胸部 | 3D | 3D，X-Ray，780014例，专注于胸部X光图像的LLMs | [官网](https://github.com/Holipori/Medical-CXR-VQA) |
| 409 | **MICCAI 2024 CARE MyoPS++** | 心脏 | 3D | 3D，CMR，2741例，5类心肌病灶分割 | [官网](http://zmic.org.cn/care_2024/track4/) |
| 410 | **Robotic Instrument Segmentation 手术机器人手术设备分割** | 内窥镜 | 2D 内窥镜 | 2D 内窥镜, 3000例, 4类手术器械分割 | [官网](https://endovissub2017-roboticinstrumentsegmentation.grand-challenge.org/) |
| 411 | **Shenzhen chest X-ray set** | 胸部 | 2D X-Ray | 2D X-Ray, 662例, 2类肺结核分类 | [官网](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#tuberculosis-image-data-sets) |
| 412 | **iSeg** | 头颈部 | 3D MRI | 3D MRI, 13例, 3类脑组织分割 | [官网](https://iseg2019.web.unc.edu/) |
| 413 | **NasalSeg Dataset** | 头颈部 | 3D | 3D，CT，130例，鼻腔和鼻旁窦分割 | — |
| 414 | **MedFM Pathological Tumor Tissue Classification** | 显微成像 | Colon) 2023 结肠镜病理切片肿瘤组织分类数据集 (2D 病理图像 | Colon) 2023 结肠镜病理切片肿瘤组织分类数据集 (2D 病理图像, 10009例, 2类结肠肿瘤分类 | — |
| 415 | **Teeth3DS** | 头颈部 | 3D IOS | 3D IOS, 1800例, 32类牙齿分割 | [官网](https://github.com/DCBIA-OrthoLab/3DTeethSeg22_challenge) |
| 416 | **MIMIC-CXR 胸部X光放射学报告** | 多模态数据集 | Report Generation | Report Generation, 377,110 张 X 光图像 | — |
| 417 | **FACE** | 多模态数据集 | 情绪识别 | 情绪识别，情绪计算的精细化大规模脑电图（EEG），专注于捕捉情绪状态的细微变化 | [官网](https://www.synapse.org/Synapse:syn50614194/wiki/620378) |
| 418 | **MedFM ChestDR 2023 胸部X射线胸部疾病筛查数据集** | 胸部 | 2D X-Ray | 2D X-Ray, 4848例, 19类胸部疾病分类 | [官网](https://github.com/wllfore/MedFMC_fewshot_baseline) |
| 419 | **StructSeg 2019 Task3 肺癌放射治疗危及器官分割** | 胸部 | 3D CT | 3D CT, 50例, 6类左右肺,脊髓, 心脏, 食道，气管分割 | [官网](https://structseg2019.grand-challenge.org/) |
| 420 | **GAMMA** | 眼科 | 2D | 2D，眼底彩照，2类，100例，多模态青光眼分割 | — |
| 421 | **MM2024 MMIS-2024 Task1** | 头颈部 | 3D | 3D，MRI T1 T2 T1c，100例，1类肿瘤分割 | [官网](https://mmis2024.com/) |
| 422 | **CMtMedQA** | 文本数据集 | QA | QA, 70K | [官网](https://github.com/jind11/MedQA) |
| 423 | **MedQA** | 文本数据集 | QA | QA, 61,097 例 QA 对 | [官网](https://github.com/jind11/MedQA) |
| 424 | **SPIDER** | 骨头 | 3D MR | 3D MR, 544例, 19类脊椎，椎间盘，脊柱管分割 | [官网](https://spider.grand-challenge.org/) |
| 425 | **NeurIPS 2022 Cell Seg** | 显微成像 | 2D 显微成像 | 2D 显微成像, 3022例, 1类细胞实例分割 | [官网](https://neurips22-cellseg.grand-challenge.org/) |
| 426 | **ROCOV2** | 多模态数据集 | caption | caption, 80080 例 image-caption 对 | [官网](https://zenodo.org/records/8333645) |
| 427 | **HRF Image Quality Assessment Dataset** | 眼科 | 2D | 2D，眼底图像，36例，2类眼部疾病分类 | [官网](https://www5.cs.fau.de/research/data/fundus-images/) |
| 428 | **DRiDB** | 眼科 | 2D 眼底图像 | 2D 眼底图像, 648例, 3类糖尿病视网膜病变分类 | [官网](https://ipg.fer.hr/ipg/resources/image_database) |
| 429 | **AbdomenAtlas 3.0** | 腹部 | Caption | Caption, QA, VQA，4500例，腹部 CT 图像-文本配对 | [官网](https://atlas-challenge.u-bourgogne.fr/dataset) |
| 430 | **EBHI-Seg** | 腹部 | 2D | 2D，pathology，4456例，6类结直肠图像分割 | [官网](https://figshare.com/articles/dataset/EBHI-SEG/21540159/1) |
| 431 | **Scientific Data \\| BRAX** | 胸部 | 2D | 2D，X-ray， 24, 959个案例，19, 351个病人，40, 967个图片，巴西人胸部X光 | [官网](https://physionet.org/content/brax/1.1.0/) |

## 🧬 疾病数据集（按疾病大类，点击展开）

> 来源：[QianfangHub/awesome-disease-datasets](https://github.com/QianfangHub/awesome-disease-datasets)（按医学疾病大类编排，含表格/影像/文本/基因等多模态）。

| 疾病大类 | 条目数 | 文件 |
| :--- | ---: | :--- |
| 动物疾病 | 0 | [disease/animal-diseases.md](disease/animal-diseases.md) |
| 心血管疾病 | 0 | [disease/cardiovascular-diseases.md](disease/cardiovascular-diseases.md) |
| 化学诱发性障碍 | 76 | [disease/chemically-induced-disorders.md](disease/chemically-induced-disorders.md) |
| 先天、遗传与新生儿疾病及异常 | 0 | [disease/congenital-hereditary-and-neonatal-diseases-and-abnormalities.md](disease/congenital-hereditary-and-neonatal-diseases-and-abnormalities.md) |
| 消化系统疾病 | 100 | [disease/digestive-system-diseases.md](disease/digestive-system-diseases.md) |
| 环境因素所致疾病 | 8 | [disease/disorders-of-environmental-origin.md](disease/disorders-of-environmental-origin.md) |
| 内分泌系统疾病 | 100 | [disease/endocrine-system-diseases.md](disease/endocrine-system-diseases.md) |
| 眼病 | 100 | [disease/eye-diseases.md](disease/eye-diseases.md) |
| 血液与淋巴系统疾病 | 100 | [disease/hemic-and-lymphatic-diseases.md](disease/hemic-and-lymphatic-diseases.md) |
| 免疫系统疾病 | 100 | [disease/immune-system-diseases.md](disease/immune-system-diseases.md) |
| 感染 | 100 | [disease/infections.md](disease/infections.md) |
| 肌肉骨骼疾病 | 100 | [disease/musculoskeletal-diseases.md](disease/musculoskeletal-diseases.md) |
| 肿瘤 | 100 | [disease/neoplasms.md](disease/neoplasms.md) |
| 神经系统疾病 | 100 | [disease/nervous-system-diseases.md](disease/nervous-system-diseases.md) |
| 营养与代谢疾病 | 0 | [disease/nutritional-and-metabolic-diseases.md](disease/nutritional-and-metabolic-diseases.md) |
| 职业病 | 0 | [disease/occupational-diseases.md](disease/occupational-diseases.md) |
| 耳鼻咽喉疾病 | 100 | [disease/otorhinolaryngologic-diseases.md](disease/otorhinolaryngologic-diseases.md) |
| 病理状况、体征与症状 | 0 | [disease/pathological-conditions-signs-and-symptoms.md](disease/pathological-conditions-signs-and-symptoms.md) |
| 呼吸道疾病 | 100 | [disease/respiratory-tract-diseases.md](disease/respiratory-tract-diseases.md) |
| 皮肤与结缔组织疾病 | 100 | [disease/skin-and-connective-tissue-diseases.md](disease/skin-and-connective-tissue-diseases.md) |
| 口颌系统疾病 | 100 | [disease/stomatognathic-diseases.md](disease/stomatognathic-diseases.md) |
| 泌尿生殖系统疾病 | 100 | [disease/urogenital-diseases.md](disease/urogenital-diseases.md) |
| 创伤与损伤 | 100 | [disease/wounds-and-injuries.md](disease/wounds-and-injuries.md) |
| **合计** | **1584** | |

**主要来源平台**：figshare(418) · NCBI(145) · Mendeley(75) · Zenodo(57) · PhysioNet(52) · Kaggle(45) · GitHub(42) · HAIDatas(29) · TCIA / cBioPortal / FinnGen / GDC / Synapse 等

## 🧪 医学图像分割 · 基准与数据集专题

> 医学图像分割领域的基准与数据集专题整理（48 篇）。

| 专题 | 一句话 |
| :--- | :--- |
| AFA-MI：对抗特征攻击数据增强的多器官 CT 分割 | — |
| AbdomenAtlas 2.0：从真实与合成数据规模化肿瘤分割（ICCV 2025） | — |
| AbdomenAtlas-8K：三周标注 8000+ CT 体积的多器官分割数据集 | — |
| AbdomenCT-1K：腹部器官分割是已解问题吗？（TPAMI 2021/2022） | AbdomenCT-1K（>1,000 例 CT、12 个医疗中心、多期相/多厂商/多疾病），含肝/肾/脾/胰四个大样本子集与四类子基准 |
| Adversariality Miner：扩散驱动的原生对抗合成增强医学分割泛化（CVPR 2026） | — |
| AortaSeg24：CTA 主动脉分支与分区多类分割挑战（Medical Image Analysis 2026） | AortaSeg24（100 个 CTA 体积，专家标注 23 个主动脉分支与 SVS/STS 分区；MICCAI 2024 挑战） |
| Author's Reply to MoNuSAC2020：对挑战评测质疑的回应与勘误（TMI 2022） | MoNuSAC2020 挑战（ISBI 2020）：最大的手工标注多类多实例病理分割数据集之一——46,000 个手注细胞核、71 名患者、31 家医院、4 种癌症类型（肾/肺/前列腺/乳腺）、4 种细胞类型（上皮、淋巴细胞、中性粒细胞、巨噬细胞）；评测指标为 panoptic quality（PQ） |
| Benchmarking：医学图像分割深度架构公平基准评测（TMI 2022） | 9 个数据集（覆盖 X-ray、CT、MRI；单/多类分割；单/多模态输入；具体名单见原文 [TBC]） |
| CC-Metrics：多实例场景的逐连通域分割评估协议（AAAI 2025） | AutoPET（全身 FDG PET/CT 转移灶，每患者平均约 10 个病灶）、HECKTOR（头颈肿瘤 PET/CT，平均 2 个病灶/图像） |
| CoNIC Challenge：推动细胞核检测、分割、分类与计数前沿（MedIA 2023） | CoNIC 挑战数据集（基于结肠组织的最大规模同类数据集：1,658 张全切片图像 WSI，覆盖核检测、分割、分类（19 类核/细胞类型）与计数） |
| Comments on MoNuSAC2020：挑战官方排名指标的复算分析与勘误（IEEE TMI 2022） | MoNuSAC 2020 挑战（ISBI 2020 卫星赛事；多器官核分割与五类核分类）公开代码、top-5 预测可视化与挑战数据 |
| DeepVCT：深度虚拟临床试验评估致密组织分割（Pattern Recognition 2024） | 2,010 个解剖学乳腺模型（大规模仿真数据）；DBT 采集几何仿真投影；0.1/0.2/0.5mm 三种重建平面间隔；评估 nnU-Net 的 volumetric breast density (VBD) 分割 |
| EMADS：完整成年果蝇大脑胞体分割基准（CVPR 2023） | — |
| ETHSeg：X 射线垃圾检视的 Amodal（无遮挡）实例分割网络与真实数据集（CVPR 2022） | WIXRayNet（自建 X 射线垃圾图片数据集：5,038 张图、30,881 个垃圾物品，含类别、物体框、实例级掩码标注） |
| FeTA-2021：胎儿脑组织标注与分割挑战结果（Medical Image Analysis 2023） | FeTA Dataset（胎儿脑 MRI 重建集，7 类组织：外部脑脊液、灰质、白质、脑室、小脑、脑干、深部灰质） |
| FullBody-AnatomyCT：知识聚合与解剖指南自动生成全身 CT 解剖分割数据集 | — |
| HECKTOR 2021：FDG-PET/CT 头颈肿瘤分割与结局预测挑战（MedIA 2023） | 头颈癌 FDG-PET/CT：训练 224 例（5 个中心），测试 101 例（2 个中心）；Task 1 原发灶分割（DSC + 中位 HD95 的 Borda 排序）、Task 2/3 PFS 预测（C-index，Task 3 用专家轮廓） |
| IMed-361M：交互式医学图像分割基准数据集与基线（CVPR 2025） | — |
| Learn2Synth：用超梯度学习最优数据合成（大脑图像分割）（ICCV 2025） | — |
| LiTS：肝脏与肝肿瘤分割基准（MedIA 2023） | LiTS 数据集：131 例训练 CT 体积、70 例未见测试 CT（原发+转移瘤，病灶大小/外观多样，七家医院与科研机构联合制作） |
| Localise2Segment：先定位裁剪再分割的危及器官分割精度研究 | — |
| MDViT：小样本医学图像分割数据集的多域视觉 Transformer | — |
| MIMO：多指标、多器官医学分割模型的评估框架 | — |
| MRGen：面向代表不足 MRI 模态的分割数据引擎（ICCV 2025） | — |
| MitoEM 挑战：大规模 3D 线粒体实例分割进展与挑战（IEEE TMI 2023） | MitoEM（两个大规模 3D EM 体积：人皮层组织 MitoEM-H、大鼠皮层组织 MitoEM-R，配合 IEEE-ISBI 2021 挑战） |
| MouseGAN++：无监督解耦+对比表征的小鼠脑多模态 MRI 合成与结构分割（TMI 2022） | 小鼠脑 MR 多模态（T1w/T2w，多模态数据缺失场景；数据集名称 [TBC]，摘要未点名） |
| MultiOrgan-LearningParadigms：标注稀缺下的多器官分割学习范式综述 | — |
| MultiOrganSeg-Survey：深度学习多器官分割系统综述 | — |
| MultiTalent：多数据集联合训练的医学图像分割（基础模型） | — |
| MyoPS：三序列心肌病理分割基准（Medical Image Analysis 2023） | MyoPS 挑战数据：45 个配对、预对齐的 CMR 图像（三个序列）；数据与评估工具经其主页注册后公开（www.sdspeople.fudan.edu.cn/zhuangxiahai/0/myops20/） |
| OAR-Ensemble：CT 序列的多器官分割集成方法 | — |
| Open Panoramic Segmentation：开放词汇/开放视场的全景分割（ECCV 2024） | 源域为针孔（pinhole）自然图像；目标域全景数据集 WildPASS、Stanford2D3D、Matterport3D |
| PENGWIN 2024：骨盆骨折分割挑战基准总结（IEEE TMI 2026） | PENGWIN 挑战数据集：多中心采集 150 例骨盆骨折 CT；用 DeepDRR 生成了 48,600 张逼真模拟 X-ray（DRR，覆盖虚拟 C 臂角度与手术器械遮挡） |
| SAM-12Datasets：SAM 在 12 个医学数据集上的计算机视觉基准评测 | — |
| SDF-ScoreSeg：基于符号距离函数的分数生成式医学分割模型 | — |
| SF-VD：标签高效的视频扩散数据增强，用于心脏荧光透视导丝分割（AAAI 2025） | 心脏荧光透视（cardiac fluoroscopy）导丝视频数据集（具体来源/名称论文未公布，[TBC]） |
| SGSGAN：3D 分割引导的风格化 GAN PET 合成（TMI 2022） | 自建全身体 PET 数据集——105 例患者（北京协和医院，PoleStar m660 PET/CT，0.1 mCi/kg 18F-FDG）；低剂量以 DRF=6 从原始计数数据合成，共 210 组低剂量-全剂量对；ROI 取肝、脑、肾、膀胱 |
| Siamese-Diffusion：噪声一致性孪生扩散的医学图像合成与分割（CVPR 2025） | — |
| StyleGAN-Aug：StyleGAN 驱动的数据增强提升 CT 分割精度 | — |
| SyntheticTumors：无标注的肝脏肿瘤分割（合成肿瘤）（CVPR 2023） | — |
| UKBOB：十亿 MRI 标注掩码——可泛化 3D 医学图像分割（ICCV 2025） | — |
| USE-Evaluator：不确定/小体积/空参考标注下分割模型的评测指标研究（MedIA 2023） | 内部卒中（stroke）数据集、BraTS 2019、Spinal Cord（脊髓）公开数据集 |
| VGD：价值引导扩散，生成高可用性医学分割合成数据（AAAI 2026） | ACDC（心脏 MRI）、Synapse（多器官 CT）、Polyps（CVC-ClinicDB & Kvasir）——三个医学分割基准；作对比的医学扩散模型有 FairDiff、Siamese-Diff、DiffBoost 等 |
| Waymo Open Dataset: Panoramic Video Panoptic Segmentation（ECCV 2022 Workshops） | Waymo Open Dataset 子集：28 个语义类别、2,860 个时间序列、5 个车载相机、三个地理区域，共 100k 标注相机图像 |
| 儿童肾性管状结构 ceCT 分割：评估、比较与改进（Medical Image Analysis 2023） | 私有儿童病理数据集：79 例腹部内脏 ceCT（动静脉期）；另含成人管状结构分割评估文献集（数据集名 [TBC]） |
| 合成光学相干断层血管造影：无需人工标注的视网膜血管分割（TMI 2024） | 3 个公开 OCTA 数据集（评估用；摘要未点名，详见正文）+ 论文发布的大规模合成 OCTA 数据集 |
| 合成数据可用性：GAN 合成心脏 MRI 提升分割鲁棒性（Medical Image Analysis 2023） | 短轴 CMR（short-axis cardiac MR）多站点/多厂商数据（心腔分割，域外泛化评测；具体数据集名摘要未列出 [TBC]） |
| 胎儿脑 MRI 自动分割与生物测量进展：FeTA 2024 挑战赛（Medical Image Analysis 2026） | FeTA 2024 challenge（多中心胎儿脑 MRI）；新增 0.55T 低场 MRI 测试集与 biometry 估计任务 |

## 🔖 其他来源

- [openmedlab/Awesome-Medical-Dataset](https://github.com/openmedlab/Awesome-Medical-Dataset)
- [QianfangHub/awesome-disease-datasets](https://github.com/QianfangHub/awesome-disease-datasets)
- [QianfangHub/top100-medical-datasets](https://github.com/QianfangHub/top100-medical-datasets)
- 知乎《医学数据集介绍文章汇总》[通用医疗GMAI](https://www.zhihu.com/people/gmai)

## 📄 许可

本仓库的**整理内容**（分类结构、说明文字、索引）采用 MIT 许可；**各数据集本身**的版权与许可归其官方所有，请以官方页面为准。

## 📬 联系合作

如需合作请联系：

<img src="assets/contact-qr.png" alt="微信·如需合作请联系" width="220">
