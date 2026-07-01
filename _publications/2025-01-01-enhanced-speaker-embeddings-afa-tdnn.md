---
title: "Enhanced Speaker Embeddings With Adaptive Feature Aggregation For Robust Speaker Diarization"
collection: publications
category: manuscripts
permalink: /publication/2025-01-01-enhanced-speaker-embeddings-afa-tdnn
excerpt: 'This paper proposes an embedding approach using Adaptive Feature Aggregation Time-Delay Neural Networks (AFA-TDNN) for robust speaker diarization, combined with Batch-Adaptive Data Augmentation (BADA), achieving a DER of 2.23% and JER of 5.9% on the AMI Meeting Corpus.'
date: 2025-01-01
venue: 'International Journal of Advances in Signal and Image Sciences (IJASIS)'
paperurl: 'https://xlescience.org/index.php/IJASIS/article/view/1525'
citation: 'Vijay Hothi, N. B. Gohil, Mehul K. Vala, Devang G. Jani, Dhaval R. Bhojani, Rushi J. Trivedi. (2025). &quot;Enhanced Speaker Embeddings With Adaptive Feature Aggregation For Robust Speaker Diarization.&quot; <i>International Journal of Advances in Signal and Image Sciences</i>, Vol. 11 No. 6s.'
---

Speaker diarization—the process of partitioning an audio stream to determine "who spoke when"—is a fundamental challenge in multi-speaker environments. This paper introduces **AFA-TDNN** (Adaptive Feature Aggregation Time-Delay Neural Network), a novel architecture that produces highly discriminative speaker embeddings through:

- **Dynamic feature weighting** across frequency and time
- **Multi-scale temporal aggregation** for capturing both short- and long-term speaker characteristics
- **Residual feature fusion** for preserving low-level acoustic cues

Combined with **Batch-Adaptive Data Augmentation (BADA)**, the system exhibits strong robustness to background noise, reverberation, and channel variability.

Evaluated on the **AMI Meeting Corpus**, the proposed system achieves:
- **Diarization Error Rate (DER): 2.23%**
- **Jaccard Error Rate (JER): 5.9%**

outperforming current state-of-the-art baselines.
