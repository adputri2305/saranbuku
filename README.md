# 📚 SaranBuku – Sistem Rekomendasi Buku Anak Berbasis Review

**SaranBuku** adalah aplikasi cerdas yang merekomendasikan buku anak berdasarkan masukan dalam bentuk bahasa alami, seperti:
- "Saya cari buku lucu untuk anak usia 6 tahun"
- "Buku tentang hewan untuk anak TK"

### 🔗 Download Data

Karena GitHub membatasi ukuran file, dua file besar disediakan melalui Google Drive:

- [Download embedding_buku.npy](https://drive.google.com/file/d/1k-Y4C3GjW4AqP0k4TcEaBG8DnyFndkbb/view?usp=sharing)
- [Download data_buku.json](https://drive.google.com/file/d/1KC3gmxZRM6M32vdvSyKc7FZCPyWZwg94/view?usp=sharing)

Setelah mendownload:
1. Upload kedua file tersebut ke Google Colab menggunakan tombol 📁
2. Atau simpan di Google Drive dan akses lewat kode

Contoh kode akses di Colab:
```python
from google.colab import files
uploaded = files.upload()  # upload manual


Aplikasi ini menggunakan deep learning untuk memahami maksud pengguna dan mencocokkannya dengan data review buku anak.

---

## 🔧 Cara Menjalankan

### 🖥️ Versi Lokal (Python)
1. Clone atau download repo ini
2. Install dependensi:
   ```bash
   pip install -r requirements.txt
