# G3DS-LiDAR: Geometry-Aware 3D Gaussian Splatting with Persistent LiDAR Priors
Official project page for **G3DS-LiDAR** (under review at ISPRS Journal of Applied Geoinformatics (JAG)).

## 📌 Abstract
Conventional 3D Gaussian Splatting (3DGS) often suffers from geometric drift, scale degradation, and floating artifacts, especially in weakly-textured, occluded, or depth-discontinuous regions.
To address these challenges, we propose **G3DS-LiDAR**, a novel geometry-aware 3D Gaussian Splatting framework that embeds persistent LiDAR geometric priors throughout the entire reconstruction pipeline.

Our contributions include:
- LiDAR-guided Gaussian initialization with robust geometric priors
- Geometric metadata anchoring and dynamic reassociation to reduce drift
- Generation-dependent weighted constraints and curvature-driven edge modeling
- Effective suppression of artifacts while preserving the efficiency of explicit Gaussian representation

## 🏗️ Pipeline Overview
<div align="center">
  <img src="https://raw.githubusercontent.com/SongJiang-WHU/G3DS-LiDAR/main/img/pipeline.png"
       alt="Pipeline Overview"
       style="width:100%; max-width:1400px;">
</div>

## 📊 Qualitative Results
<div align="center">
  <img src="https://raw.githubusercontent.com/SongJiang-WHU/G3DS-LiDAR/main/img/Fig6.png"
       style="width:100%; max-width:1400px;"><br>
  <img src="https://raw.githubusercontent.com/SongJiang-WHU/G3DS-LiDAR/main/img/Fig11.png"
       style="width:100%; max-width:1400px;"><br>
  <img src="https://raw.githubusercontent.com/SongJiang-WHU/G3DS-LiDAR/main/img/Fig12.png"
       style="width:100%; max-width:1400px;">
</div>

## 🎬 Demo Videos

> ⏳ **Loading Notice:** GIFs are large files and may take 10–30 seconds to load. Please wait patiently.
>
> ⚠️ **Quality Note:**
> - Embedded GIFs are compressed for preview and may appear blurry.
> - For the highest quality visualization, download the original MP4 videos linked below.

### Indoor Scene Reconstruction Demos

<div align="center">
  <img src="https://github.com/SongJiang-WHU/G3DS-LiDAR/blob/main/demo/office3.gif?raw=true" width="100%" alt="Office 3 Scene">
  <p><i>Office 3 Scene — <a href="./demo/office3.mp4">Download High-Quality MP4</a></i></p>
</div>

<div align="center">
  <img src="https://github.com/SongJiang-WHU/G3DS-LiDAR/blob/main/demo/office4.gif?raw=true" width="100%" alt="Office 4 Scene">
  <p><i>Office 4 Scene — <a href="./demo/office4.mp4">Download High-Quality MP4</a></i></p>
</div>

<div align="center">
  <img src="https://github.com/SongJiang-WHU/G3DS-LiDAR/blob/main/demo/room0.gif?raw=true" width="100%" alt="Room 0 Scene">
  <p><i>Room 0 Scene — <a href="./demo/room0.mp4">Download High-Quality MP4</a></i></p>
</div>

<div align="center">
  <img src="https://github.com/SongJiang-WHU/G3DS-LiDAR/blob/main/demo/room2.gif?raw=true" width="100%" alt="Room 2 Scene">
  <p><i>Room 2 Scene — <a href="./demo/room2.mp4">Download High-Quality MP4</a></i></p>
</div>

---

### Outdoor Scene Reconstruction Demos

<div align="center">
  <img src="https://github.com/SongJiang-WHU/G3DS-LiDAR/blob/main/demo/fastlivo2.gif?raw=true" width="100%" alt="FAST-LIVO2 Outdoor Scene">
  <p><i>FAST-LIVO2 Outdoor Scene — <a href="./demo/fastlivo2.mp4">Download High-Quality MP4</a></i></p>
</div>

<div align="center">
  <img src="https://github.com/SongJiang-WHU/G3DS-LiDAR/blob/main/demo/HLS-Ours.gif?raw=true" width="100%" alt="HLS Outdoor Scene">
  <p><i>HLS Outdoor Scene — <a href="./demo/HLS-Ours.mp4">Download High-Quality MP4</a></i></p>
</div>

## 🚧 Code Release
The full code will be released **upon paper acceptance**.

For inquiries, please contact:
Jiang Song: songjiang@whu.edu.cn

## 📄 Citation
If you find our work useful, please cite:
```bibtex
@article{song2025g3ds,
  title={G3DS-LiDAR: Geometry-Aware 3D Gaussian Splatting with Persistent LiDAR Priors},
  author={Jiang Song, Changjun Chen, Hong Xie, Zongqian Zhan, Ronglin Zhang, Shuo Wang, Li Yan},
  journal={ISPRS Journal of Applied Geoinformatics},
  year={2025}
}
