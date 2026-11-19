# Awesome-AI-Animation-Video-Generation

# Top AI Animation & Video Generation Ecosystem

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

- **[Runway (Gen-3 Alpha / Gen-4)](https://runwayml.com)**  
  Industry-leading generative video and AI filmmaking suite offering text/image-to-video, Motion Brush camera/subject controls, Act-One performance capture, and VFX tools.

- **[Luma Dream Machine](https://lumalabs.ai)**  
  High-speed cloud AI video generation platform producing physically coherent, high-dynamic-range animations with keyframe interpolation and camera motion presets.

- **[Pika Labs (Pika Art)](https://pika.art)**  
  Creative AI video and animation platform featuring Pikaffects, Modify Region inpainting, lip-syncing, sound effects, and stylized video generation.

- **[Kling AI](https://klingai.com)**  
  High-resolution generative video platform supporting long-form 1080p motion synthesis, multi-element consistency, motion brush controls, and character lip-sync.

- **[Viggle AI](https://viggle.ai)**  
  Controllable AI character animation platform powered by JST-1 video-3D foundation models that make any static character image dance, move, or act from reference videos.

- **[DomoAI](https://domoai.app)**  
  Cloud AI video-to-video and animation restyling platform specialized in converting live-action footage into anime, comic, 3D cartoon, and stylized motion graphics.

- **[Kaiber](https://kaiber.ai)**  
  Audio-reactive AI animation and music-video generation studio offering frame-by-frame style transformations, camera choreography, and Superstudio canvas workflows.

- **[Haiper](https://haiper.ai)**  
  Perceptual foundation-model video creation platform providing text-to-video, image-to-video, video repainting, and controllable motion templates.

- **[Leonardo.Ai (Motion)](https://leonardo.ai)**  
  Cloud generative art and animation suite enabling creators to animate generated concept art and illustrations with adjustable motion strength and camera movement.

- **[OpenAI Sora / Google Veo / Hailuo MiniMax](https://sora.com)**  
  Frontier cloud video generation models capable of synthesizing multi-shot coherent narratives, complex physics, and cinematic camera movements from multimodal prompts.


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
