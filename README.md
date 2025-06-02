# Otomotiv B2B ERP Sistemi

Web tabanlı, modüler bir B2B ERP çözümüdür. Otomotiv sektörüne özel olarak tasarlanmıştır.

## 🚀 Özellikler
- ASP.NET Core ile yazılmış backend
- React + TailwindCSS ile yazılmış modern ve responsive frontend
- MSSQL ve Firebird veritabanı uyumluluğu
- Kullanıcı rol yönetimi (Admin, Bayi, Plasiyer, Muhasebe)
- OEM numarası ve çapraz kod arama destekli ürün modülü
- Excel ile toplu ürün yükleme / dışa aktarma
- Sanal POS ve kargo API entegrasyon altyapısı
- Fatura, irsaliye, fiş yönetimi

## 🔧 Kurulum
### Backend
```bash
cd backend
dotnet restore
dotnet ef database update
dotnet run
