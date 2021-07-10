# USE DATABASE DAN SHOW TABLE, PILIH TABLE YANG AKAN DI BACKUP
![tabel](https://user-images.githubusercontent.com/81984937/125171117-ad363e00-e1dc-11eb-9081-8fc3e6de2e39.JPG)

# BACKUP DAN RECOVERY TABLE 
![bayar](https://user-images.githubusercontent.com/81984937/125171135-c9d27600-e1dc-11eb-8eea-65242e7ea890.JPG)

# BACKUP MENGGUNAKAN MYSQLDUMP
![dump](https://user-images.githubusercontent.com/81984937/125171151-e66eae00-e1dc-11eb-9ede-3cf51fe81396.JPG)
![dump2](https://user-images.githubusercontent.com/81984937/125171155-e8387180-e1dc-11eb-930e-584875e2b099.JPG)

# SCRIPT  CRONJOB BACKUP OTOMATIS SETIAP JAM 12 MALAM
0 0 * * 7 mysqldump -u root -p78545 arrafijehansyah_311910668 >  arrafijehansyah_311910668_bckup.sql
