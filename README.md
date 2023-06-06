# ecommerce-django-project
1. pastikan di lokal sudah terinstall database postgreSQL
2. setting.py -> ubah setingan env properties database ke postgreSQL di lokal
3. lakukan migrate [python manage.py migrate]
4. migrasi data yang ada pada folder backupDatabase. jika menggunakan dbeaver -> klik kanan pada schema table toko_produkitem -> import data -> CSV -> pilih file CSV yang ada di folder backupDatabase -> next -> processed
5. compile service -> jalankan service -> python manage.py runserver