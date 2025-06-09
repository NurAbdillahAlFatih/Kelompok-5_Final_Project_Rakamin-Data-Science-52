# 🔍 Resign Risk Alert System – Data Science Bootcamp Final Project

Proyek ini bertujuan membangun sistem prediksi risiko resign karyawan menggunakan machine learning, dengan fokus pada efisiensi alokasi biaya pelatihan dan retensi karyawan.

## 🎯 Objectives
- Memprediksi probabilitas resign karyawan dari dataset HR Analytics (19.158 kandidat)
- Menyegmentasi risiko resign (high, medium, low) untuk treatment yang tepat sasaran
- Mengurangi turnover rate dari 28.5% ke target ideal 5–10%

## 🧠 Project Summary
- **EDA**: City Development Index & Training Hours berperan besar dalam keputusan resign.
- **Feature Engineering**: Menambahkan variabel `estimated_salary` berdasarkan pendidikan & pengalaman.
- **Modeling**: Logistic Regression (recall 71%) dipilih karena deteksi resign tertinggi dan tidak overfitting.
- **Segmentation**: Berdasarkan threshold 0.45 & 0.70 untuk mengarahkan intervensi.
- **Deployment**: Aplikasi interaktif dibangun dengan Streamlit + GitHub integration.

## ⚙️ Tools & Stack
Python • Pandas • Scikit-learn • SMOTE • Streamlit • GitHub

## 📈 Impact
- Deteksi 3.401 dari 4.790 karyawan yang berpotensi resign (71% recall)
- Estimasi pengurangan turnover rate dari 28.5% → 7.5%
- Strategi T&D dialokasikan ulang: 50% (high), 35% (medium), 15% (low)
