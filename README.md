# Day-1--Expedition-33-_Raihan-Maula-Alwafi
Repository ini berisi dokumentasi kegiatan di hari pertama proyek workshop yang membahas dasar-dasar prompt engineering, Git, dan GitHub.
Repository ini bertujuan untuk mendokumentasikan hasil pembelajaran yang telah dilakukan di kegiatan hari pertama proyek workshop, mengenai prompt engineering, git, dan github. 

Kegunaan repository: 
1. Menyimpan rangkuman materi
2. Mendokumentasikan pengetahuan yang telah diperoleh
3. Menyimpan hasil praktik pembuatan proyek dengan AI
4. Mempelajari penggunaan Git dan GitHub untuk mengelola proyek
5. Menjadi referensi pembelajaran

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
From AI to Github 
By: Nugi Farhan 

Objektif hari ini 
1.	Dapat menjelaskan bagaimana prompt ai yang lebih sepsifik dapat mengasilkan yang lebih baik 
2.	Dapat mengidentifikasi repository, commit, branch, dan pull request.
3.	Dapat membedakan apa itu git dan github
4.	Dapat melakukan version controlling 

Prompt engineering 
Cara merancang instruksi agar ai memberikan jawaban yang tepat, relevan, dan layak digunakan 
Prompt adalah instruksi atau masukan yang anda berikan kepada model untuk mendapatkan hasil tertentu
contoh:
1.	Without text 
2.	With context 

Ada beberapa part yang harus dilakukan untuk kasih instruksi ke AI:
1.	Role 
2.	Task
3.	Context 
4.	Format
Ketika mengerjakan proyek skala besar, setiap penggunaan ai harus memiliki context batasan, agar output yang dihasilkan dapat sesuai dengan hasil yang diharapkan 

Keuntungan prompt engineering 
1.	Meningkatkan performa ai model 
2.	Mengurangi bias dan respon yang offensive 
3.	Meningkatkan kontrol dan predictability: 
ketika kita ga kasih batasan ke AI, AI gatau apa yang kita mau. Sehingga kita mempunyai kontrol untuk output yang akan 
1.	Memberikan pengalaman yang lebih baik 
2.	Memberikan pengalaman yang lebih baik 
3.	Meningkatkan kontrol dan predictability: ketika kita ga kasih batasan ke AI, AI gatau apa yang kita mau. Sehingga kita mempunya
4.	Mengurangi bias dan respon yang offensive 
5.	Meningkatkan performa ai model 

GITHUB 
Git adalah version contol sistem yang melacak siapa, kapan, dan apa saja yang sudah di rubah dalam suatu file. Git diciptakan oleh linus torvalds pada tahun 2005. 
3 main area yang harus dipahami saat menggunakan git: 
1.	Working directory 
Adalah salinan dari satu versi proyek yang sedang kamu kerjakan. File file di dalamnya diambil dari database yang tersimpan di direktori git, kemudia ditempatkan di komputer agar dapat digunakan atau di modifikasi.
2.	Staging area
Adalah file yang umumnya berada di dalam direktori git dan berfungsi untuk menyimpan informasi mengenai perubahan apa saja yang akan dimasukan kedalam commit berikutnya. Dalam istilah teknis git, staging area disebut sebagai indeks
3.	Git directory 
Adalah tempat git menyimpan metadata dan object database dari sebuah proyek, bagian ini merupakan komponen terpenting dalam git, karena berisi seluruh m=informasi yang dibutuhkan git untuk mengelola proyek. Ketika kamu melakukan clone repository dari komputer lain, bagian ini lah yang akan disalin 

Git
Sistem version control terdistribusi (DVCS) yang digunakan untuk melacak dan mengelola perubahan kode secara lokal.

GitHub
Platform berbasis web yang digunakan untuk menyimpan repository Git secara online.

Essential git command: 
1.	Git init
mengidentifikasi file atau repository, dan akan track semua file yang ada di git
2.	Git add
memindahkan file ke staging area 
3.	Git commit -m ‘message’ 
menyimpan file ke repository

Essential git to github command: 
1.	Git remote addd <name> <url> 
Add untracked file or unstaged changes 
2.	Git push origin main  
3.	git pull origin main 
