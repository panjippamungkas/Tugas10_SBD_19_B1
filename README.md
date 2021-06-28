# Tugas 10 SBD 19-B1

```
Nama        : Panji Putra Pamungkas
Nim         : 311910587
Kelas       : TI. 19. B1
Mata Kuliah : Sistem Basis Data - Tugas 10
```

### Back up dan restore database.

Masuk ke dalam data base nama_nim.

![1](https://user-images.githubusercontent.com/81550517/123598382-a42d9000-d81e-11eb-9e45-dac91a1b0c06.png)

1. Backup dan restore dengan SQL

  - Melakukan lock pada table yang di inginkan (optional)

![2](https://user-images.githubusercontent.com/81550517/123598664-f40c5700-d81e-11eb-8f3b-f81d7dcca661.png)

  - Peritah backup pada table yang di inginkan.

![3](https://user-images.githubusercontent.com/81550517/123599261-9c222000-d81f-11eb-9b75-f1c9bd3e7a64.png)

  - File table yang sudah di backup dapat di temukan pada directori C:\xampp\mysql\data\panjiputrapamungkas_311910587

![5](https://user-images.githubusercontent.com/81550517/123599712-1b175880-d820-11eb-85ae-e91027f79e31.png)

  - Proses restore table yang sudah di backup dan hasil nya.

![4](https://user-images.githubusercontent.com/81550517/123599365-b956ee80-d81f-11eb-9f72-6a43f3ce657b.png)

2. Backup dan restore dengan MySQLDump.

  - Peritah backup

![6](https://user-images.githubusercontent.com/81550517/123600174-9bd65480-d820-11eb-8868-838b505a4106.png)

  - Perintah restore

![7](https://user-images.githubusercontent.com/81550517/123601152-8a417c80-d821-11eb-927c-ef7497a9846d.png)

3. Script backup otomatis setiap hari minggu jam 12 malam

``` 0 0 * * 7 mysqldump -u root -p panjiputrapamungkas_311910587 > panjippamungkas_db_backup.sql ```


