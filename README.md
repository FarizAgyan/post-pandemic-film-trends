# ðŸŽ¬ Post-Pandemic Film Trends

Comparing pre and post COVID-19 film industry performance to inform future production and marketing strategy. Project ini merupakan bagian dari **Bootcamp Data Analyst with Excel (EXC175)**.

**Author:** Fariz Agyan

---

## ðŸ“– Overview

Industri film sempat mengalami disrupsi besar akibat pandemi COVID-19. Memahami perubahan pola produksi, pendapatan, dan preferensi penonton pasca pandemi menjadi penting untuk merumuskan strategi produksi dan pemasaran yang lebih adaptif ke depannya.

## ðŸŽ¯ Tujuan Analisis

- Membandingkan performa film sebelum dan sesudah COVID-19
- Mengidentifikasi tren produksi, pendapatan, ROI, dan genre
- Memberikan insight untuk perencanaan produksi dan pemasaran

## â“ Identifikasi Masalah

1. Penurunan drastis jumlah produksi film sesudah COVID-19
2. Penurunan signifikan rata-rata pendapatan dan keuntungan per tahun
3. Perubahan preferensi genre yang memengaruhi strategi pemasaran

## ðŸ—‚ï¸ Dataset

- **Source:** [Full TMDB Movies Dataset 2024 (1M Movies) â€” Kaggle](https://www.kaggle.com/)
- **Sample:** Film rilis tahun 2010â€“2024
- **Key columns:** id, title, release_date, budget, revenue, genre, dll.
- **Split period:**
  - Pre-COVID: 2010â€“2019
  - Post-COVID: 2020â€“2024

## ðŸ” Key Findings

**Financial metrics (Pre vs Post COVID):**

| Metrik | Pre-COVID | Post-COVID | Perubahan |
|---|---|---|---|
| Total Profit | 195.6 M (unit dataset) | 35.4 M | â†“ ~82% |
| Total Budget | 89.2 M | 23.8 M | â†“ ~73% |
| Total Revenue | 284.9 M | 59.2 M | â†“ ~79% |
| Total Film | 2.923 | 519 | â†“ ~82% |
| Average ROI | 3,45x | 2,88x | â†“ |

- Profit tahunan turun lebih dari setengahnya, ke sekitar **$7,1 Milyar**; rata-rata budget produksi anjlok dari **$8,9 Milyar** menjadi **$4,8 Milyar** pasca pandemi.
- Produksi film menurun drastis: dari **231 film** di 2019 menjadi hanya **111 film** di 2020. Tahun paling produktif dalam satu dekade terakhir adalah **2016 (329 film)**.
- Meski jumlah produksi menurun, **ROI tahunan naik ke 238%**, mencerminkan industri menjadi lebih selektif dalam memilih proyek yang bernilai (revenue turun, tapi ROI relatif membaik).
- **Total revenue industri anjlok lebih dari 80%** pada 2020 (dari ~$29,3 Milyar ke ~$5 Milyar) dan belum sepenuhnya pulih hingga akhir periode data.
- **Pergeseran preferensi genre:**
  - **Drama** tetap dominan namun kehilangan pangsa pasar (dari Â±30% ke Â±26%)
  - **Horror** melonjak tajam (+58%), menjadi genre dengan pertumbuhan pangsa pasar tertinggi
  - **Romance** mengalami penurunan pangsa pasar paling dalam
  - Persaingan antar genre menjadi lebih seimbang dibanding sebelum pandemi

## ðŸ’¡ Recommendations

1. **Ubah pendekatan produksi** dari "jualan aman" (genre populer lama) ke eksplorasi genre yang lebih berani dan beragam.
2. **Reinterpretasi genre lama** (Drama, Romance) dengan sudut pandang baru, perpaduan genre, atau karakter/konflik yang lebih relevan dengan penonton pasca pandemi.
3. **Fokus pada genre bermargin tinggi & berpotensi viral** seperti Horror dan Mystery â€” biaya produksi rendah, potensi profit tinggi jika dikemas dengan kampanye pemasaran yang tepat.
4. **Perkuat distribusi digital & pasar global** melalui platform OTT (Netflix, Prime, Disney+) untuk menjangkau audiens global sekaligus membuka revenue stream tambahan dari lisensi jangka panjang.

## ðŸ§° Tools

`Microsoft Excel` â€” data cleaning, pivot table, dan dashboard interaktif

## ðŸ“ Repository Contents

- `Project_Portfolio_-_Dashboard_-_Fariz_Agyan.xlsb` â€” Dashboard interaktif berisi KPI dan 4 chart analisis (tren produksi, revenue, dan pergeseran genre)
- `Project_Portfolio_-_PPT_-_Fariz_Agyan.pptx` â€” Slide presentasi hasil analisis dan rekomendasi

---

*"Industri film pasca-pandemi bukan soal kembali ke masa lalu, tapi soal menciptakan masa depan yang lebih tajam, berani, dan relevan."*