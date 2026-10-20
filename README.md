# Tugas Analisis 1 — Transformer & Self-Attention

Repositori ini berisi pengerjaan Tugas Analisis 1 pada praktikum Pekan 5 mata kuliah yang membahas Transformer dan Self-Attention.

## Isi Repositori

- `lab_pekan_05_transformer_self_attention.py` — kode Python untuk eksperimen Self-Attention.
- `attention_heatmap_pekan_05.png` — visualisasi distribusi bobot perhatian pada kalimat Bahasa Indonesia.
- `Laporan_Tugas_Analisis_1_Transformer.pdf` — laporan analisis, jika file PDF turut diunggah.

## Teknologi

- Python 3.11.9
- NumPy
- Matplotlib

## Eksperimen

Kalimat yang digunakan:

“Hewan itu tidak menyeberangi jalan karena ia terlalu lelah.”

Eksperimen menampilkan distribusi bobot Self-Attention dalam bentuk heatmap untuk mengamati hubungan perhatian antara token.

## Cara Menjalankan

Pastikan Python dan pustaka yang diperlukan telah terpasang.

```bash
python -m pip install numpy matplotlib
python lab_pekan_05_transformer_self_attention.py
```

## Catatan

Hasil heatmap merupakan demonstrasi perhitungan berdasarkan implementasi pada skrip praktikum, bukan bukti bahwa model bahasa terlatih telah memahami makna kalimat secara nyata.
