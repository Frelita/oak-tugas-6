# oak-tugas-6

# Bagian Kiri: Multiprocessor Symmetric
"Bagian kiri gambar ini menunjukkan arsitektur Multiprocessor Symmetric. Di sistem ini, ada beberapa prosesor yang setara — semua prosesor bisa langsung mengakses main memory dan perangkat input/output melalui satu bus. Setiap prosesor juga memiliki cache sendiri untuk menyimpan data sementara, agar proses lebih cepat.

Karena semua prosesor setara, mereka bisa berbagi tugas dan bekerja bersama-sama dalam memproses berbagai aplikasi. Namun, karena mereka berbagi bus dan memory, kalau banyak prosesor aktif bersamaan, bisa terjadi bottleneck atau kemacetan akses data. Sistem ini cocok untuk pekerjaan berat yang butuh banyak pemrosesan paralel seperti server besar atau superkomputer."

# Bagian Kanan: Multiple Processor
"Bagian kanan gambar menunjukkan arsitektur Multiple Processor. Pada sistem ini, terdapat satu CPU utama yang langsung berhubungan dengan main memory. CPU utama ini mengatur kerja dari beberapa CPU lainnya. CPU-CPU tambahan tidak langsung akses memory, mereka hanya menerima tugas dari CPU utama.

Di sistem seperti ini, ada pembagian peran yang lebih jelas, CPU utama bertindak sebagai pengontrol, sementara CPU lain membantu menjalankan proses. Arsitektur ini biasanya lebih sederhana pengelolaannya, tapi juga membuat sistem sangat bergantung pada CPU utama."
