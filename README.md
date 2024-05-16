# ukuran

Domikado berfungsi untuk melakukan monitoring harian pekerjaan setiap individu yang ada dalam tim berbasiskan poin. 
Cara memantau pekerjaan dibagi menjadi dua bagian:
1. Menggunakan webhook push, maka akan terekap semua pesan commit yang muncul.
2. Menggunakan kepuasan berbasiskan user yang bisa di beri rating.
3. Sepakati dahulu dalam satu hari, satu orang bisa menyelesaikan berapa poin? Misal sehari: 7 poin.
4. Buat dahulu format standar kode unik task, dimana setiap segmen kode memiliki arti.

## Yang bisa di commit untuk di ukur
1. Proses belajar: membuat tutorial di markdown file di repo, sehingga berkontribusi membuat tutorial untuk yang lainnya
2. Proses ngoding: satu commit minimal satu buah fungsi baik baru atau perubahan

## Standar Pesan Commit

Format: kodeuniktask||nama fungsi serta detail yang dikerjakan 
Dengan ketentuan:
1. Pada saat scrum meeting, backlog setiap task terdapat kode unik dan poin. 
2. Dimana poin merupakan target perkiraan banyaknya commit yang akan dilakukan untuk menyelesaikan task tersebut. 
3. Sehingga jumlah commit adalah, jumlah langkah yang dilakukan untuk menyelesaikan satu buah task
4. Kode unik task sebaiknya mudah diingat dan berisi info modul dan info lainnya yang informatif
