# Laporan-modul-1-2-praktikum-basis-data
#### Nama : M.Rizal Heris Diyanto
#### kelas : XI-RPL2
#### Absen : 10

### MODUL 1

### 1.Install(XAMPP)DULU
![Screenshot_1 (2)](https://user-images.githubusercontent.com/113566103/190312112-fe5c8dfe-191b-45c3-9795-f254d90c777d.png)
### 2.Aktifkan MySQL di XAMPP
![image](https://user-images.githubusercontent.com/113566103/190312398-1337b22d-be62-4989-a790-e19a47b2cc7f.png)
### 3.terus buka command prompt
![image](https://user-images.githubusercontent.com/113566103/190313553-32b1f162-5e50-4592-951d-8f65845958bd.png)
### *CARA MEMBUAT TITLE
title nama_kalian
![image](https://user-images.githubusercontent.com/113566103/190317515-480e26b4-6a75-497b-95fa-04a9f04a2d57.png)
### 4.masuk direktori mysql

```
cd xampp/mysql/bin
```
![image](https://user-images.githubusercontent.com/113566103/190314723-896065aa-ddd7-42d0-a0d7-15b831f50ead.png)
### 5.ketikan syntax berikut untuk masuk ke mariaDB
```
mysql -u root
```
![image](https://user-images.githubusercontent.com/113566103/190315351-3f5225de-a8b1-4a82-aa11-17595b9cfd8c.png)


## MODUL 2

### 1. cara melihat database
```
show databases;
```
![image](https://user-images.githubusercontent.com/113566103/190316116-5c2556d4-564a-4fcd-90c4-3736911117d9.png)
### 2. 
>## Modul 2
- ### Cara melihat daftar database
```
show databases;
```


![image](https://user-images.githubusercontent.com/92255670/190309535-53e99a2d-071f-4b8a-a6b5-d7f9b6c4cd75.png)

- ### Cara membuat database
```
create database nama_database;
```

![image](https://user-images.githubusercontent.com/92255670/190311061-2402935f-72f3-4e58-91ef-deeaa6ff9c8c.png)

- ### Cara memilih dan masuk dafar database yang kita inginkan 

```
use nama_database;
```

![image](https://user-images.githubusercontent.com/92255670/190312060-2618fb47-49b7-4242-b6ad-1e2ffc73719f.png)

- ### Cara membuat table

```
create table name_table(nama varchar(50)not null,no int(3)not null);
```


![image](https://user-images.githubusercontent.com/92255670/190313876-73124c48-987b-467d-b775-a94d8cd51a73.png)

- ### Cara melihat daftar table

```
show tables;
```

![image](https://user-images.githubusercontent.com/92255670/190314476-a41bb5ec-8393-4404-aa93-6e3f2c6fbff8.png)

- ### Cara melihat isi (struktur) di sebuah tabel

```
desc name_table;
```


![image](https://user-images.githubusercontent.com/92255670/190314810-773e8af2-cd89-4cdf-827b-3016b01c41cf.png)



