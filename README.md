<h1 align="center">🏢 CompanySystem</h1>

<p align="center">
  Kurumsal şirketler için geliştirilen, kapsamlı ve modüler C# şirket yönetim sistemi.<br>
  Kullanıcı yönetimi, finansal işlemler, görev takibi, departman yapısı ve çok daha fazlası.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/.NET-8.0-blue.svg" />
  <img src="https://img.shields.io/badge/status-active-brightgreen.svg" />
  <img src="https://img.shields.io/badge/license-MIT-lightgrey.svg" />
</p>

---

## 🎯 Genel Bilgi

**CompanySystem**, C# ve ASP.NET Core ile geliştirilen, şirketlerin operasyonel süreçlerini tek panelden yönetmesini sağlayan açık kaynaklı bir platformdur.

- 👥 Personel / kullanıcı yönetimi
- 🧾 Fatura, kasa, gelir/gider modülleri
- 📅 Görev ve toplantı takibi
- 🏢 Departman ve yetkilendirme sistemi
- 📈 Dashboard ve raporlama

---

## 🧰 Teknoloji Yığını

| Teknoloji           | Açıklama                           |
|---------------------|------------------------------------|
| ASP.NET Core        | Backend & API                      |
| Entity Framework    | ORM / Database bağlantısı          |
| SQL Server / SQLite | Veritabanı                         |
| Razor Pages / Blazor| UI / Frontend                      |
| Identity / JWT      | Kimlik doğrulama & yetkilendirme   |

---

## ⚙️ Kurulum

### Gereksinimler

- .NET 8 SDK
- SQL Server (veya SQLite)
- Visual Studio 2022+ veya Rider

### Kurulum Adımları

```bash
# Depoyu klonla
git clone https://github.com/fikretardabulut/CompanySystem.git
cd CompanySystem

# (Opsiyonel) Veritabanı yapılandırmasını güncelle
# appsettings.json veya appsettings.Development.json

# Veritabanını oluştur
dotnet ef database update

# Uygulamayı çalıştır
dotnet run
