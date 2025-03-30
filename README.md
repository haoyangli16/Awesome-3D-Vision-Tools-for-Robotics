# Awesome-3D-Vision-Tools-for-Robotics

This repository serves as a curated list of useful 3D computer vision tools and research projects relevant to Embodied AI tasks. It focuses on areas like 3D reconstruction from images/videos and point tracking.

## Table of Contents

- [Awesome-3D-Vision-Tools-for-Robotics](#awesome-3d-vision-tools-for-robotics)
  - [Table of Contents](#table-of-contents)
  - [Image → Point Cloud Reconstruction](#image--point-cloud-reconstruction)
    - [UniK3D](#unik3d)
    - [MoGe](#moge)
  - [Video → Point Cloud Reconstruction](#video--point-cloud-reconstruction)
    - [VGGT](#vggt)
    - [VGGSfM](#vggsfm)
    - [MegaSAM](#megasam)
  - [Point Tracking](#point-tracking)
    - [Stereo 4D](#stereo-4d)
    - [CoTracker3](#cotracker3)
  - [Contributing](#contributing)
  - [License](#license)

---

## Image → Point Cloud Reconstruction

Methods for reconstructing 3D point clouds from single or multiple static images, often estimating depth and camera intrinsics.

### UniK3D

*   **Task:** Single Image to Point Cloud (predicts depth & intrinsics)
*   [Website](https://lpiccinelli-eth.github.io/pub/unik3d/) | [Paper](https://arxiv.org/abs/2503.16591) | [Code](https://github.com/lpiccinelli-eth/unik3d) | [Demo](https://huggingface.co/spaces/lpiccinelli/UniK3D-demo)

### MoGe

*   **Task:** Single Image to Point Cloud (Multi-modal Conditioned Generation)
*   [Website](https://wangrc.site/MoGePage/) | [Paper](https://arxiv.org/pdf/2410.19115) | [Code](https://github.com/microsoft/moge) | [Demo](https://huggingface.co/spaces/Ruicheng/MoGe)

---

## Video → Point Cloud Reconstruction

Methods leveraging temporal information from video sequences for more robust 3D reconstruction or scene understanding.

### VGGT 

*   **Task:** Video to Point Cloud (predicts depth & intrinsics per frame)
*   [Website](https://vgg-t.github.io/) | [Paper](https://arxiv.org/abs/2503.11651) | [Code](https://github.com/facebookresearch/vggt) | [Demo](https://huggingface.co/spaces/facebook/vggt)

### VGGSfM 

*   **Task:** Structure from Motion from Video
*   [Website](https://vggsfm.github.io/) | [Paper](https://arxiv.org/abs/2312.04563) | [Code](https://github.com/facebookresearch/vggsfm) | [Demo](https://huggingface.co/spaces/facebook/vggsfm)

### MegaSAM

*   **Task:** Video-based Scene Understanding / Segmentation (Related to reconstruction)
*   [Website](https://mega-sam.github.io/) | [Paper](https://arxiv.org/abs/2412.04463) | [Code](https://github.com/mega-sam/mega-sam)

---

## Point Tracking

Methods for tracking the 3D or 2D motion of points or pixels over time in video sequences.

### Stereo 4D

*   **Task:** Dense 4D Scene Flow Estimation from Stereo Video
*   [Website](https://stereo4d.github.io/) | [Paper](https://arxiv.org/pdf/2412.09621) | [Code](https://github.com/Stereo4d/stereo4d-code)

### CoTracker3

*   **Task:** Tracking Any Point in a Video
*   [Website](https://cotracker3.github.io/) | [Paper](https://arxiv.org/abs/2410.11831) | [Code](https://github.com/facebookresearch/co-tracker)

---

## Contributing

Contributions are welcome! If you know of other relevant tools or papers, please open an Issue or Pull Request. Please try to follow the existing format, including links to the project website, paper, code, and demo if available.

## License

This list is provided under the [MIT License](LICENSE). Note that the licenses of the individual projects listed here may vary.