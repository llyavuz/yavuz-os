<div align="center">

<pre>
 __   __ ___  __   __ _   _  ____        ___  ____  
 \ \ / // _ \ \ \ / /| | | ||_  / _____ / _ \/ ___| 
  \ V /| |_| | \ V / | |_| | / / |_____| | | \___ \ 
   |_| |_| |_|  \_/   \___/ /___|       \___/|____/  v3.0
</pre>

### Hardened Cyber-Deck OS & İnteraktif Siber Güvenlik Portföyü

[![Live Demo](https://img.shields.io/badge/CANLI_SİSTEM-yavuzcan.pages.dev-00ff66?style=for-the-badge&logo=cloudflare&logoColor=black)](https://yavuzcan.pages.dev)
[![Zero Dependency](https://img.shields.io/badge/DEPENDENCY-ZERO_(100%25_VANILLA)-00ff66?style=for-the-badge)](https://github.com/llyavuz/yavuz-os)
[![Security Hardened](https://img.shields.io/badge/SECURITY-A%2B_HARDENED-00ff66?style=for-the-badge)](https://yavuzcan.pages.dev/.well-known/security.txt)
[![AI Co-Engineered](https://img.shields.io/badge/CO--ENGINEERED-AI_PAIR_PROGRAMMING-ffb000?style=for-the-badge)](#yapay-zeka-destekli-geliştirme-süreci)

**YAVUZ-OS v3.0**, klasik özgeçmiş sitelerinin ötesine geçmek için tasarlanmış; **sıfır dış bağımlılıklı (Zero-Dependency)**, 90'lar retro terminal/CRT estetiğini modern tarayıcı API'leri ve tavizsiz siber güvenlik standartlarıyla birleştiren tarayıcı tabanlı bir **Cyber-Deck İşletim Sistemi** simülasyonudur.

</div>

---

## Projenin Amacı ve Vizyonu

Bu proje, statik bir portföy sayfası sunmak yerine ziyaretçiyi doğrudan interaktif bir çalışma masasının başına oturtmayı hedefler. Ziyaretçiler; sürüklenebilir pencere yöneticisi içinde geliştiricinin özgeçmişini ve projelerini incelerken, aynı anda tarayıcı içinde sentezlenen 8-bit chiptune müzik dinleyebilir, CTF şifre kırma görevlerini çözebilir, otonom siber saldırı/savunma simülasyonunu tetikleyebilir ve istemci tarafı donanım istihbarat tarayıcısını test edebilir.

---

## Yapay Zeka Destekli Geliştirme Süreci

Bu proje, **İnsan Mühendisliği + Yapay Zeka Eşli Programlama (AI-Assisted Pair Programming)** yaklaşımıyla uçtan uca tasarlanmış ve canlı ortama alınmıştır. Geliştirme sürecinde yapay zeka yalnızca kod üreten bir araç olarak değil; bir **Güvenlik Denetçisi (AppSec Reviewer)**, **Arayüz Mimarı** ve **DevOps Otomasyon Asistanı** olarak konumlandırılmıştır:

* **Mimari Tasarım ve İteratif Geliştirme:** Tek dosyalık (`index.html`), harici kütüphane veya CDN barındırmayan sıfır bağımlılıklı mimari kararları, katman (`z-index`) yönetimi ve Yeşil/Amber CRT fosfor tema senkronizasyonu yapay zeka ile birlikte iteratif olarak kurgulandı.
* **Proaktif Güvenlik Sertleştirmesi (10/10 Hardening):** Kod yazımı sırasında oluşabilecek tüm DOM-XSS vektörleri AI denetiminden geçirilerek `innerHTML` kullanımı tamamen yasaklandı; bunun yerine güvenli `textContent` manipülasyonu uygulandı.
* **Web Audio API Matematiksel Sentezi:** Harici ses dosyası yüklemeden 8-bit chiptune melodileri (`YAVUZ_FM`) ve siber saldırı alarm frekanslarını (`sawtooth` / `square` dalga formları) üreten osilatör algoritmaları yapay zeka ile birlikte matematiksel olarak modellendi.
* **Otomasyon ve CI/CD Süreci:** Yerel dosya enjeksiyonları, sürüm yedeklemeleri ve GitHub -> Cloudflare Pages dağıtım hattı PowerShell otomasyon betikleriyle hatasız şekilde yönetildi.

---

## Sistem Modülleri ve İnteraktif Özellikler

### 1. Masaüstü Uygulamaları ve Pencere Yöneticisi
* **`CV_Yavuz.exe`:** Eğitim, topluluk liderliği (GDG Burdur Organizatörü), staj ve teknik yetkinlikleri içeren interaktif özgeçmiş penceresi.
* **`Projeler.dir`:** **AegisMesh** (Shannon Entropisi tabanlı AI-SOC & Honeypot), **FiyatRadar** (TLS/JA3 parmak izi taklitli B2B istihbarat motoru), **TÜBİTAK 2209-A YBS Karar Destek Sistemi** ve **FocusFam Backend** projelerinin teknik detayları.
* **`Hack_CTF.exe` & `SecTools.exe`:** Ziyaretçilerin kriptografik bulmacaları çözebileceği mini CTF meydan okuması ve yerleşik güvenlik araçları.
* **`Cyber_Snake.exe` & `Pomodoro.exe`:** Klasik retro yılan oyunu ve odaklanma zamanlayıcısı.
* **`Terminal.sh` & `Guvenlik.log`:** Komut satırı arayüzü ve sistem güvenlik kayıtları.
* **`Iletisim.bat`:** Bot kazıyıcılarına (scraper) karşı çalışma anında (`atob`) çözülen iletişim bilgileri.

### 2. Merkez Cyber-Deck Kokpiti ve İnteraktif Araçlar
* **`SYSTEM_BOOT // YAVUZ_BIO.SYS`:** Canlı çalışma süresi (`UPTIME`) sayacı, geliştirici kimlik kartı ve tek tıkla değişen anlık geliştirici durum güncellemeleri.
* **`[SİSTEMİ TARA]` (İstemci Ortam İstihbaratı):** Tarayıcının yerleşik donanım API'lerini (`navigator.hardwareConcurrency`, `deviceMemory`, `getBattery`, ekran çözünürlüğü ve saat dilimi) kullanarak daktilo efektiyle canlı istemci analizi yapar. *Hiçbir veri sunucuya gönderilmez; %100 yerel çalışır.*
* **`[SALDIRI TESTİ]` (AegisMesh AI-SOC Simülasyonu):** Sahte bir HTTP Flood / Botnet saldırısı başlatır; ekrani kırmızı alarm durumuna geçirir, Shannon Bilgi Entropisi anomalisini (`7.96`) tespit edip saldırganı Tarpit tuzağına yönlendirir ve otonom Nginx WAF kuralı üreterek sistemi tekrar güvenli moda alır.
* **`YAVUZ_FM // 8-BIT` (Web Audio API Synth Radyo):** Sıfır ses dosyası ile tarayıcı içinde gerçek zamanlı kare dalga (`square wave`) osilatörleriyle 3 farklı retro parça (*Cyber-Deck Night*, *Burdur Terminal Beat*, *90s Keygen Nostalgia*) çalan ve 12 kanallı canlı frekans ekolayzırına sahip kasetçalar.
* **`[MATRIX]` & Konami Kodu (`↑ ↑ ↓ ↓ ← → ← → B A`):** Tüm masaüstü katmanında gerçek zamanlı HTML5 Canvas Matrix dijital kod yağmurunu başlatır.
* **`DUVAR_NOTU.stick` & Başarım Sistemi:** Ziyaretçilerin `localStorage` üzerinde kendi izlerini bırakabildiği XSS korumalı yapışkan not duvarı ve gizli etkileşimlerle açılan başarım bildirimleri.
* **`SHIELD_HUD` Radarı:** Sağ üst köşede canlı tarama yapan radar, güvenlik durumu göstergesi ve tek tıkla **Yeşil / Amber CRT Fosfor** tema değiştiricisi.

---

## Tavizsiz Güvenlik Mimarisi (10/10 Hardening)

Proje, modern web güvenliği standartlarına göre **A+** seviyesinde sertleştirilmiştir:

1. **Sıfır Dış Bağımlılık (Zero Supply-Chain Risk):** Harici CDN, üçüncü parti JavaScript kütüphanesi, harici font veya izleyici (tracker) içermez. Tüm kod tek bir denetlenebilir kaynakta toplanmıştır.
2. **Katı Content Security Policy (`_headers`):** Cloudflare Pages üzerinde sunulan HTTP başlıkları ile `object-src 'none'`, `base-uri 'self'`, `form-action 'none'` ve `frame-ancestors 'none'` kuralları zorunlu tutulur.
3. **DOM-XSS Koruması:** Kullanıcı girdisi işleyen tüm alanlarda (`DUVAR_NOTU.stick` vb.) `innerHTML` kesinlikle kullanılmaz; tüm DOM güncellemeleri `textContent` ile gerçekleştirilir.
4. **Anti-Clickjacking & HSTS:** `X-Frame-Options: DENY` ve `Strict-Transport-Security` (2 yıl, `includeSubDomains; preload`) ile tam taşıma güvenliği sağlanır.
5. **RFC 9116 Uyumluluğu:** Güvenlik araştırmacıları için standart [`.well-known/security.txt`](https://yavuzcan.pages.dev/.well-known/security.txt) dosyası aktif olarak sunulur.

---

## Dizin Yapısı

<ul>
  <li><code>index.html</code> — Tüm işletim sistemi arayüzü, pencere yöneticisi, WebAudio synth ve güvenlik katmanı</li>
  <li><code>_headers</code> — Cloudflare Pages A+ HTTP güvenlik başlıkları (CSP, HSTS, Permissions-Policy)</li>
  <li><code>.well-known/security.txt</code> — RFC 9116 uyumlu güvenlik iletişim politikası</li>
  <li><code>README.md</code> — Proje dokümantasyonu</li>
</ul>

---

## Yerelde Çalıştırma ve Dağıtım (Deploy)

Hiçbir derleme aracına (`npm`, `webpack`, `vite` vb.) ihtiyaç duymadan saniyeler içinde çalıştırabilirsiniz:

<pre>
git clone https://github.com/llyavuz/yavuz-os.git
cd yavuz-os
# index.html dosyasını herhangi bir modern tarayıcıda açın
</pre>

Canlı sürüm, `main` dalına gönderilen her commit sonrasında **Cloudflare Pages** altyapısı üzerinden otomatik olarak **`https://yavuzcan.pages.dev`** adresinde yayınlanmaktadır.

---

<div align="center">

**Yavuz Can** — Yönetim Bilişim Sistemleri (YBS) | Security & Backend Developer | GDG Burdur Organizatörü  
[GitHub](https://github.com/llyavuz) • [Canlı Cyber-Deck](https://yavuzcan.pages.dev)

</div>
