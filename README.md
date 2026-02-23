<div align="center">
  
# 💒 KarWed | Profesyonel Düğün Salonu Yönetim Sistemi

[![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)](https://dotnet.microsoft.com/)
[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![MVC](https://img.shields.io/badge/MVC-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**Düğün ve etkinlik mekanları için tasarlanmış, kapsamlı, modern ve kullanıcı dostu bir SaaS çözümüdür.**
KarWed ile rezervasyonları yönetin, finansal takibinizi yapın ve müşteri ilişkilerinizi bir üst seviyeye taşıyın.

</div>

---

## ✨ Özellikler

- **📅 Akıllı Rezervasyon Yönetimi:** Tarih çakışmalarını önleyen takvim entegrasyonu.
- **💰 Finansal Takip:** Gelişmiş gelir/gider tabloları ve otomatik makbuz oluşturma.
- **🛡️ Güvenli Altyapı:** Kimlik doğrulama, yetkilendirme ve rol yönetimi (Admin/Personel).
- **📱 Responsive Tasarım:** Tüm cihazlarda (Mobil, Tablet, Masaüstü) kusursuz görünüm.
- **📊 Gelişmiş Raporlama:** SP (Stored Procedure) destekli, özelleştirilebilir yazdırma düzenine sahip detaylı raporlar.

## 🚀 Teknolojik Altyapı

Proje, modern ve ölçeklenebilir teknolojiler kullanılarak geliştirilmiştir:

- **Backend:** C# & .NET Core MVC
- **Veritabanı:** MS SQL Server / SQLite (Entity Framework Core)
- **Güvenlik:** ASP.NET Core Identity
- **Frontend / Arayüz:** HTML5, CSS3, JavaScript
- **Mimari:** Model-View-Controller (MVC) Tasarım Deseni

## 📂 Proje Yapısı

```bash
📦 KarWed
├── 📁 Controllers    # İş mantığı ve yönlendirmeleri yöneten sınıflar
├── 📁 Models         # Veritabanı tabloları ve iş nesneleri
├── 📁 ViewModels     # View'lara veri taşıyan özel modeller (Örn: RaporViewModel)
├── 📁 Views          # Kullanıcı arayüzü dosyaları (.cshtml)
├── 📁 Data           # Veritabanı bağlamı (DbContext) ve Data Provider'lar
├── 📁 Migrations     # Entity Framework veritabanı şema güncellemeleri
├── 📁 Services       # Dış servisler ve API entegrasyonları
├── 📁 Hubs           # SignalR bağlantı noktaları (Gerçek zamanlı işlemler için)
└── 📁 wwwroot        # CSS, JS, Görüntüler ve kütüphaneler (Statik dosyalar)
```

## 🛠️ Kurulum İşlemleri

Projeyi yerel ortamınızda (localhost) çalıştırmak için aşağıdaki adımları izleyin:

### Gereksinimler
- [.NET SDK](https://dotnet.microsoft.com/download) (En güncel sürüm önerilir)
- IDE (Visual Studio, VS Code veya JetBrains Rider)
- SQL Server (Eğer MS SQL kullanılacaksa)

### Adımlar

1. Projeyi bilgisayarınıza klonlayın:
   ```bash
   git clone https://github.com/EnesKaraca44/KarWed.git
   ```
2. Proje dizinine gidin:
   ```bash
   cd KarWed
   ```
3. Gerekli bağımlılıkları yükleyin:
   ```bash
   dotnet restore
   ```
4. `appsettings.json` dosyasını açarak `DefaultConnection` adımını kendi veritabanı ayarlarınıza göre yapılandırın.

5. Veritabanını oluşturun ve migration'ları uygulayın:
   ```bash
   dotnet ef database update
   ```
6. Projeyi başlatın:
   ```bash
   dotnet run
   ```

## 👨‍💻 Geliştirici

**Enes Karaca**
- GitHub: [@EnesKaraca44](https://github.com/EnesKaraca44)

---
*Bu proje, etkinlik mekanı yönetimi süreçlerini dijitalleştirmek ve kolaylaştırmak amacıyla geliştirilmiştir.*
