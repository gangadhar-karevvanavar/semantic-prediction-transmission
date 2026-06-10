# Semantic Text Transmission via Prediction with Small Language Models: Cost-Similarity Trade-off

This repository contains simulation codes for the paper:

**"Semantic Text Transmission via Prediction with Small Language Models: Cost-Similarity Trade-off"**

---

## Paper Summary

This work studies semantic text communication over noiseless and character-erasure channels. The proposed framework exploits the inherent predictability and correlations in natural language to reduce transmission costs by allowing the destination to predict or complete words that may differ from the source text while maintaining semantic similarity.

The objective is to characterize achievable trade-offs between:

- Average transmission cost
- Average semantic similarity

Semantic similarity is measured using cosine similarity between vector embeddings of source words and predicted/completed words at the destination.

The work investigates:
- Neural language model based prediction
- First-order Markov chain based prediction
- Threshold-based transmission policies
- Periodic transmission policies
- Character-level Huffman coding

Key observations include:
- Threshold policies outperform periodic policies for a given transmission cost.
- Neural language models achieve higher semantic similarity than Markov-based models for the same cost.
- Improved performance comes with higher computational complexity.
- Character-erasure channels significantly degrade prediction performance.
- Huffman coding reduces the required transmission cost for achieving a target semantic similarity.

---

## Paper Links

### IEEE
[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10615608)


