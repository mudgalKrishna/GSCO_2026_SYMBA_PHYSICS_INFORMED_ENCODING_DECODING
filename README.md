# GSCO_2026_SYMBA_PHYSICS_INFORMED_ENCODING_DECODING
# Physics-Informed SYMBA

**GAT-Based Squared Amplitude Prediction for Particle Physics**

This project translates Feynman diagram descriptions into symbolic squared amplitudes \(|\mathcal{M}|^2\) using a multi-modal neural architecture combining Graph Attention Networks (GAT) with Transformers.

## Overview

The model takes three inputs:
- **Amplitude text** → Tokenized symbolic expression
- **Feynman diagram** → Graph structure (nodes=vertices, edges=propagators)
- **Global physics scalars** → Coupling order, color factors, QED/QCD flag

Outputs the squared amplitude as a symbolic expression token-by-token.

