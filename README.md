# EnochSight

**EnochSight** is a Python-based visual modeling project that converts textual cosmology descriptions from ancient manuscripts—specifically Chapter 72 of the *Book of Enoch* ("The Book of the Courses of the Heavenly Luminaries")—into 3D environments and interactive visualizations using text-to-3D pipeline concepts.

---

## Features

- **Text Processing & Passage Extraction**: Cleans raw historical text and uses keyword targeting (`portal`, `gate`, `sun`, `wind`, `storehouses`) to isolate visual imagery.
- **Automated Prompt Generation**: Converts descriptive text passages into structured prompts designed for Text-to-3D AI generation services.
- **3D API Integration & Simulation**: Connects to the **Tripo AI API** (v2) for text-to-3D mesh generation with a fallback geometry simulator (`trimesh`) if no API key is present.
- **Interactive Visualizations**: Renders 3D meshes and feature scatter plots directly in interactive environments using `plotly`.

---

## Installation

Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/your-username/EnochSight.git](https://github.com/your-username/EnochSight.git)
cd EnochSight
pip install -r requirements.txt
