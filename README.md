# IdentityApp – ASP.NET Core Identity User & Role Management

Bu proje, ASP.NET Core Identity altyapısını kullanarak kullanıcı kimlik doğrulama, rol yönetimi, e-posta doğrulama, şifre sıfırlama ve yönetici paneli işlevlerini sunan tam özellikli bir örnek uygulamadır. Uygulama, kurumsal senaryolara uygun şekilde tasarlanmış olup kimlik yönetimi ve yetkilendirme süreçlerinin tamamını uçtan uca göstermektedir.

---

## 📌 Özellikler

### 🔐 Kimlik Yönetimi
- Kullanıcı kayıt  
- E-posta doğrulama (token tabanlı)  
- Parola sıfırlama  
- Login / Logout  
- Hesap kilitleme (Lockout)  
- Başarısız giriş sayısı sıfırlama  
- Ek kullanıcı alanları (FullName)

### 🛡 Rol Yönetimi
- Rol oluşturma  
- Rol düzenleme  
- Role bağlı kullanıcıları listeleme  
- Kullanıcıya rol ekleme / rol kaldırma  

### 🧭 Yönetici Paneli
- Kullanıcı listeleme  
- Yeni kullanıcı oluşturma  
- Kullanıcı bilgilerini düzenleme  
- Parola güncelleme  
- Rol atama  
- Kullanıcı silme  

### 📧 SMTP E-posta Servisi
- HTML formatında e-posta gönderimi  
- Hesap onayı bağlantısı  
- Parola sıfırlama bağlantısı  

---

## 🛠 Kullanılan Teknolojiler

| Teknoloji | Amaç |
|----------|-------|
| **ASP.NET Core MVC** | Web arayüzü |
| **ASP.NET Core Identity** | Kimlik doğrulama & roller |
| **Entity Framework Core** | ORM & veritabanı |
| **SQL Server / LocalDb** | Veritabanı |
| **SMTP** | E-posta gönderimi |
