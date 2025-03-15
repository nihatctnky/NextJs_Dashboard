# 🚀 Admin Dashboard

Bu proje **Next.js, TypeScript ve TailwindCSS** kullanılarak geliştirilmiş **Admin Dashboard** uygulamasıdır. Kullanıcı ve ürün yönetimi yapabilir, grafiksel analizler ile verileri görüntüleyebilirsiniz.

---

## 📌 Proje Özellikleri

- ✅ **Ürün Yönetimi**: Ürün ekleme, düzenleme, silme
- ✅ **Resim Ekleme**: Ürünleri URL ile resim ekleyerek katalog oluşturma
- ✅ **Kullanıcı Yönetimi**: Kullanıcıları görüntüleme, silme, modal yapısı
- ✅ **Grafikler ile Analiz**:

- Doughnut Grafiği: Ürün kategorilerini ve stok durumlarını değerlendirme
- Line Grafiği: Satış oranlarını analiz etme
- ✅ **Sipariş Takibi**: Siparişlerin yönetimi
- ✅ **Toastify Bildirimleri**: Yapılan işlemlerin okunaklı hale getirilmesi
- ✅ **JSON Server**: Veri çekme işlemleri için kullanıldı
- ✅ **Chart.js Kullanımı**: Grafik verileri **react-chartjs-2** kütüphanesiyle sağlandı

---

## 📦 Kullanılan Kütüphaneler ve Açıklamaları

- **chart.js (^4.4.8)** → Grafik çizimlerini sağlamak için kullanılan güçlü bir kütüphane.
- **json-server (^1.0.0-beta.3)** → Sahte bir REST API oluşturmak ve veri çekmek için kullanılan hafif bir sunucu.
- **millify (^6.1.0)** → Büyük sayıları kısa ve okunaklı hale getirmek için kullanılan yardımcı kütüphane.
- **next (15.2.2)** → React tabanlı, hızlı ve ölçeklenebilir web uygulamaları geliştirmek için kullanılan framework.
- **react (^19.0.0)** → Kullanıcı arayüzleri oluşturmak için kullanılan popüler JavaScript kütüphanesi.
- **react-chartjs-2 (^5.3.0)** → Chart.js kütüphanesini React projelerinde kullanmayı kolaylaştıran bileşenler.
- **react-dom (^19.0.0)** → React bileşenlerini tarayıcı DOM’una bağlayan kütüphane.
- **react-icons (^5.5.0)** → Popüler ikon setlerini React uygulamalarında kullanmayı sağlayan kütüphane.
- **react-toastify (^11.0.5)** → Kullanıcıya bildirim göstermek için kullanılan popüler kütüphane.

---

# 🌎 Admin Dashboard

This is an **Admin Dashboard** application built with **Next.js, TypeScript, and TailwindCSS**. You can manage users and products, and visualize data using interactive charts.

---

## 📌 Features

- ✅ **Product Management**: Add, edit, and delete products
- ✅ **Image Upload**: Add product images via URL and create a catalog
- ✅ **User Management**: View, delete, and manage users via modal
- ✅ **Data Visualization**:

- Doughnut Chart: Track product categories and stock details
- Line Chart: Analyze sales data
- ✅ **Order Tracking**: Manage orders efficiently
- ✅ **Toastify Notifications**: Improve readability of system updates
- ✅ **JSON Server**: Used for data fetching
- ✅ **Chart.js**: Implemented via **react-chartjs-2**

---

## 📦 Dependencies & Descriptions

- **chart.js (^4.4.8)** → A powerful library for creating charts and graphs.
- **json-server (^1.0.0-beta.3)** → A lightweight server to create a mock REST API.
- **millify (^6.1.0)** → A utility to format large numbers into readable strings.
- **next (15.2.2)** → A React-based framework for building fast and scalable web applications.
- **react (^19.0.0)** → A popular JavaScript library for building user interfaces.
- **react-chartjs-2 (^5.3.0)** → A wrapper for using Chart.js in React applications.
- **react-dom (^19.0.0)** → A library to render React components into the browser DOM.
- **react-icons (^5.5.0)** → A package that provides popular icon sets for React applications.
- **react-toastify (^11.0.5)** → A notification library for displaying toast messages in React.

## 🚀 Setup & Run

1. **Clone the repository**

   ```sh
   git clone https://github.com/your-username/admin-dashboard.git
   cd admin-dashboard
   ```

2. **Install dependencies**

   ```sh
   npm install
   ```

3. **Start JSON Server**

   ```sh
   npx json-server --watch db.json --port 5000
   ```

4. **Run the project**

   ```sh
   npm run dev
   ```

---

## 📸 Live Demo 📸

![](dashboard.gif)
