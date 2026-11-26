### Tech Stack & Tooling

<div align="center">

  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />

  <br>

  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Computer_Vision-Grad--CAM-02569B?style=for-the-badge" alt="Computer Vision" />
  <img src="https://img.shields.io/badge/Optimization-Swarm_Intelligence-4B0082?style=for-the-badge" alt="Swarm Intelligence" />

  <br>

  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt" />

</div>

---

### Machine Learning Projects

| Project | Focus | Stack | Key Highlights |
| :--- | :--- | :--- | :--- |
| **[GeoLoq](https://huggingface.co/spaces/skiessq/GeoLoq)** | AI Visual Geolocation & Explainability | `PyTorch` `ResNet-101` `Grad-CAM` `SwarmPackagePy` `Gradio` | - Built Python scripts to curate and balance **40,000+** street-view images from the OpenStreetView-5M dataset across **19 countries** and **8 Portuguese cities**.<br>- Trained two custom CNN baselines from scratch (**0.52** and **0.66** macro F1, improved to **0.54** and **0.68** via swarm optimization) before fine-tuning pretrained **ResNet-101** models to reach **0.71** (+17 p.p.) on countries and **0.84** (+16 p.p.) on cities.<br>- Benchmarked PSO, Artificial Bee Colony (ABC), and Grid Search on learning rate and dropout.<br>- Integrated **Grad-CAM** heatmaps to visualize geographic decision cues and deployed an interactive public inference app on **Hugging Face Spaces**. |

---

### Open Source Contributions

| Repository | Scope | Stack | Details |
| :--- | :--- | :--- | :--- |
| **[godotengine/godot](https://github.com/godotengine/godot/pulls?q=is%3Apr+author%3Askiessq+is%3Amerged)** | Merged Core Contributions | `C++` | - **VisualShader:** Fixed graph duplication bug by rewriting node reparenting logic (cherry-picked for **4.6.2**).<br>- **FileSystemDock:** Refactored UI container theme variations and scroll-hint behavior to prevent panel blending when bottom-docked (cherry-picked for **4.6.3**). |
```[cite: 1]
