# Enhancing Object Recognition through Evolutionary Selection of Features

## Project Overview
This repository documents an academic project that improves the **HMAX model**, a hierarchical computational model of the human visual system for object recognition. The core innovation of this work is the application of a **Genetic Algorithm (GA)** to optimize the selection of image patches, representing a significant advancement over traditional random feature selection.  

By integrating an evolutionary algorithm, the project demonstrates a more intelligent and biologically plausible approach to identify the most informative features, resulting in a **more robust and efficient model**.

---

## Repository Contents

### report/
- `report.pdf`: Complete academic report detailing the methodology, experiments, and findings.

### code/
- `part1_HMAX_model.ipynb`: Baseline HMAX model implementation serving as a performance benchmark.
- `part2_GA_optimization.ipynb`: Genetic Algorithm implementation and its integration with the HMAX model for enhanced feature selection.

---

## Key Results
- The Genetic Algorithm significantly improved model performance compared to the original random-patch approach.  
- GA-enhanced HMAX consistently selected more **discriminative features**, improving recognition accuracy and generalization, especially with limited training data.  
- Results validate **evolutionary computation** as a powerful tool for optimizing feature selection in computer vision tasks.
