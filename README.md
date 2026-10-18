# Awesome Optical-to-SAR Translation

A curated bibliography accompanying the survey *Optical-to-SAR Translation in Remote Sensing: A Systematic Review and Benchmark*.

This resource reproduces the method names and taxonomy of **Fig. 2** in the manuscript. The collection includes both methods applied to optical-to-SAR translation and general-purpose techniques that may be transferable. **Inclusion does not imply validation on optical-to-SAR datasets.**

> **Bibliography status:** This is a working draft. Candidate paper titles, years and URLs require a final bibliographic check against the original publications. Blank entries are deliberately left unresolved rather than replaced by search links.

## Method taxonomy

Upload the figure as `figures/taxonomy.png` and uncomment the following line:

<!-- ![Method taxonomy](figures/taxonomy.png) -->

## Literature by category


## GAN-Based

### Paired Supervised Conditional Methods

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| Pix2Pix | Image-to-Image Translation with Conditional Adversarial Networks | 2017 | [Paper](https://arxiv.org/abs/1611.07004) |
| Pix2PixHD | High-Resolution Image Synthesis and Semantic Manipulation with Conditional GANs | 2018 | [Paper](https://arxiv.org/abs/1711.11585) |
| SPADE | Semantic Image Synthesis with Spatially-Adaptive Normalization | 2019 | [Paper](https://arxiv.org/abs/1903.07291) |
| GauGAN | Semantic Image Synthesis with Spatially-Adaptive Normalization | 2019 | [Paper](https://arxiv.org/abs/1903.07291) |
| OASIS | You Only Need Adversarial Supervision for Semantic Image Synthesis | 2021 | [Paper](https://arxiv.org/abs/2012.04781) |
| SEAN | SEAN: Image Synthesis with Semantic Region-Adaptive Normalization | 2020 | [Paper](https://arxiv.org/abs/1911.12861) |
| GRIT | To be verified | — | To be verified |
| DSG-GAN | To be verified | — | To be verified |
| VD-GAN | To be verified | — | To be verified |
| CoCosNet | To be verified | — | To be verified |
| CoCosNet v2 | To be verified | — | To be verified |
| DRPAN | To be verified | — | To be verified |

### Unpaired Constraint-Based Methods

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| CycleGAN | Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks | 2017 | [Paper](https://arxiv.org/abs/1703.10593) |
| DualGAN | DualGAN: Unsupervised Dual Learning for Image-to-Image Translation | 2017 | [Paper](https://arxiv.org/abs/1704.02510) |
| DiscoGAN | Learning to Discover Cross-Domain Relations with Generative Adversarial Networks | 2017 | [Paper](https://arxiv.org/abs/1703.05192) |
| UNIT | Unsupervised Image-to-Image Translation Networks | 2017 | [Paper](https://arxiv.org/abs/1703.00848) |
| CUT | Contrastive Learning for Unpaired Image-to-Image Translation | 2020 | [Paper](https://arxiv.org/abs/2007.15651) |
| AttentionGAN | To be verified | — | To be verified |
| U-GAT-IT | U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation | 2020 | [Paper](https://arxiv.org/abs/1907.10830) |
| DcGAN | To be verified | — | To be verified |
| DCLGAN | Dual Contrastive Learning for Unsupervised Image-to-Image Translation | 2021 | [Paper](https://arxiv.org/abs/2104.07689) |
| UVCGAN | To be verified | — | To be verified |
| CRPGAN | To be verified | — | To be verified |
| SANTA | To be verified | — | To be verified |
| LANIT | To be verified | — | To be verified |
| NICE-GAN | To be verified | — | To be verified |

### Diversity-Oriented Generation Methods

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| BicycleGAN | Toward Multimodal Image-to-Image Translation | 2017 | [Paper](https://arxiv.org/abs/1711.11586) |
| MUNIT | Multimodal Unsupervised Image-to-Image Translation | 2018 | [Paper](https://arxiv.org/abs/1804.04732) |
| DRIT | Diverse Image-to-Image Translation via Disentangled Representations | 2018 | [Paper](https://arxiv.org/abs/1808.00948) |
| StarGAN v2 | StarGAN v2: Diverse Image Synthesis for Multiple Domains | 2020 | [Paper](https://arxiv.org/abs/1912.01865) |
| DRIT++ | DRIT++: Diverse Image-to-Image Translation via Disentangled Representations | 2020 | [Paper](https://arxiv.org/abs/1905.01270) |
| DR-AVIT | To be verified | — | To be verified |
| ACLGAN | To be verified | — | To be verified |
| StyleGAN-NADA | To be verified | — | To be verified |
| MSGAN | Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis | 2019 | [Paper](https://arxiv.org/abs/1903.05628) |
| Image2StyleGAN | Image2StyleGAN: How to Embed Images Into the StyleGAN Latent Space? | 2019 | [Paper](https://arxiv.org/abs/1904.03189) |
| FUNIT | Few-Shot Unsupervised Image-to-Image Translation | 2019 | [Paper](https://arxiv.org/abs/1905.01723) |


## Diffusion, Flow-Based, and Foundation-Model-Enabled

### Task-specific Generative Models / Conditional Diffusion

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| Palette | Palette: Image-to-Image Diffusion Models | 2022 | [Paper](https://arxiv.org/abs/2111.05826) |
| SR3 | Image Super-Resolution via Iterative Refinement | 2021 | [Paper](https://arxiv.org/abs/2104.07636) |
| ControlNet | Adding Conditional Control to Text-to-Image Diffusion Models | 2023 | [Paper](https://arxiv.org/abs/2302.05543) |
| SDEdit | SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations | 2022 | [Paper](https://arxiv.org/abs/2108.01073) |
| ILVR | ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models | 2021 | [Paper](https://arxiv.org/abs/2108.02938) |
| RePaint | RePaint: Inpainting using Denoising Diffusion Probabilistic Models | 2022 | [Paper](https://arxiv.org/abs/2201.09865) |
| DDRM | Denoising Diffusion Restoration Models | 2022 | [Paper](https://arxiv.org/abs/2201.11793) |
| DPS | Diffusion Posterior Sampling for General Noisy Inverse Problems | 2023 | [Paper](https://arxiv.org/abs/2209.14687) |

### Task-specific Generative Models / Bridge-Based Translation

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| EGSDE | To be verified | — | To be verified |
| BBDM | BBDM: Image-to-Image Translation with Brownian Bridge Diffusion Models | 2023 | [Paper](https://arxiv.org/abs/2205.07680) |
| LBM | LBM: Latent Bridge Matching for Fast Image-to-Image Translation | 2025 | To be verified |
| I2SB | I2SB: Image-to-Image Schrödinger Bridge | 2023 | [Paper](https://arxiv.org/abs/2302.05872) |
| DDIBs | Dual Diffusion Implicit Bridges for Image-to-Image Translation | 2023 | [Paper](https://arxiv.org/abs/2203.08382) |
| CycleDiffusion | CycleDiffusion: Diffusion-Based Image Editing with Stochastic Coupling | 2023 | [Paper](https://arxiv.org/abs/2210.05559) |

### Task-specific Generative Models / Flow-Based Translation

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| Paired-Flow | To be verified | — | To be verified |
| Rectified Flow | Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow | 2023 | [Paper](https://arxiv.org/abs/2209.03003) |
| Sequential Reflow | To be verified | — | To be verified |

### Pretrained Generative Model Adaptation / Conditional Control

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| T2I-Adapter | T2I-Adapter: Learning Adapters to Dig out More Controllable Ability for Text-to-Image Diffusion Models | 2023 | [Paper](https://arxiv.org/abs/2302.08453) |
| IP-Adapter | IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models | 2023 | [Paper](https://arxiv.org/abs/2308.06721) |
| Uni-ControlNet | To be verified | — | To be verified |
| GLIGEN | GLIGEN: Open-Set Grounded Text-to-Image Generation | 2023 | [Paper](https://arxiv.org/abs/2301.07093) |

### Pretrained Generative Model Adaptation / Instruction and Editing-based Translation

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| SDEdit | SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations | 2022 | [Paper](https://arxiv.org/abs/2108.01073) |
| Plug-and-Play | Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation | 2023 | [Paper](https://arxiv.org/abs/2211.12572) |
| Pix2Pix-Zero | Zero-shot Image-to-Image Translation | 2023 | [Paper](https://arxiv.org/abs/2302.03027) |
| MasaCtrl | MasaCtrl: Tuning-Free Mutual Self-Attention Control for Consistent Image Synthesis and Editing | 2023 | [Paper](https://arxiv.org/abs/2304.08465) |
| DiffEdit | DiffEdit: Diffusion-based Semantic Image Editing with Mask Guidance | 2023 | [Paper](https://arxiv.org/abs/2210.11427) |
| Prompt-to-Prompt | Prompt-to-Prompt Image Editing with Cross Attention Control | 2023 | [Paper](https://arxiv.org/abs/2208.01626) |
| InstructPix2Pix | InstructPix2Pix: Learning to Follow Image Editing Instructions | 2023 | [Paper](https://arxiv.org/abs/2211.09800) |

### Pretrained Generative Model Adaptation / Domain Adaptation and Fine-tuning

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| LoRA | LoRA: Low-Rank Adaptation of Large Language Models | 2022 | [Paper](https://arxiv.org/abs/2106.09685) |
| SVDiff | To be verified | — | To be verified |
| DiffFit | To be verified | — | To be verified |

### Foundation-Model-Assisted Translation / Visual Representation Guidance

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| DINO | Emerging Properties in Self-Supervised Vision Transformers | 2021 | [Paper](https://arxiv.org/abs/2104.14294) |
| DINOv2 | DINOv2: Learning Robust Visual Features without Supervision | 2024 | [Paper](https://arxiv.org/abs/2304.07193) |
| MAE | Masked Autoencoders Are Scalable Vision Learners | 2022 | [Paper](https://arxiv.org/abs/2111.06377) |
| SAM | Segment Anything | 2023 | [Paper](https://arxiv.org/abs/2304.02643) |
| Grounding DINO | Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection | 2024 | [Paper](https://arxiv.org/abs/2303.05499) |
| SARATR-X | To be verified | — | To be verified |
| SARMAE | To be verified | — | To be verified |

### Foundation-Model-Assisted Translation / Cross-Modal Representation Guidance

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| CROMA | To be verified | — | To be verified |
| DeCUR | To be verified | — | To be verified |
| SkySense | To be verified | — | To be verified |

### Foundation-Model-Assisted Translation / Vision-Language Guidance

| Method | Full Paper Title | Year | Paper |
|---|---|---|---|
| CLIP | Learning Transferable Visual Models From Natural Language Supervision | 2021 | [Paper](https://arxiv.org/abs/2103.00020) |
| RemoteCLIP | To be verified | — | To be verified |
| GeoRSCLIP | To be verified | — | To be verified |
| EarthGPT | EarthGPT: A Universal Multi-modal Large Language Model for Multi-sensor Image Comprehension in Remote Sensing Domain | 2024 | [Paper](https://arxiv.org/abs/2401.16822) |
| GeoChat | GeoChat: Grounded Large Vision-Language Model for Remote Sensing | 2024 | [Paper](https://arxiv.org/abs/2311.15826) |
| SARCLIP | To be verified | — | To be verified |

## Structured bibliography

The editable source of this list is [`methods.csv`](methods.csv). Repeated methods are retained when Fig. 2 assigns them to multiple methodological roles.

## Citation

Ye et al., *Optical-to-SAR Translation in Remote Sensing: A Systematic Review and Benchmark* (manuscript). Full publication information will be added when available.

## Notes

- Method names and category assignments follow Fig. 2 of the supplied v3 manuscript.
- Publication years are intended to refer to formal publication years when known; please check them against the version you cite.
- Do not treat candidate links as independently verified bibliographic records.
