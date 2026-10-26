# JOAI 2026 Neural Decoding Code
Full code of my neural decoding model for JOAI 2026.

For MIT Maker Portfolio reviewers:
Since my model code lived on Google Colab, I manually committed it to a fresh repository. The commit history therefore appears nearly empty.
I attest that I developed this model alone.

Libraries and model structures used:
PyTorch, LightGBM, scikit-learn, NumPy, pandas, SciPy.
Transformer, Conv1D–LSTM, ResNet–BiGRU–Attention, Temporal Convolutional Network (TCN), multilayer perceptron (MLP), and Ridge regression meta-learner.

My work (as left in the final code):
- Developed a 6-branch ensemble combining deep learning and gradient-boosted trees (to predict mouse behavior from neural activity).
- Engineered extensive spatiotemporal features, including brain-region interactions, bilateral asymmetries, temporal derivatives, lagged signals, rolling statistics, and subject-specific normalization.
- Implemented custom multi-task learning with auxiliary derivative (Δy) prediction, Mixup/CutMix augmentation, mixed-precision training, and early stopping.
- Built a multi-seed, five-fold cross-validation pipeline with out-of-fold predictions, test-time augmentation, and Ridge-based ensemble optimization.
- Developed vectorized feature-precomputation routines, model diagnostics, and prediction-uncertainty analysis to improve computational efficiency and evaluate robustness.

This model was used for the first (main) round of Japan Olympiad in Artificial Intelligence 2026, where I won gold.
