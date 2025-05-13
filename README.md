# CCTA Coronary Segmentation & Plaque Detection

Proyek ini memuat pipeline analisis citra CT Angiografi Jantung (CCTA) menggunakan deep learning & morfologi. Dataset tidak disimpan di repo ini, tapi diambil otomatis dari Hugging Face.

## 📦 Dataset
Dataset: [MedHK23/CCA](https://huggingface.co/datasets/MedHK23/CCA)

## 🚀 Cara Menjalankan

1. Clone repo:
```bash
git clone https://github.com/namakamu/CCTAAAA.git
cd CCTAAAA

2. Install dependencies:
```bash
pip install -r requirements.txt

3. Salin .env.example → .env, dan isi dengan token Hugging Face:
```bash
HF_TOKEN=hf_xxxxxxxxx

4. Jalankan notebook notebooks/explore_ccta.ipynb
