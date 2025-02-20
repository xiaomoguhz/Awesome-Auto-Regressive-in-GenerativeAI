# Awesome Auto-regressive in GenerativeAI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome auto-regressive papers in generative AI, inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

### 3D Generation
<details open>
<summary>3D shape generation</summary>

- [AR-1-to-3: Single Image to Consistent 3D Object Generation via Next-View Prediction](), Zhang et al., arXiv 2025
- [MARS: Mesh AutoRegressive Model for 3D Shape Detailization](https://arxiv.org/abs/2502.11390), Gao et al., arXiv 2025
- [Nautilus: Locality-aware Autoencoder for Scalable Mesh Generation](https://arxiv.org/abs/2501.14317), Wang et al., arXiv 2025 | [Project](https://nautilusmeshgen.github.io/) | [Code](https://github.com/yuxuan-w/nautilus)
- [TAR3D: Creating High-Quality 3D Assets via Next-Part Prediction](https://arxiv.org/abs/2412.16919), Zhang et al., arXiv 2024 | [Code](https://github.com/HVision-NKU/TAR3D)
- [3D representation in 512-Byte: Variational tokenizer is the key for autoregressive 3D generation](https://arxiv.org/abs/2412.02202), Zhang et al., arXiv 2024 | [Project](https://sparse-mvs-2.github.io/VAT.IO/) | [Code](https://github.com/sparse-mvs-2/VAT)
- [3D-WAG: Hierarchical Wavelet-Guided Autoregressive Generation for High-Fidelity 3D Shapes](https://arxiv.org/abs/2411.19037), Medi et al., arXiv 2024 
- [Scaling Mesh Generation via Compressive Tokenization](https://arxiv.org/abs/2411.07025), Weng et al., arXiv 2024 | [Project](https://whaohan.github.io/bpt/) | [Code](https://github.com/whaohan/bpt)
- [EdgeRunner: Auto-regressive Auto-encoder for Artistic Mesh Generation](https://arxiv.org/abs/2409.18114), Tang et al., arXiv 2024 | [Project](https://research.nvidia.com/labs/dir/edgerunner/) | [Code](https://github.com/NVlabs/EdgeRunner)
- [MeshAnything V2: Artist-Created Mesh Generation with Adjacent Mesh Tokenization](https://arxiv.org/abs/2408.02555), Chen et al., arXiv 2024 | [Project](https://buaacyw.github.io/meshanything-v2/) | [Code](https://github.com/buaacyw/MeshAnythingV2) | [Video]()
- [MeshAnything: Artist-Created Mesh Generation with Autoregressive Transformers](https://arxiv.org/abs/2406.10163), Chen et al., arXiv 2024 | [Project](https://buaacyw.github.io/mesh-anything/) | [Code](https://github.com/buaacyw/MeshAnything)
- [MeshXL: Neural Coordinate Field for Generative 3D Foundation Models](https://arxiv.org/abs/2405.20853), Chen et al., arXiv 2024 | [Project](https://meshxl.github.io/) | [Code](https://github.com/OpenMeshLab/MeshXL)
- [Pivotmesh: Generic 3d mesh generation via pivot vertices guidance.](https://arxiv.org/abs/2405.16890), Weng et al., arXiv 2024 | [Project](https://whaohan.github.io/pivotmesh/) | [Code](https://github.com/whaohan/pivotmesh)
- [MeshGPT: Generating Triangle Meshes with Decoder-Only Transformers](https://arxiv.org/abs/2311.15475), Siddiqui et al., CVPR 2024 Highlight | [Project](https://nihalsid.github.io/mesh-gpt/) | [Code](https://github.com/audi/MeshGPT) | [Video](https://www.youtube.com/watch?v=UV90O1_69_o)
- [Autoregressive 3D Shape Generation via Canonical Mapping](https://arxiv.org/abs/2204.01955), Cheng et al., ECCV 2022 | [Code](https://github.com/AnjieCheng/CanonicalVAE)
- [ShapeFormer: Transformer-based Shape Completion via Sparse Representation](https://arxiv.org/abs/2201.10326), Yan et al., CVPR 2022 | [Project](https://shapeformer.github.io/) | [Code](https://github.com/qheldiv/shapeformer)
- [AutoSDF: Shape Priors for 3D Completion, Reconstruction and Generation](https://arxiv.org/abs/2203.09516), Mittal et al., CVPR 2022 | [Project](https://yccyenchicheng.github.io/AutoSDF/) | [Code](https://github.com/yccyenchicheng/AutoSDF/)
- [PolyGen: An Autoregressive Generative Model of 3D Meshes](https://arxiv.org/abs/2002.10880), Nash et al., ICML 2020 | [Code](https://github.com/google-deepmind/deepmind-research/tree/master/polygen)

</details>

<details open>
<summary>Articulated object generation</summary>

- [MeshArt: Generating Articulated Meshes with Structure-guided Transformers](https://arxiv.org/abs/2412.11596), Gao et al., arXiv 2024 | [Project](https://daoyig.github.io/Mesh_Art/) | [Code](https://github.com/Seed3D/MagicArticulate) | [Video](https://www.youtube.com/embed/0XaHFbmb_FQ?si=xKZOdhQDNFMmUmm5) | [Data](https://syncandshare.lrz.de/getlink/fi4Moni3SkJJeFA8HAEZdR/release_v1)
</details>

<details open>
<summary>Automatic rigging</summary>

- [MagicArticulate: Make Your 3D Models Articulation-Ready](https://arxiv.org/abs/2502.12135), Song et al., arXiv 2025 | [Project](https://chaoyuesong.github.io/MagicArticulate/) | [Code](https://github.com/Seed3D/MagicArticulate) | [Video](https://www.youtube.com/watch?v=eJP_VR4cVnk) | [Data](https://huggingface.co/datasets/chaoyue7/Articulation-XL2.0)
- [RigAnything: Template-Free Autoregressive Rigging for Diverse 3D Assets](https://arxiv.org/abs/2502.09615), Liu et al., arXiv 2025 | [Project](https://www.liuisabella.com/RigAnything/) | [Video](https://www.liuisabella.com/RigAnything/#full_video)
</details>

<details open>
<summary>Motion generation</summary>

- [ScaMo: Exploring the Scaling Law in Autoregressive Motion Generation Model](https://arxiv.org/abs/2412.14559), Lu et al., arXiv 2024 | [Project](https://shunlinlu.github.io/ScaMo/) | [Code](https://github.com/shunlinlu/ScaMo_code)
- [Synergy and Synchrony in Couple Dances](https://arxiv.org/abs/2409.04440), Maluleke et al., arXiv 2024 | [Project](https://von31.github.io/synNsync/)
- [BAMM: Bidirectional Autoregressive Motion Model](https://arxiv.org/abs/2403.19435), Pinyoanuntapong et al., ECCV 2024 | [Project](https://exitudio.github.io/BAMM-page/) | [Code](https://github.com/exitudio/BAMM/)
- [MoMask: Generative Masked Modeling of 3D Human Motions](https://arxiv.org/abs/2312.00063), Guo et al., CVPR 2024 | [Project](https://ericguo5513.github.io/momask/) | [Code](https://github.com/EricGuo5513/momask-codes) | [Demo](https://huggingface.co/spaces/MeYourHint/MoMask)
- [HumanTOMATO: Text-aligned Whole-body Motion Generation](https://arxiv.org/abs/2310.12978), Lu et al., ICML 2024 | [Project](https://lhchen.top/HumanTOMATO/) | [Code](https://github.com/IDEA-Research/HumanTOMATO)
- [MotionGPT: Human Motion as Foreign Language](https://arxiv.org/abs/2306.14795), Jiang et al., NeurIPS 2023 | [Project](https://motion-gpt.github.io/) | [Code](https://github.com/OpenMotionLab/MotionGPT) | [Demo](https://huggingface.co/spaces/OpenMotionLab/MotionGPT)
- [T2M-GPT: Generating Human Motion from Textual Descriptions with Discrete Representations](https://arxiv.org/abs/2301.06052), Zhang et al., CVPR 2023 | [Project](https://mael-zys.github.io/T2M-GPT/) | [Code](https://github.com/Mael-zys/T2M-GPT) | [Demo](https://huggingface.co/spaces/vumichien/Generate_human_motion)
- [TM2T: Stochastical and Tokenized Modeling for the Reciprocal Generation of 3D Human Motions and Texts](https://arxiv.org/abs/2207.01696), Guo et al., ECCV 2022 | [Project](https://ericguo5513.github.io/TM2T/) | [Code](https://github.com/EricGuo5513/TM2T)
</details>

<details open>
<summary>4D generation</summary>

- [AR4D: Autoregressive 4D Generation from Monocular Videos](https://arxiv.org/abs/2501.01722), Zhu et al., arXiv 2025 | [Project](https://hanxinzhu-lab.github.io/AR4D/)
</details>

<details open>
<summary>Garment generation</summary>

- [DressCode: Autoregressively Sewing and Generating Garments from Text Guidance](https://arxiv.org/abs/2401.16465), He et al., SIGGRAPH 2024 | [Project](https://ihe-kaii.github.io/DressCode/) | [Code](https://github.com/IHe-KaiI/DressCode) | [Video](https://www.youtube.com/watch?v=ofFyJBKL-Qg&feature=youtu.be)
</details>

<details open>
<summary>CAD generation</summary>

- [SkexGen: Autoregressive Generation of CAD Construction Sequences with Disentangled Codebooks](https://arxiv.org/abs/2207.04632), Xu et al., ICML 2022 | [Project](https://samxuxiang.github.io/skexgen/) | [Code](https://github.com/samxuxiang/SkexGen) | [Video](https://www.youtube.com/watch?v=j5LB7yMwNVE)
</details>

### Image generation

<details open>
<summary>Image generation</summary>

- [Parallelized Autoregressive Visual Generation](https://arxiv.org/abs/2412.15119), Wang et al., arXiv 2024 | [Project](https://epiphqny.github.io/PAR-project/) | [Code](https://github.com/Epiphqny/PAR)
- [RandAR: Decoder-only Autoregressive Visual Generation in Random Orders](https://arxiv.org/abs/2412.01827), Pang et al., arXiv 2024 | [Project](https://rand-ar.github.io/) | [Code](https://github.com/ziqipang/RandAR)
- [Randomized Autoregressive Visual Generation](https://arxiv.org/abs/2411.00776), Yu et al., arXiv 2024 | [Project](https://yucornetto.github.io/projects/rar.html) | [Code](https://github.com/bytedance/1d-tokenizer) | [Demo](https://huggingface.co/spaces/yucornetto/RAR)
- [Fluid: Scaling Autoregressive Text-to-image Generative Models with Continuous Tokens](https://arxiv.org/abs/2410.13863), Fan et al., arXiv 2024
- [Customize Your Visual Autoregressive Recipe with Set Autoregressive Modeling](https://arxiv.org/abs/2410.10511), Liu et al., arXiv 2024 | [Project](https://poppuppy.github.io/sar.github.io/) | [Code](https://github.com/poppuppy/SAR)
- [Autoregressive Image Generation without Vector Quantization](https://arxiv.org/abs/2406.11838), Li et al., arXiv 2024 | [Code](https://github.com/LTH14/mar)
- [Autoregressive Model Beats Diffusion: Llama for Scalable Image Generation](https://arxiv.org/abs/2406.06525), Sun et al., arXiv 2024 | [Project](https://peizesun.github.io/llamagen/) | [Code](https://github.com/FoundationVision/LlamaGen)
- [Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction](https://arxiv.org/abs/2404.02905), Tian et al., NeruIPS 2024 Best Paper | [Code](https://github.com/FoundationVision/VAR)
- [Muse: Text-To-Image Generation via Masked Generative Transformers](https://arxiv.org/abs/2301.00704), Chang et al., PMLR 2023 | [Project](https://muse-model.github.io/)
- [Scaling Autoregressive Models for Content-Rich Text-to-Image Generation](https://arxiv.org/abs/2206.10789), Yu et al., TMLR 2022 
- [Autoregressive Image Generation using Residual Quantization](https://arxiv.org/abs/2203.01941), Lee et al., CVPR 2022 | [Code](https://github.com/kakaobrain/rq-vae-transformer)
- [Vector-quantized Image Modeling with Improved VQGAN](https://arxiv.org/abs/2110.04627), Yu et al., ICLR 2022 | [Project](https://research.google/blog/vector-quantized-image-modeling-with-improved-vqgan/)
- [Taming Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2012.09841), Esser et al., CVPR 2021 | [Code](https://github.com/CompVis/taming-transformers)
- [Generative Pretraining from Pixels](https://cdn.openai.com/papers/Generative_Pretraining_from_Pixels_V2.pdf), Chen et al., ICML 2020 | [Code](https://github.com/openai/image-gpt)
- [Parallel Multiscale Autoregressive Density Estimation](https://arxiv.org/abs/1703.03664), Reed et al., ICML 2017
- [Conditional Image Generation with PixelCNN Decoders](https://arxiv.org/abs/1606.05328), Van den Oord et al., NIPS 2016 | [Code](https://github.com/anantzoid/Conditional-PixelCNN-decoder)
</details>



### Video generation

<details open>
<summary>Video generation</summary>

- [Autoregressive Video Generation without Vector Quantization](https://arxiv.org/abs/2412.14169), Deng et al., arXiv 2024 | [Code](https://github.com/baaivision/NOVA)
- [DiCoDe: Diffusion-Compressed Deep Tokens for Autoregressive Video Generation with Language Models](https://arxiv.org/abs/2412.04446), Li et al., arXiv 2024 | [Project](https://liyizhuo.com/DiCoDe/)
- [Progressive Autoregressive Video Diffusion Models](https://arxiv.org/abs/2410.08151), Xie et al., arXiv 2024 | [Project](https://desaixie.github.io/pa-vdm/) | [Code](https://github.com/desaixie/pa_vdm)
- [Loong: Generating Minute-level Long Videos with Autoregressive Language Models](https://arxiv.org/abs/2410.02757), Wang et al., arXiv 2024 | [Project](https://epiphqny.github.io/Loong-video/)
- [ARLON: Boosting Diffusion Transformers With Autoregressive Models for Long Video Generation](https://arxiv.org/abs/2410.20502), Li et al., arXiv 2024 | [Project](https://arlont2v.github.io/)
- [LARP: Tokenizing Videos with a Learned Autoregressive Generative Prior](https://arxiv.org/abs/2410.21264), Wang et al., arXiv 2024 | [Project](https://hywang66.github.io/larp/) | [Code](https://github.com/hywang66/LARP/)
- [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125), Kondratyuk et al., ICML 2024 | [Project](https://sites.research.google/videopoet/)
- [ART•V: Auto-Regressive Text-to-Video Generation with Diffusion Models](https://arxiv.org/abs/2311.18834), Weng et al., arXiv 2023 | [Project](https://warranweng.github.io/art.v/)
- [Transframer: Arbitrary Frame Prediction with Generative Models](https://arxiv.org/abs/2203.09494), Nash et al., TMLR 2023 | [Code](https://github.com/lucidrains/transframer-pytorch)
- [CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers](https://arxiv.org/abs/2205.15868), Hong et al., ICLR 2023 | [Code](https://github.com/THUDM/CogVideo) 
- [VideoGPT: Video Generation using VQ-VAE and Transformers](https://arxiv.org/abs/2104.10157), Yan et al., arXiv 2021 | [Project](https://wilsonyan.com/videogpt/index.html) | [Code](https://github.com/wilson1yan/VideoGPT)

</details>



