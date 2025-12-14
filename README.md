

# 🧠 Variational Autoencoder (VAE) with L1 Distance

This project implements a **Variational Autoencoder (VAE)** where the reconstruction loss is based on **L1 distance (Mean Absolute Error)** instead of the more common MSE or BCE loss.

The notebook demonstrates both the **theoretical idea** and the **practical implementation** using deep learning.

---

## ✨ Key Highlights

* 🔬 Custom **VAE architecture**
* 📏 Uses **L1 (MAE) reconstruction loss**
* 🧮 KL-divergence regularization
* 📉 Stable training behavior
* 🧪 Notebook-based experimentation and visualization

---

## 📂 Project Structure

```
.
├── Variational_auto_encoder_with_L1_distance.ipynb
├── README.md
└── requirements.txt   # optional
```

---

## 🧠 What is Different About This VAE?

Most VAEs use:

* **Binary Cross-Entropy (BCE)** → for normalized images
* **Mean Squared Error (MSE)** → sensitive to outliers

This project instead uses:

### ✅ **L1 Distance (Mean Absolute Error)**

Advantages:

* More **robust to outliers**
* Encourages **sharper reconstructions**
* Often better for real-valued data

---

## 🧮 Loss Function

The total VAE loss is:

```
Total Loss = L1 Reconstruction Loss + KL Divergence
```

Where:

* **L1 Loss** measures reconstruction quality
* **KL Divergence** enforces latent space regularization

---

## 🛠️ Requirements

* Python 3.8+
* PyTorch (or TensorFlow, depending on your implementation)
* NumPy
* Matplotlib
* Jupyter Notebook

Example installation:

```bash
pip install torch numpy matplotlib
```

---

## ▶️ How to Run

1. Clone the repository
2. Start Jupyter Notebook

   ```bash
   jupyter notebook
   ```
3. Open:

   ```
   Variational_auto_encoder_with_L1_distance.ipynb
   ```
4. Run cells sequentially

---

## 📊 Experiments Included

* Encoder–decoder architecture
* Latent space sampling
* Reconstruction visualization
* Training loss tracking
* Comparison behavior vs traditional losses

---

## 🧯 GitHub Rendering Note

If GitHub shows:

```
Invalid Notebook: metadata.widgets missing state
```

✔️ The notebook is **not broken**
❌ GitHub preview has limitations

✅ **Solution:**
Download the notebook and open it locally (or use the fixed version provided).

---

## 📌 Use Cases

* Representation learning
* Anomaly detection
* Image reconstruction
* Latent space exploration
* Research and experimentation

---

## 🚀 Future Improvements

* Latent space visualization (t-SNE / PCA)
* L1 vs L2 loss comparison
* Conditional VAE extension
* Quantitative reconstruction metrics

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🙌 Acknowledgements

Inspired by foundational work on **Variational Autoencoders** and modern deep learning practices.

