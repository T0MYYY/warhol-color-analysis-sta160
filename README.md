# Warhol's Marilyn Monroe — Color Analysis | UC Davis STA 160 Final Project

<!-- BADGES_BEGIN -->
<p align="center">
  <img alt="Course" src="https://img.shields.io/badge/Course-STA%20160-022851?style=flat-square&labelColor=2a323d">
  <img alt="UC Davis" src="https://img.shields.io/badge/UC%20Davis-Multivariate%20Stats-FFBF00?style=flat-square&labelColor=2a323d">
  <img alt="Term" src="https://img.shields.io/badge/Term-Spring%202023-2a323d?style=flat-square&labelColor=2a323d">
  <img alt="Author" src="https://img.shields.io/badge/Author-Solo-1f7a3d?style=flat-square&labelColor=2a323d">
  <img alt="Status" src="https://img.shields.io/badge/Status-Final-ec5800?style=flat-square&labelColor=2a323d">
  <img alt="Report" src="https://img.shields.io/badge/Report-PDF-EC2025?style=flat-square&labelColor=2a323d">
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-notebook-F37626?style=flat-square&labelColor=2a323d&logo=jupyter&logoColor=white">
  <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=flat-square&labelColor=2a323d&logo=opencv&logoColor=white">
  <img alt="Pillow" src="https://img.shields.io/badge/Pillow-10.x-0078d4?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-1.x-F7931E?style=flat-square&labelColor=2a323d&logo=scikitlearn&logoColor=white">
  <img alt="Plotly" src="https://img.shields.io/badge/Plotly-5.x-3F4F75?style=flat-square&labelColor=2a323d&logo=plotly&logoColor=white">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1.x-013243?style=flat-square&labelColor=2a323d&logo=numpy&logoColor=white">
  <img alt="seaborn" src="https://img.shields.io/badge/seaborn-0.13-4C72B0?style=flat-square&labelColor=2a323d">
  <img alt="rembg" src="https://img.shields.io/badge/rembg-segmentation-059669?style=flat-square&labelColor=2a323d">
</p>
<!-- BADGES_END -->

**Course:** STA 160, Spring 2023 — UC Davis
**Author:** Chiyang Chen

<p align="center">
  <img src="images/shot_red_marilyn_1964-19604.png" width="18%">
  <img src="images/shot_lightblue_marilyn_1964-19604.png" width="18%">
  <img src="images/shot_segablue_marilyn_1964-19604.png" width="18%">
  <img src="images/shot_orange_marilyn_1964-19604.png" width="18%">
  <img src="images/shot_turquoise_marilyn_1964-19604.png" width="18%">
</p>

## Project Description

A statistical and visual analysis of color properties across five of Andy Warhol's iconic 1964 *Marilyn Monroe* silkscreen prints. The five color variants analyzed are: **Red**, **Light Blue**, **Sega Blue**, **Orange**, and **Turquoise**.

The project applies image processing, K-Means clustering, conditional entropy, and HSV color manipulation to quantify and compare the color composition of each print, and to programmatically modify specific regions of interest (e.g., eyeshadow).

## Analysis Sections

| Section | Description |
|---|---|
| Color Analysis | RGB & HSV visualization, 3D interactive plots, conditional entropy between color channels |
| Region Identification | Background, hair, and eyeshadow segmentation using color thresholding and deep learning |
| K-Means Color Extraction | Cluster image colors at varying k; compare color distributions across prints |
| Eyeshadow Color Modification | HSV-based masking to programmatically change eyeshadow hue |

## Files

| File/Folder | Description |
|---|---|
| `notebook.ipynb` | Main Jupyter notebook with all analysis and visualizations |
| `report.pdf` | Written project report |
| `images/` | Five PNG image variants of the Warhol Marilyn Monroe prints |
| `interactive/` | Five HSV 3D interactive HTML plots (one per color variant) |

## Libraries

- PIL/Pillow
- OpenCV (cv2)
- numpy
- matplotlib
- sklearn
- scipy
