# Awesome Face & Diffusion Papers

**语言 / Language:** [简体中文](README.md) | [**English**](README.en.md)

> A curated list of **diffusion-model** works related to **human faces**: paper / code / project demos, covering face editing, swapping & reenactment, restoration / super-resolution / relighting, 3D face & avatar generation, ID-preserving portrait customization, talking-head animation, personalization & controllable synthesis, and forgery detection / security / bias analysis.
>
> Table fields: **Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub**.
>
> The list is **updated periodically**. Contributions and corrections are welcome.

---

## Contents

- [1. Face Editing & Attribute Manipulation](#1-face-editing--attribute-manipulation)
- [2. Swapping / Reenactment / Animation](#2-swapping--reenactment--animation)
- [3. Restoration / Super-Resolution / Relighting](#3-restoration--super-resolution--relighting)
- [4. 3D Face & Avatar Generation](#4-3d-face--avatar-generation)
- [5. Personalization & Controllable Synthesis](#5-personalization--controllable-synthesis)
- [6. Detection / Security / Bias](#6-detection--security--bias)
- [7. ID-Preserving & Personalized Portrait](#7-id-preserving--personalized-portrait)
- [8. Talking-Head & Audio-Driven Animation](#8-talking-head--audio-driven-animation)

---

## 1. Face Editing & Attribute Manipulation

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2023 | CVPR | DiffusionRig | Learns personalized priors for facial appearance (light/expression/pose) editing | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2304.06711.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=adobe-research/diffusion-rig)](https://github.com/adobe-research/diffusion-rig) |
| 2023 | CVPR | DiffusionDisentanglement | Uncovers the disentanglement capability in text-to-image diffusion for attribute editing | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Uncovering_the_Disentanglement_Capability_in_Text-to-Image_Diffusion_Models_CVPR_2023_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=UCSBNLP-Chang/DiffusionDisentanglement)](https://github.com/UCSBNLP-Chang/DiffusionDisentanglement) |
| 2023 | ICLR | Asyrp | Reveals a semantic latent space (h-space) in diffusion models for attribute editing | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2210.10960.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://kwonminki.github.io/Asyrp/) |  |
| 2023 | WACV | SDG | Semantic diffusion guidance (image/text) for controllable synthesis without retraining | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/WACV2023/papers/Liu_More_Control_for_Free_Image_Synthesis_With_Semantic_Diffusion_Guidance_WACV_2023_paper.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](http://xh-liu.github.io/sdg/) |  |
| 2023 | SIGGRAPH | Blended Latent Diffusion | Local text-driven image editing via blending in latent space | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2206.02779.pdf) |  |  |
| 2023 | Arxiv | PAIR-Diffusion | Object-level image editing with structure-and-appearance paired diffusion | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2303.17546.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Picsart-AI-Research/PAIR-Diffusion)](https://github.com/Picsart-AI-Research/PAIR-Diffusion) |
| 2022 | CVPR | DiffusionCLIP | Text-guided diffusion for robust image/face manipulation via CLIP-loss fine-tuning | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_DiffusionCLIP_Text-Guided_Diffusion_Models_for_Robust_Image_Manipulation_CVPR_2022_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=gwang-kim/DiffusionCLIP)](https://github.com/gwang-kim/DiffusionCLIP) |

## 2. Swapping / Reenactment / Animation

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2026 | WACV | VFace | Training-free, plug-and-play diffusion video face swapping: frequency-spectrum attention interpolation + target structure guidance + flow-guided temporal smoothing | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2602.07835) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Sanoojan/VFace)](https://github.com/Sanoojan/VFace) |
| 2025 | WACV | REFace | Reframes swapping as self-supervised inpainting; multi-step DDIM + CLIP disentanglement for high-fidelity, efficient swaps | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2409.07269) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Sanoojan/REFace)](https://github.com/Sanoojan/REFace) |
| 2023 | CVPR | DiffSwap | High-fidelity, controllable face swapping via 3D-aware masked diffusion | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_DiffSwap_High-Fidelity_and_Controllable_Face_Swapping_via_3D-Aware_Masked_Diffusion_CVPR_2023_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=zengbohan0217/FADM)](https://github.com/zengbohan0217/FADM) |
| 2023 | CVPR | LFDM | Latent flow diffusion for conditional image-to-video generation (face driving) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2303.13744) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=nihaomiao/CVPR23_LFDM)](https://github.com/nihaomiao/CVPR23_LFDM) |
| 2023 | CVPR | Diffusion Video Autoencoders | Disentangled video encoding for temporally consistent face video editing | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Diffusion_Video_Autoencoders_Toward_Temporally_Consistent_Face_Video_Editing_via_CVPR_2023_paper.pdf) |  |  |
| 2023 | CVPRW | FADM | Face animation with an attribute-guided diffusion model | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023W/GCV/papers/Zeng_Face_Animation_With_an_Attribute-Guided_Diffusion_Model_CVPRW_2023_paper.pdf) |  |  |
| 2023 | Arxiv | Laughing Matters | Laughing-face video generation using diffusion models | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2305.08854.pdf) |  |  |

## 3. Restoration / Super-Resolution / Relighting

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2025 | ICCV | DynFaceRestore | Dynamic blur-level mapping + step/region-wise guidance to balance fidelity and quality in blind face restoration | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/ICCV2025/papers/Do_DynFaceRestore_Balancing_Fidelity_and_Quality_in_Diffusion-Guided_Blind_Face_Restoration_ICCV_2025_paper.pdf) |  |  |
| 2025 | CVPR | OSDFace | One-step diffusion for efficient blind face restoration | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2411.17163) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=jkwang28/OSDFace)](https://github.com/jkwang28/OSDFace) |
| 2024 | ECCV | DiffBIR | Generative diffusion prior for blind image/face restoration | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2308.15070) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=XPixelGroup/DiffBIR)](https://github.com/XPixelGroup/DiffBIR) |
| 2024 | TPAMI | DifFace | Blind face restoration via diffused error contraction; only an L1-trained backbone, no complex losses | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://doi.org/10.1109/tpami.2024.3432651) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=zsyOAOA/DifFace)](https://github.com/zsyOAOA/DifFace) |
| 2023 | ICCV | DiFaReli | Single-image face relighting with diffusion | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2304.09479.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://diffusion-face-relighting.github.io/) |  |
| 2023 | CVPR | DR2 | Diffusion-based robust degradation remover for blind face restoration | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_DR2_Diffusion-Based_Robust_Degradation_Remover_for_Blind_Face_Restoration_CVPR_2023_paper.pdf) |  |  |
| 2022 | CVPR | RePaint | Free-form mask inpainting via DDPM sampling | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=andreas128/RePaint)](https://github.com/andreas128/RePaint) |
| 2022 | TPAMI | SR3 | Image super-resolution via iterative refinement (diffusion) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9887996) |  |  |
| 2022 | Journal | SRDiff | Single-image super-resolution with a diffusion probabilistic model | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2104.14951.pdf) |  |  |

## 4. 3D Face & Avatar Generation

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2024 | CVPR | DiffPortrait3D | Zero-shot controllable diffusion for 3D-consistent novel-view synthesis from a single portrait (keeps ID & expression) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2312.13016) | [![link](https://img.shields.io/badge/Website-9cf)](https://freedomgu.github.io/DiffPortrait3D/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=FreedomGu/DiffPortrait3D)](https://github.com/FreedomGu/DiffPortrait3D) |
| 2023 | CVPR | RODIN | A generative diffusion model for sculpting 3D digital avatars | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_RODIN_A_Generative_Model_for_Sculpting_3D_Digital_Avatars_Using_CVPR_2023_paper.pdf) |  |  |
| 2023 | CVPR | Score Jacobian Chaining | Lifts pretrained 2D diffusion models for 3D generation | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Score_Jacobian_Chaining_Lifting_Pretrained_2D_Diffusion_Models_for_3D_CVPR_2023_paper.pdf) |  |  |
| 2023 | ICCV | Chupa | Carves 3D clothed humans from skinned priors using 2D diffusion | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2305.11870.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://snuvclab.github.io/chupa/) |  |
| 2023 | Arxiv | Adding 3D Geometry Control | Adds 3D geometry control to diffusion models | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2306.08103.pdf) |  |  |

## 5. Personalization & Controllable Synthesis

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2023 | CVPR | Custom Diffusion | Multi-concept customization of text-to-image diffusion | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2023/papers/Kumari_Multi-Concept_Customization_of_Text-to-Image_Diffusion_CVPR_2023_paper.pdf) |  |  |
| 2023 | SIGGRAPH | E4T | An encoder for fast personalization of text-to-image models | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2302.12228.pdf) | [![link](https://img.shields.io/badge/Website-9cf)](https://tuning-encoder.github.io/) |  |
| 2022 | NeurIPS | Diffusion Priors | Diffusion models as plug-and-play priors | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2206.09012.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=AlexGraikos/diffusion_priors)](https://github.com/AlexGraikos/diffusion_priors) |
| 2022 | Arxiv | SDM | Semantic image synthesis via diffusion models (segmentation-driven) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2207.00050.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=WeilunWang/semantic-diffusion-model)](https://github.com/WeilunWang/semantic-diffusion-model) |
| 2022 | Arxiv | Pyramidal DDPM | Pyramidal denoising diffusion probabilistic models | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2208.01864.pdf) |  |  |

## 6. Detection / Security / Bias

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2025 | CVPR | Forensics Adapter | Adds an adapter to CLIP to learn face-swap blending boundaries for generalizable face forgery detection | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://doi.org/10.1109/cvpr52734.2025.01789) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=OUCVAS/ForensicsAdapter)](https://github.com/OUCVAS/ForensicsAdapter) |
| 2025 | CVPR | DFD-FCG | Facial Component Guidance + CLIP side-network decoder for generalizable video Deepfake detection | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2025/papers/Han_Towards_More_General_Video-based_Deepfake_Detection_through_Facial_Component_Guided_CVPR_2025_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=aiiu-lab/DFD-FCG)](https://github.com/aiiu-lab/DFD-FCG) |
| 2024 | CVPR | FatFormer | Forgery-aware adaptive Transformer (image + frequency + language alignment) for generalizable synthetic/Deepfake detection | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://doi.org/10.1109/cvpr52733.2024.01024) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Michel-liu/FatFormer)](https://github.com/Michel-liu/FatFormer) |
| 2024 | CVPR | NPR | Captures up-sampling artifacts via Neighboring Pixel Relationships for generalizable Deepfake detection | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://openaccess.thecvf.com/content/CVPR2024/papers/Tan_Rethinking_the_Up-Sampling_Operations_in_CNN-based_Generative_Network_for_Generalizable_CVPR_2024_paper.pdf) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=chuangchuangtan/NPR-DeepfakeDetection)](https://github.com/chuangchuangtan/NPR-DeepfakeDetection) |
| 2023 | IEEE TIFS | Diffusion-PAD | Image-diffusion-augmented robust face presentation attack detection | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10149339) |  |  |
| 2023 | NeurIPS | Stable Bias | Analyzing societal representations (bias) in diffusion models | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2303.11408) |  |  |
| 2022 | AAAI | Patch Diffusion | A general module for face manipulation detection | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://ojs.aaai.org/index.php/AAAI/article/view/20233) |  |  |
| 2022 | Arxiv | Generated Faces in the Wild | Quantitative comparison of faces from Stable Diffusion / Midjourney / DALL·E 2 | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/pdf/2210.00586.pdf) |  |  |

## 7. ID-Preserving & Personalized Portrait

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2024 | Arxiv | InstantID | Zero-shot identity-preserving generation; plug-and-play IdentityNet (strong semantic + weak spatial) for SD/SDXL | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2401.07519) | [![link](https://img.shields.io/badge/Website-9cf)](https://instantid.github.io/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=InstantID/InstantID)](https://github.com/InstantID/InstantID) |
| 2024 | CVPR | PhotoMaker | Stacked ID embedding to customize realistic, editable portraits from one/few reference photos | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2312.04461) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=TencentARC/PhotoMaker)](https://github.com/TencentARC/PhotoMaker) |
| 2024 | NeurIPS | PuLID | Contrastive alignment + a Lightning branch for pure, fast ID customization with high fidelity & editability | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2404.16022) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=ToTheBeginning/PuLID)](https://github.com/ToTheBeginning/PuLID) |
| 2023 | Arxiv | IP-Adapter | Decoupled cross-attention image-prompt adapter; FaceID variant for face personalization | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2308.06721) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=tencent-ailab/IP-Adapter)](https://github.com/tencent-ailab/IP-Adapter) |

## 8. Talking-Head & Audio-Driven Animation

| Year | Venue | Method | Problem & Core Idea | Paper | Project | GitHub |
| --- | --- | --- | --- | --- | --- | --- |
| 2024 | ECCV | EMO | Audio2Video diffusion; weak conditions for end-to-end, highly expressive talking-head videos | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2402.17485) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=HumanAIGC/EMO)](https://github.com/HumanAIGC/EMO) |
| 2024 | NeurIPS | VASA-1 | Real-time high-quality talking faces from a single image + audio (latent DiT) | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2404.10667) | [![link](https://img.shields.io/badge/Website-9cf)](https://www.microsoft.com/en-us/research/project/vasa-1/) |  |
| 2024 | Arxiv | AniPortrait | Audio → 3D landmarks → diffusion for photorealistic portrait animation & face reenactment | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2403.17694) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Zejun-Yang/AniPortrait)](https://github.com/Zejun-Yang/AniPortrait) |
| 2024 | Arxiv | Hallo | Hierarchical audio-driven portrait animation; hierarchical cross-attention aligning audio with lip/expression/pose | [![paper](https://img.shields.io/badge/Paper-b31b1b)](https://arxiv.org/abs/2406.08801) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=fudan-generative-vision/hallo)](https://github.com/fudan-generative-vision/hallo) |

---
