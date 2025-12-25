# Startup-Ideas

## 📌 Proje Hakkında
Startup-Ideas, kullanıcıların girişim fikirlerini paylaşabileceği, beğenebileceği ve puanlayabileceği bir web uygulamasıdır.  
ASP.NET Core MVC ile geliştirilmiş olup Entity Framework Core kullanılarak veritabanı işlemleri gerçekleştirilmiştir.  

## 🚀 Özellikler
- Yeni fikir ekleme (Create)
- Fikirleri listeleme (Read)
- Fikirleri düzenleme (Update)
- Fikirleri silme (Delete)
- Fikirleri beğenme ve puanlama

## 🗄️ Veritabanı
- **SQL Server / SQLite** desteklenmektedir.
- Ana tablo: `Ideas`
  - Id (int, PK, Identity)
  - Title (nvarchar(200), Not Null)
  - Description (nvarchar(max), Not Null)
  - CreatedDate (datetime2, Default: SYSUTCDATETIME())
  - Likes (int, Default: 0)
  - Rating (int, Nullable, 1–5 arası)

## ⚙️ Kullanılan Teknolojiler
- ASP.NET Core MVC
- Entity Framework Core
- Bootstrap (UI için)
- SQL Server / SQLite

## 🌐 Deployment
Proje Render.com üzerinde canlıya alınmıştır.  
Uygulamaya şu adresten erişebilirsiniz:  
👉 [https://startup-ideas.onrender.com](https://startup-ideas.onrender.com)

## 📷 Ekran Görüntüleri
- Veritabanı şeması (SSMS)
- CRUD işlemleri ekranları
- Deployment sonrası canlı uygulama

## 👩‍💻 Geliştirici
- **Adı:** Meryem Kavak  
- **Üniversite:** Yozgat Bozok Üniversitesi  
- **Bölüm:** Bilgisayar Mühendisliği (2. sınıf)
