# Awesome-AI-Animation-Video-Generation

## Top AI Animation & Video Generation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Text/Image-to-Video Diffusion, AI Storyboarding & Video Directing, Character Motion Transfer & Local ComfyUI Video Pipelines*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Animation & Video Generation**. These tools synthesize fluid video clips from text prompts or reference keyframes, direct multi-shot animated storyboards, transfer human motion onto characters, restyle live-action video into anime or 3D, and interpolate frames locally on consumer GPUs.



**Examples** include Runway Gen-3 / Gen-4, Luma Dream Machine, Pika Labs, Kling AI, Haiper, Kaiber, Viggle AI, Leonardo Motion, DomoAI, Stable Video Diffusion, and kaomei/stickman-video-director (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for open-weight video foundation models, AI video directing & storyboard automation, character pose transfer, ComfyUI video nodes, and optical-flow frame interpolation — ideal for AI filmmakers, animators, VFX artists, and researchers building transparent local video pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Size (Valuation / Revenue) | Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[OpenAI (Sora)](https://sora.com)** | Frontier generative video model producing complex cinematic scenes and high-fidelity motion. | $852B Valuation ($1.25T target; $3.7B+ Revenue) | $20/month (via ChatGPT Plus; Pro tier at $200/month) | Free tier discontinued; previously limited access (trial quota up to 30 watermarked clips/mo). Paid tiers provide metered priority credits. |
| **[Kling AI](https://klingai.com)** (Kuaishou) | High-resolution generative video platform supporting 1080p motion synthesis, camera controls, and lip-sync. | $18B Valuation ($240M ARR; parent Kuaishou ~$25B Market Cap) | $10/month (or $6.60/month billed annually for Standard Plan, 660 credits) | 66 credits daily (refreshes every 24 hours, non-accumulating; ~6 video generations/day, 720p with watermark, non-commercial). |
| **[Hailuo AI](https://hailuoai.video)** (MiniMax) | Cloud video foundation model platform generating hyper-realistic motion physics, camera moves, and cinematic quality. | $5.5B–$8B Market Cap / Valuation ($116.6M H1 2026 Revenue) | $14.99/month (or $8.40/month billed annually for Standard Plan, 1,000 credits) | 100–200 welcome credits on initial sign-up (valid for 3 days; ~2–4 videos, 768p with watermark); daily bonus drops (50 credits/day when active). |
| **[Runway (Gen-3 / Gen-4)](https://runwayml.com)** | Industry-leading generative video & VFX suite with Motion Brush, Act-One performance capture, and camera choreography. | $5.3B Valuation ($200M ARR) | $15/month ($12/month billed annually for Standard Plan, 625 credits/mo) | 125 credits one-time free exploration grant upon sign-up (does not renew monthly; watermarked 720p exports, 5 GB storage). |
| **[Luma Dream Machine](https://lumalabs.ai)** | High-speed cloud AI video platform producing physically coherent animations with keyframing and camera presets. | $4.0B Valuation ($50M+ Revenue) | $9.99/month (Lite Plan, ~3,200 credits/mo; Plus Plan at $30/mo for commercial rights) | 80 credits daily (resets every 24 hours, non-accumulating; personal non-commercial use only, draft/720p watermarked output). |
| **[Pika Labs (Pika Art)](https://pika.art)** | Creative AI video platform featuring Pikaffects, video expansion, regional inpainting, lip-syncing, and sound effects. | $470M–$700M Valuation ($135M raised) | $10/month ($8/month billed annually for Starter Plan, 600 credits/mo) | Free tier ($0/mo) includes interface access with 0 recurring monthly credits (video generation requires credit packs starting at $5 or paid subscription; watermark-free, non-commercial). |
| **[Viggle AI](https://viggle.ai)** | Controllable character animation platform powered by JST-1 video-3D foundation model for motion transfer and choreography. | $100M–$250M Est. Valuation ($26M raised) | $9.99/month ($7.99/month billed annually for Pro Plan, 80 credits/mo) | 5 credits/generations per day (resets daily, 1 generation at a time, 1-min upload cap, watermarked outputs, 7-day asset storage). |
| **[Leonardo.Ai (Motion)](https://leonardo.ai)** | Generative art and animation suite to animate illustrations and concept art with adjustable motion strength and camera tools. | $80M+ Acquisition Valuation (Acquired by Canva) | $12/month ($10/month billed annually for Essential Plan, 8,500 fast tokens/mo) | 150 fast tokens daily (resets every 24 hours, non-accumulating; public creations, standard generation queue). |
| **[Haiper](https://haiper.ai)** | Perceptual foundation-model video creation platform providing text-to-video, image-to-video, repainting, and motion templates. | $50M–$100M Est. Valuation ($19.2M raised, ~$2M ARR) | $9.99/month ($8/month billed annually for Explorer Plan, 500 credits/mo) | ~10 free video generations per day (refreshes daily at midnight UTC, non-accumulating, 720p resolution, watermarked, non-commercial). |
| **[Kaiber](https://kaiber.ai)** | Audio-reactive AI animation and music-video studio offering style transformations, choreography, and canvas workflows. | Undisclosed ($10M+ raised, ~$2.6M ARR) | $10/month ($8/month billed annually for Starter Plan, 500 credits/mo) | 5-day trial for $5 (includes 500 credits and full feature access, auto-renews to Creator plan at $29/mo unless cancelled; no perpetual free tier). |
| **[DomoAI](https://domoai.app)** | Cloud AI video-to-video restyling platform converting live-action footage into anime, comic, 3D cartoon, and stylized motion. | Private / Bootstrapped (Independent creator platform) | $9.99/month ($6.99/month billed annually for Basic Plan, 500 credits/mo) | 15 credits one-time free trial on sign-up (enough for 1 test style transfer/video generation; watermarked, non-commercial). |





## Open-Source GitHub Projects



- **[kaomei/stickman-video-director](https://github.com)**  

  Open-source AI video directing and stickman animation workflow tool designed for orchestrating character poses, scene pacing, and automated animated video storytelling.



- **[Wan2.1 / Wan2.2 (`Wan-Video/Wan2.1`)](https://github.com)**  

  Flagship open-source (`Apache-2.0`) video foundation model suite from Alibaba supporting text-to-video, image-to-video, video editing, and visual text generation on consumer and data-center GPUs.



- **[HunyuanVideo (`Tencent-Hunyuan/HunyuanVideo`)](https://github.com)**  

  Large-scale open-source video generation foundation model delivering cinema-grade motion coherence, realistic physics, and native ComfyUI / Diffusers integration.



- **[CogVideoX (`THUDM/CogVideo`)](https://github.com)**  

  Open-source (`Apache-2.0`) Diffusion Transformer video generation family from Tsinghua/Zhipu AI featuring 3D causal VAEs for smooth, temporally consistent text- and image-to-video synthesis.



- **[LTX-Video (`Lightricks/LTX-Video`)](https://github.com)**  

  Real-time open-source DiT-based video generation model capable of synthesizing high-resolution 30 fps animations faster than real time on local GPUs.



- **[Mochi 1 (`genmoai/mochi`)](https://github.com)**  

  Open-source (`Apache-2.0`) Asymmetric Diffusion Transformer (AsymmDiT) video generation model engineered for high-fidelity human motion and prompt adherence.



- **[Stable Video Diffusion (`Stability-AI/generative-models`)](https://github.com)**  

  Foundational open-source image-to-video latent diffusion model family (`SVD` / `SVD-XT`) turning still images into smooth multi-frame animated clips.



- **[FramePack (`lllyasviel/FramePack`)](https://github.com)**  

  Memory-efficient open-source (`Apache-2.0`) autoregressive next-frame-prediction video diffusion architecture enabling long-horizon 30 fps video generation on 6GB–12GB consumer GPUs.



- **[SkyReels-V2 (`SkyworkAI/SkyReels-V2`)](https://github.com)**  

  Open-source infinite-length film-grade video generation model combining diffusion forcing, reinforcement learning, and multi-shot cinematic directing capabilities.



- **[AnimateDiff (`guoyww/AnimateDiff`)](https://github.com)**  

  Iconic open-source (`Apache-2.0`) plug-and-play motion module framework that animates personalized Stable Diffusion / SDXL checkpoints with LoRA camera controls (`MotionLoRA`).



- **[MimicMotion (`Tencent/MimicMotion`)](https://github.com)**  

  Open-source high-resolution human motion transfer framework using confidence-aware pose guidance to animate any character image cleanly from driving videos.



- **[Moore-AnimateAnyone (`MooreThreads/Moore-AnimateAnyone`)](https://github.com)**  

  Popular open-source (`Apache-2.0`) pose-driven character animation pipeline transferring full-body dance and acting sequences onto reference character illustrations.



- **[LivePortrait (`KwaiVGI/LivePortrait`)](https://github.com)**  

  Fast, open-source (`MIT`) portrait and anime character animation engine featuring stitching and retargeting controls for expressive eyes, lips, and head motion.



- **[ToonCrafter (`ToonCrafter/ToonCrafter`)](https://github.com)**  

  SIGGRAPH Asia open-source generative cartoon interpolation framework that synthesizes fluid intermediate anime frames between two sparse keyframe drawings.



- **[Open-Sora (`hpcaitech/Open-Sora`)](https://github.com)**  

  Open-source (`Apache-2.0`) video generation ecosystem democratizing high-resolution spatial-temporal Diffusion Transformer training and inference.



- **[ComfyUI-AnimateDiff-Evolved (`Kosinkadink/ComfyUI-AnimateDiff-Evolved`)](https://github.com)**  

  Comprehensive open-source (`AGPL-3.0`) ComfyUI node suite enabling infinite-length context windows, prompt traveling, ControlNet/IPAdapter motion scheduling, and latent interpolation.



- **[ComfyUI-VideoHelperSuite (`Kosinkadink/ComfyUI-VideoHelperSuite`)](https://github.com)**  

  Essential open-source (`AGPL-3.0`) ComfyUI toolkit for loading, batching, frame-interpolating, audio-syncing, and encoding high-bitrate MP4/WebM/GIF animations.



### Additional Strong Open-Source Options



- **[RIFE (`megvii-research/ECCV2022-RIFE`)](https://github.com)** and **[FILM (`google-research/frame-interpolation`)](https://github.com)** for real-time optical-flow frame interpolation upscaling 16/24 fps AI videos to smooth 60 fps.

- **[MuseTalk (`TMElyralab/MuseTalk`)](https://github.com)** and **[Hallo2 (`fudan-generative-vision/hallo2`)](https://github.com)** for open-source audio-driven talking-head lip-sync and long-duration portrait animation.

- **[DWPose (`IDEA-Research/DWPose`)](https://github.com)** and **[SAM 2 (`facebookresearch/sam2`)](https://github.com)** for extracting skeletal stickman/pose sequences and rotoscoped object masks from reference videos.

- **[ComfyUI-WanVideoWrapper (`kijai/ComfyUI-WanVideoWrapper`)](https://github.com)** and **[ComfyUI-GGUF (`city96/ComfyUI-GGUF`)](https://github.com)** for running quantized FP8/GGUF open-weight video models smoothly on consumer GPUs.

- **[Remotion (`remotion-dev/remotion`)](https://github.com)** and **[Manim Community (`ManimCommunity/manim`)](https://github.com)** for programmatic code-driven video rendering and mathematical/explainer animations.
