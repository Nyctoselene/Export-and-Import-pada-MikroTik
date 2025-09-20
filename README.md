# Export dan Import pada mikrotik 

Melakukan export dan import konfigurasi pada MikroTik:
1. Export konfigurasi MikroTi
New Terminal > ketik perintah export compact file=”Backup-Config"

       [admin@MikroTik] > export compact file="Backup-Config"

Hasil perintah Export berupa file dengan ekstensi *.rsc. File ini dapat dibuka dan diedit menggunakan text editor

2. Import konfigurasi MikroTik
New Terminal > ketik perintah import file-name=”Basic Config”

        [admin@MikroTik] > import file-name="Basic-Config"
 
Kesimpulan: 
Perintah export tidak akan menyimpan/menampilkan konfigurasi account dan password internal user MikroTikOS

Sekian yang dapat saya sampaikan, mohon maaf apabila ada salah kata atau kekurangan dalam penyampaian. Akhir kata, Wassalam. 
