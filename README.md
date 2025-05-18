# 🕹️ Analisis Sentimen pada Review Game Citampi Stories di Google Play Store
Project Analisis Sentimen *Coding Camp 2025 by DBS Foundation* oleh Hafizha Aghnia Hasya <br>
Proyek ini bertujuan untuk memahami persepsi dan sentimen pengguna terhadap game Citampi Stories berdasarkan review yang mereka berikan di Google Play Store. Analisis dilakukan dengan pendekatan Natural Language Processing (NLP) untuk mengklasifikasikan sentimen (positif, negatif, netral).

## 🧪 Tahapan Analisis
### 1. Pengumpulan Data
- Mengambil data review dari Google Play Store menggunakan scraping tools
- Data diambil pada tanggal 10 April 2025, 5.02 AM

### 2. Pembersihan & Preprocessing Teks
- Menghapus tanda baca, angka, simbol
- Case folding
- Tokenization
- Stopword removal
- Lemmatization

### 3. Labeling Sentimen
- Menggunakan pendekatan lexicon-based untuk mengklasifikasikan sentimen review menjadi positif, negatif, atau netral berdasarkan skor kata-kata dalam teks.

### 4. Analisis Eksploratif & Visualisasi
- Distribusi sentimen
- Wordcloud dari review

### 5. Klasifikasi Sentimen
- Menggunakan 8 skema percobaan pelatihan klasifikasi
- Evaluasi akurasi
- Inference/Testing
