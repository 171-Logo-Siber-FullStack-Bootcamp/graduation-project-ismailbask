# E commerce Website Project

# Description

**For this project;**
- A homepage showing the products,
- A page where users can register and log in,
- A profile page,
- A "my products page" has been created where the user will add products, update the product and delete the product,
- Searching by products,
- Operations such as searching for products according to categories were carried out.

## Used technologies
**On the frontend side;**
- **vue** and **vuetify** were used

**On the backend side;**
- nodejs,
- express,
- cloudinary (_where product photos are stored_),
- elasticsearch (_Elasticsearch was used to search for products_)
- Used sessionstorage for user login.
 
**On the database side;**
- postgre sql used

**Requirements**
- For Elasticsearch and Kibana to work on Windows 10, version 7.15.2 must be installed.

**Relational database:**

![database_erd](https://user-images.githubusercontent.com/87307720/160713671-3da2ff29-6213-4b2b-bd47-f0ae6525c816.png)

![pg_database1](https://user-images.githubusercontent.com/87307720/160715136-b77f537d-266a-4772-9e04-d8433f95db35.png)
![pg_database2](https://user-images.githubusercontent.com/87307720/160715226-22c7facb-3fb7-4119-bebb-448de06c766e.png)
![pg_database3](https://user-images.githubusercontent.com/87307720/160715318-327016a9-a34c-43ec-8ab1-1ff5f1fdcc94.png)

## Installation

**Install dependencies in backand file**


```sh
npm i
```
elasticsearch and kibana to run
```sh
C:\your_root\elasticsearch-7.15.2\bin>elasticsearch.bat
C:\your_root\kibana-7.15.2-windows-x86_64\bin>kibana.bat
```
and run the server
```sh
npm run dev
```

**Install dependencies in frontand file**
```

npm install

```


**Compiles and hot-reloads for development**
```
npm run serve
```
## Project video:

[Youtube] – Proje Video

[Youtube]: https://www.youtube.com/watch?v=62DAuaObmeY> (sayfanın en sonuna eklenmelidir.)





[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7469431&assignment_repo_type=AssignmentRepo)
# Logo Siber Güvenlik ve Ağ Teknolojileri Full Stack Bootcamp Bitirme Projesi

- Tek sayfadan oluşacak bir e-ticaret sitesi

## Proje Detayları:

- Vue.js ile tek sayfadan oluşan bir e-ticaret sistemi tasarlayacağız.
- 10 adet kategori olacak.
- Tüm backend işlemleri Node.js ile yapılacak.
- Arayüz Vue.js ile yapılacak.
- Ürünler API’den çekilecek. İstenilen API kullanılabilir. API’yi kendiniz tasarlayabilirsiniz.
- ElasticSearch ile ana sayfada arama alanı yapılacak.
- Winston kullanılacak.
- Ürüne tıkladığımız zaman bir kutusu ekrana gelecek ve ürünün bilgileri yer alacak.
- Relational veritabanı için PostgreSQL kullanılacak.

