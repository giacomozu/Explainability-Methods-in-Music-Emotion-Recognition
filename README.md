# Explainability Methods in Music Emotion Recognition 🎶

This repository accompanies the Master’s thesis  
**“Explainability Methods in Music Emotion Recognition”**  
*Giacomo Zuliani, Politecnico di Torino, 2025*

📄 [Read the Thesis (PDF)](./Giacomo_s_thesis_2.pdf)

---

## 📚 Thesis Overview

The thesis investigates how **explainability** can be integrated into **Music Emotion Recognition (MER)** models, which are often treated as opaque black boxes.

Two complementary approaches were explored:

1. **Feature-based route**  
   - Uses symbolic and mid-level musical features (e.g., chroma, chords, perceptual descriptors such as dissonance or rhythmic stability).  
   - These features allow interpretable models (linear regression, shallow networks), helping researchers and musicians understand *which* musical properties drive emotional perception.

2. **Perceptual route (ViT + LRP + Sonification)**  
   - A Vision Transformer (ViT) was fine-tuned on spectrograms to classify clips as **Happy** or **Sad**.  
   - Explanations were derived using **Layer-wise Relevance Propagation (LRP)**.  
   - Instead of only visualizing attribution maps, the explanations were **sonified**: louder segments in the reconstructed audio correspond to the parts most relevant for the model’s decision.  
   - This turns explanations into something we can *hear*, making the model’s reasoning more intuitive and perceptually aligned.

---

## 🎧 Listening Examples

A set of audio examples is provided to demonstrate the sonification process.  
You can directly listen to them here:

👉 **[Interactive Audio Examples on GitHub Pages](https://giacomozu.github.io/Explainability-Methods-in-Music-Emotion-Recognition/)**

The examples include:

- ✅ Correctly classified *Happy* and *Sad* excerpts (original vs. sonified).  
- ⚠️ Misclassified excerpts (e.g., a Happy clip predicted as Sad), with both original and sonified versions.  

Together, they represent the four quadrants of the confusion matrix.

---

## 📂 Repository Structure

examples/ # Original and sonified audio clips (WAV)
docs/index.html # Static page with embedded audio players (GitHub Pages)
README.md # Project description (this file)


---

## 🔗 Reference in Thesis

This repository is referenced in the thesis for sonification experiments:

> *“Listening examples (original vs. sonified) are available online at the companion GitHub repository.”*

Citation (APA style):

Zuliani, G. (2025). *Explainability Methods in Music Emotion Recognition* (Master’s thesis, Politecnico di Torino).  
Available at: [https://github.com/giacomozu/Explainability-Methods-in-Music-Emotion-Recognition](https://github.com/giacomozu/Explainability-Methods-in-Music-Emotion-Recognition)

---

## 🚀 Future Work

- Extend the set of examples with more genres and emotions.  
- Combine audio explanations with **visual heatmaps** in a multimodal interface.  
- Explore applications in **music recommendation** and **creative tools for composers**.

---

## 👤 Author

**Giacomo Zuliani**  
Master of Science in Energy Engineering  
Politecnico di Torino (2025)


