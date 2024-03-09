# Tubes1_Kelompok56

Kelompok 56 : 
1. Vincent Hasiholan 13518108
2. Devinzen - 13522064

Pembuatan Bot untuk Permainan Diamonds dengan Algoritma Greedy

Bot yang dibuat berfokus pada pengambilan diamond. Bot ini menarget diamond mana yang memiliki poin tertinggi dan jarak terpendek di daerah sekitarnya dalam bentuk diamond (karena pergerakkannya di dalam grid, maka daerah yang dianalisa dari diamond adalah x + y = 5). Setelah itu bot bergerak ke diamond itu. Setelah inverntory penuh, bot bergerak kembali ke base. 

Keterangan tambahan: bot kembali ke base bila time limit sudah mendekati jarak bot ke base. Bot dibangun dengan menggunakan bahasa pemrograman python.

## Cara memasang bot

Install bot starter pack dan ikuti langkah-langkahnya https://github.com/haziqam/tubes1-IF2110-bot-starter-pack.git

clone repository ini
```
git clone https://github.com/Devinzenzhang/Tubes1_Kelompok56
```

replace main.py di bot starter pack dengan main.py dari repository ini (di folder src)

tambahkan sisyphus.py ke folder tubes1-IF2110-bot-starter-pack/game/logic/

## Cara menjalankan bot

```
python main.py --logic Sisyphus --email=your_email@example.com --name=your_name --password=your_password --team etimo
```

Untuk menjalankan beberapa bot ubah file run-bots.bat (untuk windows) atau run-bots.sh (untuk linux) lalu jalankan
