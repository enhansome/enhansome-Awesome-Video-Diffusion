# Awesome Video Diffusion with stars

A curated list of recent diffusion models for video generation, editing, restoration, understanding, nerf, etc.

<p align="center">
<img src="https://makeavideo.studio/assets/overview.webp" width="240px"/>
<img src="https://makeavideo.studio/assets/A_teddy_bear_painting_a_portrait.webp" width="240px"/>    
</p>

<p align="center">
<img src="https://tuneavideo.github.io/assets/teaser.gif" width="480px"/>  
</p>

<p align="center">
<img src="https://github.com/ChenyangQiQi/FateZero/blob/main/docs/gif_results/17_car_posche_01_concat_result.gif?raw=true" width="240px"/>
<img src="https://github.com/ChenyangQiQi/FateZero/blob/main/docs/gif_results/3_sunflower_vangogh_conat_result.gif?raw=true" width="240px"/>    
</p>

<p align="center">
(Source: <a href="https://makeavideo.studio/">Make-A-Video</a>, <a href="https://tuneavideo.github.io/">Tune-A-Video</a>, and <a href="https://fate-zero-edit.github.io/">Fate/Zero</a>.)
</p>

## Table of Contents <!-- omit in toc -->

* [Open-source Toolboxes and Foundation Models](#open-source-toolboxes-and-foundation-models)
* [Evaluation Benchmarks and Metrics](#evaluation-benchmarks-and-metrics)
* [Commercial Product](#commercial-product)
* [Video Generation](#video-generation)
* [Efficient Video Generation](#efficient-video-generation)
* [Controllable Video Generation](#controllable-video-generation)
* [Character Customization](#character-customization)
* [Motion Customization](#motion-customization)
* [Long Video / Film Generation](#long-video--film-generation)
* [Video Generation with 3D/Physical Prior](#video-generation-with-3dphysical-prior)
* [Video Editing](#video-editing)
* [Human or Subject Motion](#human-or-subject-motion)
* [Video Enhancement and Restoration](#video-enhancement-and-restoration)
* [Audio Synthesis for Video](#audio-synthesis-for-video)
* [Talking Head Generation](#talking-head-generation)
* [Reinforcement Learning for Video Generation](#reinforcement-learning-for-video-generation)
* [Policy Learning](#policy-learning)
* [Virtual Try-On](#virtual-try-on)
* [3D](#3d)
* [4D](#4d)
* [Game Generation](#game-generation)
* [AI Safety](#ai-safety)
* [Rendering with Virtual Engine](#rendering-with-virtual-engine)
* [Open-World Model](#open-world-model)
* [Video Understanding](#video-understanding)
* [Healthcare and Biology](#healthcare-and-biology)
* [Other Applications](#other-applications)
* [Code-rendered Video Generation](#code-rendered-video-generation)

### Open-source Toolboxes and Foundation Models

* [Diffusers (Text-to-video synthesis)](https://huggingface.co/docs/diffusers/main/en/api/pipelines/text_to_video#texttovideo-synthesis)\
  [![Star](https://img.shields.io/github/stars/huggingface/diffusers.svg?style=social\&label=Star)](https://github.com/huggingface/diffusers) ⭐ 34,428 | 🐛 1,387 | 🌐 Python | 📅 2026-09-02

* [Open-Sora](https://github.com/hpcaitech/Open-Sora) ⭐ 29,347 | 🐛 14 | 🌐 Python | 📅 2026-04-09\
  [![Star](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social\&label=Star)](https://github.com/hpcaitech/Open-Sora) ⭐ 29,347 | 🐛 14 | 🌐 Python | 📅 2026-04-09
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/hpcaitech/Open-Sora/blob/main/docs/zh_CN/README.md) ⭐ 29,347 | 🐛 14 | 🌐 Python | 📅 2026-04-09

* [Stable Video Diffusion](https://github.com/Stability-AI/generative-models) ⭐ 27,279 | 🐛 339 | 🌐 Python | 📅 2025-12-16\
  [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social\&label=Star)](https://github.com/Stability-AI/generative-models) ⭐ 27,279 | 🐛 339 | 🌐 Python | 📅 2025-12-16
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stability.ai/news/stable-video-diffusion-open-ai-video-model)

* [Wan-Video](https://github.com/Wan-Video/Wan2.1) ⭐ 16,926 | 🐛 379 | 🌐 Python | 📅 2026-03-05\
  [![Star](https://img.shields.io/github/stars/Wan-Video/Wan2.1.svg?style=social\&label=Star)](https://github.com/Wan-Video/Wan2.1) ⭐ 16,926 | 🐛 379 | 🌐 Python | 📅 2026-03-05
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wanxai.com/)

* [DiffSynth-Studio](https://github.com/modelscope/DiffSynth-Studio) ⭐ 13,039 | 🐛 565 | 🌐 Python | 📅 2026-09-01\
  [![Star](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.svg?style=social\&label=Star)](https://github.com/modelscope/DiffSynth-Studio) ⭐ 13,039 | 🐛 565 | 🌐 Python | 📅 2026-09-01

* [HunyuanVideo: A Systematic Framework For Large Video Generative Models](https://arxiv.org/abs/2412.03603)\
  [![Star](https://img.shields.io/github/stars/Tencent/HunyuanVideo.svg?style=social\&label=Star)](https://github.com/Tencent/HunyuanVideo) ⭐ 12,495 | 🐛 183 | 🌐 Python | 📅 2026-06-29

* [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) ⭐ 12,204 | 🐛 267 | 🌐 Python | 📅 2026-03-08\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/Open-Sora-Plan) ⭐ 12,204 | 🐛 267 | 🌐 Python | 📅 2026-03-08
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/PKU-YuanGroup/Open-Sora-Plan/blob/main/docs/Report-v1.0.0.md) ⭐ 12,204 | 🐛 267 | 🌐 Python | 📅 2026-03-08

* [Cosmos](https://github.com/NVIDIA/Cosmos) ⭐ 11,709 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2026-08-31\
  [![Star](https://img.shields.io/github/stars/NVIDIA/Cosmos.svg?style=social\&label=Star)](https://github.com/NVIDIA/Cosmos) ⭐ 11,709 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2026-08-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03575)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos1/)

* [LTX-Video](https://github.com/Lightricks/LTX-Video) ⭐ 10,925 | 🐛 99 | 🌐 Python | 📅 2026-01-05\
  [![Star](https://img.shields.io/github/stars/Lightricks/LTX-Video.svg?style=social\&label=Star)](https://github.com/Lightricks/LTX-Video) ⭐ 10,925 | 🐛 99 | 🌐 Python | 📅 2026-01-05

* [ModelScope (Text-to-video synthesis)](https://modelscope.cn/models/damo/text-to-video-synthesis/summary)\
  [![Star](https://img.shields.io/github/stars/modelscope/modelscope.svg?style=social\&label=Star)](https://github.com/modelscope/modelscope) ⭐ 9,120 | 🐛 18 | 🌐 Python | 📅 2026-09-01

* [SkyReels-V2](https://github.com/SkyworkAI/SkyReels-V2) ⭐ 7,488 | 🐛 351 | 🌐 Python | 📅 2026-01-29\
  [![Star](https://img.shields.io/github/stars/SkyworkAI/SkyReels-V2.svg?style=social\&label=Star)](https://github.com/SkyworkAI/SkyReels-V2) ⭐ 7,488 | 🐛 351 | 🌐 Python | 📅 2026-01-29
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.skyreels.ai/)

* [VideoCrafter: A Toolkit for Text-to-Video Generation and Editing](https://github.com/VideoCrafter/VideoCrafter) ⭐ 5,073 | 🐛 74 | 🌐 Python | 📅 2026-01-09\
  [![Star](https://img.shields.io/github/stars/VideoCrafter/VideoCrafter.svg?style=social\&label=Star)](https://github.com/VideoCrafter/VideoCrafter) ⭐ 5,073 | 🐛 74 | 🌐 Python | 📅 2026-01-09

* [FastVideo: A unified inference and post-training framework for accelerated video generation](https://github.com/hao-ai-lab/FastVideo) ⭐ 4,290 | 🐛 170 | 🌐 Python | 📅 2026-09-02
  [![Star](https://img.shields.io/github/stars/hao-ai-lab/FastVideo.svg?style=social\&label=Star)](https://github.com/hao-ai-lab/FastVideo) ⭐ 4,290 | 🐛 170 | 🌐 Python | 📅 2026-09-02

* [Mochi 1](https://www.genmo.ai/blog)\
  [![Star](https://img.shields.io/github/stars/genmoai/mochi.svg?style=social\&label=Star)](https://github.com/genmoai/mochi) ⭐ 3,722 | 🐛 59 | 🌐 Python | 📅 2025-11-14
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.genmo.ai/blog)

* [Pyramidal Flow Matching for Efficient Video Generative Modeling](https://pyramid-flow.github.io/)\
  [![Star](https://img.shields.io/github/stars/jy0205/Pyramid-Flow.svg?style=social\&label=Star)](https://github.com/jy0205/Pyramid-Flow) ⭐ 3,211 | 🐛 73 | 🌐 Python | 📅 2024-12-21
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pyramid-flow.github.io/)

* [Step-Video-T2V Technical Report: The Practice, Challenges, and Future of Video Foundation Model](https://arxiv.org/abs/2502.10248)\
  [![Star](https://img.shields.io/github/stars/stepfun-ai/Step-Video-T2V.svg?style=social\&label=Star)](https://github.com/stepfun-ai/Step-Video-T2V) ⭐ 3,188 | 🐛 47 | 🌐 Python | 📅 2025-03-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10248)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yuewen.cn/videos)

* [LightX2V: Light Video Generation Inference Framework](https://github.com/ModelTC/lightx2v) ⭐ 2,767 | 🐛 188 | 🌐 Python | 📅 2026-09-02\
  [![Star](https://img.shields.io/github/stars/ModelTC/lightx2v.svg?style=social\&label=Star)](https://github.com/ModelTC/lightx2v) ⭐ 2,767 | 🐛 188 | 🌐 Python | 📅 2026-09-02

* [Helios: Real Real-Time Long Video Generation Model](https://arxiv.org/abs/2603.04379)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Helios.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/Helios) ⭐ 2,128 | 🐛 42 | 🌐 Python | 📅 2026-08-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.04379)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/Helios-Page/)

* [text-to-video-synthesis-colab](https://github.com/camenduru/text-to-video-synthesis-colab) ⭐ 1,513 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2024-03-28\
  [![Star](https://img.shields.io/github/stars/camenduru/text-to-video-synthesis-colab.svg?style=social\&label=Star)](https://github.com/camenduru/text-to-video-synthesis-colab) ⭐ 1,513 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2024-03-28

* [Wunjo CE (Video Generation and Editing)](https://github.com/wladradchenko/wunjo.wladradchenko.ru) ⭐ 1,170 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-25\
  [![Star](https://img.shields.io/github/stars/wladradchenko/wunjo.wladradchenko.ru.svg?style=social\&label=Star)](https://github.com/wladradchenko/wunjo.wladradchenko.ru) ⭐ 1,170 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-25

* [Show-1](https://github.com/showlab/Show-1) ⭐ 1,148 | 🐛 16 | 🌐 Python | 📅 2025-09-13\
  [![Star](https://img.shields.io/github/stars/showlab/Show-1.svg?style=social\&label=Star)](https://github.com/showlab/Show-1) ⭐ 1,148 | 🐛 16 | 🌐 Python | 📅 2025-09-13
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Show-1/)

* [Allegro](https://rhymes.ai/blog-details/allegro-advanced-video-generation-model)\
  [![Star](https://img.shields.io/github/stars/rhymes-ai/Allegro.svg?style=social\&label=Star)](https://github.com/rhymes-ai/Allegro) ⭐ 1,136 | 🐛 20 | 🌐 Python | 📅 2025-02-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15458)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rhymes.ai/blog-details/allegro-advanced-video-generation-model)

* [Hotshot-XL (text-to-GIF)](https://github.com/hotshotco/Hotshot-XL) ⭐ 1,111 | 🐛 21 | 🌐 Python | 📅 2024-01-23\
  [![Star](https://img.shields.io/github/stars/hotshotco/Hotshot-XL.svg?style=social\&label=Star)](https://github.com/hotshotco/Hotshot-XL) ⭐ 1,111 | 🐛 21 | 🌐 Python | 📅 2024-01-23

* [Waver: Wave Your Way to Lifelike Video Generation](https://github.com/FoundationVision/Waver) ⭐ 952 | 🐛 18 | 📅 2025-08-27
  [![Star](https://img.shields.io/github/stars/FoundationVision/Waver.svg?style=social\&label=Star)](https://github.com/FoundationVision/Waver) ⭐ 952 | 🐛 18 | 📅 2025-08-27

* [VideoTuna](https://videoverses.github.io/videotuna/)\
  [![Star](https://img.shields.io/github/stars/VideoVerses/VideoTuna.svg?style=social\&label=Star)](https://github.com/VideoVerses/VideoTuna) ⭐ 553 | 🐛 13 | 🌐 Python | 📅 2025-09-15
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoverses.github.io/videotuna/)

* [Movie Gen: A Cast of Media Foundation Models](https://ai.meta.com/research/publications/movie-gen-a-cast-of-media-foundation-models/)\
  [![Star](https://img.shields.io/github/stars/facebookresearch/MovieGenBench.svg?style=social\&label=Star)](https://github.com/facebookresearch/MovieGenBench) ⭐ 442 | 🐛 1 | 📅 2025-03-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13720)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.youtube.com/playlist?list=PL86eLlsPNfyi27GSizYjinpYxp7gEl5K8)

* [Omni-Rewriter](https://github.com/WayneJin0918/Omni-Rewriter) ⭐ 84 | 🐛 0 | 🌐 Python | 📅 2026-08-20\
  [![Star](https://img.shields.io/github/stars/WayneJin0918/Omni-Rewriter.svg?style=social\&label=Star)](https://github.com/WayneJin0918/Omni-Rewriter) ⭐ 84 | 🐛 0 | 🌐 Python | 📅 2026-08-20
  [![Website](https://img.shields.io/badge/Website-9cf)](https://waynejin0918.github.io/Omni-Rewriter/)\
  Open agentic prompt-expansion harness for image/video generation (schema → validate → bounded repair → dialect render; H3/Seedance/Seedream/Qwen-Image). Expand ≠ generate.

* [NanoI2V](https://github.com/Shubham2376G/NanoI2V) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-07-18\
  [![Star](https://img.shields.io/github/stars/Shubham2376G/NanoI2V.svg?style=social\&label=Star)](https://github.com/Shubham2376G/NanoI2V) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-07-18
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shubham2376g.github.io/NanoI2V/)\
  A step-by-step teaching series for building an Image-to-Video model from scratch in PyTorch, covering 3D VAEs, DiT, Flow Matching, RoPE, and conditioning.

* [zeroscope\_v2](https://huggingface.co/cerspense/zeroscope_v2_576w)\
  [![Website](https://img.shields.io/badge/576w-9cf)](https://huggingface.co/cerspense/zeroscope_v2_576w)
  [![Website](https://img.shields.io/badge/XL-9cf)](https://huggingface.co/cerspense/zeroscope_v2_XL)

* [I2VGen-XL (image-to-video / video-to-video)](https://modelscope.cn/models/damo/Image-to-Video/summary)\
  [![Website](https://img.shields.io/badge/Website\(I2V\)-9cf)](https://modelscope.cn/models/damo/Image-to-Video/summary)
  [![Website](https://img.shields.io/badge/Website\(V2V\)-9cf)](https://modelscope.cn/models/damo/Video-to-Video/summary)

### Evaluation Benchmarks and Metrics

* [VBench-2.0: Advancing Video Generation Benchmark Suite for Intrinsic Faithfulness](https://arxiv.org/abs/2503.21755) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social\&label=Star)](https://github.com/Vchitect/VBench) ⭐ 1,757 | 🐛 73 | 🌐 Python | 📅 2026-08-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21755)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VBench-2.0-project/)

* [VBench: Comprehensive Benchmark Suite for Video Generative Models](https://arxiv.org/abs/2311.17982) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social\&label=Star)](https://github.com/Vchitect/VBench?tab=readme-ov-file) ⭐ 1,757 | 🐛 73 | 🌐 Python | 📅 2026-08-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17982)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VBench-project/)

* [Panda-70M: Captioning 70M Videos with Multiple Cross-Modality Teachers](https://arxiv.org/abs/2402.19479) (CVPR, 2024)\
  [![Star](https://img.shields.io/github/stars/snap-research/Panda-70M.svg?style=social\&label=Star)](https://github.com/snap-research/Panda-70M) ⭐ 705 | 🐛 41 | 🌐 Python | 📅 2024-10-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.19479)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/snap-research/Panda-70M) ⭐ 705 | 🐛 41 | 🌐 Python | 📅 2024-10-25
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://snap-research.github.io/Panda-70M/)

* [Evaluation of Text-to-Video Generation Models: A Dynamics Perspective](https://arxiv.org/pdf/2407.01094) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/MingXiangL/DEVIL.svg?style=social\&label=Star)](https://github.com/MingXiangL/DEVIL) ⭐ 273 | 🐛 4 | 🌐 Python | 📅 2024-12-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.01094)

* [OpenS2V-Nexus: A Detailed Benchmark and Million-Scale Dataset for Subject-to-Video Generation](https://arxiv.org/abs/2505.20292) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/OpenS2V-Nexus.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/OpenS2V-Nexus) ⭐ 228 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2026-05-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.20292)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/OpenS2V-Nexus/)

* [ChronoMagic-Bench: A Benchmark for Metamorphic Evaluation of Text-to-Time-lapse Video Generation](https://arxiv.org/abs/2406.18522) (NeurIPS, 2024)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/ChronoMagic-Bench.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/ChronoMagic-Bench) ⭐ 213 | 🐛 2 | 🌐 Python | 📅 2026-04-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.18522)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/ChronoMagic-Bench/)

* [EvalCrafter: Benchmarking and Evaluating Large Video Generation Models](https://arxiv.org/abs/2310.11440) (Oct., 2023)\
  [![Star](https://img.shields.io/github/stars/EvalCrafter/EvalCrafter.svg?style=social\&label=Star)](https://github.com/EvalCrafter/EvalCrafter) ⭐ 195 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2024-10-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.11440)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://evalcrafter.github.io/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/RaphaelLiu/EvalCrafter_T2V_Dataset)

* [MEt3R: Measuring Multi-View Consistency in Generated Images](https://geometric-rl.mpi-inf.mpg.de/met3r/static/assets/met3r.pdf) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/mohammadasim98/MEt3R.svg?style=social\&label=Star)](https://github.com/mohammadasim98/MEt3R) ⭐ 193 | 🐛 3 | 🌐 Python | 📅 2026-02-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://geometric-rl.mpi-inf.mpg.de/met3r/static/assets/met3r.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://geometric-rl.mpi-inf.mpg.de/met3r/)

* [VidProM: A Million-scale Real Prompt-Gallery Dataset for Text-to-Video Diffusion Models](https://arxiv.org/abs/2403.06098) (May., 2024)\
  [![Star](https://img.shields.io/github/stars/WangWenhao0716/VidProM.svg?style=social\&label=Star)](https://github.com/WangWenhao0716/VidProM) ⭐ 186 | 🐛 2 | 📅 2024-09-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06098)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/WangWenhao0716/VidProM) ⭐ 186 | 🐛 2 | 📅 2024-09-26
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://vidprom.github.io/)

* [Evaluation Agent, Efficient and Promptable Evaluation Framework for Visual Generative Models](https://arxiv.org/abs/2412.09645) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/Vchitect/Evaluation-Agent.svg?style=social\&label=Star)](https://github.com/Vchitect/Evaluation-Agent) ⭐ 130 | 🐛 1 | 🌐 Python | 📅 2026-08-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09645)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/Evaluation-Agent-project/)

* [T2V-CompBench: A Comprehensive Benchmark for Compositional Text-to-video Generation](https://arxiv.org/abs/2407.14505) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/KaiyueSun98/T2V-CompBench.svg?style=social\&label=Star)](https://github.com/KaiyueSun98/T2V-CompBench) ⭐ 123 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2025-10-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.14505)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-compbench.github.io/)

* [PEEKABOO: Interactive Video Generation via Masked-Diffusion](https://arxiv.org/abs/2312.07509) (CVPR, 2024)\
  [![Star](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social\&label=Star)](https://github.com/microsoft/Peekaboo) ⭐ 110 | 🐛 4 | 🌐 Python | 📅 2024-04-15
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07509)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jinga-lala.github.io/projects/Peekaboo/)

* [Frechet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos](https://arxiv.org/pdf/2407.16124) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/DSL-Lab/FVMD-frechet-video-motion-distance.svg?style=social\&label=Star)](https://github.com/DSL-Lab/FVMD-frechet-video-motion-distance) ⭐ 84 | 🐛 1 | 🌐 Python | 📅 2026-07-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.16124)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pypi.org/project/fvmd/1.0.0/)

* [Impossible Videos](https://arxiv.org/abs/2503.14378) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/showlab/Impossible-Videos.svg?style=social\&label=Star)](https://github.com/showlab/Impossible-Videos) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2025-07-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14378)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Impossible-Videos/)

* [T2VScore: Towards A Better Metric for Text-to-Video Generation](https://arxiv.org/abs/2401.07781) (Jan., 2024)\
  [![Star](https://img.shields.io/github/stars/showlab/T2VScore.svg?style=social\&label=Star)](https://github.com/showlab/T2VScore) ⭐ 81 | 🐛 3 | 📅 2024-04-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.07781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/T2VScore/)

* [StoryBench: A Multifaceted Benchmark for Continuous Story Visualization](https://arxiv.org/abs/2308.11606) (NeurIPS, 2023)\
  [![Star](https://img.shields.io/github/stars/google/storybench.svg?style=social\&label=Star)](https://github.com/google/storybench) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.11606)

* [FETV: A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation](https://arxiv.org/abs/2311.01813) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/llyx97/FETV.svg?style=social\&label=Star)](https://github.com/llyx97/FETV) ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2024-03-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.01813)

* [ReLight My NeRF: A Dataset for Novel View Synthesis and Relighting of Real World Objects](https://openaccess.thecvf.com/content/CVPR2023/html/Toschi_ReLight_My_NeRF_A_Dataset_for_Novel_View_Synthesis_and_CVPR_2023_paper.html) (CVPR, 2023)\
  [![Star](https://img.shields.io/github/stars/eyecan-ai/rene.svg?style=social\&label=Star)](https://github.com/eyecan-ai/rene) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/html/Toschi_ReLight_My_NeRF_A_Dataset_for_Novel_View_Synthesis_and_CVPR_2023_paper.html)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://eyecan-ai.github.io/rene/)

* [Is Your World Simulator a Good Story Presenter? A Consecutive Events-Based Benchmark for Future Long Video Generation](https://arxiv.org/abs/2412.16211) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/ypwang61/StoryEval.svg?style=social\&label=Star)](https://github.com/ypwang61/StoryEval/tree/main) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2025-05-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.16211)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ypwang61.github.io/project/StoryEval/)

* [LikePhys: Evaluating Intuitive Physics Understanding in Video Diffusion Models via Likelihood Preference](https://arxiv.org/abs/2510.11512) (Oct., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.11512)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yuanjianhao508.github.io/LikePhys/)

* [Stable Cinemetrics: Structured Taxonomy and Evaluation for Professional Video Generation](https://arxiv.org/abs/2509.26555) (Sep., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.26555)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stable-cinemetrics.github.io/)

### Commercial Product

* [Veo 2](https://sora.com/) ([Google](https://deepmind.google/technologies/veo/veo-2/))\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://deepmind.google/technologies/veo/veo-2/)

* [Kling](https://klingai.com/?gad_source=1\&gclid=CjwKCAiAudG5BhAREiwAWMlSjMtrwX5RsW6xQvRSSg05fn1bA8wo9-AJiAKTIr-IkZnewbLXpCM44RoCkrsQAvD_BwE) ([KuaiShou](https://www.kuaishou.com/en))\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://klingai.com/?gad_source=1\&gclid=CjwKCAiAudG5BhAREiwAWMlSjMtrwX5RsW6xQvRSSg05fn1bA8wo9-AJiAKTIr-IkZnewbLXpCM44RoCkrsQAvD_BwE)

* [Gen 3](https://app.runwayml.com/login) ([Runway](https://runwayml.com/))\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://app.runwayml.com/login)

* [Dream Machine](https://lumalabs.ai/dream-machine) ([Luma AI](https://lumalabs.ai/dream-machine))\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lumalabs.ai/dream-machine)

* [Sora](https://sora.com/) ([Open AI](https://openai.com/))\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sora.com/)

* [Wunjo](https://wunjo.online/) ([WR](https://wladradchenko.ru/en#products))\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wunjo.online/)

* [Shortodella](https://shortodella.com/)\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shortodella.com/)

* [Seedream AI Studio](https://seedream4.video/)\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://seedream4.video/)

* [Riffkit](https://riffkit.ai/)\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://riffkit.ai/)
  [![GitHub](https://img.shields.io/badge/GitHub-riffkit%2Fskill-181717?logo=github)](https://github.com/riffkit/skill) ⭐ 7 | 🐛 0 | 📅 2026-08-25

* [SEELE TV](https://seele.tv/)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://seele.tv/)

### Video Generation

* [Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets](https://arxiv.org/abs/2311.15127) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social\&label=Star)](https://github.com/Stability-AI/generative-models) ⭐ 27,279 | 🐛 339 | 🌐 Python | 📅 2025-12-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15127)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stability.ai/news/stable-video-diffusion-open-ai-video-model)

* [Packing Input Frame Context in Next-Frame Prediction Models for Video Generation](https://lllyasviel.github.io/frame_pack_gitpage/pack.pdf) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/lllyasviel/FramePack.svg?style=social\&label=Star)](https://github.com/lllyasviel/FramePack) ⭐ 17,240 | 🐛 488 | 🌐 Python | 📅 2025-10-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.08685)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lllyasviel.github.io/frame_pack_gitpage/)

* [CogVideoX: Text-to-video generation](https://github.com/THUDM/CogVideo/blob/main/resources/CogVideoX.pdf) ⭐ 12,993 | 🐛 117 | 🌐 Python | 📅 2025-11-04 (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social\&label=Star)](https://github.com/THUDM/CogVideo) ⭐ 12,993 | 🐛 117 | 🌐 Python | 📅 2025-11-04
  [![paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://github.com/THUDM/CogVideo/blob/main/resources/CogVideoX.pdf) ⭐ 12,993 | 🐛 117 | 🌐 Python | 📅 2025-11-04

* [AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning](https://arxiv.org/abs/2307.04725) (Jul., 2023)\
  [![Star](https://img.shields.io/github/stars/guoyww/animatediff.svg?style=social\&label=Star)](https://github.com/guoyww/animatediff/) ⭐ 12,232 | 🐛 318 | 🌐 Python | 📅 2024-07-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.04725)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://animatediff.github.io/)

* [MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model](https://arxiv.org/abs/2311.16498) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social\&label=Star)](https://github.com/magic-research/magic-animate) ⭐ 10,896 | 🐛 109 | 🌐 Python | 📅 2025-08-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/magicanimate)

* [SkyReels-V2: Infinite-length Film Generative Model](https://arxiv.org/abs/2504.13074) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/SkyworkAI/SkyReels-V2.svg?style=social\&label=Star)](https://github.com/SkyworkAI/SkyReels-V2) ⭐ 7,488 | 🐛 351 | 🌐 Python | 📅 2026-01-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.13074)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.skyreels.ai/home?utm_campaign=github_SkyReels_V2)

* [StoryDiffusion: Consistent Self-Attention for Long-Range Image and Video Generation](https://arxiv.org/abs/2405.01434) (May, 2024)\
  [![Star](https://img.shields.io/github/stars/HVision-NKU/StoryDiffusion.svg?style=social\&label=Star)](https://github.com/HVision-NKU/StoryDiffusion) ⭐ 6,459 | 🐛 119 | 🌐 Jupyter Notebook | 📅 2024-09-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.01434)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://storydiffusion.github.io/)

* [VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models](https://arxiv.org/abs/2401.09047) (Jan., 2024)\
  [![Star](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social\&label=Star)](https://github.com/AILab-CVC/VideoCrafter) ⭐ 5,073 | 🐛 74 | 🌐 Python | 📅 2026-01-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09047)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ailab-cvc.github.io/videocrafter2/)

* [Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation](https://arxiv.org/abs/2212.11565) (ICCV 2023)\
  [![Star](https://img.shields.io/github/stars/showlab/Tune-A-Video?style=social)](https://github.com/showlab/Tune-A-Video) ⭐ 4,363 | 🐛 37 | 🌐 Python | 📅 2023-10-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.11565)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tuneavideo.github.io/)

* [Text2video-Zero: Text-to-Image Diffusion Models Are Zero-Shot Video Generators](https://arxiv.org/abs/2303.13439) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/Picsart-AI-Research/Text2Video-Zero.svg?style=social\&label=Star)](https://github.com/Picsart-AI-Research/Text2Video-Zero) ⭐ 4,243 | 🐛 51 | 🌐 Python | 📅 2023-05-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13439)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://text2video-zero.github.io/)

* [VACE: All-in-One Video Creation and Editing](https://arxiv.org/pdf/2503.07598) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/ali-vilab/VACE.svg?style=social\&label=Star)](https://github.com/ali-vilab/VACE) ⭐ 3,935 | 🐛 59 | 🌐 Python | 📅 2025-10-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07598)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ali-vilab.github.io/VACE-Page/)

* [MAGI-1: Autoregressive Video Generation at Scale](https://static.magi.world/static/files/MAGI_1.pdf) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/SandAI-org/Magi-1.svg?style=social\&label=Star)](https://github.com/SandAI-org/Magi-1) ⭐ 3,778 | 🐛 46 | 🌐 Python | 📅 2026-06-17
  [![PDF](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://static.magi.world/static/files/MAGI_1.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](SandAI-org/Magi-1)

* [InstructVideo: Instructing Video Diffusion Models with Human Feedback](https://arxiv.org/abs/2312.12490) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/damo-vilab/i2vgen-xl.svg?style=social\&label=Star)](https://github.com/damo-vilab/i2vgen-xl/blob/main/doc/InstructVideo.md) ⭐ 3,155 | 🐛 115 | 🌐 Python | 📅 2025-01-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12490)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://instructvideo.github.io/)

* [DreamVideo: Composing Your Dream Videos with Customized Subject and Motion](https://arxiv.org/abs/2312.04433) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/damo-vilab/i2vgen-xl.svg?style=social\&label=Star)](https://github.com/damo-vilab/i2vgen-xl) ⭐ 3,155 | 🐛 115 | 🌐 Python | 📅 2025-01-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamvideo-t2v.github.io/)

* [Hierarchical Spatio-temporal Decoupling for Text-to-Video Generation](https://arxiv.org/abs/2312.04483) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/damo-vilab/i2vgen-xl.svg?style=social\&label=Star)](https://github.com/damo-vilab/i2vgen-xl) ⭐ 3,155 | 🐛 115 | 🌐 Python | 📅 2025-01-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04483)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://higen-t2v.github.io/)

* [DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors](https://arxiv.org/abs/2310.12190) (Oct., 2023)\
  [![Star](https://img.shields.io/github/stars/Doubiiu/DynamiCrafter.svg?style=social\&label=Star)](https://github.com/Doubiiu/DynamiCrafter) ⭐ 3,007 | 🐛 91 | 🌐 Python | 📅 2024-09-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12190)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://doubiiu.github.io/projects/DynamiCrafter/)

* [MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance](https://arxiv.org/abs/2406.19680) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/Tencent/MimicMotion.svg?style=social\&label=Star)](https://github.com/Tencent/MimicMotion) ⭐ 2,653 | 🐛 93 | 🌐 Python | 📅 2025-11-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tencent.github.io/MimicMotion/)

* [InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation](https://arxiv.org/abs/2307.06942) (Jul., 2023)\
  [![Star](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social\&label=Star)](https://github.com/OpenGVLab/InternVideo/tree/main/Data/InternVid) ⭐ 2,374 | 🐛 147 | 🌐 Python | 📅 2026-07-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06942)

* [Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers](https://arxiv.org/abs/2405.05945) (May, 2024)\
  [![Star](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-T2X.svg?style=social\&label=Star)](https://github.com/Alpha-VLLM/Lumina-T2X) ⭐ 2,250 | 🐛 57 | 🌐 Python | 📅 2025-02-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05945)

* [Helios: Real Real-Time Long Video Generation Model](https://arxiv.org/abs/2603.04379) (Mar., 2026)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Helios.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/Helios) ⭐ 2,128 | 🐛 42 | 🌐 Python | 📅 2026-08-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.04379)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/Helios-Page/)

* [Real-Time Video Generation with Pyramid Attention Broadcast](https://arxiv.org/abs/2408.12588) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/VideoSys.svg?style=social\&label=Star)](https://github.com/NUS-HPC-AI-Lab/VideoSys) ⭐ 2,024 | 🐛 26 | 🌐 Python | 📅 2025-08-27
  [![paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12588)

* [Latte: Latent Diffusion Transformer for Video Generation](https://arxiv.org/abs/2401.03048) (Jan., 2024)\
  [![Star](https://img.shields.io/github/stars/Vchitect/Latte.svg?style=social\&label=Star)](https://github.com/Vchitect/Latte) ⭐ 1,948 | 🐛 3 | 🌐 Python | 📅 2026-08-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.03048)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maxin-cn.github.io/latte_project/)

* [DreaMoving: A Human Video Generation Framework based on Diffusion Models](https://arxiv.org/abs/2312.05107) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/dreamoving/dreamoving-project.svg?style=social\&label=Star)](https://github.com/dreamoving/dreamoving-project) ⭐ 1,790 | 🐛 10 | 📅 2024-01-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05107)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamoving.github.io/dreamoving/)

* [Any-to-Any Generation via Composable Diffusion](https://arxiv.org/abs/2305.11846) (May, 2023)\
  [![Star](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social\&label=Star)](https://github.com/microsoft/i-Code/tree/main/i-Code-V3) ⭐ 1,704 | 🐛 35 | 🌐 Jupyter Notebook | 📅 2024-09-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11846)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://codi-gen.github.io/)

* [StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text](https://arxiv.org/abs/2403.14773) (Mar., 2024)\
  [![Star](https://img.shields.io/github/stars/Picsart-AI-Research/StreamingT2V.svg?style=social\&label=Star)](https://github.com/Picsart-AI-Research/StreamingT2V) ⭐ 1,629 | 🐛 40 | 🌐 Python | 📅 2025-03-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14773)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://streamingt2v.github.io/)

* [Upscale-A-Video: Temporal-Consistent Diffusion Model for Real-World Video Super-Resolution](https://arxiv.org/abs/2312.06640) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/sczhou/Upscale-A-Video.svg?style=social\&label=Star)](https://github.com/sczhou/Upscale-A-Video) ⭐ 1,471 | 🐛 37 | 🌐 Python | 📅 2024-09-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06640)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shangchenzhou.com/projects/upscale-a-video/)

* [Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos](https://arxiv.org/abs/2304.01186) (Apr., 2023)\
  [![Star](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social\&label=Star)](https://github.com/mayuelala/FollowYourPose) ⭐ 1,358 | 🐛 12 | 🌐 Python | 📅 2024-03-20
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://follow-your-pose.github.io/)

* [MagicTime: Time-lapse Video Generation Models as Metamorphic Simulators](https://arxiv.org/abs/2404.05014) (Apr., 2024)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/MagicTime.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/MagicTime) ⭐ 1,337 | 🐛 10 | 🌐 Python | 📅 2026-04-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.05014)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/MagicTime/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/BestWishYsh/ChronoMagic)

* [Show-1: Marrying Pixel and Latent Diffusion Models for Text-to-Video Generation](https://arxiv.org/abs/2309.15818) (Sep., 2023)\
  [![Star](https://img.shields.io/github/stars/showlab/Show-1.svg?style=social\&label=Star)](https://github.com/showlab/Show-1) ⭐ 1,148 | 🐛 16 | 🌐 Python | 📅 2025-09-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15818)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Show-1/)

* [MOVA: Towards Scalable and Synchronized Video-Audio Generation](https://arxiv.org/abs/2602.08794) (Feb., 2026)
  [![Star](https://img.shields.io/github/stars/OpenMOSS/MOVA.svg?style=social\&label=Star)](https://github.com/OpenMOSS/MOVA) ⭐ 1,108 | 🐛 32 | 🌐 Python | 📅 2026-09-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.08794)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mosi.cn/models/mova)

* [DisCo: Disentangled Control for Referring Human Dance Generation in Real World](https://arxiv.org/abs/2307.000400) (Jul., 2023)\
  [![Star](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social\&label=Star)](https://github.com/Wangt-CN/DisCo) ⭐ 1,072 | 🐛 36 | 🌐 Python | 📅 2024-07-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://disco-dance.github.io/)

* [MotionDirector: Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2310.08465) (Sep., 2023)\
  [![Star](https://img.shields.io/github/stars/showlab/MotionDirector.svg?style=social\&label=Star)](https://github.com/showlab/MotionDirector) ⭐ 1,053 | 🐛 26 | 🌐 Python | 📅 2024-08-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08465)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/MotionDirector/)

* [DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion](https://arxiv.org/abs/2304.06025) (Apr., 2023)\
  [![Star](https://img.shields.io/github/stars/johannakarras/DreamPose.svg?style=social\&label=Star)](https://github.com/johannakarras/DreamPose) ⭐ 1,004 | 🐛 35 | 🌐 Python | 📅 2023-11-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://grail.cs.washington.edu/projects/dreampose/)

* [Magvit: Masked Generative Video Transformer](https://arxiv.org/abs/2212.05199) (Dec., 2022)\
  [![Star](https://img.shields.io/github/stars/MAGVIT/magvit.svg?style=social\&label=Star)](https://github.com/MAGVIT/magvit) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.05199)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magvit.cs.cmu.edu/)

* [PIA: Your Personalized Image Animator via Plug-and-Play Modules in Text-to-Image Models](https://arxiv.org/abs/2312.13964) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/open-mmlab/PIA.svg?style=social\&label=Star)](https://github.com/open-mmlab/PIA) ⭐ 975 | 🐛 7 | 🌐 Python | 📅 2024-08-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.13964)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pi-animator.github.io/)

* [Fine-Grained Open Domain Image Animation with Motion Guidance](https://arxiv.org/abs/2311.12886) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/alibaba/animate-anything.svg?style=social\&label=Star)](https://github.com/alibaba/animate-anything) ⭐ 972 | 🐛 17 | 🌐 Python | 📅 2024-10-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12886)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://animationai.github.io/AnimateAnything/)

* [SEINE: Short-to-Long Video Diffusion Model for Generative Transition and Prediction](https://arxiv.org/abs/2310.20700) (Oct., 2023)\
  [![Star](https://img.shields.io/github/stars/Vchitect/SEINE.svg?style=social\&label=Star)](https://github.com/Vchitect/SEINE) ⭐ 967 | 🐛 24 | 🌐 Python | 📅 2024-11-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.20700)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/SEINE-project/)

* [VideoComposer: Compositional Video Synthesis with Motion Controllability](https://arxiv.org/abs/2306.02018) (Jun., 2023)\
  [![Star](https://img.shields.io/github/stars/damo-vilab/videocomposer.svg?style=social\&label=Star)](https://github.com/damo-vilab/videocomposer) ⭐ 955 | 🐛 37 | 🌐 Python | 📅 2023-11-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02018)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videocomposer.github.io/)

* [LAVIE: High-Quality Video Generation with Cascaded Latent Diffusion Models](https://arxiv.org/abs/2309.15103) (Sep., 2023)\
  [![Star](https://img.shields.io/github/stars/Vchitect/LaVie.svg?style=social\&label=Star)](https://github.com/Vchitect/LaVie) ⭐ 952 | 🐛 23 | 🌐 Python | 📅 2024-11-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15103)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/LaVie-project/)

* [Causal Forcing: Autoregressive Diffusion Distillation Done Right for High-Quality Real-Time Interactive Video Generation](https://arxiv.org/abs/2602.02214) (Feb., 2026)\
  [![Star](https://img.shields.io/github/stars/thu-ml/Causal-Forcing.svg?style=social\&label=Star)](https://github.com/thu-ml/Causal-Forcing) ⭐ 944 | 🐛 33 | 🌐 Python | 📅 2026-08-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.02214)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://thu-ml.github.io/CausalForcing.github.io/)

* [Identity-Preserving Text-to-Video Generation by Frequency Decomposition](https://arxiv.org/abs/2411.17440) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/ConsisID) ⭐ 856 | 🐛 36 | 🌐 Python | 📅 2026-04-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/ConsisID/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/BestWishYsh/ConsisID-preview-Data)

* [UltraViCo: Breaking Extrapolation Limits in Video Diffusion Transformers](https://arxiv.org/abs/2511.20123) (Oct., 2025)\
  [![Star](https://img.shields.io/github/stars/thu-ml/RIFLEx.svg?style=social\&label=Star)](https://github.com/thu-ml/RIFLEx) ⭐ 825 | 🐛 24 | 🌐 Python | 📅 2026-06-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.20123)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://thu-ml.github.io/UltraViCo.github.io/)

* [RIFLEx: A Free Lunch for Length Extrapolation in Video Diffusion Transformers](https://arxiv.org/abs/2502.15894) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/thu-ml/RIFLEx.svg?style=social\&label=Star)](https://github.com/thu-ml/RIFLEx) ⭐ 825 | 🐛 24 | 🌐 Python | 📅 2026-06-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.15894)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://riflex-video.github.io/)

* [MagicDance: Realistic Human Dance Video Generation with Motions & Facial Expressions Transfer](https://arxiv.org/abs/2311.12052) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/Boese0601/MagicDance.svg?style=social\&label=Star)](https://github.com/Boese0601/MagicDance) ⭐ 776 | 🐛 31 | 🌐 Python | 📅 2024-07-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12052)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boese0601.github.io/magicdance/)

* [PUSA V1.0: Surpassing Wan-I2V with $500 Training Cost by Vectorized Timestep Adaptation](https://arxiv.org/abs/2507.16116) (July., 2025)
  [![Star](https://img.shields.io/github/stars/Yaofang-Liu/Pusa-VidGen.svg?style=social\&label=Star)](https://github.com/Yaofang-Liu/Pusa-VidGen) ⭐ 686 | 🐛 28 | 🌐 Python | 📅 2026-02-13\
  [![PDF](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.16116)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yaofang-liu.github.io/Pusa_Web/)

* [Autoregressive Video Generation without Vector Quantization](https://arxiv.org/abs/2412.14169) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/baaivision/NOVA.svg?style=social\&label=Star)](https://github.com/baaivision/NOVA) ⭐ 660 | 🐛 0 | 🌐 Python | 📅 2025-10-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14169)

* [MagicAvatar: Multimodal Avatar Generation and Animation](https://arxiv.org/abs/2308.14748) (Aug., 2023)\
  [![Star](https://img.shields.io/github/stars/magic-research/magic-avatar.svg?style=social\&label=Star)](https://github.com/magic-research/magic-avatar) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14748)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-avatar.github.io/)

* [Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization](https://arxiv.org/abs/2402.03161) (Feb., 2024)\
  [![Star](https://img.shields.io/github/stars/jy0205/LaVIT.svg?style=social\&label=Star)](https://github.com/jy0205/LaVIT) ⭐ 604 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2024-10-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03161)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-lavit.github.io/)

* [VEnhancer: Generative Space-Time Enhancement for Video Generation](https://arxiv.org/abs/2407.07667) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/Vchitect/VEnhancer.svg?style=social\&label=Star)](https://github.com/Vchitect/VEnhancer) ⭐ 579 | 🐛 21 | 🌐 Python | 📅 2024-09-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.07667)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VEnhancer-project/)

* [AniDoc: Animation Creation Made Easier](https://arxiv.org/pdf/2412.14173) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/yihao-meng/AniDoc.svg?style=social\&label=Star)](https://github.com/yihao-meng/AniDoc) ⭐ 572 | 🐛 5 | 🌐 Python | 📅 2025-04-15
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.14173)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yihao-meng.github.io/AniDoc_demo/)

* [UniVideo: Unified Understanding, Generation, and Editing for Videos](https://arxiv.org/abs/2510.08377) (Oct., 2025)\
  [![Star](https://img.shields.io/github/stars/KlingAIResearch/UniVideo.svg?style=social\&label=Star)](https://github.com/KlingAIResearch/UniVideo) ⭐ 555 | 🐛 2 | 🌐 Python | 📅 2026-07-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.08377)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://congwei1230.github.io/UniVideo/)

* [FreeInit: Bridging Initialization Gap in Video Diffusion Models](https://arxiv.org/abs/2312.07537) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/TianxingWu/FreeInit.svg?style=social\&label=Star)](https://github.com/TianxingWu/FreeInit) ⭐ 543 | 🐛 12 | 🌐 Python | 📅 2024-01-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07537)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tianxingwu.github.io/pages/FreeInit/)

* [Latent Video Diffusion Models for High-Fidelity Video Generation With Arbitrary Lengths](https://arxiv.org/abs/2211.13221) (Nov., 2022)\
  [![Star](https://img.shields.io/github/stars/YingqingHe/LVDM.svg?style=social\&label=Star)](https://github.com/YingqingHe/LVDM) ⭐ 505 | 🐛 18 | 🌐 Python | 📅 2024-11-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.13221)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yingqinghe.github.io/LVDM/)

* [FIFO-Diffusion: Generating Infinite Videos from Text without Training](https://arxiv.org/abs/2405.11473) (May, 2024)\
  [![Star](https://img.shields.io/github/stars/jjihwan/FIFO-Diffusion_public.svg?style=social\&label=Star)](https://github.com/jjihwan/FIFO-Diffusion_public) ⭐ 486 | 🐛 5 | 🌐 Python | 📅 2024-10-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.11473)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jjihwan.github.io/projects/FIFO-Diffusion)

* [Conditional Image-to-Video Generation with Latent Flow Diffusion Models](https://arxiv.org/abs/2303.13744) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/nihaomiao/CVPR23_LFDM.svg?style=social\&label=Star)](https://github.com/nihaomiao/CVPR23_LFDM) ⭐ 470 | 🐛 6 | 🌐 Python | 📅 2024-06-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13744)

* [Magic-Me: Identity-Specific Video Customized Diffusion](https://arxiv.org/abs/2402.09368) (Feb., 2024)\
  [![Star](https://img.shields.io/github/stars/Zhen-Dong/Magic-Me.svg?style=social\&label=Star)](https://github.com/Zhen-Dong/Magic-Me) ⭐ 458 | 🐛 12 | 🌐 Python | 📅 2024-02-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09368)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-me-webpage.github.io/)

* [Mm-Diffusion: Learning Multi-Modal Diffusion Models for Joint Audio and Video Generation](https://arxiv.org/abs/2212.09478) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/researchmm/MM-Diffusion.svg?style=social\&label=Star)](https://github.com/researchmm/MM-Diffusion) ⭐ 452 | 🐛 17 | 🌐 Python | 📅 2024-06-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.09478)

* [FreeNoise: Tuning-Free Longer Video Diffusion Via Noise Rescheduling](https://arxiv.org/abs/2310.15169) (Oct., 2023)\
  [![Star](https://img.shields.io/github/stars/arthur-qiu/LongerCrafter.svg?style=social\&label=Star)](https://github.com/arthur-qiu/LongerCrafter) ⭐ 430 | 🐛 1 | 🌐 Python | 📅 2025-08-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.15169)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://haonanqiu.com/projects/FreeNoise.html)

* [Lumina-Video: Efficient and Flexible Video Generation with Multi-scale Next-DiT](https://arxiv.org/abs/2502.06782) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-Video.svg?style=social\&label=Star)](https://github.com/Alpha-VLLM/Lumina-Video) ⭐ 417 | 🐛 5 | 🌐 Python | 📅 2025-03-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06782)

* [Large Motion Video Autoencoding with Cross-modal Video VAE](https://arxiv.org/abs/2412.17805) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.17805)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/VideoVerses/VideoVAEPlus) ⭐ 411 | 🐛 9 | 🌐 Python | 📅 2025-01-19

* [Cinematic Mindscapes: High-quality Video Reconstruction from Brain Activity](https://arxiv.org/abs/2305.11675) (May, 2023)\
  [![Star](https://img.shields.io/github/stars/jqin4749/MindVideo.svg?style=social\&label=Star)](https://github.com/jqin4749/MindVideo) ⭐ 391 | 🐛 5 | 🌐 Python | 📅 2023-12-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11675)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mind-video.com/)

* [ID-Animator: Zero-Shot Identity-Preserving Human Video Generation](https://arxiv.org/abs/2404.15275) (Apr., 2024)\
  [![Star](https://img.shields.io/github/stars/ID-Animator/ID-Animator.svg?style=social\&label=Star)](https://github.com/ID-Animator/ID-Animator) ⭐ 382 | 🐛 20 | 🌐 Python | 📅 2024-06-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15275)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://id-animator.github.io/)

* [McVd: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation](https://arxiv.org/abs/2205.09853) (NeurIPS 2022)\
  [![Star](https://img.shields.io/github/stars/Tobi-r9/RaMViD.svg?style=social\&label=Star)](https://github.com/voletiv/mcvd-pytorch) ⭐ 370 | 🐛 13 | 🌐 Python | 📅 2022-09-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.09853)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mask-cond-video-diffusion.github.io)

* [AnimateZero: Video Diffusion Models are Zero-Shot Image Animators](https://arxiv.org/abs/2312.03793) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/vvictoryuki/AnimateZero.svg?style=social\&label=Star)](https://github.com/vvictoryuki/AnimateZero) ⭐ 357 | 🐛 3 | 📅 2023-12-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03793)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vvictoryuki.github.io/animatezero.github.io/)

* [Text2Performer: Text-Driven Human Video Generation](https://arxiv.org/abs/2304.08483) (Apr., 2023)\
  [![Star](https://img.shields.io/github/stars/yumingj/Text2Performer.svg?style=social\&label=Star)](https://github.com/yumingj/Text2Performer) ⭐ 325 | 🐛 1 | 🌐 Python | 📅 2023-09-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08483)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yumingj.github.io/projects/Text2Performer)

* [Video Probabilistic Diffusion Models in Projected Latent Space](https://arxiv.org/abs/2302.07685) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/sihyun-yu/PVDM.svg?style=social\&label=Star)](https://github.com/sihyun-yu/PVDM) ⭐ 322 | 🐛 5 | 🌐 Python | 📅 2024-05-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.07685)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sihyun.me/PVDM/)

* [Video-T1: Test-Time Scaling for Video Generation](https://arxiv.org/abs/2503.18942) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/liuff19/Video-T1.svg?style=social\&label=Star)](https://github.com/liuff19/Video-T1) ⭐ 319 | 🐛 4 | 🌐 Python | 📅 2026-03-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.18942)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://liuff19.github.io/Video-T1/)

* [Video Diffusion Alignment via Reward Gradient](https://arxiv.org/abs/2407.08737) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/mihirp1998/VADER.svg?style=social\&label=Star)](https://github.com/mihirp1998/VADER) ⭐ 318 | 🐛 11 | 🌐 Python | 📅 2025-03-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08737)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vader-vid.github.io/)

* [T2V-Turbo-v2: Enhancing Video Generation Model Post-Training Through Data, Reward, and Conditional Guidance Design](https://arxiv.org/pdf/2410.05677) (Oct, 2024)\
  [![Star](https://img.shields.io/github/stars/Ji4chenLi/t2v-turbo.svg?style=social\&label=Star)](https://github.com/Ji4chenLi/t2v-turbo) ⭐ 312 | 🐛 7 | 🌐 Python | 📅 2025-01-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.05677)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-turbo-v2.github.io/)

* [VideoBooth: Diffusion-based Video Generation with Image Prompts](https://arxiv.org/abs/2312.00777) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/Vchitect/VideoBooth.svg?style=social\&label=Star)](https://github.com/Vchitect/VideoBooth) ⭐ 309 | 🐛 6 | 🌐 Python | 📅 2024-06-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00777)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VideoBooth-project/)

* [Gen-L-Video: Multi-Text to Long Video Generation via Temporal Co-Denoising](https://arxiv.org/abs/2305.18264) (May, 2023)\
  [![Star](https://img.shields.io/github/stars/G-U-N/Gen-L-Video.svg?style=social\&label=Star)](https://github.com/G-U-N/Gen-L-Video) ⭐ 307 | 🐛 16 | 🌐 Jupyter Notebook | 📅 2025-10-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18264)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://g-u-n.github.io/projects/gen-long-video/index.html)

* [Training-Free Efficient Video Generation via Dynamic Token Carving](https://arxiv.org/abs/2505.16864) (May., 2025)
  [![Star](https://img.shields.io/github/stars/dvlab-research/Jenga.svg?style=social\&label=Star)](https://github.com/dvlab-research/Jenga) ⭐ 288 | 🐛 9 | 🌐 Python | 📅 2025-08-04\
  [![PDF](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.16864)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://julianjuaner.github.io/projects/jenga/)

* [LAMP: Learn A Motion Pattern for Few-Shot-Based Video Generation](https://arxiv.org/abs/2310.10769) (Oct., 2023)\
  [![Star](https://img.shields.io/github/stars/RQ-Wu/LAMP.svg?style=social\&label=Star)](https://github.com/RQ-Wu/LAMP) ⭐ 284 | 🐛 9 | 🌐 Python | 📅 2024-04-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10769)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rq-wu.github.io/projects/LAMP/)

* [StyleCrafter: Enhancing Stylized Text-to-Video Generation with Style Adapter](https://arxiv.org/abs/2312.00330) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/GongyeLiu/StyleCrafter.svg?style=social\&label=Star)](https://github.com/GongyeLiu/StyleCrafter) ⭐ 272 | 🐛 6 | 🌐 Python | 📅 2025-04-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00330)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gongyeliu.github.io/StyleCrafter.github.io/)

* [ConsistI2V: Enhancing Visual Consistency for Image-to-Video Generation](https://arxiv.org/abs/2402.04324) (Feb., 2024)\
  [![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/ConsistI2V.svg?style=social\&label=Star)](https://github.com/TIGER-AI-Lab/ConsistI2V) ⭐ 260 | 🐛 1 | 🌐 Python | 📅 2024-07-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.04324)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tiger-ai-lab.github.io/ConsistI2V/)

* [Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation](https://arxiv.org/abs/2307.06940) (Jul., 2023)\
  [![Star](https://img.shields.io/github/stars/VideoCrafter/Animate-A-Story.svg?style=social\&label=Star)](https://github.com/VideoCrafter/Animate-A-Story) ⭐ 258 | 🐛 3 | 📅 2024-02-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videocrafter.github.io/Animate-A-Story/)

* [Identifying and Solving Conditional Image Leakage in Image-to-Video Diffusion Model](https://arxiv.org/abs/2406.15735) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/thu-ml/cond-image-leakage.svg?style=social\&label=Star)](https://github.com/thu-ml/cond-image-leakage/tree/main?tab=readme-ov-file) ⭐ 257 | 🐛 8 | 📅 2026-03-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15735)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cond-image-leak.github.io/)

* [VINO: A Unified Visual Generator with Interleaved OmniModal Context](https://arxiv.org/abs/2601.02358) (Jan., 2026)\
  [![Star](https://img.shields.io/github/stars/SOTAMak1r/VINO-code.svg?style=social\&label=Star)](https://github.com/SOTAMak1r/VINO-code) ⭐ 234 | 🐛 2 | 🌐 Python | 📅 2026-03-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.02358)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sotamak1r.github.io/VINO-web/)

* [Sketch Video Synthesis](https://arxiv.org/abs/2311.15306) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/yudianzheng/SketchVideo.svg?style=social\&label=Star)](https://github.com/yudianzheng/SketchVideo) ⭐ 222 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2024-07-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15306)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sketchvideo.github.io/)

* [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (Jan., 2024)\
  [![Star](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social\&label=Star)](https://github.com/JeffWang987/WorldDreamer) ⭐ 207 | 🐛 4 | 📅 2024-01-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09985)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/)

* [WF-VAE: Enhancing Video VAE by Wavelet-Driven Energy Flow for Latent Video Diffusion Model](https://arxiv.org/abs/2411.17459) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/WF-VAE.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/WF-VAE) ⭐ 206 | 🐛 5 | 🌐 Python | 📅 2025-05-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17459)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-repair.github.io/)

* [LivePhoto: Real Image Animation with Text-guided Motion Control](https://arxiv.org/abs/2312.02928) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/XavierCHEN34/LivePhoto.svg?style=social\&label=Star)](https://github.com/XavierCHEN34/LivePhoto) ⭐ 205 | 🐛 4 | 🌐 Python | 📅 2026-03-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02928)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xavierchen34.github.io/LivePhoto-Page/)

* [Live2Diff: Live Stream Translation via Uni-directional Attention in Video Diffusion Models](https://arxiv.org/abs/2407.08701) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/open-mmlab/Live2Diff.svg?style=social\&label=Star)](https://github.com/open-mmlab/Live2Diff) ⭐ 200 | 🐛 5 | 🌐 Python | 📅 2024-07-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08701)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://live2diff.github.io/)

* [Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance](https://arxiv.org/abs/2306.00943) (Jun., 2023)\
  [![Star](https://img.shields.io/github/stars/VideoCrafter/Make-Your-Video.svg?style=social\&label=Star)](https://github.com/VideoCrafter/Make-Your-Video) ⭐ 196 | 🐛 4 | 🌐 Python | 📅 2024-02-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00943)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://doubiiu.github.io/projects/Make-Your-Video/)

* [FusionFrames: Efficient Architectural Aspects for Text-to-Video Generation Pipeline](https://arxiv.org/abs/2311.13073) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/ai-forever/KandinskyVideo.svg?style=social\&label=Star)](https://github.com/ai-forever/KandinskyVideo) ⭐ 186 | 🐛 7 | 🌐 Python | 📅 2024-05-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13073)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ai-forever.github.io/kandinsky-video/)

* [Spatiotemporal Skip Guidance for Enhanced Video Diffusion Sampling](https://arxiv.org/abs/2411.18664) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/junhahyung/STGuidance.svg?style=social\&label=Star)](https://github.com/junhahyung/STGuidance) ⭐ 179 | 🐛 9 | 🌐 Python | 📅 2025-09-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18664)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://junhahyung.github.io/STGuidance)

* [AVID: Any-Length Video Inpainting with Diffusion Model](https://arxiv.org/abs/2312.03816) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/zhang-zx/AVID.svg?style=social\&label=Star)](https://github.com/zhang-zx/AVID) ⭐ 177 | 🐛 9 | 📅 2024-02-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03816)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhang-zx.github.io/AVID/)

* [VideoElevator: Elevating Video Generation Quality with Versatile Text-to-Image Diffusion Models](https://arxiv.org/abs/2403.05438) (Mar., 2024)\
  [![Star](https://img.shields.io/github/stars/YBYBZhang/VideoElevator.svg?style=social\&label=Star)](https://github.com/YBYBZhang/VideoElevator) ⭐ 163 | 🐛 1 | 🌐 Python | 📅 2024-04-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.05438)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoelevator.github.io/)

* [GPT4Motion: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning](https://arxiv.org/abs/2311.12631) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/jiaxilv/GPT4Motion.svg?style=social\&label=Star)](https://github.com/jiaxilv/GPT4Motion) ⭐ 144 | 🐛 6 | 🌐 Python | 📅 2024-06-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12631)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gpt4motion.github.io/)

* [SimDA: Simple Diffusion Adapter for Efficient Video Generation](https://arxiv.org/abs/2308.09710) (Aug., 2023)\
  [![Star](https://img.shields.io/github/stars/ChenHsing/SimDA.svg?style=social\&label=Star)](https://github.com/ChenHsing/SimDA) ⭐ 128 | 🐛 5 | 🌐 Python | 📅 2024-05-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.09710)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chenhsing.github.io/SimDA/)

* [RepVideo: Rethinking Cross-Layer Representation for Video Generation](https://arxiv.org/pdf/2501.08994) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/Vchitect/RepVideo.svg?style=social\&label=Star)](https://github.com/Vchitect/RepVideo) ⭐ 123 | 🐛 5 | 🌐 Python | 📅 2025-01-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.08994)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/RepVid-Webpage/)

* [PEEKABOO: Interactive Video Generation via Masked-Diffusion](https://arxiv.org/abs/2312.07509) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social\&label=Star)](https://github.com/microsoft/Peekaboo) ⭐ 110 | 🐛 4 | 🌐 Python | 📅 2024-04-15
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07509)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jinga-lala.github.io/projects/Peekaboo/)

* [SinFusion: Training Diffusion Models on a Single Image or Video](https://arxiv.org/abs/2211.11743) (Nov., 2022)\
  [![Star](https://img.shields.io/github/stars/YingqingHe/LVDM.svg?style=social\&label=Star)](https://github.com/yanivnik/sinfusion-code) ⭐ 110 | 🐛 5 | 🌐 Python | 📅 2025-01-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.11743)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yanivnik.github.io/sinfusion/)

* [Diffusion Models for Video Prediction and Infilling](https://arxiv.org/abs/2206.07696) (TMLR 2022)\
  [![Star](https://img.shields.io/github/stars/Tobi-r9/RaMViD.svg?style=social\&label=Star)](https://github.com/Tobi-r9/RaMViD) ⭐ 105 | 🐛 4 | 🌐 Python | 📅 2023-11-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2206.07696)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/video-diffusion-prediction)

* [LayerFlow : A Unified Model for Layer-aware Video Generation](https://arxiv.org/abs/2506.04228) (May., 2025)
  [![Star](https://img.shields.io/github/stars/dvlab-research/Jenga.svg?style=social\&label=Star)](https://github.com/SihuiJi/LayerFlow) ⭐ 98 | 🐛 3 | 🌐 Python | 📅 2025-08-18\
  [![PDF](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.04228)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sihuiji.github.io/LayerFlow-Page/)

* [Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator](https://arxiv.org/abs/2309.14494) (Sep., 2023)\
  [![Star](https://img.shields.io/github/stars/SooLab/Free-Bloom.svg?style=social\&label=Star)](https://github.com/SooLab/Free-Bloom) ⭐ 97 | 🐛 2 | 🌐 Python | 📅 2024-03-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14494)

* [Progressive Autoregressive Video Diffusion Models](https://arxiv.org/abs/2410.08151) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/desaixie/pa_vdm.svg?style=social\&label=Star)](https://github.com/desaixie/pa_vdm) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2025-05-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.08151)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://desaixie.github.io/pa-vdm/)

* [VIDM: Video Implicit Diffusion Models](https://arxiv.org/abs/2212.00235) (AAAI 2023)\
  [![Star](https://img.shields.io/github/stars/MKFMIKU/VIDM.svg?style=social\&label=Star)](https://github.com/MKFMIKU/VIDM) ⭐ 68 | 🐛 3 | 🌐 Python | 📅 2023-11-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.00235)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kfmei.page/vidm/)

* [Diffusion Probabilistic Modeling for Video Generation](https://arxiv.org/abs/2203.09481) (Mar., 2022)\
  [![Star](https://img.shields.io/github/stars/buggyyang/RVD.svg?style=social\&label=Star)](https://github.com/buggyyang/RVD) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2026-01-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.09481)

* [SphereDiff: Tuning-free Omnidirectional Panoramic Image and Video Generation via Spherical Latent Representation](https://arxiv.org/abs/2504.14396) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/pmh9960/SphereDiff.svg?style=social\&label=Star)](https://github.com/pmh9960/SphereDiff) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2026-02-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.14396)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pmh9960.github.io/research/SphereDiff/)

* [TI2V-Zero: Zero-Shot Image Conditioning for Text-to-Video Diffusion Models](https://arxiv.org/abs/2404.16306) (CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/merlresearch/TI2V-Zero.svg?style=social\&label=Star)](https://github.com/merlresearch/TI2V-Zero) ⭐ 55 | 🐛 3 | 🌐 Python | 📅 2024-06-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16306)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://merl.com/research/highlights/TI2V-Zero)

* [VideoRepair: Improving Text-to-Video Generation via Misalignment Evaluation and Localized Refinement](https://arxiv.org/pdf/2411.15115) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/daeunni/VideoRepair.svg?style=social\&label=Star)](https://github.com/daeunni/VideoRepair) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2026-04-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15115)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-repair.github.io/)

* [Physics-Driven Diffusion Models for Impact Sound Synthesis from Videos](https://arxiv.org/abs/2303.16897) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/sukun1045/video-physics-sound-diffusion.svg?style=social\&label=Star)](https://github.com/sukun1045/video-physics-sound-diffusion) ⭐ 49 | 🐛 5 | 🌐 Python | 📅 2024-07-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.16897)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sukun1045.github.io/video-physics-sound-diffusion/)

* [Target-Aware Video Diffusion Models](https://arxiv.org/abs/2503.18950) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/taeksuu/tavid.svg?style=social\&label=Star)](https://github.com/taeksuu/tavid) ⭐ 45 | 🐛 1 | 🌐 Python | 📅 2026-02-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18950)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://taeksuu.github.io/tavid/)

* [Enhancing Motion in Text-to-Video Generation with Decomposed Encoding and Conditioning](https://arxiv.org/abs/2410.24219) (Oct., 2024 | NeurIPS 2024)\
  [![Star](https://img.shields.io/github/stars/PR-Ryan/DEMO.svg?style=social\&label=Star)](https://github.com/PR-Ryan/DEMO) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2024-11-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.24219)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pr-ryan.github.io/DEMO-project/)

* [ART•V: Auto-Regressive Text-to-Video Generation with Diffusion Models](https://arxiv.org/abs/2311.18834) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/WarranWeng/ART.V.svg?style=social\&label=Star)](https://github.com/WarranWeng/ART.V) ⭐ 43 | 🐛 3 | 📅 2023-11-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18834)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://warranweng.github.io/art.v/)

* [GenDeF: Learning Generative Deformation Field for Video Generation](https://arxiv.org/abs/2312.04561) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/aim-uofa/GenDeF.svg?style=social\&label=Star)](https://github.com/aim-uofa/GenDeF) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2026-03-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04561)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aim-uofa.github.io/GenDeF/)

* [Reuse and Diffuse: Iterative Denoising for Text-to-Video Generation](https://arxiv.org/abs/2309.03549) (Sep., 2023)\
  [![Star](https://img.shields.io/github/stars/anonymous0x233/ReuseAndDiffuse.svg?style=social\&label=Star)](https://github.com/anonymous0x233/ReuseAndDiffuse) ⭐ 38 | 🐛 0 | 🌐 Python | 📅 2023-11-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.03549)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous0x233.github.io/ReuseAndDiffuse/)

* [Video Diffusion Transformers are In-Context Learners](https://arxiv.org/abs/2412.10783) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/feizc/Video-In-Context.svg?style=social\&label=Star)](https://github.com/feizc/Video-In-Context) ⭐ 37 | 🐛 3 | 🌐 Python | 📅 2025-01-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.10783)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://huggingface.co/feizhengcong/Video-In-Context)

* [VideoDreamer: Customized Multi-Subject Text-to-Video Generation with Disen-Mix Finetuning](https://arxiv.org/abs/2311.00990) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/videodreamer23/videodreamer23.github.io.svg?style=social\&label=Star)](https://github.com/videodreamer23/videodreamer23.github.io) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00990)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videodreamer23.github.io/)

* [MotionCrafter: One-Shot Motion Customization of Diffusion Models](https://arxiv.org/abs/2312.05288) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/zyxElsa/MotionCrafter.svg?style=social\&label=Star)](https://github.com/zyxElsa/MotionCrafter) ⭐ 29 | 🐛 4 | 📅 2024-01-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05288)

* [Efficient Video Prediction via Sparsely Conditioned Flow Matching](https://arxiv.org/abs/2211.14575) (Nov., 2022)\
  [![Star](https://img.shields.io/github/stars/araachie/river.svg?style=social\&label=Star)](https://github.com/araachie/river) ⭐ 27 | 🐛 5 | 🌐 Python | 📅 2024-06-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.14575)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://araachie.github.io/river/)

* [Aligning Text-to-Video Generation Models with Prompt Optimization](https://arxiv.org/abs/2503.20491) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/thu-coai/VPO.svg?style=social\&label=Star)](https://github.com/thu-coai/VPO/tree/main) ⭐ 25 | 🐛 2 | 🌐 Python | 📅 2025-07-20
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.20491)

* [AnimateZoo: Zero-shot Video Generation of Cross-Species Animation via Subject Alignment](https://arxiv.org/abs/2404.04946) (Apr., 2024)\
  [![Star](https://img.shields.io/github/stars/JustinXu0/AnimateZoo.svg?style=social\&label=Star)](https://github.com/JustinXu0/AnimateZoo) ⭐ 22 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.04946)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://justinxu0.github.io/AnimateZoo/)

* [Inference-Time Text-to-Video Alignment with Diffusion Latent Beam Search](https://arxiv.org/abs/2501.19252) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/shim0114/T2V-Diffusion-Search.svg?style=social\&label=Star)](https://github.com/shim0114/T2V-Diffusion-Search) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2026-08-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.19252)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/t2v-dlbs)

* [Smooth Video Synthesis with Noise Constraints on Diffusion Models for One-shot Video Tuning](https://arxiv.org/abs/2311.17536) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/SPengLiang/SmoothVideo.svg?style=social\&label=Star)](https://github.com/SPengLiang/SmoothVideo) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2023-11-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17536)

* [FlowZero: Zero-Shot Text-to-Video Synthesis with LLM-Driven Dynamic Scene Syntax](https://arxiv.org/abs/2311.15813) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/aniki-ly/FlowZero.svg?style=social\&label=Star)](https://github.com/aniki-ly/FlowZero) ⭐ 18 | 🐛 0 | 📅 2023-11-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15813)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://flowzero-video.github.io/)

* [DreamVideo: High-Fidelity Image-to-Video Generation with Image Retention and Text Guidance](https://arxiv.org/abs/2312.03018) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/anonymous0769/DreamVideo.svg?style=social\&label=Star)](https://github.com/anonymous0769/DreamVideo) ⭐ 17 | 🐛 0 | 📅 2024-07-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03018)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous0769.github.io/DreamVideo/)

* [Empowering Dynamics-aware Text-to-Video Diffusion with Large Language Models](https://arxiv.org/abs/2308.13812) (Aug., 2023)\
  [![Star](https://img.shields.io/github/stars/scofield7419/Dysen.svg?style=social\&label=Star)](https://github.com/scofield7419/Dysen) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2024-03-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.13812)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://haofei.vip/Dysen-VDM/)

* [Learn the Force We Can: Enabling Sparse Motion Control in Multi-Object Video Generation](https://arxiv.org/abs/2306.03988) (Jun., 2023)\
  [![Star](https://img.shields.io/github/stars/araachie/yoda.svg?style=social\&label=Star)](https://github.com/araachie/yoda) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2025-02-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.03988)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://araachie.github.io/yoda/)

* [InfLVG: Reinforce Inference-Time Consistent Long Video Generation with GRPO](https://arxiv.org/abs/2505.17574) (May., 2025)
  [![Star](https://img.shields.io/github/stars/MAPLE-AIGC/InfLVG.svg?style=social\&label=Star)](https://github.com/MAPLE-AIGC/InfLVG) ⭐ 8 | 🐛 1 | 📅 2025-05-22\
  [![PDF](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.17574)

* [VISTA: A Test-Time Self-Improving Video Generation Agent](https://arxiv.org/abs/2510.15831) (Oct., 2025 | CVPR 2026)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.15831)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://g-vista.github.io/)

* [ReVision: High-Quality, Low-Cost Video Generation with Explicit 3D Physics Modeling for Complex Motion and Interaction](https://arxiv.org/abs/2504.21855) (Apr., 2025)\
  [![PDF](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.21855)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://revision-video.github.io/)

* [Turbo2K: Towards Ultra-Efficient and High-Quality 2K Video Synthesis](https://jingjingrenabc.github.io/turbo2k/) (Apr., 2025)\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jingjingrenabc.github.io/turbo2k/)

* [Seaweed-7B: Cost-Effective Training of Video Generation Foundation Model](https://seaweed.video/seaweed.pdf) (Apr., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.08685)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://seaweed.video/)

* [MagicComp: Training-free Dual-Phase Refinement for Compositional Video Generation](https://arxiv.org/abs/2503.14428) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/Hong-yu-Zhang/MagicComp.svg?style=social\&label=Star)](https://github.com/Hong-yu-Zhang/MagicComp)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.14428)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hong-yu-zhang.github.io/MagicComp-Page/)

* [Temporal Regularization Makes Your Video Generator Stronger](https://arxiv.org/abs/2503.15417) (Mar., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.15417)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://haroldchen19.github.io/FluxFlow/)

* [DLFR-VAE: Dynamic Latent Frame Rate VAE for Video Generation](https://arxiv.org/abs/2502.11897) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11897)

* [Magic 1-For-1: Generating One Minute Video Clips within One Minute](https://arxiv.org/abs/2502.07701) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/DA-Group-PKU/Magic-1-For-1.svg?style=social\&label=Star)](https://github.com/DA-Group-PKU/Magic-1-For-1)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07701)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-141.github.io/Magic-141/)

* [MotiF: Making Text Count in Image Animation with Motion Focal Loss](https://arxiv.org/abs/2412.16153) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.16153)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wang-sj16.github.io/motif/#BibTeX)

* [VideoDPO: Omni-Preference Alignment for Video Diffusion Generation](https://arxiv.org/pdf/2412.14167) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.14167)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videodpo.github.io/)

* [Track4Gen: Teaching Video Diffusion Models to Track Points Improves Video Generation](https://arxiv.org/abs/2412.06016) (Dec., 2024 | CVPR 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06016)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hyeonho99.github.io/track4gen/)

* [Instructional Video Generation](https://arxiv.org/abs/2412.04189) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04189)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://excitedbutter.github.io/Instructional-Video-Generation/)

* [Mimir: Improving Video Diffusion Models for Precise Text Understanding](https://arxiv.org/abs/2412.03085) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03085)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lucaria-academy.github.io/Mimir/)

* [Improved Video VAE for Latent Video Diffusion Model](https://arxiv.org/abs/2411.06449) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.06449)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wpy1999.github.io/IV-VAE/)

* [VideoAgent: Self-Improving Video Generation](https://arxiv.org/abs/2410.10076)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10076)

* [xGen-VideoSyn-1: High-fidelity Text-to-Video Synthesis with Compressed Representations](https://arxiv.org/abs/2408.12590) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/SalesforceAIResearch/xgen-videosyn.svg?style=social\&label=Star)](https://github.com/SalesforceAIResearch/xgen-videosyn)
  [![paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12590)

* [FreeLong: Training-Free Long Video Generation with SpectralBlend Temporal Attention](https://arxiv.org/abs/2407.19918) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.19918)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yulu.net.cn/freelong/)

* [ExVideo: Extending Video Diffusion Models via Parameter-Efficient Post-Tuning](https://arxiv.org/abs/2406.14130) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.14130)

* [Video-Infinity: Distributed Long Video Generation](https://arxiv.org/abs/2406.16260) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16260)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-infinity.tanzhenxiong.com/)

* [MotionBooth: Motion-Aware Customized Text-to-Video Generation](https://arxiv.org/abs/2406.17758) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jianzongwu.github.io/projects/motionbooth/)

* [Text-Animator: Controllable Visual Text Video Generation](https://arxiv.org/abs/2406.17777) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17777)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://laulampaul.github.io/text-animator.html)

* [UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation](https://arxiv.org/abs/2406.01188) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01188)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://unianimate.github.io/)

* [T2V-Turbo: Breaking the Quality Bottleneck of Video Consistency Model with Mixed Reward Feedback](https://arxiv.org/abs/2405.18750) (May, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18750)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-turbo.github.io/)

* [Collaborative Video Diffusion: Consistent Multi-video Generation with Camera Control](https://arxiv.org/abs/2405.17414) (May, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17414)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://collaborativevideodiffusion.github.io/)

* [Human4DiT: Free-view Human Video Generation with 4D Diffusion Transformer](https://arxiv.org/abs/2405.17405) (May, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17405)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://human4dit.github.io/)

* [Vidu: a Highly Consistent, Dynamic and Skilled Text-to-Video Generator with Diffusion Models](https://arxiv.org/abs/2405.04233) (May, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.04233)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.shengshu-ai.com/vidu)

* [TRIP: Temporal Residual Learning with Image Noise Prior for Image-to-Video Diffusion Models](https://arxiv.org/abs/2403.17005) (CVPR 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17005)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://trip-i2v.github.io/TRIP/)

* [VSTAR: Generative Temporal Nursing for Longer Dynamic Video Synthesis](https://arxiv.org/abs/2403.13501) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.13501)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yumengli007.github.io/VSTAR/)

* [Intention-driven Ego-to-Exo Video Generation](https://arxiv.org/abs/2403.09194) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.09194)

* [Snap Video: Scaled Spatiotemporal Transformers for Text-to-Video Synthesis](https://arxiv.org/abs/2402.14797) (Feb., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14797)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/snapvideo/)

* [One-Shot Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2402.14780) (Feb., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous-314.github.io/)

* [Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion](https://arxiv.org/abs/2402.03162) (Feb., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://direct-a-video.github.io/)

* [Boximator: Generating Rich and Controllable Motions for Video Synthesis](https://arxiv.org/abs/2402.01566) (Feb., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01566)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boximator.github.io/)

* [Lumiere: A Space-Time Diffusion Model for Video Generation](https://arxiv.org/abs/2401.12945) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.12945)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lumiere-video.github.io/)

* [ActAnywhere: Subject-Aware Video Background Generation](https://arxiv.org/abs/2401.10822) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10822)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://actanywhere.github.io/)

* [CustomVideo: Customizing Text-to-Video Generation with Multiple Subjects](https://arxiv.org/abs/2401.09962) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09962)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kyfafyd.wang/projects/customvideo/)

* [UniVG: Towards UNIfied-modal Video Generation](https://arxiv.org/abs/2401.09084) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09084)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://univg-baidu.github.io/)

* [360DVD: Controllable Panorama Video Generation with 360-Degree Video Diffusion Model](https://arxiv.org/abs/2401.06578) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.06578)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://akaneqwq.github.io/360DVD/)

* [RAVEN: Rethinking Adversarial Video Generation with Efficient Tri-plane Networks](https://arxiv.org/abs/2401.06035) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.06035)

* [MagicVideo-V2: Multi-Stage High-Aesthetic Video Generation](https://arxiv.org/abs/2401.04468) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04468)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magicvideov2.github.io/)

* [VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM](https://arxiv.org/abs/2401.01256) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01256)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videodrafter.github.io/)

* [FlashVideo: A Framework for Swift Inference in Text-to-Video Generation](https://arxiv.org/abs/2401.00869) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00869)

* [I2V-Adapter: A General Image-to-Video Adapter for Video Diffusion Models](https://arxiv.org/abs/2312.16693) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.16693)

* [A Recipe for Scaling up Text-to-Video Generation with Text-free Videos](https://arxiv.org/abs/2312.15770) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.15770)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tf-t2v.github.io/)

* [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14125)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.research.google/videopoet/)

* [VideoLCM: Video Latent Consistency Model](https://arxiv.org/abs/2312.09109) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09109)

* [Photorealistic Video Generation with Diffusion Models](https://arxiv.org/abs/2312.06662) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06662)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://walt-video-diffusion.github.io/)

* [MTVG : Multi-text Video Generation with Text-to-Video Models](https://arxiv.org/abs/2312.04086) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04086)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kuai-lab.github.io/mtvg-page)

* [GenTron: Delving Deep into Diffusion Transformers for Image and Video Generation](https://arxiv.org/abs/2312.04557) (CVPR 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04557)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.shoufachen.com/gentron_website/)

* [F3-Pruning: A Training-Free and Generalized Pruning Strategy towards Faster and Finer Text-to-Video Synthesis](https://arxiv.org/abs/2312.03459) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03459)

* [Fine-grained Controllable Video Generation via Object Appearance and Context](https://arxiv.org/abs/2312.02919) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02919)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hhsinping.github.io/factor/)

* [MicroCinema: A Divide-and-Conquer Approach for Text-to-Video Generation](https://arxiv.org/abs/2311.18829) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18829)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wangyanhui666.github.io/MicroCinema.github.io/)

* [VideoAssembler: Identity-Consistent Video Generation with Reference Entities using Diffusion Model](https://arxiv.org/abs/2311.17338) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17338)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoassembler.github.io/videoassembler/)

* [MotionZero:Exploiting Motion Priors for Zero-shot Text-to-Video Generation](https://arxiv.org/abs/2311.16635) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16635)

* [Decouple Content and Motion for Conditional Image-to-Video Generation](https://arxiv.org/abs/2311.14294) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.14294)

* [MoVideo: Motion-Aware Video Generation with Diffusion Models](https://arxiv.org/abs/2311.11325) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11325)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jingyunliang.github.io/MoVideo/)

* [Make Pixels Dance: High-Dynamic Video Generation](https://arxiv.org/abs/2311.10982) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10982)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://makepixelsdance.github.io/)

* [Emu Video: Factorizing Text-to-Video Generation by Explicit Image Conditioning](https://arxiv.org/abs/2311.10709) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10709)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://emu-video.metademolab.com/)

* [Optimal Noise pursuit for Augmenting Text-to-Video Generation](https://arxiv.org/abs/2311.00949) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00949)

* [Hierarchical Masked 3D Diffusion Model for Video Outpainting](https://arxiv.org/abs/2309.02119) (Sep., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.02119)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fanfanda.github.io/M3DDM/)

* [VideoGen: A Reference-Guided Latent Diffusion Approach for High Definition Text-to-Video Generation](https://arxiv.org/abs/2309.00398) (Sep., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.00398)

* [ModelScope Text-to-Video Technical Report](https://arxiv.org/abs/2308.06571) (Aug., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.06571)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://modelscope.cn/models/damo/text-to-video-synthesis/summary)

* [Dual-Stream Diffusion Net for Text-to-Video Generation](https://arxiv.org/abs/2308.08316) (Aug., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08316)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous.4open.science/r/Private-C3E8)

* [Probabilistic Adaptation of Text-to-Video Models](https://arxiv.org/abs/2306.01872) (Jun., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.01872)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-adapter.github.io/video-adapter/)

* [VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation](https://arxiv.org/abs/2305.10874) (May, 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10874)

* [Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models](https://arxiv.org/abs/2305.10474) (May, 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10474)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/pyoco/)

* [LaMD: Latent Motion Diffusion for Video Generation](https://arxiv.org/abs/2304.11603) (Apr., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.11603)

* [Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2304.08818) (CVPR 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08818)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/VideoLDM/)

* [Generative Disco: Text-to-Video Generation for Music Visualization](https://arxiv.org/abs/2304.08551) (Apr., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08551)

* [Latent-Shift: Latent Diffusion with Temporal Shift](https://arxiv.org/abs/2304.08477) (Apr., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08477)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://latent-shift.github.io/)

* [Seer: Language Instructed Video Prediction with Latent Diffusion Models](https://arxiv.org/abs/2303.14897) (Mar., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14897)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://seervideodiffusion.github.io/)

* [Decomposed Diffusion Models for High-Quality Video Generation](https://arxiv.org/abs/2303.08320) (CVPR 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.08320)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://modelscope.cn/models/damo/text-to-video-synthesis/summary)

* [Learning 3D Photography Videos via Self-supervised Diffusion on Single Images](https://arxiv.org/abs/2302.10781) (Feb., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.10781)

* [Structure and Content-Guided Video Synthesis With Diffusion Models](https://arxiv.org/abs/2302.03011) (Feb., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03011)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.runwayml.com/gen2)

* [MagicVideo: Efficient Video Generation With Latent Diffusion Models](https://arxiv.org/abs/2211.11018) (Nov., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.11018)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magicvideo.github.io/#)

* [Imagen Video: High Definition Video Generation With Diffusion Models](https://arxiv.org/abs/2210.02303) (Oct., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.02303)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://imagen.research.google/video/)

* [Make-A-Video: Text-to-Video Generation without Text-Video Data](https://openreview.net/forum?id=nJfylDvgzlq) (ICLR 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openreview.net/forum?id=nJfylDvgzlq)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://makeavideo.studio)

* [Video Diffusion Models](https://arxiv.org/abs/2204.03458) (Apr., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.03458)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-diffusion.github.io/)

### Efficient Video Generation

* [SageAttention2: Efficient Attention with Thorough Outlier Smoothing and Per-thread INT4 Quantization](https://arxiv.org/abs/2411.10958) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/thu-ml/SageAttention)](https://github.com/thu-ml/SageAttention) ⭐ 3,697 | 🐛 209 | 🌐 Cuda | 📅 2026-01-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10958)

* [SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference Acceleration](https://arxiv.org/abs/2410.02367) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/thu-ml/SageAttention)](https://github.com/thu-ml/SageAttention) ⭐ 3,697 | 🐛 209 | 🌐 Cuda | 📅 2026-01-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02367)

* [SpargeAttn: Accurate Sparse Attention Accelerating Any Model Inference](https://arxiv.org/abs/2502.18137) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/thu-ml/SpargeAttn)](https://github.com/thu-ml/SpargeAttn) ⭐ 1,043 | 🐛 64 | 🌐 Cuda | 📅 2026-02-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.18137)

* [FlashVideo:Flowing Fidelity to Detail for Efficient High-Resolution Video Generation](https://arxiv.org/abs/2502.05179) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/FoundationVision/FlashVideo.svg?style=social\&label=Star)](https://github.com/FoundationVision/FlashVideo) ⭐ 483 | 🐛 14 | 🌐 Python | 📅 2025-03-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.05179)

* [Adaptive Caching for Faster Video Generation with Diffusion Transformers](https://arxiv.org/pdf/2411.02397) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/AdaCache-DiT/AdaCache.svg?style=social\&label=Star)](https://github.com/AdaCache-DiT/AdaCache) ⭐ 172 | 🐛 7 | 🌐 Python | 📅 2024-11-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.02397)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://adacache-dit.github.io/)

* [CachedSearch: Training-Free Cached Exploration for Test-Time Search in Video Diffusion](https://arxiv.org/abs/2607.23159) (Jul., 2026)\
  [![Star](https://img.shields.io/github/stars/shreshthsaini/CachedSearch.svg?style=social\&label=Star)](https://github.com/shreshthsaini/CachedSearch) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2607.23159)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shreshthsaini.github.io/CachedSearch/)

* [Fast Video Generation with Sliding Tile Attention](https://arxiv.org/abs/2502.04507) (Feb, 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.04507)

* [Sparse VideoGen: Accelerating Video Diffusion Transformers with Spatial-Temporal Sparsity](https://arxiv.org/abs/2502.01776) (Feb, 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01776)

* [Diffusion Adversarial Post-Training for One-Step Video Generation](https://arxiv.org/abs/2501.08316) (Jan, 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08316)

* [From Slow Bidirectional to Fast Causal Video Generators](https://arxiv.org/pdf/2412.07772) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07772)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://causvid.github.io/)

* [SnapGen-V: Generating a Five-Second Video within Five Seconds on a Mobile Device](https://arxiv.org/pdf/2412.10494) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.10494)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/snapgen-v/)

* [Mobile Video Diffusion](https://arxiv.org/abs/2412.07583) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07583)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://qualcomm-ai-research.github.io/mobile-video-diffusion/)

* [MoViE: Mobile Diffusion for Video Editing](https://arxiv.org/abs/2412.06578) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06578)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://qualcomm-ai-research.github.io/mobile-video-editing/)

* [Individual Content and Motion Dynamics Preserved Pruning for Video Diffusion Models](https://arxiv.org/abs/2411.18375) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18375)

* [Fast and Memory-Efficient Video Diffusion Using Streamlined Inference](https://arxiv.org/abs/2411.01171) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.01171)

### Controllable Video Generation

* [LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/abs/2407.03168) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/KwaiVGI/LivePortrait.svg?style=social\&label=Star)](https://github.com/KwaiVGI/LivePortrait) ⭐ 19,002 | 🐛 289 | 🌐 Python | 📅 2026-06-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.03168)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/KwaiVGI/LivePortrait) ⭐ 19,002 | 🐛 289 | 🌐 Python | 📅 2026-06-01

* [Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation](https://arxiv.org/abs/2311.17117) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/HumanAIGC/AnimateAnyone.svg?style=social\&label=Star)](https://github.com/HumanAIGC/AnimateAnyone) ⭐ 14,788 | 🐛 83 | 📅 2025-09-20
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanaigc.github.io/animate-anyone/)

* [Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance](https://arxiv.org/abs/2403.14781) (Mar., 2024)\
  [![Star](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social\&label=Star)](https://github.com/fudan-generative-vision/champ) ⭐ 4,262 | 🐛 49 | 🌐 Python | 📅 2024-07-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fudan-generative-vision.github.io/champ/)

* [ReCamMaster: Camera-Controlled Generative Rendering from A Single Video](https://arxiv.org/abs/2503.11647) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/KwaiVGI/ReCamMaster.svg?style=social\&label=Star)](https://github.com/KwaiVGI/ReCamMaster) ⭐ 1,856 | 🐛 72 | 🌐 Python | 📅 2025-11-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11647)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jianhongbai.github.io/ReCamMaster/)

* [ControlNeXt: Powerful and Efficient Control for Image and Video Generation](https://arxiv.org/pdf/2408.06070) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/dvlab-research/ControlNeXt.svg?style=social\&label=Star)](https://github.com/dvlab-research/ControlNeXt) ⭐ 1,647 | 🐛 52 | 🌐 Python | 📅 2024-09-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.06070)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pbihao.github.io/projects/controlnext/index.html)

* [MotionCtrl: A Unified and Flexible Motion Controller for Video Generation](https://arxiv.org/abs/2312.03641) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/TencentARC/MotionCtrl.svg?style=social\&label=Star)](https://github.com/TencentARC/MotionCtrl) ⭐ 1,500 | 🐛 29 | 🌐 Python | 📅 2025-02-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03641)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/MotionCtrl/)

* [GEN3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control](https://arxiv.org/abs/2503.03751) (Mar., 2025 | CVPR 2025)\
  [![Star](https://img.shields.io/github/stars/nv-tlabs/GEN3C.svg?style=social\&label=Star)](https://github.com/nv-tlabs/GEN3C) ⭐ 1,413 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2026-06-15
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.03751)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/GEN3C/)

* [Tora: Trajectory-oriented Diffusion Transformer for Video Generation](https://arxiv.org/abs/2407.21705) (Jul., 2024 | CVPR 2025)\
  [![Star](https://img.shields.io/github/stars/alibaba/Tora.svg?style=social\&label=Star)](https://github.com/alibaba/Tora) ⭐ 1,241 | 🐛 11 | 🌐 Python | 📅 2026-07-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21705)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ali-videoai.github.io/tora_video/)

* [ControlVideo: Training-free Controllable Text-to-Video Generation](https://arxiv.org/abs/2305.13077) (May, 2023)\
  [![Star](https://img.shields.io/github/stars/YBYBZhang/ControlVideo.svg?style=social\&label=Star)](https://github.com/YBYBZhang/ControlVideo) ⭐ 862 | 🐛 3 | 🌐 Python | 📅 2023-10-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13077)

* [Identity-Preserving Text-to-Video Generation by Frequency Decomposition](https://arxiv.org/abs/2411.17440) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/ConsisID) ⭐ 856 | 🐛 36 | 🌐 Python | 📅 2026-04-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/ConsisID/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/BestWishYsh/ConsisID-preview-Data)

* [UniAnimate-DiT: Human Image Animation with Large-Scale Video Diffusion Transformer](https://kszpxxzmc.github.io/GenDoP/) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/ali-vilab/UniAnimate-DiT.svg?style=social\&label=Star)](https://github.com/ali-vilab/UniAnimate-DiT) ⭐ 851 | 🐛 44 | 🌐 Python | 📅 2025-04-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.11289)

* [MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model](https://arxiv.org/abs/2405.20222) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social\&label=Star)](https://github.com/MyNiuuu/MOFA-Video) ⭐ 766 | 🐛 24 | 🌐 Python | 📅 2024-12-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://myniuuu.github.io/MOFA_Video/)

* [Enabling Versatile Controls for Video Diffusion Models](https://arxiv.org/abs/2503.16983) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/PaddlePaddle/PaddleMIX.svg?style=social\&label=Star)](https://github.com/PaddlePaddle/PaddleMIX/tree/develop/ppdiffusers/examples/ppvctrl) ⭐ 724 | 🐛 152 | 🌐 Python | 📅 2026-03-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.16421)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pp-vctrl.github.io)

* [SynCamMaster: Synchronizing Multi-Camera Video Generation from Diverse Viewpoints](https://arxiv.org/abs/2412.07760) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/KwaiVGI/SynCamMaster.svg?style=social\&label=Star)](https://github.com/KwaiVGI/SynCamMaster) ⭐ 697 | 🐛 21 | 🌐 Python | 📅 2025-05-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07760)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jianhongbai.github.io/SynCamMaster/)

* [CameraCtrl: Enabling Camera Control for Video Diffusion Models](https://arxiv.org/abs/2404.02101) (Apr., 2024)\
  [![Star](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social\&label=Star)](https://github.com/hehao13/CameraCtrl) ⭐ 664 | 🐛 28 | 🌐 Python | 📅 2024-05-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hehao13.github.io/projects-CameraCtrl/)

* [VideoPainter: Any-length Video Inpainting and Editing with Plug-and-Play Context Control](https://arxiv.org/abs/2503.05639) (May, 2025 | SIGGRAPH 2025)\
  [![Star](https://img.shields.io/github/stars/TencentARC/VideoPainter.svg?style=social\&label=Star)](https://github.com/TencentARC/VideoPainter) ⭐ 633 | 🐛 16 | 🌐 Python | 📅 2025-04-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.05639)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yxbian23.github.io/project/video-painter/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/collections/TencentARC/videopainter-67cc49c6146a48a2ba93d159)

* [X-Portrait: Expressive Portrait Animation with Hierarchical Motion Attention](https://arxiv.org/abs/2403.15931) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15931)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://byteaigc.github.io/x-portrait/)
  [![Star](https://img.shields.io/github/stars/bytedance/X-Portrait.svg?style=social\&label=Star)](https://github.com/bytedance/X-Portrait) ⭐ 541 | 🐛 13 | 🌐 Python | 📅 2025-10-14

* [Light-A-Video: Training-free Video Relighting via Progressive Light Fusion](https://arxiv.org/abs/2502.08590) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/bcmi/Light-A-Video.svg?style=social\&label=Star)](https://github.com/bcmi/Light-A-Video/) ⭐ 519 | 🐛 17 | 🌐 Python | 📅 2025-10-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08590)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bujiazi.github.io/light-a-video.github.io/)

* [DragAnything: Motion Control for Anything using Entity Representation](https://arxiv.org/abs/2403.07420) (ECCV, 2024)\
  [![Star](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social\&label=Star)](https://github.com/showlab/DragAnything) ⭐ 506 | 🐛 20 | 🌐 Python | 📅 2024-07-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07420)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://weijiawu.github.io/draganything_page/)

* [FRAMER: INTERACTIVE FRAME INTERPOLATION](https://arxiv.org/pdf/2410.18978) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/aim-uofa/Framer.svg?style=social\&label=Star)](https://github.com/aim-uofa/Framer) ⭐ 500 | 🐛 7 | 🌐 Python | 📅 2025-01-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.18978)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aim-uofa.github.io/Framer/)

* [Video-As-Prompt: Unified Semantic Control for Video Generation](https://arxiv.org/pdf/2510.20888) (Nov, 2025)\
  [![Star](https://img.shields.io/github/stars/bytedance/Video-As-Prompt.svg?style=social\&label=Star)](https://github.com/bytedance/Video-As-Prompt) ⭐ 452 | 🐛 6 | 🌐 Python | 📅 2026-02-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.20888)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bytedance.github.io/Video-As-Prompt/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/BianYx/VAP-Data)

* [Control-A-Video: Controllable Text-to-Video Generation with Diffusion Models](https://arxiv.org/abs/2305.13840) (May, 2023)\
  [![Star](https://img.shields.io/github/stars/Weifeng-Chen/control-a-video.svg?style=social\&label=Star)](https://github.com/Weifeng-Chen/control-a-video) ⭐ 402 | 🐛 19 | 🌐 Python | 📅 2023-07-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://controlavideo.github.io/)

* [3DTrajMaster: Mastering 3D Trajectory for Multi-Entity Motion in Video Generation](https://drive.google.com/file/d/111Z5CMJZupkmg-xWpV4Tl4Nb7SRFcoWx/view) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/KwaiVGI/3DTrajMaster.svg?style=social\&label=Star)](https://github.com/KwaiVGI/3DTrajMaster) ⭐ 371 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-07-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://drive.google.com/file/d/111Z5CMJZupkmg-xWpV4Tl4Nb7SRFcoWx/view)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/ObjCtrl-2.5D/)

* [FlipSketch: Flipping assets Drawings to Text-Guided Sketch Animations](https://arxiv.org/pdf/2411.10818) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/hmrishavbandy/FlipSketch.svg?style=social\&label=Star)](https://github.com/hmrishavbandy/FlipSketch) ⭐ 359 | 🐛 6 | 🌐 Python | 📅 2025-06-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.10818)

* [ATI: Any Trajectory Instruction for Controllable Video Generation](https://arxiv.org/pdf/2505.22944) (Jun., 2025)
  [![Star](https://img.shields.io/github/stars/bytedance/ATI.svg?style=social\&label=Star)](https://github.com/bytedance/ATI) ⭐ 357 | 🐛 6 | 🌐 Python | 📅 2025-08-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.22944)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anytraj.github.io/)

* [HumanVid: Demystifying Training Data for Camera-controllable Human Image Animation](https://arxiv.org/pdf/2407.17438) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/zhenzhiwang/HumanVid.svg?style=social\&label=Star)](https://github.com/zhenzhiwang/HumanVid) ⭐ 350 | 🐛 0 | 🌐 Python | 📅 2026-05-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.17438)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanvid.github.io/#)

* [FlexiAct: Towards Flexible Action Control in Heterogeneous Scenarios](https://arxiv.org/abs/2505.03730) (May, 2025 | SIGGRAPH 2025)\
  [![Star](https://img.shields.io/github/stars/shiyi-zh0408/FlexiAct.svg?style=social\&label=Star)](https://github.com/shiyi-zh0408/FlexiAct) ⭐ 341 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2025-10-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.03730)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shiyi-zh0408.github.io/projectpages/FlexiAct/)

* [Cinemo: Consistent and Controllable Image Animation with Motion Diffusion Models](https://arxiv.org/abs/2407.15642) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/maxin-cn/Cinemo.svg?style=social\&label=Star)](https://github.com/maxin-cn/Cinemo) ⭐ 296 | 🐛 3 | 🌐 Python | 📅 2025-05-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.15642)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maxin-cn.github.io/cinemo_project/)

* [Identifying and Solving Conditional Image Leakage in Image-to-Video Diffusion Model](https://arxiv.org/abs/2406.15735) (Jun., 2024 | NeurIPS 2024)\
  [![Star](https://img.shields.io/github/stars/thu-ml/cond-image-leakage.svg?style=social\&label=Star)](https://github.com/thu-ml/cond-image-leakage/tree/main?tab=readme-ov-file) ⭐ 257 | 🐛 8 | 📅 2026-03-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15735)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cond-image-leak.github.io/)

* [LayerAnimate: Layer-level Control for Animation](https://arxiv.org/abs/2501.08295) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/IamCreateAI/LayerAnimate.svg?style=social\&label=Star)](https://github.com/IamCreateAI/LayerAnimate) ⭐ 196 | 🐛 0 | 🌐 Python | 📅 2025-08-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08295)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://layeranimate.github.io/)

* [AnimateAnything: Consistent and Controllable Animation for video generation](https://arxiv.org/pdf/2411.10836) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/yu-shaonian/AnimateAnything.svg?style=social\&label=Star)](https://github.com/yu-shaonian/AnimateAnything) ⭐ 188 | 🐛 2 | 📅 2025-06-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.10836)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yu-shaonian.github.io/Animate_Anything/)

* [MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance](https://arxiv.org/abs/2503.16421) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/quanhaol/MagicMotion.svg?style=social\&label=Star)](https://github.com/quanhaol/MagicMotion) ⭐ 187 | 🐛 7 | 🌐 Python | 📅 2026-02-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.16421)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://quanhaol.github.io/magicmotion-site/)

* [CamI2V: Camera-Controlled Image-to-Video Diffusion Model](https://arxiv.org/pdf/2410.15957) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/ZGCTroy/CamI2V.svg?style=social\&label=Star)](https://github.com/ZGCTroy/CamI2V) ⭐ 171 | 🐛 9 | 🌐 Python | 📅 2025-09-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.15957)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zgctroy.github.io/CamI2V/)

* [DynamiCtrl: Rethinking the Basic Structure and the Role of Text for High-quality Human Image Animation](https://arxiv.org/abs/2503.21246) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/gulucaptain/DynamiCtrl.svg?style=social\&label=Star)](https://github.com/gulucaptain/DynamiCtrl) ⭐ 142 | 🐛 2 | 🌐 Python | 📅 2025-05-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21246)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gulucaptain.github.io/DynamiCtrl/)

* [GenDoP: Auto-regressive Camera Trajectory Generation as a Director of Photography](https://arxiv.org/abs/2504.07083) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/3DTopia/GenDoP.svg?style=social\&label=Star)](https://github.com/3DTopia/GenDoP) ⭐ 129 | 🐛 2 | 🌐 Python | 📅 2025-12-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.07083)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kszpxxzmc.github.io/GenDoP/)

* [GenDoP: Auto-regressive Camera Trajectory Generation as a Director of Photography](https://kszpxxzmc.github.io/GenDoP/) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/3DTopia/GenDoP.svg?style=social\&label=Star)](https://github.com/3DTopia/GenDoP) ⭐ 129 | 🐛 2 | 🌐 Python | 📅 2025-12-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.07083)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kszpxxzmc.github.io/GenDoP/)

* [BlobGEN-Vid: Compositional Text-to-Video Generation with Blob Video Representations](https://arxiv.org/abs/2501.07647) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/Tian-one/FCVG.svg?style=social\&label=Star)](https://github.com/Tian-one/FCVG) ⭐ 118 | 🐛 2 | 🌐 Python | 📅 2025-02-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.07647)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://blobgen-vid2.github.io/)

* [Generative Inbetweening through Frame-wise Conditions-Driven Video Generation](https://arxiv.org/abs/2412.11755) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/Tian-one/FCVG.svg?style=social\&label=Star)](https://github.com/Tian-one/FCVG) ⭐ 118 | 🐛 2 | 🌐 Python | 📅 2025-02-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11755)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fcvg-inbetween.github.io/)

* [SG-I2V: Self-Guided Trajectory Control in Image-to-Video Generation](https://arxiv.org/pdf/2411.04989) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04989)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kmcode1.github.io/Projects/SG-I2V/)
  [![Star](https://img.shields.io/github/stars/Kmcode1/SG-I2V.svg?style=social\&label=Star)](https://github.com/Kmcode1/SG-I2V) ⭐ 116 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-11-26

* [FreeTraj: Tuning-Free Trajectory Control in Video Diffusion Models](https://arxiv.org/abs/2406.16863) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social\&label=Star)](https://github.com/arthur-qiu/FreeTraj) ⭐ 114 | 🐛 0 | 🌐 Python | 📅 2025-09-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16863)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://haonanqiu.com/projects/FreeTraj.html)

* [IllumiCraft: Unified Geometry and Illumination Diffusion for Controllable Video Generation](https://arxiv.org/abs/2506.03150) (Jun., 2025)
  [![Star](https://img.shields.io/github/stars/UVA-Computer-Vision-Lab/FrameINO.svg?style=social\&label=Star)](https://github.com/yuanze-lin/IllumiCraft) ⭐ 111 | 🐛 0 | 🌐 Python | 📅 2026-07-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.03150)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yuanze-lin.me/IllumiCraft_page/)

* [SketchVideo: Sketch-based Video Generation and Editing](https://arxiv.org/abs/2503.23284) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/IGLICT/SketchVideo.svg?style=social\&label=Star)](https://github.com/IGLICT/SketchVideo) ⭐ 106 | 🐛 3 | 🌐 Python | 📅 2025-04-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.23284)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://geometrylearning.com/SketchVideo/)

* [TrailBlazer: Trajectory Control for Diffusion-Based Video Generation](https://arxiv.org/abs/2401.00896) (Jan., 2024)\
  [![Star](https://img.shields.io/github/stars/hohonu-vicml/Trailblazer.svg?style=social\&label=Star)](https://github.com/hohonu-vicml/Trailblazer) ⭐ 102 | 🐛 4 | 🌐 Python | 📅 2024-05-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00896)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hohonu-vicml.github.io/Trailblazer.Page/)

* [Image Conductor: Precision Control for Interactive Video Synthesis](https://arxiv.org/pdf/2406.15339) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social\&label=Star)](https://github.com/liyaowei-stu/ImageConductor) ⭐ 101 | 🐛 4 | 🌐 Python | 📅 2024-07-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.15339)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://liyaowei-stu.github.io/project/ImageConductor/)

* [TC-Light: Temporally Coherent Generative Rendering for Realistic World Transfer](https://arxiv.org/abs/2506.18904) (Jun., 2025)
  [![Star](https://img.shields.io/github/stars/Linketic/TC-Light.svg?style=social\&label=Star)](https://github.com/Linketic/TC-Light) ⭐ 94 | 🐛 2 | 🌐 Python | 📅 2025-11-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.18904)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dekuliutesla.github.io/tclight/)

* [MusicInfuser: Making Video Diffusion Listen and Dance](https://arxiv.org/abs/2503.14505) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/SusungHong/MusicInfuser.svg?style=social\&label=Star)](https://github.com/SusungHong/MusicInfuser) ⭐ 86 | 🐛 4 | 🌐 Python | 📅 2026-05-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14505)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://susunghong.github.io/MusicInfuser)

* [Reangle-A-Video: 4D Video Generation as Video-to-Video Translation](https://arxiv.org/abs/2503.09151) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/HyeonHo99/Reangle-Video.svg?style=social\&label=Star)](https://github.com/HyeonHo99/Reangle-Video) ⭐ 83 | 🐛 1 | 🌐 Python | 📅 2025-07-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.09151)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hyeonho99.github.io/reangle-a-video/)

* [Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation](https://arxiv.org/pdf/2501.05020) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.05020)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chen-yingjie.github.io/projects/Perception-as-Control/)
  [![Star](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social\&label=Star)](https://github.com/chen-yingjie/Perception-as-Control) ⭐ 81 | 🐛 2 | 🌐 Python | 📅 2025-08-05

* [ObjCtrl-2.5D: Training-free Object Control with Camera Poses](https://arxiv.org/pdf/2412.07721) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/wzhouxiff/ObjCtrl-2.5D.svg?style=social\&label=Star)](https://github.com/wzhouxiff/ObjCtrl-2.5D) ⭐ 60 | 🐛 2 | 🌐 Python | 📅 2025-04-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07721)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/ObjCtrl-2.5D/)

* [FloVD: Optical Flow Meets Video Diffusion Model for Camera-Controlled Video Synthesis](https://jinwonjoon.github.io/flovd_site/FloVD_files/main.pdf) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social\&label=Star)](https://github.com/JinWonjoon/FloVD/) ⭐ 53 | 🐛 5 | 🌐 Python | 📅 2025-05-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://jinwonjoon.github.io/flovd_site/FloVD_files/main.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jinwonjoon.github.io/flovd_site/)

* [OmniVDiff: Omni Controllable Video Diffusion for Generation and Understanding](https://tele-ai.github.io/OmniVDiff/) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/Tele-AI/OmniVDiff.svg?style=social\&label=Star)](https://github.com/Tele-AI/OmniVDiff) ⭐ 48 | 🐛 5 | 🌐 Python | 📅 2025-12-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10825)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tele-ai.github.io/OmniVDiff/)

* [AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance](https://arxiv.org/abs/2502.08189) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/AnyCharV/AnyCharV.svg?style=social\&label=Star)](https://github.com/AnyCharV/AnyCharV) ⭐ 41 | 🐛 2 | 🌐 Python | 📅 2025-02-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anycharv.github.io/)

* [Frame In-N-Out: Unbounded Controllable Image-to-Video Generation](https://arxiv.org/abs/2505.21491) (May, 2025)
  [![Star](https://img.shields.io/github/stars/UVA-Computer-Vision-Lab/FrameINO.svg?style=social\&label=Star)](https://github.com/UVA-Computer-Vision-Lab/FrameINO) ⭐ 33 | 🐛 3 | 🌐 Python | 📅 2026-05-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.21491)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://uva-computer-vision-lab.github.io/Frame-In-N-Out/)

* [EgoControl: Controllable Egocentric Video Generation via 3D Full-Body Poses](https://arxiv.org/abs/2511.18173) (CVPR 2026)
  [![Star](https://img.shields.io/github/stars/CVG-Bonn/EgoControl.svg?style=social\&label=Star)](https://github.com/CVG-Bonn/EgoControl/) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-07-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.18173)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cvg-bonn.github.io/EgoControl/)

* [Consistent Human Image and Video Generation with Spatially Conditioned Diffusion](https://arxiv.org/abs/2412.14531) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/ljzycmd/SCD.svg?style=social\&label=Star)](https://github.com/ljzycmd/SCD) ⭐ 17 | 🐛 0 | 📅 2025-09-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14531)

* [**ID-Crafter: VLM-Grounded Online RL for Compositional Multi-Subject Video Generation**](https://arxiv.org/pdf/2511.00511v3) (CVPR, 2026) [![Star](https://img.shields.io/github/stars/paulpanwang/ID-Crafter.svg?style=social\&label=Star)](https://github.com/paulpanwang/ID-Crafter) ⭐ 15 | 🐛 1 | 🌐 Shell | 📅 2026-03-24 [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.00511v3) [![Website](https://img.shields.io/badge/Website-9cf)](https://paulpanwang.github.io/ID-Crafter)

* [C-Drag: Chain-of-Thought Driven Motion Controller for Video Generation](https://arxiv.org/abs/2502.19868) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/WesLee88524/C-Drag-Official-Repo.svg?style=social\&label=Star)](https://github.com/WesLee88524/C-Drag-Official-Repo) ⭐ 14 | 🐛 5 | 🌐 Python | 📅 2025-02-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.19868)

* [Beyond Static Scenes: Camera-controllable Background Generation for Human Motion](https://yaomingshuai.github.io/Beyond-Static-Scenes.github.io/) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/Yaomingshuai/Beyond-Static-Scenes.svg?style=social\&label=Star)](https://github.com/Yaomingshuai/Beyond-Static-Scenes) ⭐ 13 | 🐛 1 | 📅 2025-04-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02004)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yaomingshuai.github.io/Beyond-Static-Scenes.github.io/)

* [PhyCo: Learning Controllable Physical Priors for Generative Motion](https://phyco-video.github.io/) (CVPR 2026)
  [![Star](https://img.shields.io/github/stars/nnsriram97/phyco.svg?style=social\&label=Star)](https://github.com/nnsriram97/phyco) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-06-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.28169)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://phyco-video.github.io/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/nnsriram97/phyco_kubric)
  [![Simulation Code](https://img.shields.io/badge/Simulation_Code-blue)](https://github.com/nnsriram97/phyco-sim) ⭐ 14 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-06-08

* [HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation](https://arxiv.org/pdf/2503.18860) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/kkakkkka/HunyuanPortrait.svg?style=social\&label=Star)](https://github.com/kkakkkka/HunyuanPortrait) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-03-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.18860)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kkakkkka.github.io/HunyuanPortrait/)

* [Hand2World: Autoregressive Egocentric Interaction Generation via Free-Space Hand Gestures](https://arxiv.org/abs/2602.09600) (Feb, 2026)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.09600)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hand2world.github.io/)

* [Dynamic Camera Poses and Where to Find Them](https://arxiv.org/abs/2504.17788) (Apr., 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.17788)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/dynpose-100k/)

* [Any2Caption:Interpreting Any Condition to Caption for Controllable Video Generation](https://arxiv.org/abs/2503.24379) (Apr., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.24379)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sqwu.top/Any2Cap/)

* [CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models](https://arxiv.org/abs/2503.10592) (Mar., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10592)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hehao13.github.io/Projects-CameraCtrl-II/)

* [X-Dancer: Expressive Music to Human Dance Video Generation](https://arxiv.org/pdf/2502.17414) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.17414)

* [CineMaster: A 3D-Aware and Controllable Framework for Cinematic Text-to-Video Generation](https://arxiv.org/abs/2502.08639) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08639)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cinemaster-dev.github.io/)

* [RealCam-I2V: Real-World Image-to-Video Generation with Interactive Complex Camera Control](https://arxiv.org/abs/2502.10059) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10059)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zgctroy.github.io/RealCam-I2V/)

* [A 3D-Aware and Controllable Framework for Cinematic Text-to-Video Generation](https://arxiv.org/abs/2502.08639) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08639)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cinemaster-dev.github.io/)

* [VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation](https://arxiv.org/pdf/2502.07531) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.07531)

* [MotionCanvas: Cinematic Shot Design with Controllable Image-to-Video Generation](https://arxiv.org/abs/2502.04299) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.04299)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://motion-canvas25.github.io/)

* [MotionCanvas: Cinematic Shot Design with Controllable Image-to-Video Generation](https://arxiv.org/pdf/2502.04299) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.04299)

* [DynVFX: Augmenting Real Videos with Dynamic Content](https://arxiv.org/pdf/2502.03621) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.03621)

* [MotionAgent: Fine-grained Controllable Video Generation via Motion Field Agent](https://arxiv.org/pdf/2502.03207) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.03207)

* [RelightVid: Temporal-Consistent Diffusion Model for Video Relighting](https://arxiv.org/abs/2501.16330) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.16330)

* [On Unifying Video Generation and Camera Pose Estimation](https://arxiv.org/abs/2501.01409) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01409)

* [VideoAnydoor: High-fidelity Video Object Insertion with Precise Motion Control](https://arxiv.org/pdf/2501.01427) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.01427)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoanydoor.github.io/)

* [DirectorLLM for Human-Centric Video Generation](https://arxiv.org/pdf/2412.14484) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.14484)

* [InterDyn: Controllable Interactive Dynamics with Video Diffusion Models](https://interdyn.is.tue.mpg.de/media/upload/interdyn_video.pdf) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://interdyn.is.tue.mpg.de/media/upload/interdyn_video.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://interdyn.is.tue.mpg.de/)

* [OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation](https://arxiv.org/pdf/2412.09623) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09623)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lwq20020127.github.io/OmniDrag/)

* [Motion Prompting: Controlling Video Generation with Motion Trajectories](https://arxiv.org/abs/2412.02700) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02700)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://motion-prompting.github.io/)

* [MVideo: Motion Control for Enhanced Complex Action Video Generation](https://arxiv.org/pdf/2411.08328) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08328)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mvideo-v1.github.io/)

* [ReCapture: Generative Video Camera Controls for User-Provided Videos using Masked Video Fine-Tuning](https://arxiv.org/abs/2411.05003) (Nov., 2024 | CVPR 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.05003)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://generative-video-camera-controls.github.io/)

* [LumiSculpt: A Consistency Lighting Control Network for Video Generation](https://arxiv.org/pdf/2410.22979) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.22979)

* [Cavia: Camera-controllable Multi-view Video Diffusion with View-Integrated Attention](https://arxiv.org/abs/2410.10774) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10774)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ir1d.github.io/Cavia/)

* [Animate Your Motion: Turning Still Images into Dynamic Videos](https://arxiv.org/abs/2403.10179)(Mar., 2023|ECCV 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.10179)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mingxiao-li.github.io/smcd/)

* [EasyControl: Transfer ControlNet to Video Diffusion for Controllable Generation and Interpolation](https://arxiv.org/abs/2408.13005) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13005)

* [TrackGo: A Flexible and Efficient Method for Controllable Video Generation](https://arxiv.org/abs/2408.11475) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11475)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhtjtcz.github.io/TrackGo-Page/#)

* [Puppet-Master: Scaling Interactive Video Generation as a Motion Prior for Part-Level Dynamics](https://arxiv.org/abs/2408.04631) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.04631)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vgg-puppetmaster.github.io/)

* [Sketch2Scene: Automatic Generation of Interactive 3D Game Scenes from User's Casual Sketches](https://arxiv.org/abs/2408.04567) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.04567)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xrvisionlabs.github.io/Sketch2Scene/)

* [Expressive Whole-Body 3D Gaussian Avatar](https://arxiv.org/abs/2407.21686) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21686)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mks0601.github.io/ExAvatar/)

* [VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control](https://arxiv.org/abs/2407.12781) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/vd3d/)

* [Still-Moving: Customized Video Generation without Customized Video Data](https://arxiv.org/abs/2407.08674) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08674)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://still-moving.github.io/)

* [MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance](https://arxiv.org/abs/2406.19680) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)

* [Motion-Zero: Zero-Shot Moving Object Control Framework for Diffusion-Based Video Generation](https://arxiv.org/abs/2401.10150) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10150)

* [Moonshot: Towards Controllable Video Generation and Editing with Multimodal Conditions](https://arxiv.org/abs/2401.01827) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01827)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Moonshot/)

* [SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models](https://arxiv.org/abs/2311.16933) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16933)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://guoyww.github.io/projects/SparseCtrl/)

* [Motion-Conditioned Diffusion Model for Controllable Video Synthesis](https://arxiv.org/abs/2304.14404) (Apr., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14404)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tsaishien-chen.github.io/MCDiff/)

* [DragNUWA: Fine-grained Control in Video Generation by Integrating Text, Image, and Trajectory](https://arxiv.org/abs/2308.08089) (Aug., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08089)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.microsoft.com/en-us/research/project/dragnuwa/)

* [Training-free Camera Control for Video Generation](https://arxiv.org/pdf/2406.10126) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.10126)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lifedecoder.github.io/CamTrol/)

* [Customizing Motion in Text-to-Video Diffusion Models](https://arxiv.org/abs/2312.04966) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04966)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://joaanna.github.io/customizing_motion/)

* [MotionClone: Training-Free Motion Cloning for Controllable Video Generation](https://arxiv.org/abs/2406.05338) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bujiazi.github.io/motionclone.github.io/)

### Character Customization

* [Phantom: Subject-consistent video generation via cross-modal alignment](https://arxiv.org/pdf/2502.11079) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/Phantom-video/Phantom.svg?style=social\&label=Star)](https://github.com/Phantom-video/Phantom) ⭐ 1,515 | 🐛 41 | 🌐 Python | 📅 2025-09-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11079)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://phantom-video.github.io/Phantom/)

* [HunyuanCustom: A Multimodal-Driven Architecture for Customized Video Generation](https://arxiv.org/abs/2505.04512) (May., 2025)\
  [![Star](https://img.shields.io/github/stars/Tencent/HunyuanCustom.svg?style=social\&label=Star)](https://github.com/Tencent/HunyuanCustom) ⭐ 1,228 | 🐛 36 | 🌐 Python | 📅 2025-10-15
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.04512)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hunyuancustom.github.io/)

* [FlexiAct: Towards Flexible Action Control in Heterogeneous Scenarios](https://arxiv.org/abs/2505.03730) (May, 2025 | SIGGRAPH 2025)\
  [![Star](https://img.shields.io/github/stars/shiyi-zh0408/FlexiAct.svg?style=social\&label=Star)](https://github.com/shiyi-zh0408/FlexiAct) ⭐ 341 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2025-10-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.03730)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shiyi-zh0408.github.io/projectpages/FlexiAct/)

* [Magic Mirror: ID-Preserved Video Generation in Video Diffusion Transformers](https://arxiv.org/abs/2501.03931) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/dvlab-research/MagicMirror.svg?style=social\&label=Star)](https://github.com/dvlab-research/MagicMirror/) ⭐ 130 | 🐛 7 | 📅 2025-06-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03931)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://julianjuaner.github.io/projects/MagicMirror/)

* [Concat-ID: Towards Universal Identity-Preserving Video Synthesis](https://arxiv.org/abs/2503.14151) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/ML-GSAI/Concat-ID.svg?style=social\&label=Star)](https://github.com/ML-GSAI/Concat-ID) ⭐ 65 | 🐛 12 | 🌐 Python | 📅 2025-05-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14151)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ml-gsai.github.io/Concat-ID-demo/)

* [CustomCrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities](https://arxiv.org/abs/2408.13239) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/WuTao-CS/CustomCrafter.svg?style=social\&label=Star)](https://github.com/WuTao-CS/CustomCrafter) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2025-01-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13239)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://customcrafter.github.io/)

* [MagicID: Hybrid Preference Optimization for ID-Consistent and Dynamic-Preserved Video Customization](https://arxiv.org/abs/2503.12689) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/EchoPluto/MagicID.svg?style=social\&label=Star)](https://github.com/EchoPluto/MagicID) ⭐ 35 | 🐛 4 | 📅 2025-03-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.12689)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://echopluto.github.io/MagicID-project/)

* [VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models](https://arxiv.org/pdf/2412.19645) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/WuTao-CS/VideoMaker.svg?style=social\&label=Star)](https://github.com/WuTao-CS/VideoMaker) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2025-03-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.19645)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wutao-cs.github.io/VideoMaker/)

* [VideoMage: Multi-Subject and Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2503.21781) (Mar., 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jasper0314-huang.github.io/videomage-customization/)

* [CINEMA: Coherent Multi-Subject Video Generation via MLLM-Based Guidance](https://arxiv.org/abs/2503.10391) (Mar., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10391)

* [FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation](https://arxiv.org/abs/2502.13995) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.13995)

* [Dynamic Concepts Personalization from Single Videos](https://arxiv.org/abs/2502.14844) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.14844)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/dynamic_concepts/)

* [Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts](https://arxiv.org/abs/2502.07802) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07802)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jeff-liangf.github.io/projects/movieweaver/)

* [Animate Anyone 2: High-Fidelity Character Image Animation with Environment Affordance](https://arxiv.org/pdf/2502.06145) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.06145)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanaigc.github.io/animate-anyone-2/)

* [Multi-subject Open-set Personalization in Video Generation](https://arxiv.org/abs/2501.06187) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06187)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/open-set-video-personalization/)

* [ConceptMaster: Multi-Concept Video Customization on Diffusion Transformer Models Without Test-Time Tuning](https://arxiv.org/abs/2501.04698) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.04698)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yuzhou914.github.io/ConceptMaster/)

* [PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation](https://arxiv.org/pdf/2411.17048) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17048)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://personalvideo.github.io/)

* [DreamVideo-2: Zero-Shot Subject-Driven Video Customization with Precise Motion Control](https://arxiv.org/abs/2410.13830) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13830)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamvideo2.github.io/)

### Motion Customization

* [DreamVideo: Composing Your Dream Videos with Customized Subject and Motion](https://arxiv.org/abs/2312.04433) (Dec., 2023 | CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social\&label=Star)](https://github.com/ali-vilab/VGen) ⭐ 3,155 | 🐛 115 | 🌐 Python | 📅 2025-01-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamvideo-t2v.github.io/)

* [MotionCtrl: A Unified and Flexible Motion Controller for Video Generation](https://arxiv.org/abs/2312.03641) (Dec., 2023 | SIGGRAPH 2024)\
  [![Star](https://img.shields.io/github/stars/TencentARC/MotionCtrl.svg?style=social\&label=Star)](https://github.com/TencentARC/MotionCtrl) ⭐ 1,500 | 🐛 29 | 🌐 Python | 📅 2025-02-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03641)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/MotionCtrl/)

* [Tora: Trajectory-oriented Diffusion Transformer for Video Generation](https://arxiv.org/abs/2407.21705) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/alibaba/Tora.svg?style=social\&label=Star)](https://github.com/alibaba/Tora) ⭐ 1,241 | 🐛 11 | 🌐 Python | 📅 2026-07-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21705)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ali-videoai.github.io/tora_video/)

* [Go-with-the-Flow: Motion-Controllable Video Diffusion Models Using Real-Time Warped Noise](https://arxiv.org/pdf/2501.08331) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/VGenAI-Netflix-Eyeline-Research/Go-with-the-Flow.svg?style=social\&label=Star)](https://github.com/VGenAI-Netflix-Eyeline-Research/Go-with-the-Flow) ⭐ 1,094 | 🐛 28 | 🌐 Python | 📅 2025-10-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.08331)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vgenai-netflix-eyeline-research.github.io/Go-with-the-Flow/)

* [MotionDirector: Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2310.08465) (Sep., 2023 | ECCV 2024)\
  [![Star](https://img.shields.io/github/stars/showlab/MotionDirector.svg?style=social\&label=Star)](https://github.com/showlab/MotionDirector) ⭐ 1,053 | 🐛 26 | 🌐 Python | 📅 2024-08-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08465)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/MotionDirector/)

* [MotionClone: Training-Free Motion Cloning for Controllable Video Generation](https://arxiv.org/abs/2406.05338) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/Bujiazi/MotionClone.svg?style=social\&label=Star)](https://github.com/Bujiazi/MotionClone/) ⭐ 518 | 🐛 4 | 🌐 Python | 📅 2025-06-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bujiazi.github.io/motionclone.github.io/)

* [DragAnything: Motion Control for Anything using Entity Representation](https://arxiv.org/abs/2403.07420) (Mar., 2024 | ECCV 2024)
  [![Star](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social\&label=Star)](https://github.com/showlab/DragAnything) ⭐ 506 | 🐛 20 | 🌐 Python | 📅 2024-07-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07420)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://weijiawu.github.io/draganything_page/)

* [FlexiAct: Towards Flexible Action Control in Heterogeneous Scenarios](https://arxiv.org/abs/2505.03730) (May, 2025 | SIGGRAPH 2025)\
  [![Star](https://img.shields.io/github/stars/shiyi-zh0408/FlexiAct.svg?style=social\&label=Star)](https://github.com/shiyi-zh0408/FlexiAct) ⭐ 341 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2025-10-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.03730)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shiyi-zh0408.github.io/projectpages/FlexiAct/)

* [LAMP: Learn A Motion Pattern for Few-Shot-Based Video Generation](https://arxiv.org/abs/2310.10769) (Oct., 2023 | CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/RQ-Wu/LAMP.svg?style=social\&label=Star)](https://github.com/RQ-Wu/LAMP) ⭐ 284 | 🐛 9 | 🌐 Python | 📅 2024-04-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10769)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rq-wu.github.io/projects/LAMP/)

* [Vmc: Video motion customization using temporal attention adaption for text-to-video diffusion models](https://arxiv.org/abs/2312.00845) (Dec., 2023 | CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/HyeonHo99/Video-Motion-Customization.svg?style=social\&label=Star)](https://github.com/HyeonHo99/Video-Motion-Customization) ⭐ 199 | 🐛 9 | 🌐 Python | 📅 2024-03-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00845)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-motion-customization.github.io/)

* [MotionPro: A Precise Motion Controller for Image-to-Video Generation](https://arxiv.org/abs/2505.20287) (May, 2025 | CVPR 2025)\
  [![Star](https://img.shields.io/github/stars/HiDream-ai/MotionPro.svg?style=social\&label=Star)](https://github.com/HiDream-ai/MotionPro) ⭐ 161 | 🐛 0 | 🌐 Python | 📅 2026-04-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.20287)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhw-zhang.github.io/MotionPro-page/)

* [Motion Inversion for Video Customization](https://arxiv.org/abs/2403.20193) (Mar., 2024)\
  [![Star](https://img.shields.io/github/stars/EnVision-Research/MotionInversion.svg?style=social\&label=Star)](https://github.com/EnVision-Research/MotionInversion) ⭐ 154 | 🐛 6 | 🌐 Python | 📅 2024-10-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.20193)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wileewang.github.io/MotionInversion/)

* [ViewExtrapolator: Novel View Extrapolation with Video Diffusion Priors](https://arxiv.org/abs/2411.14208) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/Kunhao-Liu/ViewExtrapolator.svg?style=social\&label=Star)](https://github.com/Kunhao-Liu/ViewExtrapolator) ⭐ 130 | 🐛 3 | 🌐 Python | 📅 2025-02-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.14208)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kunhao-liu.github.io/ViewExtrapolator/)

* [FreeTraj: Tuning-Free Trajectory Control in Video Diffusion Models](https://arxiv.org/abs/2406.16863) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social\&label=Star)](https://github.com/arthur-qiu/FreeTraj) ⭐ 114 | 🐛 0 | 🌐 Python | 📅 2025-09-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16863)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://haonanqiu.com/projects/FreeTraj.html)

* [Trajectory Attention For Fine-grained Video Motion Control](https://arxiv.org/abs/2411.14208) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/xizaoqu/TrajectoryAttntion.svg?style=social\&label=Star)](https://github.com/xizaoqu/TrajectoryAttntion) ⭐ 101 | 🐛 3 | 🌐 Python | 📅 2025-05-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19324)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xizaoqu.github.io/trajattn/)

* [Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion](https://arxiv.org/abs/2402.03162) (Feb., 2024)\
  [![Star](https://img.shields.io/github/stars/ysy31415/direct_a_video.svg?style=social\&label=Star)](https://github.com/ysy31415/direct_a_video) ⭐ 95 | 🐛 2 | 🌐 Python | 📅 2024-05-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://direct-a-video.github.io/)

* [Video Motion Transfer with Diffusion Transformers](https://arxiv.org/abs/2412.07776) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/ditflow/ditflow.svg?style=social\&label=Star)](https://github.com/ditflow/ditflow) ⭐ 82 | 🐛 4 | 🌐 Python | 📅 2025-07-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07776)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ditflow.github.io/)

* [Collaborative Video Diffusion: Consistent Multi-video Generation with Camera Control](https://arxiv.org/abs/2405.17414) (May., 2024)\
  [![Star](https://img.shields.io/github/stars/CollaborativeVideoDiffusion/CVD.svg?style=social\&label=Star)](https://github.com/CollaborativeVideoDiffusion/CVD) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2024-12-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17414)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://collaborativevideodiffusion.github.io/)

* [Frame In-N-Out: Unbounded Controllable Image-to-Video Generation](https://arxiv.org/abs/2505.21491) (May, 2025)
  [![Star](https://img.shields.io/github/stars/UVA-Computer-Vision-Lab/FrameINO.svg?style=social\&label=Star)](https://github.com/UVA-Computer-Vision-Lab/FrameINO) ⭐ 33 | 🐛 3 | 🌐 Python | 📅 2026-05-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.21491)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://uva-computer-vision-lab.github.io/Frame-In-N-Out/)

* [Spectral Motion Alignment for Video Motion Transfer using Diffusion Models](https://arxiv.org/abs/2403.15249) (Mar., 2024)\
  [![Star](https://img.shields.io/github/stars/geonyeong-park/Spectral-Motion-Alignment.svg?style=social\&label=Star)](https://github.com/geonyeong-park/Spectral-Motion-Alignment) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2024-12-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15249)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://geonyeong-park.github.io/spectral-motion-alignment/)

* [Training-free Guidance in Text-to-Video Generation via Multimodal Planning and Structured Noise Initialization](https://arxiv.org/pdf/2504.08641) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/jialuli-luka/Video-MSG.svg?style=social\&label=Star)](https://github.com/jialuli-luka/Video-MSG) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2025-04-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.08641)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-msg.github.io/)

* [MotionShop: Zero-Shot Motion Transfer in Video Diffusion Models with Mixture of Score Guidance](https://motionshop-diffusion.github.io/MotionShop.pdf) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/gemlab-vt/motionshop.svg?style=social\&label=Star)](https://github.com/gemlab-vt/motionshop) ⭐ 26 | 🐛 2 | 📅 2024-12-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://motionshop-diffusion.github.io/MotionShop.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://motionshop-diffusion.github.io/)

* [TrajectoryMover: Generative Movement of Object Trajectories in Videos](https://arxiv.org/abs/2603.29092) (Mar., 2026)
  [![Star](https://img.shields.io/github/stars/kiranchhatre/TrajectoryMover.svg?style=social\&label=Star)](https://github.com/kiranchhatre/TrajectoryMover) ⭐ 6 | 🐛 1 | 📅 2026-04-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.29092)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chhatrekiran.github.io/trajectorymover/)

* [LMP: Leveraging Motion Prior in Zero-Shot Video Generation with Diffusion Transformer](https://arxiv.org/abs/2505.14167) (May, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.14167)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vpx-ecnu.github.io/LMP-Website/)

* [Separate Motion from Appearance: Customizing Motion via Customizing Text-to-Video Diffusion Models](https://arxiv.org/abs/2501.16714) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.16714)

* [Training-Free Motion-Guided Video Generation with Enhanced Temporal Consistency Using Motion Consistency Loss](https://arxiv.org/abs/2501.07563v1) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.07563v1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhangxinyu-xyz.github.io/SimulateMotion.github.io/)

* [Free-Form Motion Control: A Synthetic Video Generation Dataset with Controllable Camera and Object Motions](https://arxiv.org/abs/2501.01425) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01425)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://henghuiding.github.io/SynFMC/)

* [CustomTTT: Motion and Appearance Customized Video Generation via Test-Time Training](https://arxiv.org/pdf/2412.15646) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.15646)

* [Latent-Reframe: Enabling Camera Control for Video Diffusion Model without Training](https://arxiv.org/abs/2412.06029) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06029)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://latent-reframe.github.io/)

* [Motion Modes: What Could Happen Next?](https://motionmodes.github.io/resources/MotionModes.pdf) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://motionmodes.github.io/resources/MotionModes.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://motionmodes.github.io/)

* [MoTrans: Customized Motion Transfer with Text-driven Video](https://arxiv.org/abs/2412.01343) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01343)

* [AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers](https://arxiv.org/abs/2411.18673) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18673)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/ac3d/)

* [I2VControl-Camera: Precise Video Camera Control with Adjustable Motion Strength](https://arxiv.org/pdf/2411.06525) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.06525)

* [Customizing Motion in Text-to-Video Diffusion Models](https://arxiv.org/abs/2312.04966) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04966)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://joaanna.github.io/customizing_motion/)

* [Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2402.14780) (Feb., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)

* [DreamMotion: Space-Time Self-Similar Score Distillation for Zero-Shot Video Editing](https://arxiv.org/abs/2403.12002) (Mar., 2024 | ECCV 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12002)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hyeonho99.github.io/dreammotion/)

* [Edit-Your-Motion: Space-Time Diffusion Decoupling Learning for Video Motion Editing](https://arxiv.org/abs/2405.04496) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.04496)

* [Video Diffusion Models are Training-free Motion Interpreter and Controller](https://arxiv.org/abs/2405.14864) (May., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14864)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xizaoqu.github.io/moft/)

* [Zero-Shot Controllable Image-to-Video Animation via Motion Decomposition](https://www.amazon.science/publications/zero-shot-controllable-image-to-video-animation-via-motion-decomposition) (Jul., 2024 | ACM MM 2024)\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://img2vidanim-0.github.io/)

* [Reenact Anything: Semantic Video Motion Transfer Using Motion-Textual Inversion](https://arxiv.org/abs/2408.00458) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.00458)

### Long Video / Film Generation

* [VideoRAG: Retrieval-Augmented Generation with Extreme Long-Context Videos](https://arxiv.org/abs/2502.01549) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/HKUDS/VideoRAG.svg?style=social\&label=Star)](https://github.com/HKUDS/VideoRAG) ⭐ 3,346 | 🐛 21 | 🌐 Python | 📅 2026-03-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01549)

* [Stable Video Infinity: Infinite-Length Video Generation with Error Recycling](https://arxiv.org/abs/2510.09212) (Oct., 2025)\
  [![Star](https://img.shields.io/github/stars/vita-epfl/Stable-Video-Infinity.svg?style=social\&label=Star)](https://github.com/vita-epfl/Stable-Video-Infinity) ⭐ 2,562 | 🐛 41 | 🌐 Python | 📅 2026-06-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.09212)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stable-video-infinity.github.io/homepage/)

* [One-Minute Video Generation with Test-Time Training](https://arxiv.org/abs/2504.05298) (Apr., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.05298)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://test-time-training.github.io/video-dit/)
  [![Star](https://img.shields.io/github/stars/test-time-training/ttt-video-dit.svg?style=social\&label=Star)](https://github.com/test-time-training/ttt-video-dit) ⭐ 2,451 | 🐛 8 | 🌐 Python | 📅 2026-02-25

* [In-Context LoRA for Diffusion Transformers](https://arxiv.org/abs/2410.23775) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.23775)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ali-vilab.github.io/In-Context-LoRA-Page/)
  [![Star](https://img.shields.io/github/stars/ali-vilab/In-Context-LoRA.svg?style=social\&label=Star)](https://github.com/ali-vilab/In-Context-LoRA) ⭐ 2,085 | 🐛 33 | 📅 2024-12-20

* [Story-Adapter: A Training-free Iterative Framework for Long Story Visualization](https://arxiv.org/abs/2410.06244) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.06244)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jwmao1.github.io/storyadapter/)
  [![Star](https://img.shields.io/github/stars/jwmao1/story-adapter.svg?style=social\&label=Star)](https://github.com/jwmao1/story-adapter) ⭐ 960 | 🐛 0 | 🌐 Python | 📅 2026-04-02

* [SEED-Story: Multimodal Long Story Generation with Large Language Model](https://arxiv.org/abs/2407.08683) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08683)
  [![Star](https://img.shields.io/github/stars/TencentARC/SEED-Story.svg?style=social\&label=Star)](https://github.com/TencentARC/SEED-Story) ⭐ 883 | 🐛 5 | 🌐 Python | 📅 2024-10-11

* [Identity-Preserving Text-to-Video Generation by Frequency Decomposition](https://arxiv.org/abs/2411.17440) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social\&label=Star)](https://github.com/PKU-YuanGroup/ConsisID) ⭐ 856 | 🐛 36 | 🌐 Python | 📅 2026-04-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/ConsisID/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/BestWishYsh/ConsisID-preview-Data)

* [RIFLEx: A Free Lunch for Length Extrapolation in Video Diffusion Transformers](https://arxiv.org/abs/2502.15894) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/thu-ml/RIFLEx.svg?style=social\&label=Star)](https://github.com/thu-ml/RIFLEx) ⭐ 825 | 🐛 24 | 🌐 Python | 📅 2026-06-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.15894)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://riflex-video.github.io/)

* [StoryMaker: Towards consistent characters in text-to-image generation](https://arxiv.org/abs/2409.12576) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.12576)
  [![Star](https://img.shields.io/github/stars/RedAIGC/StoryMaker.svg?style=social\&label=Star)](https://github.com/RedAIGC/StoryMaker) ⭐ 723 | 🐛 19 | 🌐 Python | 📅 2024-12-02

* [VideoPainter: Any-length Video Inpainting and Editing with Plug-and-Play Context Control](https://arxiv.org/abs/2503.05639) (May, 2025 | SIGGRAPH 2025)\
  [![Star](https://img.shields.io/github/stars/TencentARC/VideoPainter.svg?style=social\&label=Star)](https://github.com/TencentARC/VideoPainter) ⭐ 633 | 🐛 16 | 🌐 Python | 📅 2025-04-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.05639)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yxbian23.github.io/project/video-painter/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/collections/TencentARC/videopainter-67cc49c6146a48a2ba93d159)

* [AutoStudio: Crafting Consistent Subjects in Multi-turn Interactive Image Generation](https://github.com/donahowe/AutoStudio) ⭐ 453 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2025-04-13 (Jul, 2024)\
  [![Star](https://img.shields.io/github/stars/donahowe/AutoStudio.svg?style=social\&label=Star)](https://github.com/donahowe/AutoStudio) ⭐ 453 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2025-04-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01388)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/donahowe/AutoStudio) ⭐ 453 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2025-04-13

* [MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation](https://arxiv.org/abs/2205.09853) (NeurIPS 2022)\
  [![Star](https://img.shields.io/github/stars/voletiv/mcvd-pytorch.svg?style=social\&label=Star)](https://github.com/voletiv/mcvd-pytorch) ⭐ 370 | 🐛 13 | 🌐 Python | 📅 2022-09-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.09853)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mask-cond-video-diffusion.github.io)

* [MovieAgent: Automated Movie Generation via Multi-Agent CoT Planning](https://arxiv.org/abs/2503.07314) (Mar., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.07314)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://weijiawu.github.io/MovieAgent/)
  [![Star](https://img.shields.io/github/stars/showlab/MovieAgent.svg?style=social\&label=Star)](https://github.com/showlab/MovieAgent) ⭐ 357 | 🐛 13 | 🌐 Python | 📅 2025-03-26

* [DiTCtrl: Exploring Attention Control in Multi-Modal Diffusion Transformer for Tuning-Free Multi-Prompt Longer Video Generation](https://arxiv.org/abs/2412.18597) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/TencentARC/DiTCtrl.svg?style=social\&label=Star)](https://github.com/TencentARC/DiTCtrl) ⭐ 324 | 🐛 8 | 🌐 Python | 📅 2025-03-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.18597)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://onevfall.github.io/project_page/ditctrl/)

* [MovieDreamer: Hierarchical Generation for Coherent Long Visual Sequence](https://arxiv.org/abs/2407.16655) (Jul, 2024)\
  [![Star](https://img.shields.io/github/stars/aim-uofa/MovieDreamer.svg?style=social\&label=Star)](https://github.com/aim-uofa/MovieDreamer) ⭐ 323 | 🐛 5 | 📅 2024-08-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.16655)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aim-uofa.github.io/MovieDreamer/)

* [Long-Context Autoregressive Video Modeling with Next-Frame Prediction](https://arxiv.org/abs/2503.19325) (Mar., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.19325)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://farlongctx.github.io/)
  [![Star](https://img.shields.io/github/stars/showlab/FAR.svg?style=social\&label=Star)](https://github.com/showlab/FAR) ⭐ 314 | 🐛 1 | 🌐 Python | 📅 2025-04-23

* [Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation](https://arxiv.org/abs/2408.09787) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/HITsz-TMG/Anim-Director.svg?style=social\&label=Star)](https://github.com/HITsz-TMG/Anim-Director) ⭐ 254 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2026-01-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09787)

* [VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning](https://arxiv.org/abs/2309.15091) (Jul, 2024)\
  [![Star](https://img.shields.io/github/stars/HL-hanlin/VideoDirectorGPT.svg?style=social\&label=Star)](https://github.com/HL-hanlin/VideoDirectorGPT) ⭐ 182 | 🐛 2 | 📅 2024-08-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15091)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videodirectorgpt.github.io/)

* [SkyScript-100M: 1,000,000,000 Pairs of Scripts and Shooting Scripts for Short Drama](https://arxiv.org/pdf/2408.09333) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/vaew/SkyScript-100M.svg?style=social\&label=Star)](https://github.com/vaew/SkyScript-100M) ⭐ 150 | 🐛 3 | 📅 2024-11-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.09333)

* [Flexible Diffusion Modeling of Long Videos](https://arxiv.org/abs/2205.11495) (May, 2022)\
  [![Star](https://img.shields.io/github/stars/plai-group/flexible-video-diffusion-modeling.svg?style=social\&label=Star)](https://github.com/plai-group/flexible-video-diffusion-modeling) ⭐ 121 | 🐛 2 | 🌐 Python | 📅 2023-02-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.11495)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fdmolv.github.io/)

* [MovieBench: A Hierarchical Movie Level Dataset for Long Video Generation](https://arxiv.org/abs/2411.15262) (CVPR 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.15262)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://weijiawu.github.io/MovieBench/)
  [![Star](https://img.shields.io/github/stars/showlab/MovieBecnh.svg?style=social\&label=Star)](https://github.com/showlab/MovieBecnh) ⭐ 102 | 🐛 1 | 🌐 Python | 📅 2025-03-16

* [DreamCinema: Cinematic Transfer with Free Camera and 3D Character](https://arxiv.org/abs/2408.12601) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/chen-wl20/DreamCinema?tab=readme-ov-file.svg?style=social\&label=Star)](https://github.com/chen-wl20/DreamCinema?tab=readme-ov-file) ⭐ 96 | 🐛 3 | 📅 2025-06-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12601)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://liuff19.github.io/DreamCinema/)

* [DreamRunner: Fine-Grained Storytelling Video Generation with Retrieval-Augmented Motion Adaptation](https://arxiv.org/pdf/2411.16657) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.16657)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamrunner-story2video.github.io/)
  [![Star](https://img.shields.io/github/stars/wz0919/DreamRunner.svg?style=social\&label=Star)](https://github.com/wz0919/DreamRunner) ⭐ 78 | 🐛 2 | 🌐 Python | 📅 2025-06-11

* [TheaterGen: Character Management with LLM for Consistent Multi-turn Image Generation](https://arxiv.org/abs/2404.18919) (Jul, 2024)\
  [![Star](https://img.shields.io/github/stars/donahowe/Theatergen.svg?style=social\&label=Star)](https://github.com/donahowe/Theatergen) ⭐ 69 | 🐛 6 | 🌐 Python | 📅 2024-09-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.18919)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://howe140.github.io/theatergen.io/)

* [AnimeShooter: A Multi-Shot Animation Dataset for Reference-Guided Video Generation](https://arxiv.org/abs/2506.03126) (Jun., 2025)\
  [![Star](https://img.shields.io/github/stars/qiulu66/Anime-Shooter.svg?style=social\&label=Star)](https://github.com/qiulu66/Anime-Shooter) ⭐ 60 | 🐛 3 | 🌐 Python | 📅 2025-06-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.03126)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://qiulu66.github.io/animeshooter/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/collections/TencentARC/videopainter-67cc49c6146a48a2ba93d159)

* [Owl-1: Omni World Model for Consistent Long Video Generation](https://arxiv.org/abs/2412.09600) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/huang-yh/Owl.svg?style=social\&label=Star)](https://github.com/huang-yh/Owl) ⭐ 52 | 🐛 2 | 📅 2024-12-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09600)

* [VideoAuteur: Towards Long Narrative Video Generation](https://arxiv.org/abs/2501.06173) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/lambert-x/VideoAuteur.svg?style=social\&label=Star)](https://github.com/lambert-x/VideoAuteur) ⭐ 44 | 🐛 4 | 📅 2025-10-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06173)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoauteur.github.io/)

* [Mind the Time: Temporally-Controlled Multi-Event Video Generation](https://arxiv.org/abs/2412.05263) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/Karine-Huang/GenMAC.svg?style=social\&label=Star)](https://github.com/Karine-Huang/GenMAC) ⭐ 36 | 🐛 3 | 🌐 Python | 📅 2026-01-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05263)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mint-video.github.io/)

* [GenMAC: Compositional Text-to-Video Generation with Multi-Agent Collaboration](https://arxiv.org/abs/2412.04440) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/Karine-Huang/GenMAC.svg?style=social\&label=Star)](https://github.com/Karine-Huang/GenMAC) ⭐ 36 | 🐛 3 | 🌐 Python | 📅 2026-01-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04440)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://karine-h.github.io/GenMAC/)

* [Redefining Temporal Modeling in Video Diffusion: The Vectorized Timestep Approach](https://arxiv.org/abs/2410.03160) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/Yaofang-Liu/FVDM.svg?style=social\&label=Star)](https://github.com/Yaofang-Liu/FVDM) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2026-01-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.03160)

* [AutoAD-Zero: A Training-Free Framework for Zero-Shot Audio Description](https://arxiv.org/abs/2407.15850) (Jul, 2024)\
  [![Star](https://img.shields.io/github/stars/Jyxarthur/AutoAD-Zero.svg?style=social\&label=Star)](https://github.com/Jyxarthur/AutoAD-Zero) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2026-05-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.15850)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.robots.ox.ac.uk/~vgg/research/autoad-zero/)

* [Mask²DiT: Dual Mask-based Diffusion Transformer for Multi-Scene Long Video Generation](https://arxiv.org/2503.19881) (Mar., 2025 | CVPR 2025)\
  [![Star](https://img.shields.io/github/stars/Tianhao-Qi/Mask2DiT.svg?style=social\&label=Star)](https://github.com/Tianhao-Qi/Mask2DiT) ⭐ 26 | 🐛 3 | 🌐 Python | 📅 2025-12-20
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.19881)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tianhao-qi.github.io/Mask2DiTProject/)

* [MotionPrompt: Optical-Flow Guided Prompt Optimization for Coherent Video Generation](https://arxiv.org/pdf/2411.15540) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15540)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://motionprompt.github.io/)
  [![Star](https://img.shields.io/github/stars/HyelinNAM/MotionPrompt.svg?style=social\&label=Star)](https://github.com/HyelinNAM/MotionPrompt) ⭐ 4 | 🐛 0 | 📅 2025-03-11

* [A²RD: Agentic Autoregressive Diffusion for Long Video Consistency](https://arxiv.org/abs/2605.06924) (May., 2026)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.06924)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dxlong2000.github.io/AARD/)

* [Long Context Tuning for Video Generation](https://arxiv.org/pdf/2503.10589) (Mar., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10589)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://guoyww.github.io/projects/long-context-video/)

* [Ouroboros-Diffusion: Exploring Consistent Content Generation in Tuning-free Long Video Diffusion](https://arxiv.org/pdf/2501.09019) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.09019)

* [LinGen: Towards High-Resolution Minute-Length Text-to-Video Generation with Linear Computational Complexity](https://arxiv.org/abs/2412.09856) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09856)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lineargen.github.io/)

* [Video Storyboarding: Multi-Shot Character Consistency for Text-to-Video Generation](https://arxiv.org/pdf/2412.07750) (Dec., 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07750)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/par/video_storyboarding/)

* [Long Video Diffusion Generation with Segmented Cross-Attention and Content-Rich Video Data Curation](https://arxiv.org/pdf/2412.01316) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01316)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://presto-video.github.io/)

* [VideoGen-of-Thought: A Collaborative Framework for Multi-Shot Video Generation](https://arxiv.org/abs/2412.02259) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02259)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cheliosoops.github.io/VGoT/)

* [MotionCharacter: Identity-Preserving and Motion Controllable Human Video Generation](https://arxiv.org/pdf/2411.18281) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18281)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://motioncharacter.github.io/)

* [Storynizor: Consistent Story Generation via Inter-Frame Synchronized and Shuffled ID Injection](https://arxiv.org/pdf/2409.19624) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.19624)

* [ACDC: Autoregressive Coherent Multimodal Generation using Diffusion Correction](https://arxiv.org/abs/2410.04721) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04721)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://acdc2025.github.io/)

* [StoryAgent: Customized Storytelling Video Generation via Multi-Agent Collaboration](https://arxiv.org/pdf/2411.04925) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04925)

* [ARLON: Boosting Diffusion Transformers With Autoregressive Models for Long Video Generation](https://arxiv.org/abs/2410.20502) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20502)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://arlont2v.github.io/)

* [Unbounded: A Generative Infinite Game of Character Life Simulation](https://arxiv.org/abs/2410.18975) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.18975)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://generative-infinite-game.github.io/)

* [Loong: Generating Minute-level Long Videos with Autoregressive Language Models](https://arxiv.org/abs/2410.02757) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02757)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://epiphqny.github.io/Loong-video/)

* [DreamCinema: Cinematic Transfer with Free Camera and 3D Character](https://arxiv.org/pdf/2410.04721) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.04721)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://acdc2025.github.io/)

* [CinePreGen: Camera Controllable Video Previsualization via Engine-powered Diffusion](https://arxiv.org/pdf/2408.17424) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.17424)

* [Kubrick: Multimodal Agent Collaborations for Synthetic Video Generation](https://arxiv.org/pdf/2408.10453) (Aug., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.10453)

* [DreamFactory: Pioneering Multi-Scene Long Video Generation with a Multi-Agent Framework](https://arxiv.org/abs/2408.11788) (Jul, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11788)

* [Streetscapes: Large-scale Consistent Street View Generation Using Autoregressive Video Diffusion](https://arxiv.org/pdf/2407.13759) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.13759)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boyangdeng.com/streetscapes/)

* [AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production](https://arxiv.org/abs/2403.07952) (Jul, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07952)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aesopai.github.io/)

* [DreamStory: Open-Domain Story Visualization by LLM-Guided Multi-Subject Consistent Diffusion](https://arxiv.org/abs/2407.12899) (Jul, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12899)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dream-xyz.github.io/dreamstory)

* [NUWA-XL: Diffusion over Diffusion for eXtremely Long Video Generation](https://arxiv.org/abs/2303.12346) (Mar., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12346)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://msra-nuwa.azurewebsites.net/#/)

### Video Generation with 3D/Physical Prior

* [ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis](https://arxiv.org/abs/2409.02048) (Sep, 2024)\
  [![Star](https://img.shields.io/github/stars/Drexubery/ViewCrafter.svg?style=social\&label=Star)](https://github.com/Drexubery/ViewCrafter) ⭐ 1,587 | 🐛 47 | 🌐 Python | 📅 2025-12-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02048)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://drexubery.github.io/ViewCrafter/)

* [Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control](https://arxiv.org/pdf/2501.03847) (Jan, 2025)\
  [![Star](https://img.shields.io/github/stars/IGL-HKUST/DiffusionAsShader.svg?style=social\&label=Star)](https://github.com/IGL-HKUST/DiffusionAsShader) ⭐ 832 | 🐛 24 | 🌐 Python | 📅 2025-06-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.03847)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://igl-hkust.github.io/das/)

* [PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation](https://arxiv.org/abs/2404.13026) (ECCV 2024)\
  [![Star](https://img.shields.io/github/stars/a1600012888/PhysDreamer.svg?style=social\&label=Star)](https://github.com/a1600012888/PhysDreamer) ⭐ 631 | 🐛 17 | 🌐 Python | 📅 2025-02-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.13026)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://physdreamer.github.io/)

* [PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation](https://arxiv.org/abs/2409.18964) (Oct, 2024)\
  [![Star](https://img.shields.io/github/stars/stevenlsw/physgen.svg?style=social\&label=Star)](https://github.com/stevenlsw/physgen) ⭐ 353 | 🐛 1 | 🌐 Python | 📅 2024-10-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.18964)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stevenlsw.github.io/physgen/)

* [AutoVFX: Physically Realistic Video Editing from Natural Language Instructions](https://arxiv.org/pdf/2411.02385) (Nov, 2024)\
  [![Star](https://img.shields.io/github/stars/haoyuhsu/autovfx.svg?style=social\&label=Star)](https://github.com/haoyuhsu/autovfx) ⭐ 331 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-04-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://haoyuhsu.github.io/autovfx-website/)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://haoyuhsu.github.io/autovfx-website/)

* [Generative Physical AI in Vision: A Survey](https://arxiv.org/abs/2501.10928) (Jan, 2025)\
  [![Star](https://img.shields.io/github/stars/BestJunYu/Awesome-Physics-aware-Generation.svg?style=social\&label=Star)](https://github.com/BestJunYu/Awesome-Physics-aware-Generation) ⭐ 298 | 🐛 5 | 📅 2025-12-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10928)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/BestJunYu/Awesome-Physics-aware-Generation) ⭐ 298 | 🐛 5 | 📅 2025-12-23

* [How Far is Video Generation from World Model: A Physical Law Perspective](https://arxiv.org/pdf/2411.02385) (Oct, 2024)\
  [![Star](https://img.shields.io/github/stars/phyworld/phyworld.svg?style=social\&label=Star)](https://github.com/phyworld/phyworld) ⭐ 179 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2025-01-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.02385)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://phyworld.github.io/)

* [PhyGenBench: Towards World Simulator: Crafting Physical Commonsense-Based Benchmark for Video Generation](https://arxiv.org/pdf/2410.05363) (Oct, 2024)\
  [![Star](https://img.shields.io/github/stars/OpenGVLab/PhyGenBench.svg?style=social\&label=Star)](https://github.com/OpenGVLab/PhyGenBench) ⭐ 165 | 🐛 8 | 🌐 Python | 📅 2024-10-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.05363)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://phygenbench123.github.io/)

* [Force Prompting: Video Generation Models Can Learn and Generalize Physics-based Control Signals](https://arxiv.org/abs/2505.19386) (May, 2025)\
  [![Star](https://img.shields.io/github/stars/brown-palm/force-prompting.svg?style=social\&label=Star)](https://github.com/brown-palm/force-prompting) ⭐ 161 | 🐛 5 | 🌐 Python | 📅 2026-04-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19386)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://force-prompting.github.io/)

* [Over++: Generative Video Compositing for Layer Interaction Effects](https://arxiv.org/abs/2512.19661) (Dec, 2025)\
  [![Star](https://img.shields.io/github/stars/luchaoqi/overplusplus.svg?style=social\&label=Star)](https://github.com/luchaoqi/overplusplus) ⭐ 125 | 🐛 0 | 🌐 Python | 📅 2026-02-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.19661)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://overplusplus.github.io/)

* [PhyT2V: LLM-Guided Iterative Self-Refinement for Physics-Grounded Text-to-Video Generation](https://arxiv.org/abs/2412.00596) (Nov, 2024)\
  [![Star](https://img.shields.io/github/stars/pittisl/PhyT2V.svg?style=social\&label=Star)](https://github.com/pittisl/PhyT2V) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2025-07-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00596)

* [IDOL: Unified Dual-Modal Latent Diffusion for Human-Centric Joint Video-Depth Generation](https://arxiv.org/abs/2407.10937) (Jul, 2024)\
  [![Star](https://img.shields.io/github/stars/yhZhai/idol.svg?style=social\&label=Star)](https://github.com/yhZhai/idol) ⭐ 56 | 🐛 2 | 📅 2024-09-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16823)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://arxiv.org/abs/2407.10937)

* [Tex4D: Zero-shot 4D Scene Texturing with Video Diffusion Models](https://arxiv.org/pdf/2410.10821) (Oct, 2024)\
  [![Star](https://img.shields.io/github/stars/ZqlwMatt/Tex4D.svg?style=social\&label=Star)](https://github.com/ZqlwMatt/Tex4D) ⭐ 55 | 🐛 1 | 🌐 Python | 📅 2025-01-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10821)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tex4d.github.io/)

* [SyncVP: Joint Diffusion for Synchronous Multi-Modal Video Prediction](https://arxiv.org/abs/2503.18933) (CVPR 2025)

  [![Star](https://img.shields.io/github/stars/PallottaEnrico/SyncVP.svg?style=social\&label=Star)](https://github.com/PallottaEnrico/SyncVP) ⭐ 25 | 🐛 2 | 🌐 Python | 📅 2025-07-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18933)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://syncvp.github.io/)

* ReVision: High-Quality, Low-Cost Video Generation with Explicit 3D Physics Modeling for Complex Motion and Interaction]\(<https://arxiv.org/abs/2504.21855>) (Apr, 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.21855)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://revision-video.github.io/)

* [DiffusionRenderer: Neural Inverse and Forward Rendering with Video Diffusion Models](https://arxiv.org/abs/2501.18590) (Feb, 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.18590)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/DiffusionRenderer/)

* [Do generative video models learn physical principles from watching videos?](https://arxiv.org/pdf/2501.09038) (Jan, 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.09038)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://physics-iq.github.io/)

* [Motion Dreamer: Realizing Physically Coherent Video Generation through Scene-Aware Motion Reasoning](https://arxiv.org/pdf/2412.00547) (Nov, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.00547)

* [Phys4DGen: A Physics-Driven Framework for Controllable and Efficient 4D Content Generation from a Single Image](https://arxiv.org/pdf/2411.16800) (Nov, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.16800)

* [PhysMotion: Physics-Grounded Dynamics From a Single Image](https://arxiv.org/abs/2411.17189) (Nov, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17189)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://supertan0204.github.io/physmotion_website/)

* [StereoCrafter: Diffusion-based Generation of Long and High-fidelity Stereoscopic 3D from Monocular Videos](https://arxiv.org/pdf/2409.07447) (Oct, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.07447)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://stereocrafter.github.io/)

* [Compositional 3D-aware Video Generation with LLM Director](https://www.microsoft.com/en-us/research/project/compositional-3d-aware-video-generation/) (Aug, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.00558)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.microsoft.com/en-us/research/project/compositional-3d-aware-video-generation/)

### Video Editing

* [Rerender A Video: Zero-Shot Text-Guided Video-to-Video Translation](https://arxiv.org/abs/2306.07954) (SIGGRAPH Asia 2023)\
  [![Star](https://img.shields.io/github/stars/williamyang1991/Rerender_A_Video.svg?style=social\&label=Star)](https://github.com/williamyang1991/Rerender_A_Video) ⭐ 3,000 | 🐛 54 | 🌐 Jupyter Notebook | 📅 2024-03-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07954)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.mmlab-ntu.com/project/rerender/)

* [MagicEdit: High-Fidelity and Temporally Coherent Video Editing](https://arxiv.org/abs/2308.14749) (Aug., 2023)\
  [![Star](https://img.shields.io/github/stars/magic-research/magic-edit.svg?style=social\&label=Star)](https://github.com/magic-research/magic-edit) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14749)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-edit.github.io/)

* [TokenFlow: Consistent Diffusion Features for Consistent Video Editing](https://arxiv.org/abs/2307.10373) (ICLR 2024)\
  [![Star](https://img.shields.io/github/stars/omerbt/TokenFlow.svg?style=social\&label=Star)](https://github.com/omerbt/TokenFlow) ⭐ 1,707 | 🐛 41 | 🌐 Python | 📅 2025-02-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.10373)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffusion-tokenflow.github.io/)

* [StableVideo: Text-driven Consistency-aware Diffusion Video Editing](https://arxiv.org/abs/2308.09592) (ICCV 2023)\
  [![Star](https://img.shields.io/github/stars/rese1f/StableVideo.svg?style=social\&label=Star)](https://github.com/rese1f/StableVideo) ⭐ 1,439 | 🐛 17 | 🌐 Python | 📅 2023-09-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.09592)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rese1f.github.io/StableVideo/)

* [FateZero: Fusing Attentions for Zero-shot Text-based Video Editing](https://arxiv.org/abs/2303.09535) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/ChenyangQiQi/FateZero.svg?style=social\&label=Star)](https://github.com/ChenyangQiQi/FateZero) ⭐ 1,162 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2023-08-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09535)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fate-zero-edit.github.io/)

* [AnyV2V: A Tuning-Free Framework For Any Video-to-Video Editing Tasks](https://arxiv.org/abs/2403.14468) (Mar., 2024)\
  [![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/AnyV2V.svg?style=social\&label=Star)](https://github.com/TIGER-AI-Lab/AnyV2V) ⭐ 655 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2024-10-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14468)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tiger-ai-lab.github.io/AnyV2V/)

* [VideoPainter: Any-length Video Inpainting and Editing with Plug-and-Play Context Control](https://arxiv.org/abs/2503.05639) (May, 2025 | SIGGRAPH 2025)\
  [![Star](https://img.shields.io/github/stars/TencentARC/VideoPainter.svg?style=social\&label=Star)](https://github.com/TencentARC/VideoPainter) ⭐ 633 | 🐛 16 | 🌐 Python | 📅 2025-04-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.05639)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yxbian23.github.io/project/video-painter/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/collections/TencentARC/videopainter-67cc49c6146a48a2ba93d159)

* [Scaling Instruction-Based Video Editing with a High-Quality Synthetic Dataset](https://arxiv.org/abs/2510.15742) (Oct., 2025)\
  [![Star](https://img.shields.io/github/stars/EzioBy/Ditto.svg?style=social\&label=Star)](https://github.com/EzioBy/Ditto) ⭐ 625 | 🐛 21 | 🌐 Python | 📅 2026-06-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.15742)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://editto.net/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/QingyanBai/Ditto-1M)

* [MiniMax-Remover: Taming Bad Noise Helps Video Object Removal](https://arxiv.org/abs/2505.24873) (May, 2025)\
  [![Star](https://img.shields.io/github/stars/zibojia/MiniMax-Remover.svg?style=social\&label=Star)](https://github.com/zibojia/MiniMax-Remover) ⭐ 600 | 🐛 11 | 🌐 Python | 📅 2025-07-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.24873)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://minimax-remover.github.io/)

* [ViViD: Video Virtual Try-on using Diffusion Models](https://arxiv.org/abs/2405.11794) (May, 2024)\
  [![Star](https://img.shields.io/github/stars/BecauseImBatman0/ViViD.svg?style=social\&label=Star)](https://github.com/BecauseImBatman0/ViViD) ⭐ 568 | 🐛 27 | 🌐 Python | 📅 2024-06-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.11794)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://becauseimbatman0.github.io/ViViD)

* [Looking Backward: Streaming Video-to-Video Translation with Feature Banks](https://arxiv.org/abs/2405.15757) (May, 2024)\
  [![Star](https://img.shields.io/github/stars/Jeff-LiangF/streamv2v.svg?style=social\&label=Star)](https://github.com/Jeff-LiangF/streamv2v) ⭐ 549 | 🐛 5 | 🌐 Python | 📅 2025-12-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15757)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jeff-liangf.github.io/projects/streamv2v/)

* [AniGS: Animatable Gaussian Avatar from a Single Image with Inconsistent Gaussian Reconstruction](https://arxiv.org/pdf/2412.02684) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/aigc3d/AniGS.svg?style=social\&label=Star)](https://github.com/aigc3d/AniGS) ⭐ 456 | 🐛 3 | 📅 2025-03-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02684)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lingtengqiu.github.io/2024/AniGS/)

* [Video-P2P: Video Editing with Cross-attention Control](https://arxiv.org/abs/2303.04761) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/ShaoTengLiu/Video-P2P.svg?style=social\&label=Star)](https://github.com/ShaoTengLiu/Video-P2P) ⭐ 430 | 🐛 5 | 🌐 Python | 📅 2025-06-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04761)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-p2p.github.io/)

* [VideoSwap: Customized Video Subject Swapping with Interactive Semantic Point Correspondence](https://arxiv.org/abs/2312.02087) (CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/showlab/VideoSwap.svg?style=social\&label=Star)](https://github.com/showlab/VideoSwap) ⭐ 404 | 🐛 5 | 🌐 Python | 📅 2024-12-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02087)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoswap.github.io/)

* [ReVideo: Remake a Video with Motion and Content Control](https://arxiv.org/abs/2405.13865) (May, 2024)\
  [![Star](https://img.shields.io/github/stars/MC-E/ReVideo.svg?style=social\&label=Star)](https://github.com/MC-E/ReVideo) ⭐ 393 | 🐛 8 | 🌐 Python | 📅 2024-09-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.13865)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mc-e.github.io/project/ReVideo/)

* [Zero-Shot Video Editing Using Off-the-Shelf Image Diffusion Models](https://arxiv.org/abs/2303.17599) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/baaivision/vid2vid-zero.svg?style=social\&label=Star)](https://github.com/baaivision/vid2vid-zero) ⭐ 356 | 🐛 8 | 🌐 Python | 📅 2023-07-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17599)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://huggingface.co/spaces/BAAI/vid2vid-zero)

* [LoRA-Edit: Controllable First-Frame-Guided Video Editing via Mask-Aware LoRA Fine-Tuning](https://arxiv.org/abs/2506.10082) (Jun, 2025)\
  [![Star](https://img.shields.io/github/stars/cjeen/LoRAEdit.svg?style=social\&label=Star)](https://github.com/cjeen/LoRAEdit) ⭐ 337 | 🐛 13 | 🌐 Python | 📅 2026-06-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.10082)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cjeen.github.io/LoraEditPaper/)

* [CoCoCo: Improving Text-Guided Video Inpainting for Better Consistency, Controllability and Compatibility](https://arxiv.org/abs/2403.12035) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12035)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cococozibojia.github.io/)
  [![Star](https://img.shields.io/github/stars/zibojia/COCOCO.svg?style=social\&label=Star)](https://github.com/zibojia/COCOCO) ⭐ 325 | 🐛 17 | 🌐 Python | 📅 2024-09-24

* [Make-A-Protagonist: Generic Video Editing with An Ensemble of Experts](https://arxiv.org/abs/2305.08850) (May, 2023)\
  [![Star](https://img.shields.io/github/stars/Make-A-Protagonist/Make-A-Protagonist.svg?style=social\&label=Star)](https://github.com/Make-A-Protagonist/Make-A-Protagonist) ⭐ 322 | 🐛 3 | 🌐 Python | 📅 2026-06-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.08850)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://make-a-protagonist.github.io/)

* [Kiwi-Edit: Versatile Video Editing via Instruction and Reference Guidance](https://arxiv.org/abs/2603.02175) (Mar., 2026)
  [![Star](https://img.shields.io/github/stars/showlab/Kiwi-Edit.svg?style=social\&label=Star)](https://github.com/showlab/Kiwi-Edit) ⭐ 320 | 🐛 15 | 🌐 Python | 📅 2026-05-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.02175)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Kiwi-Edit/)

* [RAVE: Randomized Noise Shuffling for Fast and Consistent Video Editing with Diffusion Models](https://arxiv.org/abs/2312.04524) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/rehg-lab/RAVE.svg?style=social\&label=Star)](https://github.com/rehg-lab/RAVE) ⭐ 312 | 🐛 3 | 🌐 Python | 📅 2025-02-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04524)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rave-video.github.io/)

* [ControlVideo: Adding Conditional Control for One Shot Text-to-Video Editing](https://arxiv.org/abs/2305.17098) (May, 2023)\
  [![Star](https://img.shields.io/github/stars/thu-ml/controlvideo.svg?style=social\&label=Star)](https://github.com/thu-ml/controlvideo) ⭐ 230 | 🐛 14 | 🌐 Python | 📅 2023-06-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17098)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ml.cs.tsinghua.edu.cn/controlvideo/)

* [Speech Driven Video Editing via an Audio-Conditioned Diffusion Model](https://arxiv.org/abs/2301.04474) (Jan., 2023)\
  [![Star](https://img.shields.io/github/stars/DanBigioi/DiffusionVideoEditing.svg?style=social\&label=Star)](https://github.com/DanBigioi/DiffusionVideoEditing) ⭐ 228 | 🐛 5 | 🌐 Python | 📅 2023-06-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.04474)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://danbigioi.github.io/DiffusionVideoEditing/)

* [VidToMe: Video Token Merging for Zero-Shot Video Editing](https://arxiv.org/abs/2312.10656) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/lixirui142/VidToMe.svg?style=social\&label=Star)](https://github.com/lixirui142/VidToMe) ⭐ 227 | 🐛 2 | 🌐 Python | 📅 2025-01-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.10656)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vidtome-diffusion.github.io/)

* [FLATTEN: optical FLow-guided ATTENtion for consistent text-to-video editing](https://arxiv.org/abs/2310.05922) (ICLR 2024)\
  [![Star](https://img.shields.io/github/stars/yrcong/flatten.svg?style=social\&label=Star)](https://github.com/yrcong/flatten) ⭐ 212 | 🐛 2 | 🌐 Python | 📅 2024-05-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05922)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://flatten-video-editing.github.io)

* [VideoCoF: Unified Video Editing with Temporal Reasoner](https://arxiv.org/abs/2512.07469) (Dec., 2025 | CVPR 2026)\
  [![Star](https://img.shields.io/github/stars/knightyxp/VideoCoF.svg?style=social\&label=Star)](https://github.com/knightyxp/VideoCoF) ⭐ 208 | 🐛 3 | 🌐 Python | 📅 2026-06-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.07469)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videocof.github.io/)
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/XiangpengYang/VideoCoF-50k)

* [VMC: Video Motion Customization using Temporal Attention Adaption for Text-to-Video Diffusion Models](https://arxiv.org/abs/2312.00845) (CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/HyeonHo99/Video-Motion-Customization.svg?style=social\&label=Star)](https://github.com/HyeonHo99/Video-Motion-Customization) ⭐ 199 | 🐛 9 | 🌐 Python | 📅 2024-03-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00845)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-motion-customization.github.io)

* [MotionEditor: Editing Video Motion via Content-Aware Diffusion](https://arxiv.org/abs/2311.18830) (Nov., 2023)\
  [![Star](https://img.shields.io/github/stars/Francis-Rings/MotionEditor.svg?style=social\&label=Star)](https://github.com/Francis-Rings/MotionEditor) ⭐ 187 | 🐛 6 | 🌐 Python | 📅 2025-09-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18830)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://francis-rings.github.io/MotionEditor/)

* [StableV2V: Stablizing Shape Consistency in Video-to-Video Editing](https://arxiv.org/pdf/2411.11045) (Nov, 2024)\
  [![Star](https://img.shields.io/github/stars/AlonzoLeeeooo/StableV2V.svg?style=social\&label=Star)](https://github.com/AlonzoLeeeooo/StableV2V) ⭐ 168 | 🐛 1 | 🌐 Python | 📅 2025-12-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.11045)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://alonzoleeeooo.github.io/StableV2V/)

* [OmniInsert: Mask-Free Video Insertion of Any Reference via Diffusion Transformer Models](https://arxiv.org/abs/2509.17627) (Sep., 2025)\
  [![Star](https://img.shields.io/github/stars/Phantom-video/OmniInsert.svg?style=social\&label=Star)](https://github.com/Phantom-video/OmniInsert) ⭐ 162 | 🐛 3 | 📅 2026-03-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.17627)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://phantom-video.github.io/OmniInsert/)

* [VideoGrain: Modulating Space-Time Attention for Multi-grained Video Editing](https://arxiv.org/abs/2502.17258) (Feb., 2025 | ICLR 2025)\
  [![Star](https://img.shields.io/github/stars/knightyxp/VideoGrain.svg?style=social\&label=Star)](https://github.com/knightyxp/VideoGrain) ⭐ 158 | 🐛 1 | 🌐 Python | 📅 2025-03-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17258)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://knightyxp.github.io/VideoGrain_project_page/)

* [Diffusion Video Autoencoders: Toward Temporally Consistent Face Video Editing via Disentangled Video Encoding](https://arxiv.org/abs/2212.02802) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/man805/Diffusion-Video-Autoencoders.svg?style=social\&label=Star)](https://github.com/man805/Diffusion-Video-Autoencoders) ⭐ 151 | 🐛 3 | 🌐 Python | 📅 2023-10-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02802)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diff-video-ae.github.io/)

* [FlowVid: Taming Imperfect Optical Flows for Consistent Video-to-Video Synthesis](https://arxiv.org/abs/2312.17681) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/Jeff-LiangF/FlowVid.svg?style=social\&label=Star)](https://github.com/Jeff-LiangF/FlowVid) ⭐ 145 | 🐛 0 | 📅 2024-06-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.17681)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jeff-liangf.github.io/projects/flowvid/)

* [Ground-A-Video: Zero-shot Grounded Video Editing using Text-to-image Diffusion Models](https://arxiv.org/abs/2310.01107) (ICLR 2024)\
  [![Star](https://img.shields.io/github/stars/Ground-A-Video/Ground-A-Video.svg?style=social\&label=Star)](https://github.com/Ground-A-Video/Ground-A-Video) ⭐ 140 | 🐛 2 | 🌐 Python | 📅 2024-05-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01107)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ground-a-video.github.io/)

* [EditVerse: Unifying Image and Video Editing and Generation with In-Context Learning](https://arxiv.org/abs/2509.20360) (Sep., 2025)\
  [![Star](https://img.shields.io/github/stars/adobe-research/EditVerse.svg?style=social\&label=Star)](https://github.com/adobe-research/EditVerse) ⭐ 139 | 🐛 1 | 🌐 Python | 📅 2025-10-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.20360)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://editverse.s3-website-us-east-1.amazonaws.com/)

* [UniEdit: A Unified Tuning-Free Framework for Video Motion and Appearance Editing](https://arxiv.org/abs/2402.13185) (Feb., 2024)\
  [![Star](https://img.shields.io/github/stars/JianhongBai/UniEdit.svg?style=social\&label=Star)](https://github.com/JianhongBai/UniEdit) ⭐ 121 | 🐛 8 | 🌐 Python | 📅 2025-04-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.13185)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jianhongbai.github.io/UniEdit/)

* [Señorita-2M : A High-Quality Instruction-based Dataset for General Video Editing by Video Specialists](https://arxiv.org/abs/2502.06734) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/zibojia/SENORITA.svg?style=social\&label=Star)](https://github.com/zibojia/SENORITA) ⭐ 112 | 🐛 9 | 🌐 Python | 📅 2025-04-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06734)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://senorita-2m-dataset.github.io/)

* [MagicStick: Controllable Video Editing via Control Handle Transformations](https://arxiv.org/abs/2312.03047) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/mayuelala/MagicStick.svg?style=social\&label=Star)](https://github.com/mayuelala/MagicStick) ⭐ 99 | 🐛 2 | 📅 2023-12-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03047)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-stick-edit.github.io/)

* [A Video is Worth 256 Bases: Spatial-Temporal Expectation-Maximization Inversion for Zero-Shot Video Editing](https://arxiv.org/abs/2312.05856) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/STEM-Inv/stem-inv.svg?style=social\&label=Star)](https://github.com/STEM-Inv/stem-inv) ⭐ 96 | 🐛 2 | 🌐 Python | 📅 2024-06-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05856)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stem-inv.github.io/page/)

* [VividFace: A Diffusion-Based Hybrid Framework for High-Fidelity Video Face Swapping](https://arxiv.org/abs/2403.16999) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/deepcs233/VividFace.svg?style=social\&label=Star)](https://github.com/deepcs233/VividFace) ⭐ 87 | 🐛 9 | 🌐 Python | 📅 2025-10-15
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.16999)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hao-shao.com/projects/vividface.html)

* [Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation](https://arxiv.org/pdf/2501.05020) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social\&label=Star)](https://github.com/chen-yingjie/Perception-as-Control) ⭐ 81 | 🐛 2 | 🌐 Python | 📅 2025-08-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.05020)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chen-yingjie.github.io/projects/Perception-as-Control/)

* [MotionV2V: Editing Motion in a Video](https://arxiv.org/abs/2511.20640) (Nov., 2025)
  [![Star](https://img.shields.io/github/stars/RyannDaGreat/MotionV2V.svg?style=social\&label=Star)](https://github.com/RyannDaGreat/MotionV2V) ⭐ 57 | 🐛 2 | 🌐 HTML | 📅 2026-03-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.20640)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ryanndagreat.github.io/MotionV2V/)

* [Slicedit: Zero-Shot Video Editing With Text-to-Image Diffusion Models Using Spatio-Temporal Slices](https://arxiv.org/abs/2405.12211) (May, 2024)\
  [![Star](https://img.shields.io/github/stars/fallenshock/Slicedit.svg?style=social\&label=Star)](https://github.com/fallenshock/Slicedit) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2024-11-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.12211)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://matankleiner.github.io/slicedit/)

* [DragVideo: Interactive Drag-style Video Editing](https://arxiv.org/abs/2312.02216) (Dec., 2023)\
  [![Star](https://img.shields.io/github/stars/RickySkywalker/DragVideo-Official.svg?style=social\&label=Star)](https://github.com/RickySkywalker/DragVideo-Official) ⭐ 57 | 🐛 4 | 📅 2024-09-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02216)

* [NOVA: Sparse Control, Dense Synthesis for Pair-Free Video Editing](https://arxiv.org/abs/2603.02802) (Mar., 2026)
  [![Star](https://img.shields.io/github/stars/WeChatCV/NovaEdit.svg?style=social\&label=Star)](https://github.com/WeChatCV/NovaEdit) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2026-03-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.02802)

* [OutDreamer: Video Outpainting with a Diffusion Transformer](https://arxiv.org/abs/2506.22298) (Jun., 2025 | IEEE TIP 2026)
  [![Star](https://img.shields.io/github/stars/zhongzero/OutDreamer.svg?style=social\&label=Star)](https://github.com/zhongzero/OutDreamer) ⭐ 47 | 🐛 0 | 📅 2026-07-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.22298)

* [Soundini: Sound-Guided Diffusion for Natural Video Editing](https://arxiv.org/abs/2304.06818) (Apr., 2023)\
  [![Star](https://img.shields.io/github/stars/kuai-lab/soundini-official.svg?style=social\&label=Star)](https://github.com/kuai-lab/soundini-official) ⭐ 44 | 🐛 0 | 📅 2023-05-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06818)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kuai-lab.github.io/soundini-gallery/)

* [VEGGIE: Instructional Editing and Reasoning of Video Concepts with Grounded Generation](https://arxiv.org/abs/2503.14350) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/Yui010206/VEGGIE-VidEdit.svg?style=social\&label=Star)](https://github.com/Yui010206/VEGGIE-VidEdit/) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2025-08-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06734)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://veggie-gen.github.io/)

* [EVA: Zero-shot Accurate Attributes and Multi-Object Video Editing](https://arxiv.org/abs/2403.16111) (Mar., 2024)\
  [![Star](https://img.shields.io/github/stars/knightyxp/EVA_Video_Edit.svg?style=social\&label=Star)](https://github.com/knightyxp/EVA_Video_Edit) ⭐ 30 | 🐛 1 | 📅 2024-03-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.16111)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://knightyxp.github.io/EVA/)

* [VASE: Object-Centric Shape and Appearance Manipulation of Real Videos](https://arxiv.org/abs/2401.02473) (Jan., 2024)\
  [![Star](https://img.shields.io/github/stars/helia95/VASE.svg?style=social\&label=Star)](https://github.com/helia95/VASE) ⭐ 15 | 🐛 0 | 📅 2024-01-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.02473)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://helia95.github.io/vase-website/)

* [CoDeF: Content Deformation Fields for Temporally Consistent Video Processing](https://arxiv.org/abs/2308.07926) (CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/qiuyu96/CoDeF.svg?style=social\&label=Star)](https://github.com/qiuyu96/CoDeF) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07926)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://qiuyu96.github.io/CoDeF/)

* [UNIC: Unified In-Context Video Editing](https://arxiv.org/abs/2506.04216) (Jun, 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.04216)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zixuan-ye.github.io/UNIC/)

* [MTV-Inpaint: Multi-Task Long Video Inpainting](https://arxiv.org/abs/2503.11412) (Mar., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11412)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mtv-inpaint.github.io/)

* [Qffusion: Controllable Portrait Video Editing via Quadrant-Grid Attention Learning](https://arxiv.org/abs/2501.06438) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06438)

* [MIVE: New Design and Benchmark for Multi-Instance Video Editing](https://arxiv.org/abs/2412.12877) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.12877)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kaist-viclab.github.io/mive-site/)

* [MotionFlow: Attention-Driven Motion Transfer in Video Diffusion Models](https://arxiv.org/abs/2412.05275) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05275)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://motionflow-diffusion.github.io/)

* [DIVE: Taming DINO for Subject-Driven Video Editing](https://arxiv.org/abs/2412.03347) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03347)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dino-video-editing.github.io/)

* [Unified Editing of Panorama, 3D Scenes, and Videos Through Disentangled Self-Attention Injection](https://arxiv.org/abs/2405.16823) (May, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16823)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://unifyediting.github.io/)

* [I2VEdit: First-Frame-Guided Video Editing via Image-to-Video Diffusion Models](https://arxiv.org/abs/2405.16537) (May, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16537)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://i2vedit.github.io/)

* [Edit-Your-Motion: Space-Time Diffusion Decoupling Learning for Video Motion Editing](https://arxiv.org/abs/2405.04496) (May, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.04496)

* [GenVideo: One-shot target-image and shape aware video editing using T2I diffusion models](https://arxiv.org/abs/2404.12541) (Apr., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.12541)

* [Spectral Motion Alignment for Video Motion Transfer using Diffusion Models](https://arxiv.org/abs/2403.15249) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15249)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://geonyeong-park.github.io/spectral-motion-alignment/)

* [DreamMotion: Space-Time Self-Similarity Score Distillation for Zero-Shot Video Editing](https://arxiv.org/abs/2403.12002) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12002)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hyeonho99.github.io/dreammotion/)

* [Video Editing via Factorized Diffusion Distillation](https://arxiv.org/abs/2403.09334) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.09334)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fdd-video-edit.github.io/)

* [FastVideoEdit: Leveraging Consistency Models for Efficient Text-to-Video Editing](https://arxiv.org/abs/2403.06269) (Mar., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06269)

* [Object-Centric Diffusion for Efficient Video Editing](https://arxiv.org/abs/2401.05735) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.05735)

* [Fairy: Fast Parallelized Instruction-Guided Video-to-Video Synthesis](https://arxiv.org/abs/2312.13834) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.13834)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fairy-video2video.github.io/)

* [RealCraft: Attention Control as A Solution for Zero-shot Long Video Editing](https://arxiv.org/abs/2312.12635) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12635)

* [MaskINT: Video Editing via Interpolative Non-autoregressive Masked Transformers](https://arxiv.org/abs/2312.12468) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12468)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maskint.github.io/)

* [Neutral Editing Framework for Diffusion-based Video Editing](https://arxiv.org/abs/2312.06708) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06708)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://neuedit.github.io/)

* [DiffusionAtlas: High-Fidelity Consistent Diffusion Video Editing](https://arxiv.org/abs/2312.03772) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03772)

* [SAVE: Protagonist Diversification with Structure Agnostic Video Editing](https://arxiv.org/abs/2312.02503) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02503)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ldynx.github.io/SAVE/)

* [Drag-A-Video: Non-rigid Video Editing with Point-based Interaction](https://arxiv.org/abs/2312.02936) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02936)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://drag-a-video.github.io/)

* [BIVDiff: A Training-Free Framework for General-Purpose Video Synthesis via Bridging Image and Video Diffusion Models](https://arxiv.org/abs/2312.02813) (Dec., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02813)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bivdiff.github.io/)

* [Motion-Conditioned Image Animation for Video Editing](https://arxiv.org/abs/2311.18827) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18827)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://facebookresearch.github.io/MoCA/)

* [Space-Time Diffusion Features for Zero-Shot Text-Driven Motion Transfer](https://arxiv.org/abs/2311.17009) (CVPR 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17009)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffusion-motion-transfer.github.io/)

* [Cut-and-Paste: Subject-Driven Video Editing with Attention Control](https://arxiv.org/abs/2311.11697) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11697)

* [LatentWarp: Consistent Diffusion Latents for Zero-Shot Video-to-Video Translation](https://arxiv.org/abs/2311.00353) (Nov., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00353)

* [Fuse Your Latents: Video Editing with Multi-source Latent Diffusion Models](https://arxiv.org/abs/2310.16400) (Oct., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.16400)

* [DynVideo-E: Harnessing Dynamic NeRF for Large-Scale Motion- and View-Change Human-Centric Video Editing](https://arxiv.org/abs/2310.10624) (Oct., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10624)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/DynVideo-E/)

* [CCEdit: Creative and Controllable Video Editing via Diffusion Models](https://arxiv.org/abs/2309.16496) (Sep., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16496)

* [MagicProp: Diffusion-based Video Editing via Motion-aware Appearance Propagation](https://arxiv.org/abs/2309.00908) (Sep., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.00908)

* [INVE: Interactive Neural Video Editing](https://arxiv.org/abs/2307.07663) (Jul., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.07663)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gabriel-huang.github.io/inve/)

* [VidEdit: Zero-Shot and Spatially Aware Text-Driven Video Editing](https://arxiv.org/abs//2306.08707) (Jun., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs//2306.08707)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videdit.github.io/)

* [Edit-A-Video: Single Video Editing with Object-Aware Consistency](https://arxiv.org/abs/2303.17599) (Mar., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.07945)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://edit-a-video.github.io/)

* [Pix2video: Video Editing Using Image Diffusion](https://arxiv.org/abs/2303.12688) (Mar., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12688)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://duyguceylan.github.io/pix2video.github.io/)

* [Dreamix: Video Diffusion Models Are General Video Editors](https://arxiv.org/abs/2302.01329) (Feb., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamix-video-editing.github.io/)

* [Shape-Aware Text-Driven Layered Video Editing](https://arxiv.org/abs/2301.13173) (Jan., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.13173)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://text-video-edit.github.io/)

### Human or Subject Motion

* [EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions](https://arxiv.org/abs/2407.08136) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/BadToBest/EchoMimic.svg?style=social)](https://github.com/BadToBest/EchoMimic) ⭐ 4,297 | 🐛 119 | 🌐 Python | 📅 2026-04-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.08136)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://badtobest.github.io/echomimic.html)

* [Human Motion Diffusion Model](https://arxiv.org/abs/2209.14916) (ICLR 2023)\
  [![Star](https://img.shields.io/github/stars/GuyTevet/motion-diffusion-model.svg?style=social\&label=Star)](https://github.com/GuyTevet/motion-diffusion-model) ⭐ 4,092 | 🐛 69 | 🌐 Python | 📅 2025-10-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.14916)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://guytevet.github.io/mdm-page/)

* [MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model](https://arxiv.org/abs/2208.15001) (Aug., 2022)\
  [![Star](https://img.shields.io/github/stars/mingyuan-zhang/MotionDiffuse.svg?style=social\&label=Star)](https://github.com/mingyuan-zhang/MotionDiffuse) ⭐ 982 | 🐛 26 | 🌐 Python | 📅 2024-07-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.15001)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)

* [Executing Your Commands via Motion Diffusion in Latent Space](https://arxiv.org/abs/2212.04048) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/ChenFengYe/motion-latent-diffusion.svg?style=social\&label=Star)](https://github.com/ChenFengYe/motion-latent-diffusion) ⭐ 746 | 🐛 39 | 🌐 Python | 📅 2023-07-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04048)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chenxin.tech/mld/)

* [AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation](https://arxiv.org/pdf/2411.17383) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/cangcz/AnchorCrafter.svg?style=social)](https://github.com/cangcz/AnchorCrafter) ⭐ 671 | 🐛 2 | 🌐 Python | 📅 2025-11-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17383)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cangcz.github.io/Anchor-Crafter/)

* [Human Motion Diffusion as a Generative Prior](https://arxiv.org/abs/2303.01418) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/priorMDM/priorMDM.svg?style=social\&label=Star)](https://github.com/priorMDM/priorMDM) ⭐ 525 | 🐛 6 | 🌐 Python | 📅 2026-04-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.01418)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://priormdm.github.io/priorMDM-page/)

* [AnyTop: Character Animation Diffusion with Any Topology](https://arxiv.org/abs/2502.17327) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/Anytop2025/Anytop.svg?style=social)](https://github.com/Anytop2025/Anytop) ⭐ 454 | 🐛 1 | 🌐 Python | 📅 2026-04-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17327)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anytop2025.github.io/Anytop-page/)

* [Single Motion Diffusion](https://arxiv.org/abs/2302.05905) (Feb., 2023)\
  [![Star](https://img.shields.io/github/stars/SinMDM/SinMDM.svg?style=social\&label=Star)](https://github.com/SinMDM/SinMDM) ⭐ 411 | 🐛 0 | 🌐 Python | 📅 2025-03-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.05905)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sinmdm.github.io/SinMDM-page/)

* [ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model](https://arxiv.org/abs/2304.01116) (Apr., 2023)\
  [![Star](https://img.shields.io/github/stars/mingyuan-zhang/ReMoDiffuse.svg?style=social\&label=Star)](https://github.com/mingyuan-zhang/ReMoDiffuse) ⭐ 380 | 🐛 13 | 🌐 Python | 📅 2024-04-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01116)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html)

* [InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions](https://arxiv.org/abs/2304.05684) (Apr., 2023)\
  [![Star](https://img.shields.io/github/stars/tr3e/InterGen.svg?style=social\&label=Star)](https://github.com/tr3e/InterGen) ⭐ 331 | 🐛 41 | 🌐 Python | 📅 2024-07-20
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.05684)

* [HumanMAC: Masked Motion Completion for Human Motion Prediction](https://arxiv.org/abs/2302.03665) (Feb., 2023)\
  [![Star](https://img.shields.io/github/stars/LinghaoChan/HumanMAC.svg?style=social\&label=Star)](https://github.com/LinghaoChan/HumanMAC) ⭐ 327 | 🐛 5 | 🌐 Python | 📅 2024-05-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03665)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lhchen.top/Human-MAC/)

* [MTVCrafter: 4D Motion Tokenization for Open-World Human Image Animation](https://arxiv.org/abs/2505.10238) (May., 2025)\
  [![Star](https://img.shields.io/github/stars/DINGYANB/MTVCrafter.svg?style=social)](https://github.com/DINGYANB/MTVCrafter) ⭐ 279 | 🐛 9 | 🌐 Python | 📅 2026-02-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.10238)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dingyanb.github.io/MTVCtafter/)

* [Avatars Grow Legs: Generating Smooth Human Motion from Sparse Tracking Inputs with Diffusion Model](https://arxiv.org/abs/2304.08577) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/facebookresearch/AGRoL.svg?style=social\&label=Star)](https://github.com/facebookresearch/AGRoL) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08577)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dulucas.github.io/agrol/)

* [Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion](https://arxiv.org/abs/2203.13777) (CVPR 2022)\
  [![Star](https://img.shields.io/github/stars/gutianpei/MID.svg?style=social\&label=Star)](https://github.com/gutianpei/MID) ⭐ 235 | 🐛 13 | 🌐 Python | 📅 2023-04-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.13777)

* [DiffSHEG: A Diffusion-Based Approach for Real-Time Speech-driven Holistic 3D Expression and Gesture Generation](https://arxiv.org/abs/2401.04747) (CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/JeremyCJM/DiffSHEG.svg?style=social\&label=Star)](https://github.com/JeremyCJM/DiffSHEG) ⭐ 207 | 🐛 13 | 🌐 Python | 📅 2024-04-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04747)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jeremycjm.github.io/proj/DiffSHEG/)

* [BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction](https://arxiv.org/abs/2211.14304) (Dec., 2022)\
  [![Star](https://img.shields.io/github/stars/BarqueroGerman/BeLFusion.svg?style=social\&label=Star)](https://github.com/BarqueroGerman/BeLFusion) ⭐ 126 | 🐛 3 | 🌐 Python | 📅 2023-10-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.14304)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://barquerogerman.github.io/BeLFusion/)

* [FLAME: Free-form Language-based Motion Synthesis & Editing](https://arxiv.org/abs/2209.00349) (AAAI 2023)\
  [![Star](https://img.shields.io/github/stars/kakaobrain/flame.svg?style=social\&label=Star)](https://github.com/kakaobrain/flame) ⭐ 118 | 🐛 6 | 🌐 Python | 📅 2024-01-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.00349)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kakaobrain.github.io/flame/)

* [Can We Use Diffusion Probabilistic Models for 3d Motion Prediction?](https://arxiv.org/abs/2302.14503) (Feb., 2023)\
  [![Star](https://img.shields.io/github/stars/cotton-ahn/diffusion-motion-prediction.svg?style=social\&label=Star)](https://github.com/cotton-ahn/diffusion-motion-prediction) ⭐ 107 | 🐛 0 | 🌐 Python | 📅 2023-09-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.14503)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/diffusion-motion-prediction)

* [Enhancing Motion in Text-to-Video Generation with Decomposed Encoding and Conditioning](https://arxiv.org/abs/2410.24219) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/PR-Ryan/DEMO.svg?style=social)](https://github.com/PR-Ryan/DEMO) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2024-11-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.24219)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pr-ryan.github.io/DEMO-project/)

* [Unifying Human Motion Synthesis and Style Transfer With Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2212.08526) (GRAPP 2023)\
  [![Star](https://img.shields.io/github/stars/mrzzy2021/styledmotionsynthesis.svg?style=social\&label=Star)](https://github.com/mrzzy2021/styledmotionsynthesis) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2022-12-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.08526)

* [HumanDiT: Pose-Guided Diffusion Transformer for Long-form Human Motion Video Generation](https://arxiv.org/abs/2502.04847) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.04847)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://agnjason.github.io/HumanDiT-page/)

* [VideoJAM: Joint Appearance-Motion Representations for Enhanced Motion Generation in Video Models](https://hila-chefer.github.io/videojam-paper.github.io/VideoJAM_arxiv.pdf) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://hila-chefer.github.io/videojam-paper.github.io/VideoJAM_arxiv.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hila-chefer.github.io/videojam-paper.github.io/)

* [OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models](https://arxiv.org/abs/2502.01061) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://omnihuman-lab.github.io/)

* [KMM: Key Frame Mask Mamba for Extended Motion Generation](https://arxiv.org/abs/2411.06481) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/steve-zeyu-zhang/KMM.svg?style=social)](https://github.com/steve-zeyu-zhang/KMM)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.06481)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://steve-zeyu-zhang.github.io/KMM/)

* [DanceFusion: A Spatio-Temporal Skeleton Diffusion Transformer for Audio-Driven Dance Motion Reconstruction](https://arxiv.org/abs/2411.04646) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04646)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://th-mlab.github.io/DanceFusion/)

* [A Comprehensive Survey on Human Video Generation: Challenges, Methods, and Insights](https://arxiv.org/abs/2407.08428) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08428)

* [OccFusion: Rendering Occluded Humans with Generative Diffusion Priors](https://arxiv.org/pdf/2406.08801) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.00316)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cs.stanford.edu/~xtiange/projects/occfusion/)

* [DiffMotion: Speech-Driven Gesture Synthesis Using Denoising Diffusion Model](https://arxiv.org/abs/2301.10047) (Jan., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.10047)

* [Modiff: Action-Conditioned 3d Motion Generation With Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2301.03949) (Jan., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.03949)

* [Pretrained Diffusion Models for Unified Human Motion Synthesis](https://arxiv.org/abs/2212.02837) (Dec., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02837)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ofa-sys.github.io/MoFusion/)

* [PhysDiff: Physics-Guided Human Motion Diffusion Model](https://arxiv.org/abs/2212.02500) (Dec., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02500)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://nvlabs.github.io/PhysDiff/)

* [Diffusion Motion: Generate Text-Guided 3d Human Motion by Diffusion Model](https://arxiv.org/abs/2210.12315) (ICASSP 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.12315)

* [Human Joint Kinematics Diffusion-Refinement for Stochastic Motion Prediction](https://arxiv.org/abs/2210.05976) (Oct., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.05976)

### Video Enhancement and Restoration

* [Enhance-A-Video: Better Generated Video for Free](https://arxiv.org/abs/2502.07508) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/Enhance-A-Video.svg?style=social\&label=Star)](https://github.com/NUS-HPC-AI-Lab/Enhance-A-Video) ⭐ 602 | 🐛 6 | 🌐 Python | 📅 2025-03-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07508)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://oahzxl.github.io/Enhance_A_Video/)

* [Disentangled Motion Modeling for Video Frame Interpolation](https://arxiv.org/abs/2406.17256) (Jun, 2024)\
  [![Star](https://img.shields.io/github/stars/JHLew/MoMo.svg?style=social\&label=Star)](https://github.com/JHLew/MoMo) ⭐ 132 | 🐛 2 | 🌐 Python | 📅 2025-05-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17256)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/JHLew/MoMo) ⭐ 132 | 🐛 2 | 🌐 Python | 📅 2025-05-01

* [SVFR: A Unified Framework for Generalized Video Face Restoration](https://arxiv.org/abs/2501.01235) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01235)

* [DiffIR2VR-Zero: Zero-Shot Video Restoration with Diffusion-based Image Restoration Models](https://arxiv.org/abs/2407.01519) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01519)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jimmycv07.github.io/DiffIR2VR_web/)

* [LDMVFI: Video Frame Interpolation with Latent Diffusion Models](https://arxiv.org/abs/2303.09508) (Mar., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09508)

* [CaDM: Codec-aware Diffusion Modeling for Neural-enhanced Video Streaming](https://arxiv.org/abs/2211.08428) (Nov., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.08428)

### Audio Synthesis for Video

* [Speech To Speech: an effort for an open-sourced and modular GPT4-o](https://github.com/huggingface/speech-to-speech) ⭐ 13,007 | 🐛 100 | 🌐 Python | 📅 2026-09-02 (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/huggingface/speech-to-speech.svg?style=social\&label=Star)](https://github.com/huggingface/speech-to-speech) ⭐ 13,007 | 🐛 100 | 🌐 Python | 📅 2026-09-02
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/huggingface/speech-to-speech) ⭐ 13,007 | 🐛 100 | 🌐 Python | 📅 2026-09-02

* [Mini-Omni: Language Models Can Hear, Talk While Thinking in Streaming](https://arxiv.org/abs/2408.16725) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/gpt-omni/mini-omni.svg?style=social\&label=Star)](https://github.com/gpt-omni/mini-omni) ⭐ 3,574 | 🐛 40 | 🌐 Python | 📅 2024-11-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.16725)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/gpt-omni/mini-omni) ⭐ 3,574 | 🐛 40 | 🌐 Python | 📅 2024-11-05

* [Taming Multimodal Joint Training for High-Quality Video-to-Audio Synthesis](https://arxiv.org/abs/2412.15322) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/hkchengrex/MMAudio.svg?style=social\&label=Star)](https://github.com/hkchengrex/MMAudio) ⭐ 2,264 | 🐛 12 | 🌐 Python | 📅 2026-02-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15322)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hkchengrex.com/MMAudio/)

* [Diverse and Aligned Audio-to-Video Generation via Text-to-Video Model Adaptation](https://arxiv.org/abs/2309.16429) (Sep., 2023)\
  [![Star](https://img.shields.io/github/stars/guyyariv/TempoTokens.svg?style=social\&label=Star)](https://github.com/guyyariv/TempoTokens) ⭐ 131 | 🐛 3 | 🌐 Python | 📅 2026-05-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16429)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pages.cs.huji.ac.il/adiyoss-lab/TempoTokens/)

* [Video-to-Audio Generation with Hidden Alignment](https://arxiv.org/abs/2407.07464) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/ariesssxu/vta-ldm.svg?style=social\&label=Star)](https://github.com/ariesssxu/vta-ldm) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.07464)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/vta-ldm)

* [Draw an Audio: Leveraging Multi-Instruction for Video-to-Audio Synthesis](https://arxiv.org/pdf/2409.06135) (Sep., 2024)\
  [![Star](https://img.shields.io/github/stars/yannqi/Draw-an-Audio-Code.svg?style=social\&label=Star)](https://github.com/yannqi/Draw-an-Audio-Code) ⭐ 45 | 🐛 1 | 📅 2024-09-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.06135)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yannqi.github.io/Draw-an-Audio/)

* [Read, Watch and Scream! Sound Generation from Text and Video](https://arxiv.org/abs/2407.05551) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/naver-ai/rewas.svg?style=social\&label=Star)](https://github.com/naver-ai/rewas) ⭐ 45 | 🐛 3 | 🌐 Python | 📅 2024-12-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.05551)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://naver-ai.github.io/rewas/)

* [STA-V2A: Video-to-Audio Generation with Semantic and Temporal Alignment](https://arxiv.org/pdf/2409.08601) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/yannqi/Draw-an-Audio-Code.svg?style=social\&label=Star)](https://github.com/y-ren16/STAV2A) ⭐ 20 | 🐛 2 | 🌐 Python | 📅 2025-08-11
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.08601)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://y-ren16.github.io/STAV2A/)

* [Video-Foley: Two-Stage Video-To-Sound Generation via Temporal Event Condition For Foley Sound](https://arxiv.org/abs/2408.11915) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/jnwnlee/video-foley.svg?style=social\&label=Star)](https://github.com/jnwnlee/video-foley) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2026-02-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11915)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jnwnlee.github.io/video-foley-demo/)

* [Stable-V2A: Synthesis of Synchronized Audio Effects with Temporal and Semantic Controls](https://arxiv.org/abs/2412.15023) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/ispamm/Stable-V2A.svg?style=social\&label=Star)](https://github.com/ispamm/Stable-V2A) ⭐ 18 | 🐛 1 | 📅 2025-05-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15023)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ispamm.github.io/Stable-V2A/)

* [Network Bending of Diffusion Models for Audio-Visual Generation](https://arxiv.org/abs/2406.19589) (CVPR, 2024)\
  [![Star](https://img.shields.io/github/stars/dzluke/DAFX2024.svg?style=social\&label=Star)](https://github.com/dzluke/DAFX2024) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2025-08-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19589)

* [AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation](https://arxiv.org/abs/2412.15191) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/snap-research/AVLink.svg?style=social\&label=Star)](https://github.com/snap-research/AVLink) ⭐ 16 | 🐛 4 | 📅 2025-08-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15191)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/AVLink/)

* [AV-DiT: Efficient Audio-Visual Diffusion Transformer for Joint Audio and Video Generation](https://arxiv.org/pdf/2406.07686) (Feb., 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.07686)

* [UniForm: A Unified Diffusion Transformer for Audio-Video Generation](https://arxiv.org/abs/2502.03897) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.03897)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://uniform-t2av.github.io/)

* [AGAV-Rater: Enhancing LMM for AI-Generated Audio-Visual Quality Assessment](https://arxiv.org/abs/2501.18314) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.18314)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://agav-rater.github.io/)

* [XMusic: Towards a Generalized and Controllable Symbolic Music Generation Framework](https://arxiv.org/abs/2501.08809) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08809)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xmusic-project.github.io/)

* [VinTAGe: Joint Video and Text Conditioning for Holistic Audio Generation](https://arxiv.org/abs/2412.10768) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.10768)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.youtube.com/watch?v=QmqWhUjPkJI)

* [YingSound: Video-Guided Sound Effects Generation with Multi-modal Chain-of-Thought Controls](https://arxiv.org/abs/2412.09551) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09551)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://giantailab.github.io/yingsound/)

* [Video-Guided Foley Sound Generation with Multimodal Controls](https://arxiv.org/pdf/2411.17698) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17698)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ificl.github.io/MultiFoley/)

* [MuVi: Video-to-Music Generation with Semantic Alignment and Rhythmic Synchronization](https://arxiv.org/abs/2410.12957) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.12957)

* [VMAs: Video-to-Music Generation via Semantic Alignment in Web Music Videos](https://www.arxiv.org/abs/2409.07450) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.07450)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://genjib.github.io/project_page/VMAs/index.html)

* [Masked Generative Video-to-Audio Transformers with Enhanced Synchronicity](https://arxiv.org/abs/2407.10387) (Jul., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.10387)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maskvat.github.io/)

* [FoleyCrafter: Bring Silent Videos to Life with Lifelike and Synchronized Sounds](https://arxiv.org/abs/2407.01494) (July, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01494)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://foleycrafter.github.io/)

### Talking Head Generation

* [Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/pdf/2406.08801) (Jun., 2024)\
  [![Star](https://img.shields.io/github/stars/fudan-generative-vision/hallo?style=social)](https://github.com/fudan-generative-vision/hallo) ⭐ 8,663 | 🐛 113 | 🌐 Python | 📅 2024-09-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.08801)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fudan-generative-vision.github.io/hallo/#/)

* [Hallo2: Long-Duration and High-Resolution Audio-driven Portrait Image Animation](https://arxiv.org/pdf/2410.07718) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/fudan-generative-vision/hallo2.svg?style=social)](https://github.com/fudan-generative-vision/hallo2) ⭐ 3,735 | 🐛 50 | 🌐 Python | 📅 2025-02-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.07718)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fudan-generative-vision.github.io/hallo2/#/)

* [Hallo3: Highly Dynamic and Realistic Portrait Image Animation with Diffusion Transformer Networks](https://arxiv.org/pdf/2412.00733) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.00733)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/fudan-generative-vision/hallo3) ⭐ 1,402 | 🐛 35 | 🌐 Python | 📅 2025-03-13

* [MEMO: Memory-Guided Diffusion for Expressive Talking Video Generation](https://arxiv.org/abs/2412.04448) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04448)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://memoavatar.github.io/)
  [![Star](https://img.shields.io/github/stars/memoavatar/memo.svg?style=social)](https://github.com/memoavatar/memo) ⭐ 1,071 | 🐛 19 | 🌐 Python | 📅 2025-08-06

* [MimicTalk: Mimicking a personalized and expressive 3D talking face in few minutes](https://arxiv.org/abs/2410.06734) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/yerfor/MimicTalk.svg?style=social)](https://github.com/yerfor/MimicTalk) ⭐ 831 | 🐛 56 | 🌐 Python | 📅 2024-10-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.06734)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mimictalk.github.io/)

* [HelloMeme: Integrating Spatial Knitting Attentions to Embed High-Level and Fidelity-Rich Conditions in Diffusion Models](https://arxiv.org/abs/2410.22901) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/HelloVision/HelloMeme.svg?style=social)](https://github.com/HelloVision/HelloMeme) ⭐ 624 | 🐛 19 | 🌐 Python | 📅 2025-06-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.22901)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://songkey.github.io/hellomeme/)

* [Audio-visual Controlled Video Diffusion with Masked Selective State Spaces Modelling for Natural Talking Head Generation](https://harlanhong.github.io/publications/actalker/index.html) (Apr., 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02542)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://harlanhong.github.io/publications/actalker/index.html)
  [![Star](https://img.shields.io/github/stars/harlanhong/ACTalker.svg?style=social)](https://github.com/harlanhong/ACTalker) ⭐ 463 | 🐛 10 | 🌐 Python | 📅 2025-08-20

* [KeySync: A Robust Approach for Leakage-free Lip Synchronization in High Resolution](https://antonibigata.github.io/KeySync/) (May, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.00497)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://antonibigata.github.io/KeySync/)
  [![Star](https://img.shields.io/github/stars/antonibigata/keysync.svg?style=social)](https://github.com/antonibigata/keysync) ⭐ 400 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2026-01-23

* [DAWN: Dynamic Frame Avatar with Non-autoregressive Diffusion Framework for Talking Head Video Generation](https://arxiv.org/abs/2410.13726) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/Hanbo-Cheng/DAWN-pytorch.svg?style=social)](https://github.com/Hanbo-Cheng/DAWN-pytorch) ⭐ 233 | 🐛 2 | 🌐 Python | 📅 2025-11-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13726)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hanbo-cheng.github.io/DAWN/)

* [TalkingMachines: Real-Time Audio-Driven FaceTime-Style Video via Autoregressive Diffusion Models](https://aaxwaz.github.io/TalkingMachines/) (Jun., 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.03099)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aaxwaz.github.io/TalkingMachines/)
  [![Star](https://img.shields.io/github/stars/aaxwaz/TalkingMachines.svg?style=social)](https://github.com/aaxwaz/TalkingMachines) ⭐ 178 | 🐛 3 | 🌐 JavaScript | 📅 2025-08-02

* [Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/evonneng/learning2listen.svg?style=social)](https://github.com/evonneng/learning2listen) ⭐ 130 | 🐛 5 | 🌐 Python | 📅 2024-08-18
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.08451)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://evonneng.github.io/learning2listen/)

* [Synergizing Motion and Appearance: Multi-Scale Compensatory Codebooks for Talking Head Video Generation](https://arxiv.org/abs/2412.00719) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/ShaelynZ/synergize-motion-appearance.svg?style=social)](https://github.com/ShaelynZ/synergize-motion-appearance) ⭐ 66 | 🐛 2 | 🌐 Python | 📅 2026-07-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00719)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shaelynz.github.io/synergize-motion-appearance/)

* [IM-Portrait: Learning 3D-aware Video Diffusion for Photorealistic Talking Heads from Monocular Videos](https://y-u-a-n-l-i.github.io/projects/IM-Portrait/) (May, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.19165)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://y-u-a-n-l-i.github.io/projects/IM-Portrait/)

* [OmniTalker: Real-Time Text-Driven Talking Head Generation with In-Context Audio-Visual Style Replication](https://humanaigc.github.io/omnitalker/) (Apr., 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02433v1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanaigc.github.io/omnitalker/)

* [MoCha: Towards Movie-Grade Talking Character Synthesis](https://arxiv.org/abs/2503.23307) (Apr., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.23307)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://congwei1230.github.io/MoCha/)

* [SayAnything: Audio-Driven Lip Synchronization with Conditional Video Diffusion](https://arxiv.org/pdf/2502.11515) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11515)

* [VQTalker: Towards Multilingual Talking Avatars through Facial Motion Tokenization](https://arxiv.org/abs/2412.09892) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09892)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://x-lance.github.io/VQTalker/)

* [IF-MDM: Implicit Face Motion Diffusion Model for High-Fidelity Realtime Talking Head Generation](https://arxiv.org/abs/2412.04000) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04000)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://ec2-3-25-102-128.ap-southeast-2.compute.amazonaws.com/IF-MDM/ifmdm_supplementary/index.html)

* [INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://arxiv.org/pdf/2412.04037) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.04037)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://grisoon.github.io/INFP/)

* [SINGER: Vivid Audio-driven Singing Video Generation with Multi-scale Spectral Diffusion Model](https://arxiv.org/pdf/2412.03430) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03430)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yl4467.github.io/)

* [FLOAT: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait](https://arxiv.org/abs/2412.01064) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01064)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://deepbrainai-research.github.io/float/)

* [EmotiveTalk: Expressive Talking Head Generation through Audio Information Decoupling and Emotional Video Diffusion](https://arxiv.org/pdf/2411.16726) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.16726)

* [LetsTalk: Latent Diffusion Transformer for Talking Video Synthesis](https://arxiv.org/pdf/2411.16748) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.16748)

* [Loopy: Taming Audio-Driven Portrait Avatar with Long-Term Motion Dependency](https://arxiv.org/pdf/2409.02634) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.02634)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://loopyavatar.github.io/)

* [PersonaTalk: Bring Attention to Your Persona in Visual Dubbing](https://arxiv.org/pdf/2409.05379) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.05379)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://grisoon.github.io/PersonaTalk/)

* [Talking With Hands 16.2M: A Large-Scale Dataset of Synchronized Body-Finger Motion and Audio for Conversational Motion Analysis and Synthesis](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lee_Talking_With_Hands_16.2M_A_Large-Scale_Dataset_of_Synchronized_Body-Finger_ICCV_2019_paper.pdf) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lee_Talking_With_Hands_16.2M_A_Large-Scale_Dataset_of_Synchronized_Body-Finger_ICCV_2019_paper.pdf)

* [GestureDiffuCLIP: Gesture Diffusion Model with CLIP Latents](https://arxiv.org/abs/2303.14613) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14613)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-mocca.github.io/GestureDiffuCLIP-Page/)

* [From Audio to Photoreal Embodiment: Synthesizing Humans in Conversations](https://evonneng.github.io/projects/audio2photoreal/static/CCA.pdf) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://evonneng.github.io/projects/audio2photoreal/static/CCA.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://evonneng.github.io/projects/audio2photoreal/index.html)

* [Takin-ADA: Emotion Controllable Audio-Driven Animation with Canonical and Landmark Loss Optimization](https://arxiv.org/pdf/2410.14283) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.14283)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://everest-ai.github.io/takinada/)

* [Listen, Denoise, Action! Audio-Driven Motion Synthesis With Diffusion Models](https://arxiv.org/abs/2211.09707) (Nov. 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09707)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.speech.kth.se/research/listen-denoise-action/)

* [TANGO: Co-Speech Gesture Video Reenactment with Hierarchical Audio Motion Embedding and Diffusion Interpolation](https://arxiv.org/pdf/2410.04221) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.04221)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pantomatrix.github.io/TANGO/)

### Reinforcement Learning for Video Generation

* [VIDEOSCORE: Building Automatic Metrics to Simulate Fine-grained Human Feedback for Video Generation](https://arxiv.org/pdf/2406.15252) (July, 2024)\
  [![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/VideoScore.svg?style=social\&label=Star)](https://github.com/TIGER-AI-Lab/VideoScore/) ⭐ 125 | 🐛 3 | 🌐 Python | 📅 2025-12-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15252)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tiger-ai-lab.github.io/VideoScore/)

* [Scaling Image and Video Generation via Test-Time Evolutionary Search](https://arxiv.org/abs/2505.17618) (Jun., 2025)\
  [![Star](https://img.shields.io/github/stars/tinnerhrhe/EvoSearch-codes.svg?style=social\&label=Star)](https://github.com/tinnerhrhe/EvoSearch-codes) ⭐ 108 | 🐛 2 | 🌐 Python | 📅 2025-10-03
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.17618)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://codegoat24.github.io/LiFT/)

* [LiFT: Leveraging Human Feedback for Text-to-Video Model Alignment](https://arxiv.org/pdf/2412.04814) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/CodeGoat24/LiFT.svg?style=social\&label=Star)](https://github.com/CodeGoat24/LiFT) ⭐ 85 | 🐛 2 | 🌐 Python | 📅 2025-05-04
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.04814)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://codegoat24.github.io/LiFT/)

* [VideoScore2: Think before You Score in Generative Video Evaluation](https://arxiv.org/abs/2509.22799) (Sep., 2025)
  [![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/VideoScore2.svg?style=social\&label=Star)](https://github.com/TIGER-AI-Lab/VideoScore2/) ⭐ 54 | 🐛 6 | 🌐 Python | 📅 2025-12-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.22799)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tiger-ai-lab.github.io/VideoScore2/)

* [DenseDPO: Fine-Grained Temporal Preference Optimization for Video Diffusion Models](https://arxiv.org/abs/2506.03517) (Jun., 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.03517)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/DenseDPO/)

* [Improving Dynamic Object Interactions in Text-to-Video Generation with AI Feedback](https://arxiv.org/abs/2412.02617) (Nov., 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02617)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/aif-dynamic-t2v/)

### Policy Learning

* [Any-point Trajectory Modeling for Policy Learning](https://arxiv.org/abs/2401.00025) (July, 2024)\
  [![Star](https://img.shields.io/github/stars/Large-Trajectory-Model/ATM.svg?style=social\&label=Star)](https://github.com/Large-Trajectory-Model/ATM) ⭐ 279 | 🐛 15 | 🌐 Python | 📅 2025-06-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00025)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xingyu-lin.github.io/atm/)

* [EgoVid-5M: A Large-Scale Video-Action Dataset for Egocentric Video Generation](https://arxiv.org/pdf/2411.08380) (Nov, 2024)\
  [![Star](https://img.shields.io/github/stars/JeffWang987/EgoVid.svg?style=social\&label=Star)](https://github.com/JeffWang987/EgoVid) ⭐ 144 | 🐛 3 | 🌐 Python | 📅 2025-07-31
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08380)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://egovid.github.io/)

* [Stag-1: Towards Realistic 4D Driving Simulation with Video Generation Model](https://arxiv.org/abs/2412.05280) (Dec, 2024)\
  [![Star](https://img.shields.io/github/stars/wzzheng/Stag.svg?style=social\&label=Star)](https://github.com/wzzheng/Stag) ⭐ 96 | 🐛 5 | 🌐 Python | 📅 2024-12-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05280)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wzzheng.net/Stag/)

* [GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy](https://arxiv.org/abs/2408.14368) (July, 2024)\
  [![Star](https://img.shields.io/github/stars/bytedance/GR-MG.svg?style=social\&label=Star)](https://github.com/bytedance/GR-MG) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2025-01-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14368)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gr-mg.github.io/)

* [Dreamitate: Real-World Visuomotor Policy Learning via Video Generation](https://arxiv.org/abs/2406.16862) (Jun, 2024)\
  [![Star](https://img.shields.io/github/stars/cvlab-columbia/dreamitate.svg?style=social\&label=Star)](https://github.com/cvlab-columbia/dreamitate) ⭐ 59 | 🐛 1 | 🌐 Python | 📅 2025-06-07
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16862)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamitate.cs.columbia.edu/)

* [This\&That: Language-Gesture Controlled Video Generation for Robot Planning](https://arxiv.org/abs/2407.05530) (Jun, 2024)\
  [![Star](https://img.shields.io/github/stars/Kiteretsu77/This_and_That_VDM.svg?style=social\&label=Star)](https://github.com/Kiteretsu77/This_and_That_VDM) ⭐ 49 | 🐛 3 | 🌐 Python | 📅 2025-12-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.05530)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cfeng16.github.io/this-and-that/)

* [Object-Centric Image to Video Generation with Language Guidance](https://arxiv.org/abs/2502.11655) (Feb, 2025)\
  [![Star](https://img.shields.io/github/stars/angelvillar96/TextOCVP.svg?style=social\&label=Star)](https://github.com/angelvillar96/TextOCVP) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-01-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11655)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://play-slot.github.io/TextOCVP/)

* [Video Prediction Policy: A Generalist Robot Policy with Predictive Visual Representations](https://arxiv.org/abs/2412.14803) (Dec, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14803)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-prediction-policy.github.io/)

* [Motion Tracks: A Unified Representation for Human-Robot Transfer in Few-Shot Imitation Learning](https://portal-cornell.github.io/motion_track_policy/) (Dec, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://portal-cornell.github.io/motion_track_policy/)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://portal-cornell.github.io/motion_track_policy/)

* [RT-Sketch: Goal-Conditioned Imitation Learning from Hand-Drawn Sketches](https://arxiv.org/abs/2403.02709) (Dec, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.02709)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rt-sketch.github.io/)

### Virtual Try-On

* [1-2-1: Renaissance of Single-Network Paradigm for Virtual Try-On](https://arxiv.org/abs/2501.05369) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/ningshuliang/1-2-1-MNVTON.svg?style=social\&label=Star)](https://github.com/ningshuliang/1-2-1-MNVTON) ⭐ 81 | 🐛 3 | 📅 2025-02-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.05369)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ningshuliang.github.io/2023/Arxiv/index.html)

* [Dynamic Try-On: Taming Video Virtual Try-on with Dynamic Attention Mechanism](https://arxiv.org/abs/2412.09822) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09822)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhengjun-ai.github.io/dynamic-tryon-page/)

* [Fashion-VDM: Video Diffusion Model for Virtual Try-On](https://arxiv.org/abs/2411.00225) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00225)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://johannakarras.github.io/Fashion-VDM/)

### 3D

* [SV4D: Dynamic 3D Content Generation with Multi-Frame and Multi-View Consistency](https://arxiv.org/abs/2407.17470) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social\&label=Star)](https://github.com/Stability-AI/generative-models) ⭐ 27,279 | 🐛 339 | 🌐 Python | 📅 2025-12-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.13764)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sv4d.github.io/)

* [MonST3R: A Simple Approach for Estimating Geometry in the Presence of Motion](https://arxiv.org/abs/2410.03825) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.03825)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://monst3r-project.github.io/)
  [![Star](https://img.shields.io/github/stars/Junyi42/monst3r.svg?style=social\&label=Star)](https://github.com/Junyi42/monst3r) ⭐ 1,388 | 🐛 30 | 🌐 Python | 📅 2025-06-16

* [Shape of Motion: 4D Reconstruction from a Single Video](https://arxiv.org/abs/2407.13764) (Jul., 2024)\
  [![Star](https://img.shields.io/github/stars/vye16/shape-of-motion.svg?style=social\&label=Star)](https://github.com/vye16/shape-of-motion/) ⭐ 1,302 | 🐛 58 | 🌐 Python | 📅 2025-08-02
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.13764)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shape-of-motion.github.io/)

* [Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models](https://arxiv.org/abs/2303.11989) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/lukashoel/text2room.svg?style=social\&label=Star)](https://github.com/lukasHoel/text2room) ⭐ 1,089 | 🐛 1 | 🌐 Python | 📅 2023-11-15
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11989)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lukashoel.github.io/text-to-room/)

* [Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions](https://arxiv.org/abs/2303.12789) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/ayaanzhaque/instruct-nerf2nerf.svg?style=social\&label=Star)](https://github.com/ayaanzhaque/instruct-nerf2nerf) ⭐ 853 | 🐛 11 | 🌐 Python | 📅 2024-02-12
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12789)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://instruct-nerf2nerf.github.io/)

* [WonderJourney: Going from Anywhere to Everywhere](https://arxiv.org/pdf/2312.03884) (CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/KovenYu/WonderJourney.svg?style=social\&label=Star)](https://github.com/KovenYu/WonderJourney) ⭐ 769 | 🐛 6 | 🌐 Python | 📅 2024-09-20
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.03884)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kovenyu.com/wonderjourney/)

* [ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model](https://arxiv.org/abs/2408.16767) (Aug., 2024)\
  [![Star](https://img.shields.io/github/stars/liuff19/ReconX.svg?style=social\&label=Star)](https://github.com/liuff19/ReconX) ⭐ 709 | 🐛 4 | 📅 2024-11-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.16767)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://liuff19.github.io/ReconX/)

* [Single-Stage Diffusion NeRF: A Unified Approach to 3D Generation and Reconstruction](https://arxiv.org/abs/2304.06714) (Apr., 2023)\
  [![Star](https://img.shields.io/github/stars/Lakonik/SSDNeRF.svg?style=social\&label=Star)](https://github.com/Lakonik/SSDNeRF) ⭐ 446 | 🐛 21 | 🌐 Python | 📅 2024-04-20
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06714)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lakonik.github.io/ssdnerf/)

* [ViewDiff: 3D-Consistent Image Generation with Text-to-Image Models](https://arxiv.org/abs/2403.01807) (CVPR, 2024)\
  [![Star](https://img.shields.io/github/stars/facebookresearch/ViewDiff.svg?style=social\&label=Star)](https://github.com/facebookresearch/ViewDiff) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01807)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lukashoel.github.io/ViewDiff/)

* [Director3D: Real-world Camera Trajectory and 3D Scene Generation from Text](https://arxiv.org/pdf/2406.17601) (June, 2024)\
  [![Star](https://img.shields.io/github/stars/imlixinyang/director3d.svg?style=social\&label=Star)](https://github.com/imlixinyang/director3d) ⭐ 382 | 🐛 7 | 🌐 Python | 📅 2025-03-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.17601)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://imlixinyang.github.io/director3d-page/)

* [Hi3D: Pursuing High-Resolution Image-to-3D Generation with Video Diffusion Models](https://arxiv.org/pdf/2409.07452) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/liuff19/ReconX.svg?style=social\&label=Star)](https://github.com/yanghb22-fdu/Hi3D-Official) ⭐ 320 | 🐛 16 | 🌐 Python | 📅 2024-09-13
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.07452)

* [DiffusioNeRF: Regularizing Neural Radiance Fields with Denoising Diffusion Models](https://arxiv.org/abs/2302.12231) (Feb., 2023)\
  [![Star](https://img.shields.io/github/stars/nianticlabs/diffusionerf.svg?style=social\&label=Star)](https://github.com/nianticlabs/diffusionerf) ⭐ 304 | 🐛 11 | 🌐 Python | 📅 2023-11-23
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.12231)

* [GPT-4V(ision) is a Human-Aligned Evaluator for Text-to-3D Generation](https://arxiv.org/abs/2401.04092) (Jan., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04092)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gpteval3d.github.io/)
  [![Star](https://img.shields.io/github/stars/3DTopia/GPTEval3D.svg?style=social\&label=Star)](https://github.com/3DTopia/GPTEval3D) ⭐ 289 | 🐛 5 | 🌐 Python | 📅 2024-06-12

* [YouDream: Generating Anatomically Controllable Consistent Text-to-3D Animals](https://arxiv.org/abs/2406.16273v1) (June, 2024)\
  [![Star](https://img.shields.io/github/stars/YouDream3D/YouDream.svg?style=social\&label=Star)](https://github.com/YouDream3D/YouDream/) ⭐ 40 | 🐛 0 | 🌐 Python | 📅 2025-02-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16273v1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://youdream3d.github.io/)

* [Vivid-ZOO: Multi-View Video Generation with Diffusion Model](https://arxiv.org/pdf/2406.08659v1) (Jun, 2024)\
  [![Star](https://img.shields.io/github/stars/Lakonik/SSDNeRF.svg?style=social\&label=Star)](https://github.com/hi-zhengcheng/vividzoo) ⭐ 39 | 🐛 0 | 📅 2024-10-19
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.08659v1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hi-zhengcheng.github.io/vividzoo/)

* [ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model](https://arxiv.org/abs/2410.07155) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/YangLing0818/Trans4D.svg?style=social\&label=Star)](https://github.com/YangLing0818/Trans4D) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-10-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07155)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/YangLing0818/Trans4D) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-10-10

* [Monocular Normal Estimation via Shading Sequence Estimation](https://arxiv.org/abs/2602.09929) (Feb., 2026)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.09929)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xinhua694.github.io/RoSE.github.io/)

* [WorldExplorer: Towards Generating Fully Navigable 3D Scenes](https://arxiv.org/abs/2506.01799) (Jun., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.01799)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://the-world-explorer.github.io/)

* [Voyager: Long-Range and World-Consistent Video Diffusion for Explorable 3D Scene Generation](https://arxiv.org/abs/2506.04225) (Jun., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.04225)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://voyager-world.github.io/)
  [![Star](https://img.shields.io/github/stars/3DTopia/GPTEval3D.svg?style=social\&label=Star)](https://github.com/Voyager-World/Voyager)

* [Difix3D+: Improving 3D Reconstructions with Single-Step Diffusion Models](https://arxiv.org/abs/2503.01774) (Mar., 2025 | CVPR 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.01774)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/difix3d/)

* [Wonderland: Navigating 3D Scenes from a Single Image](https://arxiv.org/abs/2412.12091) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.12091)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/wonderland/)

* [L3DG: Latent 3D Gaussian Diffusion](https://arxiv.org/abs/2112.03288) (Oct., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.03288)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://barbararoessle.github.io/l3dg/)

* [WonderWorld: Interactive 3D Scene Generation from a Single Image](https://arxiv.org/abs/2406.09394) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.09394)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wonderworld-2024.github.io/)

* [MultiDiff: Consistent Novel View Synthesis from a Single Image](https://sirwyver.github.io/MultiDiff/static/assets/MultiDiff.pdf) (CVPR, 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://sirwyver.github.io/MultiDiff/static/assets/MultiDiff.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sirwyver.github.io/MultiDiff/)

* [Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields](https://arxiv.org/abs/2305.11588) (May, 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11588)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://eckertzhang.github.io/Text2NeRF.github.io/)

* [RoomDreamer: Text-Driven 3D Indoor Scene Synthesis with Coherent Geometry and Texture](https://arxiv.org/abs/2305.11337) (May, 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11337)

* [NeuralField-LDM: Scene Generation with Hierarchical Latent Diffusion Models](https://arxiv.org/abs/2304.09787) (CVPR 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.09787)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/NFLDM/)

* [NerfDiff: Single-image View Synthesis with NeRF-guided Distillation from 3D-aware Diffusion](https://arxiv.org/abs/2302.10109) (Feb., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.10109)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jiataogu.me/nerfdiff/)

* [DiffRF: Rendering-guided 3D Radiance Field Diffusion](https://arxiv.org/abs/2212.01206) (CVPR 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sirwyver.github.io/DiffRF/)

### 4D

* [DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion](https://arxiv.org/pdf/2411.04928) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social\&label=Star)](https://github.com/wenqsun/DimensionX) ⭐ 1,333 | 🐛 27 | 🌐 Python | 📅 2025-10-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04928)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chenshuo20.github.io/DimensionX/)

* [Diffuman4D: 4D Consistent Human View Synthesis from Sparse-View Videos with Spatio-Temporal Diffusion Models](https://arxiv.org/abs/2507.13344) (July, 2025)
  [![Star](https://img.shields.io/github/stars/zju3dv/Diffuman4D.svg?style=social\&label=Star)](https://github.com/zju3dv/Diffuman4D) ⭐ 632 | 🐛 6 | 🌐 Python | 📅 2026-04-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.13344)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffuman4d.github.io/)

* [Diffuman4D: 4D Consistent Human View Synthesis from Sparse-View Videos with Spatio-Temporal Diffusion Models](https://arxiv.org/abs/2507.13344) (July, 2025)
  [![Star](https://img.shields.io/github/stars/zju3dv/Diffuman4D.svg?style=social\&label=Star)](https://github.com/zju3dv/Diffuman4D) ⭐ 632 | 🐛 6 | 🌐 Python | 📅 2026-04-10
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.13344)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffuman4d.github.io/)

* [AvatarArtist: Open-Domain 4D Avatarization](https://arxiv.org/abs/2503.19906) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/ant-research/AvatarArtist.svg?style=social\&label=Star)](https://github.com/ant-research/AvatarArtist) ⭐ 280 | 🐛 2 | 🌐 Python | 📅 2025-06-14
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.19906)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kumapowerliu.github.io/AvatarArtist/)

* [Diff4Splat: Controllable 4D Scene Generation with Latent Dynamic Reconstruction Models](https://arxiv.org/abs/2511.00503) (November, 2025)
  [![Star](https://img.shields.io/github/stars/paulpanwang/Diff4Splat.svg?style=social\&label=Star)](https://github.com/paulpanwang/Diff4Splat) ⭐ 121 | 🐛 1 | 🌐 Python | 📅 2026-04-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.00503)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://paulpanwang.github.io/Diff4Splat/)
  [![Video](https://img.shields.io/badge/Video-F00)](https://www.youtube.com/watch?v=IZKt-pvCLd0)

* [Not All Frame Features Are Equal: Video-to-4D Generation via Decoupling Dynamic-Static Features](https://arxiv.org/abs/2502.08377) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/paintscene4d/paintscene4d.github.io.svg?style=social\&label=Star)](https://github.com/paintscene4d/paintscene4d.github.io) ⭐ 25 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08377)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://paintscene4d.github.io/)

* [PaintScene4D: Consistent 4D Scene Generation from Text Prompts](https://arxiv.org/abs/2412.04471) (Dec., 2024)\
  [![Star](https://img.shields.io/github/stars/paintscene4d/paintscene4d.github.io.svg?style=social\&label=Star)](https://github.com/paintscene4d/paintscene4d.github.io) ⭐ 25 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04471)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://paintscene4d.github.io/)

* [In-2-4D: Inbetweening from Two Single-View Images to 4D Generation](https://arxiv.org/abs/2504.08366) (Apr, 2025)\
  [![Star](https://img.shields.io/github/stars/sauradip/In-2-4D.svg?style=social\&label=Star)](https://github.com/sauradip/In-2-4D) ⭐ 17 | 🐛 1 | 📅 2025-09-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]()
  [![Website](https://img.shields.io/badge/Website-9cf)](https://in-2-4d.github.io/)

* [Taming Video Diffusion Models for Panoramic 4D Scene Generation](https://arxiv.org/abs/2504.21650) (May, 2025)\
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/HoloTime.svg?style=social\&label=Star)](https://zhouhyocean.github.io/holotime/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.21650)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhouhyocean.github.io/holotime/)

* [Vivid4D: Improving 4D Reconstruction from Monocular Video by Video Inpainting](https://arxiv.org/abs/2504.11092) (Apr., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.11092)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xdimlab.github.io/Vivid4D/)

* [DreamDrive: Generative 4D Scene Modeling from Street View Images](https://arxiv.org/pdf/2501.00601) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.00601)

* [Stereo4D Learning How Things Move in 3D from Internet Stereo Videos](https://arxiv.org/pdf/2412.09621) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09621)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stereo4d.github.io/)

* [4Real-Video: Learning Generalizable Photo-Realistic 4D Video Diffusion](https://arxiv.org/abs/2412.04462) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04462)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/4Real-Video/)

* [CAT4D: Create Anything in 4D with Multi-View Video Diffusion Models](https://arxiv.org/abs/2411.18613) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18613)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cat-4d.github.io/)

### Game Generation

* [Playable Game Generation](https://arxiv.org/pdf/2412.00887) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.00887)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://124.156.151.207)

### AI Safety

* [What Matters in Detecting AI-Generated Videos like Sora?](https://arxiv.org/abs/2406.19568) (Jun., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19568)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://justin-crchang.github.io/3DCNNDetection.github.io/)

### Rendering with Virtual Engine

* [UnrealZoo: Enriching Photo-realistic Virtual Worlds for Embodied AI](https://arxiv.org/abs/2412.20977) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/UnrealZoo/unrealzoo-gym.svg?style=social\&label=Star)](https://github.com/UnrealZoo/unrealzoo-gym) ⭐ 356 | 🐛 13 | 🌐 Python | 📅 2026-08-28
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.20977)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://unrealzoo.site/)

* [Infinigen Indoors: Photorealistic Indoor Scenes using Procedural Generation](https://arxiv.org/abs/2406.11824) (CVPR 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.11824)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://infinigen.org/)

* [Scene Co-pilot: Procedural Text to Video Generation with Human in the Loop](https://arxiv.org/abs/2411.18644) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18644)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://abolfazl-sh.github.io/Scene_co-pilot_site/)

### Open-World Model

* [Oasis: A Universe in a Transformer](https://www.decart.ai/articles/oasis-interactive-ai-video-game-model) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/etched-ai/open-oasis.svg?style=social\&label=Star)](https://github.com/etched-ai/open-oasis) ⭐ 2,125 | 🐛 34 | 🌐 Python | 📅 2024-11-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.decart.ai/articles/oasis-interactive-ai-video-game-model)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.decart.ai/articles/oasis-interactive-ai-video-game-model)

* [VideoWorld: Exploring Knowledge Learning from Unlabeled Videos](https://arxiv.org/abs/2501.09781) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/bytedance/VideoWorld.svg?style=social\&label=Star)](https://github.com/bytedance/VideoWorld) ⭐ 799 | 🐛 13 | 🌐 Python | 📅 2026-02-25
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.09781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maverickren.github.io/VideoWorld.github.io/)

* [3D-VLA: A 3D Vision-Language-Action Generative World Model](https://arxiv.org/abs/2403.09631) (ICML 2024)\
  [![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-VLA.svg?style=social\&label=Star)](https://github.com/UMass-Foundation-Model/3D-VLA) ⭐ 631 | 🐛 13 | 🌐 Python | 📅 2024-10-29
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.09631)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vis-www.cs.umass.edu/3dvla/)

* [Aether: Geometric-Aware Unified World Modeling](https://arxiv.org/pdf/2503.18945) (Mar., 2025)\
  [![Star](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social\&label=Star)](https://github.com/OpenRobotLab/Aether) ⭐ 609 | 🐛 0 | 🌐 Python | 📅 2025-10-26
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.18945)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aether-world.github.io/#team)

* [AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents](https://arxiv.org/abs/2407.18901) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/stonybrooknlp/appworld.svg?style=social\&label=Star)](https://github.com/stonybrooknlp/appworld/) ⭐ 500 | 🐛 19 | 🌐 Python | 📅 2026-02-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.18901)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://appworld.dev/)

* [GameFactory: Creating New Games with Generative Interactive Videos](https://arxiv.org/abs/2501.08325) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/KwaiVGI/GameFactory.svg?style=social\&label=Star)](https://github.com/KwaiVGI/GameFactory) ⭐ 497 | 🐛 6 | 🌐 Python | 📅 2025-03-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08325)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vvictoryuki.github.io/gamefactory/)

* [MineWorld: a Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/pdf/2504.08388) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/microsoft/MineWorld.svg?style=social\&label=Star)](https://github.com/microsoft/MineWorld) ⭐ 489 | 🐛 9 | 🌐 Python | 📅 2026-05-08
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.08388)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/microsoft/MineWorld) ⭐ 489 | 🐛 9 | 🌐 Python | 📅 2026-05-08

* [WORLDMEM: Long-term Consistent World Simulation with Memory](https://arxiv.org/pdf/2504.12369) (Apr., 2025)\
  [![Star](https://img.shields.io/github/stars/xizaoqu/WorldMem.svg?style=social\&label=Star)](https://github.com/xizaoqu/WorldMem) ⭐ 389 | 🐛 5 | 🌐 Python | 📅 2026-02-21
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.12369)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xizaoqu.github.io/worldmem/)

* [Inference-time Physics Alignment of Video Generative Models with Latent World Models](https://arxiv.org/abs/2601.10553) (Jan., 2026)\
  [![Star](https://img.shields.io/github/stars/facebookresearch/WMReward.svg?style=social\&label=Star)](https://github.com/facebookresearch/WMReward) ⭐ 94 | 🐛 1 | 🌐 Python | 📅 2026-07-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.10553)

* [Digital Life Project: Autonomous 3D Characters with Social Intelligence](https://arxiv.org/abs/2312.04547) (CVPR 2024)\
  [![Star](https://img.shields.io/github/stars/caizhongang/Digital_Life_Project.svg?style=social\&label=Star)](https://github.com/caizhongang/Digital_Life_Project) ⭐ 45 | 🐛 0 | 📅 2024-09-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04547)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://digital-life-project.com/)

* [Vid2World: Crafting Video Diffusion Models to Interactive World Models](https://arxiv.org/abs/2505.14357) (May., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14357)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://knightnemo.github.io/vid2world/)

* [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07825)

* [Vid2Sim: Realistic and Interactive Simulation from Video for Urban Navigation](https://arxiv.org/abs/2501.06693) (Jan., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06693)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://metadriverse.github.io/vid2sim/)

* [GenEx: Generating an Explorable World](https://arxiv.org/abs/2412.09624) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09624)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://genex.world/)

* [The Matrix: Infinite-Horizon World Generation with Real-Time Moving Control](https://arxiv.org/pdf/2412.03568) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03568)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://thematrix1999.github.io/)

* [Navigation World Models](https://arxiv.org/abs/2412.03572) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03572)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.amirbar.net/nwm/)

* [Genie 2: A large-scale foundation world model](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) (Dec., 2024)\
  [![Website](https://img.shields.io/badge/Website-9cf)](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/)

* [Understanding World or Predicting Future? A Comprehensive Survey of World Models](https://arxiv.org/abs/2411.14499) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.14499)

### Video Understanding

* [A Generalist Framework for Panoptic Segmentation of Images and Videos](https://arxiv.org/abs/2210.06366) (Oct., 2022)\
  [![Star](https://img.shields.io/github/stars/google-research/pix2seq.svg?style=social\&label=Star)](https://github.com/google-research/pix2seq) ⚠️ Archived
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.06366)

* [DiffusionRet: Generative Text-Video Retrieval with Diffusion Model](https://arxiv.org/abs/2303.09867) (ICCV 2023)\
  [![Star](https://img.shields.io/github/stars/jpthu17/DiffusionRet.svg?style=social\&label=Star)](https://github.com/jpthu17/DiffusionRet) ⭐ 142 | 🐛 2 | 🌐 Python | 📅 2024-04-09
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09867)

* [VLM-Grounder: A VLM Agent for Zero-Shot 3D Visual Grounding](https://arxiv.org/pdf/2410.13860) (Oct., 2024)\
  [![Star](https://img.shields.io/github/stars/OpenRobotLab/VLM-Grounder.svg?style=social\&label=Star)](https://github.com/OpenRobotLab/VLM-Grounder) ⭐ 133 | 🐛 3 | 🌐 Python | 📅 2025-05-22
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13860)

* [Divot: Diffusion Powers Video Tokenizer for Comprehension and Generation](https://arxiv.org/abs/2412.04432) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/TencentARC/Divot.svg?style=social\&label=Star)](https://github.com/TencentARC/Divot) ⭐ 87 | 🐛 3 | 🌐 Python | 📅 2025-02-27
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04432)

* [Diffusion Action Segmentation](https://arxiv.org/abs/2303.17959) (ICCV 2023)\
  [![Star](https://img.shields.io/github/stars/Finspire13/DiffAct.svg?style=social\&label=Star)](https://github.com/Finspire13/DiffAct) ⭐ 81 | 🐛 3 | 🌐 Python | 📅 2023-08-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17959)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://daochang.site/DiffAct-Project-Page/)

* [DiffTAD: Temporal Action Detection with Proposal Denoising Diffusion](https://arxiv.org/abs/2303.14863) (Mar., 2023)\
  [![Star](https://img.shields.io/github/stars/sauradip/DiffusionTAD.svg?style=social\&label=Star)](https://github.com/sauradip/DiffusionTAD) ⭐ 37 | 🐛 3 | 📅 2023-03-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14863)

* [PDPP:Projected Diffusion for Procedure Planning in Instructional Videos](https://arxiv.org/abs/2303.14676) (CVPR 2023)\
  [![Star](https://img.shields.io/github/stars/MCG-NJU/PDPP.svg?style=social\&label=Star)](https://github.com/MCG-NJU/PDPP) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2023-08-30
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14676)

* [Refined Semantic Enhancement Towards Frequency Diffusion for Video Captioning](https://arxiv.org/abs/2211.15076) (Nov., 2022)\
  [![Star](https://img.shields.io/github/stars/lzp870/RSFD.svg?style=social\&label=Star)](https://github.com/lzp870/RSFD) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2023-08-06
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.15076)

* [UniReal: Universal Image Generation and Editing via Learning Real-world Dynamics](https://arxiv.org/pdf/2412.07774) (Dec., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07774)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xavierchen34.github.io/UniReal-Page/)

* [Exploring Diffusion Models for Unsupervised Video Anomaly Detection](https://arxiv.org/abs/2304.05841) (Apr., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.05841)

### Healthcare and Biology

* [Artificial Intelligence for Biomedical Video Generation](https://arxiv.org/pdf/2411.07619) (Nov., 2024)\
  [![Star](https://img.shields.io/github/stars/Finspire13/DiffAct.svg?style=social\&label=Star)](https://github.com/Finspire13/DiffAct) ⭐ 81 | 🐛 3 | 🌐 Python | 📅 2023-08-16
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.07619)

* [FEAT: Full-Dimensional Efficient Attention Transformer for Medical Video Generation](https://arxiv.org/abs/2506.04956) (Jun., 2025)\
  [![Star](https://img.shields.io/github/stars/Yaziwel/FEAT.svg?style=social\&label=Star)](https://github.com/Yaziwel/FEAT) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2025-09-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.11943)

* [Medical Video Generation for Disease Progression Simulation](https://arxiv.org/abs/2411.11943) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.11943)

* [Exploring Variational Autoencoders for Medical Image Generation: A Comprehensive Study](https://arxiv.org/abs/2411.07348) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.07348)

* [MedSora: Optical Flow Representation Alignment Mamba Diffusion Model for Medical Video Generation](https://arxiv.org/abs/2411.01647) (Nov., 2024)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.01647)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wongzbb.github.io/MedSora/)

* [Annealed Score-Based Diffusion Model for Mr Motion Artifact Reduction](https://arxiv.org/abs/2301.03027) (Jan., 2023)\
  [![arxiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.03027)

* [Feature-Conditioned Cascaded Video Diffusion Models for Precise Echocardiogram Synthesis](https://arxiv.org/abs/2303.12644) (Mar., 2023)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12644)

* [Neural Cell Video Synthesis via Optical-Flow Diffusion](https://arxiv.org/abs/2212.03250) (Dec., 2022)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.03250)

### Other Applications

* [History-Guided Video Diffusion](https://arxiv.org/abs/2502.06764) (Feb., 2025)\
  [![Star](https://img.shields.io/github/stars/kwsong0113/diffusion-forcing-transformer.svg?style=social\&label=Star)](https://github.com/kwsong0113/diffusion-forcing-transformer) ⭐ 709 | 🐛 9 | 🌐 Python | 📅 2025-07-01
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06764)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boyuan.space/history-guidance/)

* [VanGogh: A Unified Multimodal Diffusion-based Framework for Video Colorization](https://arxiv.org/pdf/2501.09499) (Jan., 2025)\
  [![Star](https://img.shields.io/github/stars/BecauseImBatman0/VanGogh.svg?style=social\&label=Star)](https://github.com/BecauseImBatman0/VanGogh) ⭐ 20 | 🐛 1 | 📅 2025-01-17
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.09499)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://becauseimbatman0.github.io/VanGogh)

* [VidSketch: Hand-drawn Sketch-Driven Video Generation with Diffusion Control](https://arxiv.org/pdf/2502.01101) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01101)

* [PhysAnimator: Physics-Guided Generative Cartoon Animation](https://arxiv.org/pdf/2501.16550) (Feb., 2025)\
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.16550)

### Code-rendered Video Generation

* [Paper2Video: Automatic Video Generation from Scientific Papers](https://arxiv.org/abs/2503.14378) (Oct., 2025)\
  [![Star](https://img.shields.io/github/stars/showlab/Paper2Video.svg?style=social\&label=Star)](https://github.com/showlab/Paper2Video) ⭐ 2,372 | 🐛 4 | 🌐 Python | 📅 2026-03-05
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.05096)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Paper2Video/)

* [Code2Video: A Code-centric Paradigm for Educational Video Generation](https://showlab.github.io/Code2Video/) (Oct., 2025)\
  [![Star](https://img.shields.io/github/stars/showlab/Code2Video.svg?style=social\&label=Star)](https://github.com/showlab/Code2Video) ⭐ 2,013 | 🐛 2 | 🌐 Python | 📅 2026-08-24
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21755)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Code2Video/)

- [AgentMarket](https://agentmarket.cloud) - B2A marketplace for AI agents. 189 APIs, 28M+ data.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-02._
