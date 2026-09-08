# DeepLearning2025_2026_Final_project
Compositional Generation in Conditional Diffusion Models: The Effect of Factor Correlation on Compositional CFG

Class-conditional DDPM on dSprites testing how training correlation between shape and scale factors degrades compositional Classifier-Free Guidance (CFG). 
Sweeps correlation strength (ρ=0–0.95), comparing joint vs. composed sampling, with ablations on DDIM steps, composition weight, and factor entanglement. 
Includes a true zero-shot benchmark, second-seed robustness check, and memorization diagnostics (FFD, nearest-neighbor distance).

**Course:** DLAI 2025/2026 
**Topic:** Image/Video Generation

## Dataset

[dSprites Dataset] — https://github.com/google-deepmind/dsprites-dataset 
737,280 procedurally generated 64×64 binary sprites with 6 latent factors (shape, scale, orientation, position, color)
a fixed-color, reduced-range subset with 3 shapes and 3 scale bins is used, 
sampled at controlled shape–scale correlations (ρ=0–0.95) and under a true zero-shot exclusion split.
## Repository

- `CompositionalGeneration_FactorCorrelation_CFG.ipynb` — Main pipeline
- `Report.pdf` — full project report

## Authors

Marthe Elgawly — 2170201 
elgawly.2170201@studenti.uniroma1.it
