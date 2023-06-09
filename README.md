# Awesome-Segment-Anything
Collect some resource about Segment Anything (SAM), including latest papers and demo.

## Papers
###  Segment Anything original paper
- [Segment Anything](https://arxiv.org/abs/2304.02643) [arXiv 2023] 

### Technical blog
- [English Blog] Introducing Segment Anything: Working toward the first foundation model for image segmentation [[Link](https://ai.facebook.com/blog/segment-anything-foundation-model-image-segmentation/)]
- [Chinese Blog] 论文解读MetaAi SAM分割一切 [[Link](https://zhuanlan.zhihu.com/p/620355474)]

### Discussion
- [Reddit] Meta AI has released *both* the Model AND the dataset for Segment Anything [[Link](https://www.reddit.com/r/singularity/comments/12cq56n/meta_ai_has_released_both_the_model_and_the/)]
- [Zhihu] Meta 发布图像分割论文 Segment Anything，将给 CV 研究带来什么影响？[[Link](https://www.zhihu.com/question/593914819)]

### arXiv papers
- SAM Fails to Segment Anything? -- SAM-Adapter: Adapting SAM in Underperformed Scenes: Camouflage, Shadow, and More [[paper](https://arxiv.org/abs/2304.09148)] [[code](https://tianrun-chen.github.io/SAM-Adaptor/)]
- Learning to "Segment Anything" in Thermal Infrared Images through Knowledge Distillation with a Large Scale Dataset SATIR [[paper](https://arxiv.org/abs/2304.07969)] [[code](https://github.com/chenjzBUAA/SATIR)]
- The Segment Anything foundation model achieves favorable brain tumor autosegmentation accuracy on MRI to support radiotherapy treatment planning [[paper](https://arxiv.org/abs/2304.07875)] 
- Deep learning universal crater detection using Segment Anything Model (SAM) [[paper](https://arxiv.org/abs/2304.07764)]
- Can SAM Segment Polyps? [[paper](https://arxiv.org/abs/2304.07583)] [[code](https://github.com/taozh2017/SAMPolyp)]
- Inpaint Anything: Segment Anything Meets Image Inpainting [[paper](https://arxiv.org/abs/2304.06790)] [[code](https://github.com/geekyutao/Inpaint-Anything)]
- **[SEEM]** Segment Everything Everywhere All at Once [[paper](https://arxiv.org/abs/2304.06718)] [[code](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)]
- SAM Struggles in Concealed Scenes -- Empirical Study on "Segment Anything" [[paper](https://arxiv.org/abs/2304.06022)]
- Segment Anything Is Not Always Perfect: An Investigation of SAM on Different Real-world Applications [[paper](https://arxiv.org/abs/2304.05750)]
- CLIP Surgery for Better Explainability with Enhancement in Open-Vocabulary Tasks [[paper](https://arxiv.org/abs/2304.05653)]
- SAMM (Segment Any Medical Model): A 3D Slicer Integration to SAM [[paper](https://arxiv.org/abs/2304.05622)]
- SAM.MD: Zero-shot medical image segmentation capabilities of the Segment Anything Model [[paper](https://arxiv.org/abs/2304.05396)]
- Brain Extraction comparing Segment Anything Model (SAM) and FSL Brain Extraction Tool [[paper](https://arxiv.org/abs/2304.04738)]
- Can SAM Segment Anything? When SAM Meets Camouflaged Object Detection [[paper](https://arxiv.org/abs/2304.04709)]
- Segment Anything Model (SAM) for Digital Pathology: Assess Zero-shot Segmentation on Whole Slide Imaging [[paper](https://arxiv.org/abs/2304.04155)]

## Application

### Image Detection/Segmentation
- [[**Grounded-Segment-Anything**](https://github.com/IDEA-Research/Grounded-Segment-Anything)]: A very interesting demo by combining Grounding DINO and Segment Anything

- [[**GroundedSAM-zero-shot-anomaly-detection**](https://github.com/caoyunkang/GroundedSAM-zero-shot-anomaly-detection)]: Segment any anomaly without any training

- [[**Semantic Segment Anything**](https://github.com/fudan-zvg/Semantic-Segment-Anything)]: SSA is an automated annotation engine that serves as the initial semantic labeling for the SA-1B dataset.

- [[**Segment Anything with Clip**](https://github.com/Curt-Park/segment-anything-with-clip)]: It aims to resolve downstream segmentation tasks with prompt engineering, such as foreground/background points, bounding box, mask, and free-formed text.

- [[**Prompt-Segment-Anything**](https://github.com/RockeyCoss/Prompt-Segment-Anything)]: This is an implementation of zero-shot instance segmentation using Segment Anything.

- [[**SAM-RBox**](https://github.com/Li-Qingyun/sam-mmrotate)]: This is an implementation of SAM (Segment Anything Model) for generating rotated bounding boxes with MMRotate.

- [[**Open-vocabulary-Segment-Anything**](https://github.com/ngthanhtin/owlvit_segment_anything)]: An interesting demo by combining OWL-ViT of Google and Segment Anything of Meta!

- [[**SegDrawer**](https://github.com/lujiazho/SegDrawer)]: Simple static web-based mask drawer, supporting semantic drawing with Segment Anything Model.

- [[**MetaSeg: Packaged version of the Segment Anything repository**](https://github.com/kadirnar/segment-anything-video)]: This repo is a packaged version of the segment-anything model.

- [[**Segment Anything EO tools**](https://github.com/aliaksandr960/segment-anything-eo)]: This tools are developed to ease the processing of spatial data (GeoTIFF and TMS) with Meta AI Segment Anything models using sliding window algorithm for big files.

- [[**SEEM**](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)]: SEEM allows users to easily segment an image using prompts of different types including visual prompts (points, marks, boxes, scribbles and image segments) and language prompts (text and audio), etc 

### Distillation and Automated Labeling

- [Autodistill](https://github.com/autodistill/autodistill): Images to inference with no labeling (use foundation models to train supervised models). `autodistill` features a `autodistill-grounded-sam` module that enables automated image annotation using Grounding DINO and SAM.

### 3D 
- [[**3D-Box via Segment Anything**](https://github.com/dvlab-research/3D-Box-Segment-Anything)]:  In this project, we extend the scope to 3D world by combining Segment Anything and VoxelNeXt. When we provide a prompt (e.g., a point / box), the result is not only 2D segmentation mask, but also 3D boxes.

- [[**Anything-3DNovel-View**](https://github.com/Anything-of-anything/Anything-3D)]: Combining Segment Anything and a series of 3D models

### Labeling
- [[**AnyLabeling**](https://github.com/vietanhdev/anylabeling)]: AnyLabeling = LabelImg + Labelme + Improved UI + Auto-labeling

### Image Generation
- [[**Segment Anything for Stable Diffusion WebUI**](https://github.com/continue-revolution/sd-webui-segment-anything)]: This extension aim for helping stable diffusion webui users to use segment anything to do stable diffusion inpainting.

- [[**IEA: Image Editing Anything**](https://github.com/feizc/IEA)]: Using stable diffusion and segmentation anything models for image editing.

- [[**Edit Anything by Segment-Anything**](https://github.com/sail-sg/EditAnything)]: This is an ongoing project aims to Edit and Generate Anything in an image, powered by Segment Anything, ControlNet, BLIP2, Stable Diffusion, etc.

- [[**Inpaint Anything**](https://github.com/geekyutao/Inpaint-Anything)]:  Segment Anything Meets Image Inpainting

- [[**Magic Copy**](https://github.com/kevmo314/magic-copy)]: Magic Copy is a Chrome extension that uses Meta's Segment Anything Model to extract a foreground object from an image and copy it to the clipboard.
