# 🛍️ ShoppingApp - MERN Stack

ShoppingApp, yeni başlayanların kolayca anlayabileceği bir **MERN Stack** projesidir.  

---

## 🚀 Teknolojiler

Bu projede kullanılan teknolojiler:

- MongoDB - NoSQL Veritabanı  
- Express.js - Node.js Web Framework  
- React - Kullanıcı Arayüzü  
- Node.js - Sunucu Tarafı  

---

## 📦 Kurulum

Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsin:

1️⃣ Depoyu Kopyala
2️⃣ Bağımlılıkları Yükle

Hem backend (Node.js) hem de frontend (React) bağımlılıklarını yüklemek için:

# Backend için

cd backend
npm install

# Frontend için

cd ../frontend
npm install

3️⃣ MongoDB Bağlantısını Ayarla (.env Dosyası)
Backend klasöründe bir .env dosyası oluştur ve aşağıdaki değişkenleri ekle:

MONGO_URI=mongodb://127.0.0.1:27017/mydatabase
PORT=5000
NODE_ENV=development

🏃‍♂️ Projeyi Çalıştır

Önce backend'i çalıştır:

cd backend
npm start
Sonra frontend'i başlat:

cd ../frontend
npm run dev
Artık proje http://localhost:3000 adresinde çalışacaktır! 🚀
