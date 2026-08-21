# Awesome Face & Diffusion 论文列表

**语言 / Language:** [**简体中文**](README.md) | [English](README.en.md)

> 系统搜集与整理 **人脸 (Face) 相关的扩散模型 (Diffusion Models)** 论文 / 代码 / Project Demo，涵盖人脸编辑、换脸与重演、修复超分与重打光、3D 人脸与数字人、身份保持定制、说话人像动画、个性化可控生成、伪造检测与安全偏见等方向。
>
> 表格字段：**年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub**。
>
> 本列表会根据时间**定期更新**，方便查阅参考。欢迎补充与勘误。

---

## 目录

- [1. 人脸编辑与属性操控 (Face Editing & Attribute Manipulation)](#1-人脸编辑与属性操控-face-editing--attribute-manipulation)
- [2. 人脸交换 / 重演 / 动画 (Swapping / Reenactment / Animation)](#2-人脸交换--重演--动画-swapping--reenactment--animation)
- [3. 人脸修复 / 超分 / 重打光 (Restoration / Super-Resolution / Relighting)](#3-人脸修复--超分--重打光-restoration--super-resolution--relighting)
- [4. 3D 人脸与数字人生成 (3D Face & Avatar Generation)](#4-3d-人脸与数字人生成-3d-face--avatar-generation)
- [5. 个性化与可控生成 (Personalization & Controllable Synthesis)](#5-个性化与可控生成-personalization--controllable-synthesis)
- [6. 伪造检测 / 安全 / 偏见分析 (Detection / Security / Bias)](#6-伪造检测--安全--偏见分析-detection--security--bias)
- [7. 身份保持与人像定制生成 (ID-Preserving & Personalized Portrait)](#7-身份保持与人像定制生成-id-preserving--personalized-portrait)
- [8. 说话人像与音频驱动动画 (Talking-Head & Audio-Driven Animation)](#8-说话人像与音频驱动动画-talking-head--audio-driven-animation)

---

## 1. 人脸编辑与属性操控 (Face Editing & Attribute Manipulation)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2023 | CVPR | DiffusionRig | 学习个性化先验，做人脸外观(光照/表情/姿态)编辑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2304.06711.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=adobe-research/diffusion-rig)](https://github.com/adobe-research/diffusion-rig) |
| 2023 | CVPR | DiffusionDisentanglement | 揭示文生图扩散隐空间的解耦能力，实现属性编辑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Uncovering_the_Disentanglement_Capability_in_Text-to-Image_Diffusion_Models_CVPR_2023_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=UCSBNLP-Chang/DiffusionDisentanglement)](https://github.com/UCSBNLP-Chang/DiffusionDisentanglement) |
| 2023 | ICLR | Asyrp | 发现扩散模型的语义隐空间(h-space)，沿其做属性编辑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2210.10960.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://kwonminki.github.io/Asyrp/) |  |
| 2023 | WACV | SDG | 语义扩散引导(图/文)，无需重训即可控合成 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/WACV2023/papers/Liu_More_Control_for_Free_Image_Synthesis_With_Semantic_Diffusion_Guidance_WACV_2023_paper.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](http://xh-liu.github.io/sdg/) |  |
| 2023 | SIGGRAPH | Blended Latent Diffusion | 隐空间融合，做局部文本驱动图像编辑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2206.02779.pdf) |  |  |
| 2023 | Arxiv | PAIR-Diffusion | 结构 + 外观解耦的对象级图像编辑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2303.17546.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Picsart-AI-Research/PAIR-Diffusion)](https://github.com/Picsart-AI-Research/PAIR-Diffusion) |
| 2022 | CVPR | DiffusionCLIP | 文本引导扩散做鲁棒图像/人脸操控，CLIP 损失微调 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_DiffusionCLIP_Text-Guided_Diffusion_Models_for_Robust_Image_Manipulation_CVPR_2022_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=gwang-kim/DiffusionCLIP)](https://github.com/gwang-kim/DiffusionCLIP) |

## 2. 人脸交换 / 重演 / 动画 (Swapping / Reenactment / Animation)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2026 | WACV | VFace | 免训练、即插即用的扩散视频换脸：频谱注意力插值 + 目标结构引导 + 光流时序平滑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2602.07835) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Sanoojan/VFace)](https://github.com/Sanoojan/VFace) |
| 2025 | WACV | REFace | 把换脸重构为自监督 inpainting，多步 DDIM + CLIP 特征解耦做高保真高效换脸 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2409.07269) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Sanoojan/REFace)](https://github.com/Sanoojan/REFace) |
| 2023 | CVPR | DiffSwap | 3D 感知掩码扩散，做高保真且可控的换脸 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_DiffSwap_High-Fidelity_and_Controllable_Face_Swapping_via_3D-Aware_Masked_Diffusion_CVPR_2023_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=zengbohan0217/FADM)](https://github.com/zengbohan0217/FADM) |
| 2023 | CVPR | LFDM | 隐流扩散做条件图像到视频生成，可驱动人脸 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2303.13744) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=nihaomiao/CVPR23_LFDM)](https://github.com/nihaomiao/CVPR23_LFDM) |
| 2023 | CVPR | Diffusion Video Autoencoders | 解耦视频编码，实现时序一致的人脸视频编辑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Diffusion_Video_Autoencoders_Toward_Temporally_Consistent_Face_Video_Editing_via_CVPR_2023_paper.pdf) |  |  |
| 2023 | CVPRW | FADM | 属性引导的扩散模型做人脸动画 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023W/GCV/papers/Zeng_Face_Animation_With_an_Attribute-Guided_Diffusion_Model_CVPRW_2023_paper.pdf) |  |  |
| 2023 | Arxiv | Laughing Matters | 用扩散模型生成自然的笑脸视频 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2305.08854.pdf) |  |  |

## 3. 人脸修复 / 超分 / 重打光 (Restoration / Super-Resolution / Relighting)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2025 | ICCV | DynFaceRestore | 动态模糊级映射 + 分步区域引导，平衡盲人脸修复的保真与质量 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/ICCV2025/papers/Do_DynFaceRestore_Balancing_Fidelity_and_Quality_in_Diffusion-Guided_Blind_Face_Restoration_ICCV_2025_paper.pdf) |  |  |
| 2025 | CVPR | OSDFace | 一步扩散做高效盲人脸修复 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2411.17163) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=jkwang28/OSDFace)](https://github.com/jkwang28/OSDFace) |
| 2024 | ECCV | DiffBIR | 生成式扩散先验做盲图像/人脸修复 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2308.15070) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=XPixelGroup/DiffBIR)](https://github.com/XPixelGroup/DiffBIR) |
| 2024 | TPAMI | DifFace | 扩散误差收缩做盲人脸修复，仅需 L1 训练的修复骨干、无需复杂损失 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://doi.org/10.1109/tpami.2024.3432651) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=zsyOAOA/DifFace)](https://github.com/zsyOAOA/DifFace) |
| 2023 | ICCV | DiFaReli | 扩散模型做单图人脸重打光 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2304.09479.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://diffusion-face-relighting.github.io/) |  |
| 2023 | CVPR | DR2 | 扩散退化移除器，做盲人脸修复 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_DR2_Diffusion-Based_Robust_Degradation_Remover_for_Blind_Face_Restoration_CVPR_2023_paper.pdf) |  |  |
| 2022 | CVPR | RePaint | DDPM 采样做任意掩码的图像修复(inpainting) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=andreas128/RePaint)](https://github.com/andreas128/RePaint) |
| 2022 | TPAMI | SR3 | 迭代精化的扩散图像超分 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9887996) |  |  |
| 2022 | Journal | SRDiff | 单图超分的扩散概率模型 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2104.14951.pdf) |  |  |

## 4. 3D 人脸与数字人生成 (3D Face & Avatar Generation)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2024 | CVPR | DiffPortrait3D | 零样本可控扩散，从单张人像合成 3D 一致的新视角(保 ID 与表情) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2312.13016) | [![link](https://img.shields.io/badge/Website-9cf)](https://freedomgu.github.io/DiffPortrait3D/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=FreedomGu/DiffPortrait3D)](https://github.com/FreedomGu/DiffPortrait3D) |
| 2023 | CVPR | RODIN | 生成式扩散模型雕刻 3D 数字人 avatar | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_RODIN_A_Generative_Model_for_Sculpting_3D_Digital_Avatars_Using_CVPR_2023_paper.pdf) |  |  |
| 2023 | CVPR | Score Jacobian Chaining | 提升预训练 2D 扩散模型做 3D 生成 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Score_Jacobian_Chaining_Lifting_Pretrained_2D_Diffusion_Models_for_3D_CVPR_2023_paper.pdf) |  |  |
| 2023 | ICCV | Chupa | 用 2D 扩散从蒙皮先验雕刻 3D 着装人体 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2305.11870.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://snuvclab.github.io/chupa/) |  |
| 2023 | Arxiv | Adding 3D Geometry Control | 给扩散模型注入 3D 几何控制 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2306.08103.pdf) |  |  |

## 5. 个性化与可控生成 (Personalization & Controllable Synthesis)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2023 | CVPR | Custom Diffusion | 文生图扩散的多概念定制化 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Kumari_Multi-Concept_Customization_of_Text-to-Image_Diffusion_CVPR_2023_paper.pdf) |  |  |
| 2023 | SIGGRAPH | E4T | 编码器实现文生图模型的快速个性化 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2302.12228.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://tuning-encoder.github.io/) |  |
| 2022 | NeurIPS | Diffusion Priors | 将扩散模型作为即插即用先验 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2206.09012.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=AlexGraikos/diffusion_priors)](https://github.com/AlexGraikos/diffusion_priors) |
| 2022 | Arxiv | SDM | 语义分割图驱动的图像合成 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2207.00050.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=WeilunWang/semantic-diffusion-model)](https://github.com/WeilunWang/semantic-diffusion-model) |
| 2022 | Arxiv | Pyramidal DDPM | 金字塔式去噪扩散概率模型 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2208.01864.pdf) |  |  |

## 6. 伪造检测 / 安全 / 偏见分析 (Detection / Security / Bias)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2025 | CVPR | Forensics Adapter | 给 CLIP 加适配器学习换脸混合边界，通用人脸伪造检测 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://doi.org/10.1109/cvpr52734.2025.01789) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=OUCVAS/ForensicsAdapter)](https://github.com/OUCVAS/ForensicsAdapter) |
| 2025 | CVPR | DFD-FCG | 面部组件引导 + CLIP 侧网络解码器，做通用视频 Deepfake 检测 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2025/papers/Han_Towards_More_General_Video-based_Deepfake_Detection_through_Facial_Component_Guided_CVPR_2025_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=aiiu-lab/DFD-FCG)](https://github.com/aiiu-lab/DFD-FCG) |
| 2024 | CVPR | FatFormer | forgery-aware 自适应 Transformer(图像 + 频域 + 语言对齐)，通用合成图/Deepfake 检测 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://doi.org/10.1109/cvpr52733.2024.01024) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Michel-liu/FatFormer)](https://github.com/Michel-liu/FatFormer) |
| 2024 | CVPR | NPR | 用邻域像素关系捕捉上采样伪影，做通用 Deepfake 检测 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2024/papers/Tan_Rethinking_the_Up-Sampling_Operations_in_CNN-based_Generative_Network_for_Generalizable_CVPR_2024_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=chuangchuangtan/NPR-DeepfakeDetection)](https://github.com/chuangchuangtan/NPR-DeepfakeDetection) |
| 2023 | IEEE TIFS | Diffusion-PAD | 图像扩散增强的鲁棒人脸呈现攻击检测(活体) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10149339) |  |  |
| 2023 | NeurIPS | Stable Bias | 分析扩散模型中的社会表征偏见 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2303.11408) |  |  |
| 2022 | AAAI | Patch Diffusion | 通用模块做人脸篡改检测 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://ojs.aaai.org/index.php/AAAI/article/view/20233) |  |  |
| 2022 | Arxiv | Generated Faces in the Wild | 定量比较 Stable Diffusion / Midjourney / DALL·E 2 生成人脸 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2210.00586.pdf) |  |  |

## 7. 身份保持与人像定制生成 (ID-Preserving & Personalized Portrait)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2024 | Arxiv | InstantID | 零样本身份保持生成，IdentityNet(强语义 + 弱空间)即插即用于 SD/SDXL | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2401.07519) | [![link](https://img.shields.io/badge/Website-9cf)](https://instantid.github.io/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=InstantID/InstantID)](https://github.com/InstantID/InstantID) |
| 2024 | CVPR | PhotoMaker | 堆叠 ID 嵌入，用单/多张参考照片定制真实且可编辑的人像 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2312.04461) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=TencentARC/PhotoMaker)](https://github.com/TencentARC/PhotoMaker) |
| 2024 | NeurIPS | PuLID | 对比对齐 + Lightning 分支，纯净且快速的 ID 定制，兼顾保真与可编辑 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2404.16022) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=ToTheBeginning/PuLID)](https://github.com/ToTheBeginning/PuLID) |
| 2023 | Arxiv | IP-Adapter | 解耦交叉注意力的图像提示适配器，FaceID 变体做人脸个性化 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2308.06721) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=tencent-ailab/IP-Adapter)](https://github.com/tencent-ailab/IP-Adapter) |

## 8. 说话人像与音频驱动动画 (Talking-Head & Audio-Driven Animation)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 论文 | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2024 | ECCV | EMO | Audio2Video 扩散，弱条件端到端生成表情丰富的说话人像视频 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2402.17485) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=HumanAIGC/EMO)](https://github.com/HumanAIGC/EMO) |
| 2024 | NeurIPS | VASA-1 | 单图 + 音频实时生成高质量对话人脸(隐空间 DiT) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2404.10667) | [![link](https://img.shields.io/badge/Website-9cf)](https://www.microsoft.com/en-us/research/project/vasa-1/) |  |
| 2024 | Arxiv | AniPortrait | 音频 → 3D landmark → 扩散，生成照片级人像动画与人脸重演 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2403.17694) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Zejun-Yang/AniPortrait)](https://github.com/Zejun-Yang/AniPortrait) |
| 2024 | Arxiv | Hallo | 层次化音频驱动的人像动画，分层跨注意力对齐音频与嘴型/表情/姿态 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2406.08801) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=fudan-generative-vision/hallo)](https://github.com/fudan-generative-vision/hallo) |

---
