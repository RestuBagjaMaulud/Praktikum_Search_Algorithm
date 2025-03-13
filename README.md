# Praktikum Algoritma Pencarian (Search Algorithms)

## Deskripsi Proyek
Proyek ini mengimplementasikan tiga algoritma pencarian graf dalam Python: Depth-First Search (DFS), Breadth-First Search (BFS), dan Uniform Cost Search (UCS). DFS menelusuri graf secara mendalam dengan rekursi sebelum kembali (backtracking). BFS menggunakan antrian untuk menelusuri graf secara luas, mengunjungi simpul-simpul terdekat terlebih dahulu. Sementara itu, UCS adalah varian BFS yang mempertimbangkan bobot sisi, memastikan jalur dengan biaya terendah ditemukan menggunakan antrian prioritas. Ketiga algoritma ini menunjukkan berbagai pendekatan dalam pencarian jalur dan traversal graf.

## Penjelasan Setiap Algoritma
- Depth First Search (DFS): Algoritma pencarian yang mengeksplorasi sejauh mungkin setiap cabang sebelum kembali ke simpul sebelumnya.
- Breadth First Search (BFS): Algoritma pencarian yang mengeksplorasi simpul pada satu level sebelum bergerak ke level berikutnya.
- Uniform Cost Search (UCS): Algoritma pencarian berbasis biaya yang selalu mengeksplorasi simpul dengan biaya terendah terlebih dahulu.

## Cara Menjalankan Code di Google Colab
1. Buka Google Colab dan buat notebook baru.
2. Clone repository ini ke Google Colab dengan menjalankan perintah berikut: !git clone https://github.com/username/repository-name.git
3. Masuk ke folder repository
4. Pastikan semua dependensi telah diinstal sebelum menjalankan kode: !pip install -r requirements.txt
5. Jalankan salah satu skrip algoritma dengan perintah berikut, misalnya: !python dfs.py
