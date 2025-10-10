
````markdown
#TUGAS_CRAWLING_PEMROSESANTEKS_A  
*Uncover Insights Faster with Automated Text Extraction*

![last-commit](https://img.shields.io/github/last-commit/lenzii02/Tugas_Crawling_PemrosesanTeks_A?style=flat&logo=git&logoColor=white&color=0080ff)
![repo-top-language](https://img.shields.io/github/languages/top/lenzii02/Tugas_Crawling_PemrosesanTeks_A?style=flat&color=0080ff)
![repo-language-count](https://img.shields.io/github/languages/count/lenzii02/Tugas_Crawling_PemrosesanTeks_A?style=flat&color=0080ff)

---

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)

---

## Overview
Proyek ini merupakan tugas untuk melakukan **Crawling/Scraping data teks** dari sumber online, lalu menjalankan **proses pemrosesan teks (preprocessing)** yang meliputi:
- Filtering (menghapus angka, simbol, hashtag, mention, dan stopword)
- Case folding (mengubah semua huruf menjadi huruf kecil)
- Stemming (mengubah kata ke bentuk dasarnya)
- Tokenizing (memecah kalimat menjadi kata per kata)

Tujuan utamanya adalah untuk memahami tahapan awal *Natural Language Processing (NLP)* dan menghasilkan data yang bersih siap untuk analisis lebih lanjut.

---

## Getting Started

###  Prerequisites
Proyek ini dijalankan menggunakan:
- **Jupyter Notebook**
- Python 3.x
- Library: `requests`, `BeautifulSoup4`, `re`, `Sastrawi`, `nltk`, dan `pandas`

---

### Installation

1. **Clone repository:**
   ```bash
   git clone https://github.com/lenzii02/Tugas_Crawling_PemrosesanTeks_A
````

2. **Masuk ke folder proyek:**

   ```bash
   cd Tugas_Crawling_PemrosesanTeks_A
   ```

3. **Instal :**

   ```bash
   pip install -r requirements.txt
   ```

   *(atau tambahkan manual jika tidak ada file requirements)*

---

### Usage

Jalankan proyek di Jupyter Notebook:

```bash
jupyter notebook Tugas_Crawling_PemrosesanTeks_A.ipynb
```

Langkah umum:

1. Jalankan cell **crawling/scraping** untuk mengambil data teks.
2. Simpan hasil mentah ke file `raw_data.txt`.
3. Jalankan cell **preprocessing** (filtering, case folding, stemming, tokenizing).
4. Simpan hasil bersih ke `cleaned_data.txt`.

---

### Testing

Proyek ini dapat diuji dengan menjalankan ulang tiap cell notebook dan memastikan:

* Data mentah berhasil diambil.
* Data hasil preprocessing sudah bersih (tanpa simbol dan stopword).

Contoh:

```bash
python test_preprocessing.py
```
