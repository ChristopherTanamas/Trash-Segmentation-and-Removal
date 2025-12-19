# Perbandingan Model Segmentasi untuk Masking Sampah dan Generatif untuk Menghilangkan Objek Sampah pada Gambar
Anggota Kelompok:
1. 222200153 - Christopher Nathaniel Tanamas
2. 222102311 - Elaine Evelyn
3. 222102176 - Grace Calista Lim
4. 222101393 - Jemima Alithia Sigar

Proyek ini berangkat dari ketidaksadaran masyarakat akan pentingnya menjaga kebersihan lingkungan. Sampah yang sering dianggap hal kecil berdampak besar pada kenyamanan, estetika, dan kesehatan masyarakat. Dengan memanfaatkan teknologi computer vision untuk mendeteksi dan mensimulasikan keadaan lingkungan tanpa sampah, proyek ini dapat menunjukkan perbedaan nyata antara lingkungan kotor dan bersih. Melalui pendekatan ini, diharapkan masyarakat dapat lebih sadar bahwa lingkungan yang rapi dan bersih harus dijaga bersama.

Dalam pemodelannya, kami membandingkan dua model segmentasi, yaitu Segformer dan DPT untuk mensegmentasi sampah secara akurat. Hasil masking ini kemudian digunakan oleh dua model generatif, yaitu Stable Difussion dan ControlNet untuk menghapus sampah dan mengisi area kosong dengan latar belakang yang natural. Pendekatan dua tahap ini memungkinkan sistem membersihkan gambar tanpa merusak detail penting lainnya.

Dataset yang digunakan adalah TACO (Trash Annotations in Context) untuk melatih model diskriminatif (segmentasi) maupun generatif.
