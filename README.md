# 🧠 Dataset_Generator_using_LLM

## Architecture

```mermaid
flowchart LR
  U[Dataset requirements] --> UI[Generator interface]
  UI --> L[LLM generation]
  L --> V[Validation and formatting]
  V --> D[Synthetic dataset]
```

A flexible and user-friendly tool to create synthetic datasets for machine learning models, data analysis, and educational purposes.\
Perfect for testing algorithms, training ML models, or demonstrating concepts.

## 📌 Features

- Customizable number of samples and features
- Supports multiple output labels for classification tasks
- Generates numerical and categorical features
- Export datasets in CSV format
- Includes basic visualization support
- Reproducible outputs using random seed

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/AryaLolusare2712/dataset-generator.git
cd dataset-generator
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook
Launch the notebook in your browser:

```bash
jupyter notebook Dataset_Generator.ipynb
```
Follow the cells to generate and visualize your custom dataset.

📁 Output
- Dataset is saved as a .csv file in your working directory.
- Optional: Visualizations such as scatter plots or histograms (if enabled).

⚙️ Customization Options
- Inside the notebook, you can configure:
- Number of rows and columns
- Feature types (categorical/numerical)

- Number of classes (for classification)

- Value ranges, distributions, and noise

- Random seed for consistent results

