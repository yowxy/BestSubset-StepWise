#    Analisis Indeks Pembangunan Manusia (IPM)  
### Best Subset Selection & Stepwise Regression

Proyek ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi **Indeks Pembangunan Manusia (IPM)** menggunakan metode pemilihan variabel regresi:

-  Best Subset Selection  
-  Stepwise Regression  

Model dibangun menggunakan pendekatan regresi linear untuk menemukan kombinasi variabel terbaik yang mampu menjelaskan variasi IPM secara optimal.

---

## Tujuan Proyek

1. Mengidentifikasi variabel yang paling berpengaruh terhadap IPM  
2. Membandingkan performa Best Subset dan Stepwise  
3. Mengevaluasi model menggunakan metrik statistik (Adj R², AIC, RMSE)  
4. Melakukan interpretasi hasil secara statistik  

---

## 📁 Struktur Project
├── data/
│ └── dataset.csv
├── notebooks/
│ └── analysis.ipynb
├── src/
│ └── model.py
├── requirements.txt
└── README.md


---

## ⚙️ Instalasi & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/username/nama-repo.git
cd nama-repo

python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows