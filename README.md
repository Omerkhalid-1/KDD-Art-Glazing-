# Artwork Protection Through Advanced Glazing Techniques

This repository contains the implementation of techniques designed to protect digital artwork through innovative adversarial learning and image processing methods. By employing edge-based protection, pattern infusion, contour modification, and artistic style fusion, the approaches presented here safeguard artwork against machine learning classifiers while preserving visual integrity.

## Key Techniques

1. **Edge-Based Protection**  
   Patterns from an auxiliary image are blended into the edges of the original artwork, adding a layer of complexity that confounds AI classifiers.

2. **Pattern Infusion for Misclassification**  
   Adversarial patterns are infused into the original image, achieving a 95% success rate in causing misclassifications. This ensures effective artwork protection.

3. **Contour Modification**  
   The algorithm selects key contours from the image and alters their colors subtly, introducing perceptual variations that disrupt classifier performance.

4. **Art-to-Art Infusion**  
   Artistic elements (e.g., cubism) from a secondary image are blended into the original artwork. This creates unique variations while preserving the original's aesthetic value, confounding classification models.

---

## Folder Structure

- **`Edge_protection.ipynb`**  
  Implements edge-based protection by blending edge patterns from reference images into the target artwork.
  
- **`Pattern_infusion.ipynb`**  
  Demonstrates adversarial pattern infusion to achieve misclassification rates as high as 95%.

- **`Contour_modification.ipynb`**  
  Modifies five selected contours from the artwork with subtle color changes to disrupt recognition models.

- **`Art_to_art_infusion.ipynb`**  
  Implements fusion of cubist patterns into the original artwork, creating variations that mislead classification algorithms.

---

## Quick Start

1. Clone this repository:
   ```bash
   git clone https://github.com/Omerkhalid-1/KDD-Art-Glazing-.git
