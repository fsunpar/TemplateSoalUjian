# Template Soal Ujian

Dapat digunakan untuk soal UTS/UAS di lingkungan Fakultas Sains. Versi asli dibuat oleh Lionov, versi terbaru oleh Jonathan.

## Cara Pakai

1. Bangkitkan versi LaTeX dari markdown Anda: `$ pandoc README.md -o README.tex`
2. Copy `main.tex` dan `LogoBackground.png` ke direktori Anda
3. Jika Anda menggunakan Git, copy juga `.gitignore`
4. Ubah isi `main.tex` bagian soal, diambil dari `README.tex`
5. Bangkitkan PDF nya `$ pdflatex main.tex`

Hasil pada `main.pdf`
