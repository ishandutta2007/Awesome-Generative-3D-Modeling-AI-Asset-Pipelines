# Awesome-Generative-3D-Modeling-AI-Asset-Pipelines

<p align="center">

  <img src="./assets/banner.svg" alt="Top Generative 3D Modeling & AI Asset Pipelines" width="100%" />

</p>



<p align="center">

  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>

  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>

  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>

</p>



# 🎨 Top Generative 3D Modeling & AI Asset Pipelines



**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  

*Focused on Text/Image-to-3D Mesh Foundation Models, AI PBR Texture Synthesis, Automated Quad Retopology, Neural Auto-Rigging & End-to-End 3D Asset Pipelines*  

**Last updated: November 2026**



This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Generative 3D Modeling & AI Asset Pipelines**. These tools power production-ready text-to-3D and single-image-to-3D asset synthesis (`TRELLIS`, `Hunyuan3D-2`, `TripoSR`, `InstantMesh`, `3d-new-era-ai`), automated 4K PBR material painting (`Paint3D`, `TEXTure`, `Material Maker`), quad retopology & UV unwrapping (`Instant Meshes`, `QuadriFlow`, `xatlas`), and automated skeletal rigging (`UniRig`, `RigNet`) for game studios, 3D technical artists, and XR creators.



**Examples** include Luma AI (Luma Genie), Meshy.ai, Tripo 3D (VAST AI), Spline AI, Rodin Gen-1 / Gen-2 (Deemos / Hyper3D), Kaedim, CSM 3D (Common Sense Machines), Masterpiece X, Sloyd.ai, and 3DFY.ai (the category leaders).



**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for open-weight 3D foundation models (`leandrodaf/3d-new-era-ai`, `Microsoft TRELLIS`, `Tencent Hunyuan3D-2`, `TripoSR`, `InstantMesh`, `Unique3D`, `CraftsMan3D`), node-based local 3D AI pipelines (`ComfyUI-3D-Pack`, `Blender`), PBR texture generators (`Paint3D`, `TEXTure`, `Material Maker`), and game-ready retopology/rigging utilities (`Instant Meshes`, `xatlas`, `UniRig`) — ideal for 3D studios building local, unlimited asset pipelines without credit-based SaaS fees.



🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)

- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)

- [💻 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#️-how-to-contribute)

- [⚠️ Disclaimer](#️-disclaimer)

- [💖 Support & Thank You](#-support--thank-you)



## 📊 Sector Overview & Market Dynamics

The global generative 3D modeling and AI asset creation market is valued at approximately **$4.8B–$6.5B in 2026**, growing at a ~28%–35% CAGR driven by AAA/indie game studios, spatial computing/XR headsets, VFX production, and automated 3D digital twins. The sector is currently **moderately fragmented**—top frontier model developers and multimodal labs compete across specialized niches (rapid prototyping, quad-topology game meshes, CAD/parametric props, and avatar rigging), while facing intense downward margin pressure from rapidly maturing open-weight foundation models and local inference pipelines.

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company valuation / scale.*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Luma AI (Luma Genie)](https://lumalabs.ai)** | Multimodal 3D capture and generative 3D asset pipeline converting text prompts, images, and videos into PBR-textured meshes and NeRF/3DGS scenes. | **~$300M–$500M+ Valuation** ($70M+ VC funding led by a16z) | **$9.99 / month** ($7.99/mo billed annually for Lite plan; $29.99/mo Plus plan with 10,000 credits/mo) | **Forever Free Plan** (Daily non-commercial test generation quota with watermarks; unlimited capture viewing) |
| **[Meshy.ai](https://meshy.ai)** | Flagship AI 3D modeling and PBR texturing suite generating game-ready, quad-retopologized, UV-unwrapped, and auto-rigged 3D assets from text or images. | **~$100M–$200M Est. Valuation** (~$15M–$25M+ est. ARR; >2M 3D creators) | **$16 / month** billed annually ($20/mo monthly for Pro plan with 1,000 credits/mo) | **Forever Free Plan** (**200 free generation credits/month**, max 10 tasks/day, CC-BY-4.0 non-commercial license) |
| **[Tripo 3D (VAST AI)](https://tripo3d.ai)** | Ultra-fast 3D foundation model SaaS and REST API generating clean quad-retopologized, rigged, and PBR-textured 3D models in seconds. | **~$100M+ Est. Valuation** ($30M+ VC funding; creators of open-source TripoSR) | **$15.90 / month** billed annually ($19.90/mo monthly for Professional plan with 3,000 credits/mo) | **Forever Free Basic Plan** (**300 free credits/month** (~10–30 generations/mo), standard queue, personal use license) |
| **[Spline AI](https://spline.design)** | Collaborative browser-based 3D design studio with native AI text-to-3D generation, AI style transfer, and direct React/Three.js/visionOS exports. | **~$50M–$100M Est. Valuation** ($15M+ VC funding led by Gradient & First Round) | **$12 / month** billed annually ($15/mo monthly for Starter; $20/mo monthly for Pro with AI generation) | **Forever Free Basic Plan** (**Unlimited personal 3D files**, interactive web embeds, 1 shared folder; Spline watermark on exports) |
| **[Rodin Gen-1 / Gen-2 (Deemos / Hyper3D)](https://hyper3d.ai)** | High-precision generative 3D asset platform producing part-aware geometry and studio-grade PBR textures from multi-view images and text prompts. | **~$50M–$100M Est. Valuation** (Venture-backed spatial AI foundation lab) | **$24 / month** billed annually ($30/mo monthly for Creator plan with ~60 model generations) | **Forever Free Plan** (Free medium-quality generation previews, 10 private asset storage slots, public gallery sharing) |
| **[Kaedim](https://kaedim3d.com)** | Hybrid AI + artist-in-the-loop 3D production pipeline converting 2D concept art into studio-grade, clean-topology, UV-unwrapped game assets. | **~$50M–$80M Est. Valuation** ($15M+ Series A led by a16z) | **$29 / month** for Indie tier ($150/mo for Starter with 10 production assets/mo) | **7-Day Paid Evaluation Trial** ($50 for 7 days testing trial, renews into monthly subscription unless canceled) |
| **[CSM 3D (Common Sense Machines)](https://csm.ai)** | Multimodal 3D asset and world generation platform turning images, sketches, and video clips into controllable, game-ready 3D meshes. | **~$40M–$70M Est. Valuation** ($15M+ VC funding led by a16z) | **$15 / month** billed annually ($20/mo monthly for Maker plan) | **Forever Free Explorer Plan** (Limited complimentary image-to-3D monthly generation credits and public gallery preview access) |
| **[Masterpiece X](https://masterpiecex.com)** | Browser-based text-to-3D generative studio engineered for game developers and XR creators, outputting textured, auto-rigged, and animated FBX/GLB models. | **~$15M–$30M Est. Valuation** (~$10M+ VC funding; Canadian spatial AI company) | **$10.99 / month** for Starter tier (750 credits/month; $19.99/mo for 1,500 credits) | **Forever Free Tier** (**250 free starter credits** upon registration to generate textured/rigged 3D models) |
| **[Sloyd.ai](https://sloyd.ai)** | Parametric + AI 3D asset generator and game-engine SDK creating customizable, clean-topology, UV-mapped props and buildings in real time. | **~$10M–$25M Est. Valuation** (Venture-backed Norwegian 3D tech startup) | **$15 / month** billed annually ($20/mo monthly for Plus plan with 50 advanced credits) | **Forever Free Guest Plan** (**1 free AI 3D generation per day**, unlimited real-time parametric editor tweaks, personal use license) |
| **[3DFY.ai](https://3dfy.ai)** | Automated prompt-to-3D and scalable catalog generation platform synthesizing clean, segmented, UV-mapped 3D models for games and e-commerce. | **~$10M–$20M Est. Valuation** (Venture-backed Israeli generative 3D company) | **$5.00 / download** (pay-as-you-go; subscription packs starting at $110/mo for 40 downloads & 400 generations) | **Free Evaluation Trial** (**10 free generation credits** upon sign-up to test prompt-to-3D previews) |



## 💻 Open-Source GitHub Projects



| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |

| :--- | :--- | :--- | :--- |

| **[3D New Era AI (`leandrodaf/3d-new-era-ai`)](https://github.com)** | **Open-Source** ($0 local/GPU generative 3D modeling & AI asset pipeline) | **100% Free forever** (Unlimited local AI 3D model synthesis, asset processing, and generative 3D workflows) | Open-source generative 3D modeling and AI asset pipeline project built to modernize local 3D creation and spatial asset workflows. |
