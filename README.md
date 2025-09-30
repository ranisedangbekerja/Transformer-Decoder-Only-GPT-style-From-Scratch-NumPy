# Transformer Decoder-Only (GPT-style) From Scratch — NumPy
Rani Nirmala Prakoso (22/493982/TK/54153)

Klik [Laporan](https://docs.google.com/document/d/143Yp9bOPVNyE9Gfw42_arzxL19WM01B1AUsxfHUoxGk/edit?usp=sharing) untuk melihat penjelasan implementasi secara singkat

Implementasi **Transformer Decoder-Only (GPT-style)** dari nol menggunakan **NumPy**.  
Proyek ini merupakan tugas kuliah untuk memahami arsitektur Transformer dengan membangun forward pass lengkap tanpa library deep learning (PyTorch/TensorFlow).

## ✨ Fitur
- Token Embedding
- Positional Encoding (sinusoidal)
- Scaled Dot-Product Attention dengan **causal mask**
- Multi-Head Self-Attention
- Feed Forward Network (FFN)
- Residual Connection + Layer Normalization (pre-norm)
- Output Layer (proyeksi ke ukuran vocab + softmax)
- **Bonus:**
  - Visualisasi attention (heatmap per-head, histogram distribusi, statistik per layer)
  - Opsi **weight tying** (embedding ↔ output projection)

## 📂 Struktur
- `transformer_from_scratch_RNP_colab.ipynb` → Implementasi dasar dan bonus (visualisasi & analisis statistik)
- `Laporan_Transformer_FromScratch_RNP.pdf` → laporan singkat (2 halaman)

## 🚀 Cara Menjalankan
1. Clone repo:
   ```bash
   git clone https://github.com/username/transformer-from-scratch.git
   cd transformer-from-scratch

2. or Open [Google Colabs](https://colab.research.google.com/drive/1iX1fnLK2eAZ0RHgXzGKs4orT5To6xoAq?usp=sharing) Link
