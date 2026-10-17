<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1200&color=FF6C37&center=true&vCenter=true&width=700&height=45&lines=GET+%2Fapi%2Fv1%2Fkimdir%2Ffurkan;Mid-Level+Full-Stack+Developer;200+OK+%E2%9C%85)](https://furkanaslan.vercel.app)

<h1>Furkan Aslan · Ben Kimim?</h1>

![Version](https://img.shields.io/badge/version-v1.0.0-FF6C37?style=flat-square) ![Status](https://img.shields.io/badge/status-online-2EA043?style=flat-square) ![Format](https://img.shields.io/badge/format-JSON-0E7AFE?style=flat-square) ![Auth](https://img.shields.io/badge/auth-herkese_açık-8A2BE2?style=flat-square)

</div>

## 📚 Ben Kimim?

**Base URL:** `https://furkanaslan.vercel.app/api/v1`

| # | Endpoint | Ne işe yarar? |
|---|---|---|
| 1 | [`GET /kimdir/furkan`](#kimdir) | Furkan kimdir? Kısa tanıtım ve odak alanları |
| 2 | [`GET /yetenekler`](#yetenekler) | Kullandığı teknolojiler ve araçlar |
| 3 | [`GET /deneyim`](#deneyim) | Çalıştığı yerler ve stajlar |
| 4 | [`GET /egitim`](#egitim) | Üniversite eğitimi |
| 5 | [`GET /sertifikalar`](#sertifikalar) | Aldığı sertifikalar ve katıldığı programlar |
| 6 | [`GET /iletisim`](#iletisim) | Ona nasıl ulaşılır |

<a id="kimdir"></a>

## 1 · Furkan kimdir?

> 📝 **Ne işe yarar?** Furkan'ı kısaca tanıtır: kim olduğu, ne yaptığı ve hangi alanlara odaklandığı.
>
> 📦 **Ne döner?** İsim, unvan, konum, kısa özet ve odak alanları (`data`), ayrıca diğer endpoint'lerin listesi (`meta`).

### 📤 Request

```http
GET /api/v1/kimdir/furkan HTTP/1.1
Host: furkanaslan.vercel.app
Accept: application/json
User-Agent: Merakli-Ziyaretci/1.0
```

### 📥 Response

![Status](https://img.shields.io/badge/Status-200_OK-2EA043?style=flat-square) ![Time](https://img.shields.io/badge/Time-42_ms-0E7AFE?style=flat-square) ![Size](https://img.shields.io/badge/Size-1.1_KB-FF6C37?style=flat-square)

`Body` `Cookies` `Headers (5)` `Test Results (4/4)`

```json
{
  "success": true,
  "status": 200,
  "message": "Furkan kimdir? İşte cevap 👋",
  "data": {
    "name": "Furkan Aslan",
    "username": "Furkanaslnn",
    "title": "Mid-Level Full-Stack Yazılım Geliştirici",
    "location": "Samsun, Türkiye",
    "summary": "Küçük işletmelerden kurumsal yapılara kadar uzanan projelerde uçtan uca sorumluluk alıyorum. React, Next.js ve Node.js ekosistemlerinde web ve mobil uygulamalar geliştirirken sunucu mimarisini (Docker, Nginx, VPS) ve deployment süreçlerini bizzat kuruyorum. Yazılım süreçlerini otomasyon ve yapay zeka entegrasyonlarıyla hızlandırıyor; teknik bilgimi SEO, büyüme stratejileri ve güçlü UI/UX standartlarıyla birleştirerek kullanıcı odaklı ve ticari değer üreten dijital ürünler inşa ediyorum.",
    "focus": [
      "Full-Stack Web & Mobil",
      "Sunucu Mimarisi & Deployment",
      "Otomasyon & Yapay Zeka",
      "UI/UX & SEO"
    ]
  },
  "meta": {
    "version": "1.0.0",
    "endpoints": ["/yetenekler", "/deneyim", "/egitim", "/sertifikalar", "/iletisim"]
  }
}
```

**Yanıt alanları**

| Alan | Açıklama |
|---|---|
| `success` | İstek başarılı mı? `true` = evet |
| `status` | Durum kodu. `200` = her şey yolunda |
| `message` | Kısa bilgi mesajı |
| `data` | Asıl bilgi burada: isim, unvan, özet ve odak alanları |
| `meta` | Ek bilgi: sürüm numarası ve diğer endpoint'lerin listesi |

<details open>
<summary><b>Headers (5)</b></summary>

_Cevapla birlikte gelen ek bilgiler: format, kullanılan teknolojiler ve geliştirici._

```http
HTTP/1.1 200 OK
Content-Type: application/json; charset=utf-8
X-Powered-By: React, Next.js, Node.js
X-Deployed-With: Docker, Nginx, VPS
X-Developer: Furkan Aslan
```

</details>

<details open>
<summary><b>Test Results (4/4)</b></summary>

_Cevabın beklenen özellikleri taşıyıp taşımadığını kontrol eden testler._

```text
PASS  Status code is 200
PASS  Docker, Nginx ve VPS ile deployment hazır
PASS  Otomasyon ve yapay zeka entegrasyonları çalışıyor
PASS  UI/UX ve SEO standartları karşılanıyor
```

</details>

## 👁️ Visualize

> 🖼️ **Ne işe yarar?** Cevabı JSON okumadan, görsel olarak gösterir: hızlı bağlantılar ve kullandığı teknolojilerin ikonları.

<div align="center">

[![WebSite](https://img.shields.io/badge/WebSite-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://furkanaslan.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/furkanaslnn)
[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/developer?id=OrangeHat+Digital&hl=tr)


<br />

<img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,py,vite,redux,tailwind,html,css,figma,docker,nginx,git,mysql,firebase,postman&perline=9" />

</div>

## 📁 Collection

Diğer endpoint'ler. Her biri ayrı bir soruyu cevaplıyor.

<a id="yetenekler"></a>

### 2 · Yetenekler

> 📝 **Ne işe yarar?** Furkan'ın kullandığı teknolojileri ve araçları kategorilere ayırarak listeler.
>
> 📦 **Ne döner?** Frontend & mobil, backend & veritabanı, DevOps, otomasyon & yapay zeka ve metodoloji listeleri. Altında hepsinin ikonlu hali var.

<details open>
<summary><b>GET</b> <code>/api/v1/yetenekler</code> — <code>200 OK</code></summary>

```http
GET /api/v1/yetenekler HTTP/1.1
Host: furkanaslan.vercel.app
```

```json
{
  "success": true,
  "status": 200,
  "data": {
    "frontend_mobil": ["JavaScript", "TypeScript", "React.js", "Next.js", "React Native", "Vite", "Redux", "TailwindCSS", "HTML5", "CSS3", "Figma", "UI/UX"],
    "backend_veritabani": ["Node.js", "Python", "REST API Entegrasyonları", "MySQL", "SQL", "NoSQL", "Firebase"],
    "devops_sistem": ["Docker", "Nginx", "VPS Yönetimi", "Git / Versiyon Kontrolü"],
    "otomasyon_yapay_zeka": ["n8n", "AI Chatbot / Instagram Bot Entegrasyonları", "Yapay Zeka Destekli Yazılım Geliştirme", "SEO Optimizasyonu", "Meta Ads", "Google Analytics"],
    "metodoloji": ["Agile", "Scrum", "Proje Yönetimi", "Problem Çözme", "Takım Çalışması"]
  }
}
```

**Frontend & Mobil**

<img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,vite,redux,tailwind,html,css,figma" />

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![UI/UX](https://img.shields.io/badge/UI%2FUX-FF6C37?style=flat-square)

**Backend & Veritabanı**

<img src="https://skillicons.dev/icons?i=nodejs,py,mysql,firebase" />

![REST API](https://img.shields.io/badge/REST_API-0E7AFE?style=flat-square) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square) ![NoSQL](https://img.shields.io/badge/NoSQL-47A248?style=flat-square)

**DevOps & Sistem**

<img src="https://skillicons.dev/icons?i=docker,nginx,git" />

![VPS](https://img.shields.io/badge/VPS_Yönetimi-2EA043?style=flat-square)

**Otomasyon & Yapay Zeka**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white) ![AI Chatbot](https://img.shields.io/badge/AI_Chatbot-8A2BE2?style=for-the-badge&logo=openai&logoColor=white) ![Instagram Bot](https://img.shields.io/badge/Instagram_Bot-E4405F?style=for-the-badge&logo=instagram&logoColor=white) ![SEO](https://img.shields.io/badge/SEO-2EA043?style=for-the-badge&logo=googlesearchconsole&logoColor=white) ![Meta Ads](https://img.shields.io/badge/Meta_Ads-0866FF?style=for-the-badge&logo=meta&logoColor=white) ![Google Analytics](https://img.shields.io/badge/Google_Analytics-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white)

**Metodoloji & Süreç Yönetimi**

![Agile](https://img.shields.io/badge/Agile-0E7AFE?style=for-the-badge) ![Scrum](https://img.shields.io/badge/Scrum-FF6C37?style=for-the-badge) ![Proje Yönetimi](https://img.shields.io/badge/Proje_Yönetimi-2EA043?style=for-the-badge) ![Problem Çözme](https://img.shields.io/badge/Problem_Çözme-8A2BE2?style=for-the-badge) ![Takım Çalışması](https://img.shields.io/badge/Takım_Çalışması-D14836?style=for-the-badge)

</details>

---

<a id="deneyim"></a>

### 3 · Deneyim

> 📝 **Ne işe yarar?** Furkan'ın çalıştığı yerleri ve stajlarını, rolleriyle ve tarihleriyle birlikte gösterir.
>
> 📦 **Ne döner?** 4 kayıt: şirket, sektör, rol, çalışma dönemi ve yaptığı işlerin özeti.

<details open>
<summary><b>GET</b> <code>/api/v1/deneyim</code> — <code>200 OK</code></summary>

```http
GET /api/v1/deneyim HTTP/1.1
Host: furkanaslan.vercel.app
```

```json
{
  "success": true,
  "status": 200,
  "count": 4,
  "data": [
    {
      "company": "NGSTech",
      "sector": "Yazılım Geliştirme Firması",
      "role": "Full-Stack Yazılım Geliştirici",
      "period": "08/2025 – 08/2026",
      "highlights": [
        "Üniversiteler, belediyeler ve özel sektör firmaları için uçtan uca yazılım çözümleri",
        "Mimari tasarımdan sunucu kurulumuna projelerin tüm yaşam döngüsünde aktif rol",
        "Yapay zekanın geliştirme sürecinde aktif asistan olarak kullanılması"
      ]
    },
    {
      "company": "Whyblue",
      "sector": "Dijital Reklam Ajansı",
      "role": "Dijital Proje Yöneticisi & Geliştirici",
      "period": "01/2026 – 08/2026",
      "highlights": [
        "Kurumsal markaların yazılım gereksinimleri ve dijital pazarlama operasyonlarının yönetimi",
        "Yazılım geliştirmenin kullanıcı deneyimi ve dijital büyüme hedefleriyle birleştirilmesi"
      ]
    },
    {
      "company": "Mobillium",
      "sector": "Digital Product & Experience Studio",
      "role": "Android Geliştirici (Staj)",
      "period": "07/2024 – 08/2024",
      "location": "İstanbul",
      "highlights": [
        "Android uygulama geliştirme temelleri"
      ]
    },
    {
      "company": "CyberNova",
      "sector": "Siber Güvenlik Şirketi",
      "role": "Siber Güvenlik ve Yazılım Geliştirici (Staj)",
      "period": "08/2024 – 09/2024",
      "location": "Samsun",
      "highlights": [
        "Kriptografi ve uygulama geliştirme",
        "Güvenlik temelli algoritmaların gerçek projelere entegrasyonu"
      ]
    }
  ]
}
```

</details>

---

<a id="egitim"></a>

### 4 · Eğitim

> 📝 **Ne işe yarar?** Furkan'ın üniversite eğitimini gösterir.
>
> 📦 **Ne döner?** Bölüm, üniversite, şehir, mezuniyet tarihi ve eğitimde odaklandığı konular.

<details open>
<summary><b>GET</b> <code>/api/v1/egitim</code> — <code>200 OK</code></summary>

```http
GET /api/v1/egitim HTTP/1.1
Host: furkanaslan.vercel.app
```

```json
{
  "success": true,
  "status": 200,
  "data": {
    "degree": "Bilgisayar Mühendisliği",
    "university": "Zonguldak Bülent Ecevit Üniversitesi",
    "city": "Zonguldak",
    "graduated": "06/2025",
    "focus": ["Yazılım geliştirme", "Veri güvenliği", "Proje yönetimi"]
  }
}
```

</details>

---

<a id="sertifikalar"></a>

### 5 · Sertifikalar

> 📝 **Ne işe yarar?** Furkan'ın aldığı sertifikaları ve katıldığı eğitim ve girişimcilik programlarını listeler.
>
> 📦 **Ne döner?** 4 kayıt: program adı, tarihi, düzenleyen kurum ve içeriği.

<details open>
<summary><b>GET</b> <code>/api/v1/sertifikalar</code> — <code>200 OK</code></summary>

```http
GET /api/v1/sertifikalar HTTP/1.1
Host: furkanaslan.vercel.app
```

```json
{
  "success": true,
  "status": 200,
  "count": 4,
  "data": [
    {
      "name": "Siber Vatan BootCamp",
      "date": "Temmuz 2023",
      "location": "Antalya",
      "detail": "10 günlük yoğun eğitim; Trendyol, Barikat, Cyrops ve BG-TEK yöneticilerinin konferans ve etkinlikleri"
    },
    {
      "name": "Siber Vatan Eğitim Sertifikası",
      "date": "Kasım 2022 – Eylül 2023",
      "modules": [
        { "provider": "CYROPS", "topic": "Linux ve CEH" },
        { "provider": "BG-TEK", "topic": "Sızma Testi ve Yetki Yükseltme" },
        { "provider": "BARİKAT", "topic": "Tersine Mühendislik" },
        { "provider": "Siber Vatan", "topic": "Web Güvenliği" }
      ]
    },
    {
      "name": "STARTUP 2025 Girişimcilik Maratonu",
      "date": "25-27 Nisan 2025",
      "organizer": "Zonguldak Teknopark & Marmara Teknokent",
      "role": "Katılımcı"
    },
    {
      "name": "KOSGEB Girişimcilik Eğitimi",
      "date": "03.12.2024",
      "format": "Online"
    }
  ]
}
```

</details>

---

<a id="iletisim"></a>

### 6 · İletişim

> 📝 **Ne işe yarar?** Furkan'a nereden ulaşabileceğini gösterir.
>
> 📦 **Ne döner?** E-posta, web sitesi, GitHub, LinkedIn ve Google Play adresleri. Tıklanabilir halleri yukarıdaki Visualize bölümünde.

<details open>
<summary><b>GET</b> <code>/api/v1/iletisim</code> — <code>200 OK</code></summary>

```http
GET /api/v1/iletisim HTTP/1.1
Host: furkanaslan.vercel.app
```

```json
{
  "success": true,
  "status": 200,
  "data": {
    "website": "https://furkanaslan.vercel.app",
    "github": "https://github.com/Furkanaslnn",
    "linkedin": "https://www.linkedin.com/in/furkanaslnn",
    "googlePlay": "https://play.google.com/store/apps/developer?id=OrangeHat+Digital&hl=tr"
  }
}
```

</details>

## 📊 GitHub İstatistikleri

> 📈 Bu bölüm canlı veridir: GitHub hesabından otomatik çekilir ve kendiliğinden güncellenir.

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Furkanaslnn&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Furkanaslnn&theme=tokyonight&hide_border=true&layout=compact" height="165" />

<img src="https://streak-stats.demolab.com?user=Furkanaslnn&theme=tokyonight&hide_border=true" />

</div>

---

<div align="center">

`GET /api/v1/kimdir/furkan` endpoint'ine şimdiye kadar atılan istek sayısı:

[![Ziyaretçi Sayısı](https://visitcount.itsvg.in/api?id=Furkanaslnn&icon=5&color=3)](https://visitcount.itsvg.in)

</div>
