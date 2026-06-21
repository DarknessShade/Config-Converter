<div align="center">
    
# ✨ Config Converter 🛡️⚡

### مبدل همه‌کاره کانفیگ‌های V2Ray · WireGuard · Clash · Sing-box — با ظاهر نوستالژیک ویندوز ۹۸
### The all-in-one V2Ray · WireGuard · Clash · Sing-box config converter — wrapped in a nostalgic Windows 98 shell

**[🇮🇷 فارسی](#-فارسی)** • **[🇬🇧 English](#-english)**

<br>

<img src="https://raw.githubusercontent.com/DarknessShade/DarknessShade/main/Image/Win98/mobileconv.jpg" width="520" alt="Hacker / Matrix theme preview">

</div>

---

<br>

# 🇮🇷 فارسی

## 📖 درباره پروژه

**Config Converter** یک وب‌اپلیکیشن **تک‌فایلی و کاملاً سمت کاربر (Client-Side)** است؛ یعنی هیچ داده‌ای به هیچ سروری ارسال نمی‌شود و همه‌چیز همان لحظه، داخل مرورگر خودتان پردازش می‌شود. این ابزار با ظاهری نوستالژیک شبیه **ویندوز ۹۸** (به‌همراه یک تم مخفی هکری/Matrix 🟢) ساخته شده و سه ابزار پرکاربرد را زیر یک سقف جمع کرده است:

| ابزار | کاربرد |
|---|---|
| ✨ **مبدل V2Ray** | ویرایش، ادغام و بازنویسی دسته‌جمعی کانفیگ‌های VLESS / VMess / Trojan / Shadowsocks و... |
| 🛡️ **مبدل WireGuard** | تبدیل فایل‌های `.conf` (از جمله ProtonVPN) به Clash، AmneziaWG و Wiresock |
| ⚡ **مبدل Clash / Sing-box** | تبدیل دوطرفه بین لینک‌های پروکسی، Clash YAML و Sing-box JSON |

<br>

## 🧩 ابزارها و قابلیت‌ها

### ✨ مبدل پیشرفته پروتکل‌های V2Ray

<img src="https://raw.githubusercontent.com/DarknessShade/DarknessShade/main/Image/Win98/V2rayconv.jpg" width="500" alt="V2Ray Converter Screenshot">

- 📥 دریافت مستقیم کانفیگ‌ها از یک **لینک سابسکریپشن**
- 📋 پشتیبانی از ورودی خام (Raw)، **Base64** و **JSON**، با تشخیص خودکار فرمت
- 🔌 پشتیبانی از پروتکل‌های: `vless://` `vmess://` `trojan://` `ss://` `ssr://` `hysteria://` `hysteria2://` `http://` `socks5://` و پروکسی‌های تلگرام
- ✏️ ویرایش دسته‌جمعی: جایگزینی همزمان **IP/دامنه** و **پورت** برای تمام کانفیگ‌ها
- 🏷️ تغییر نام دسته‌جمعی کانفیگ‌ها (با شماره‌گذاری خودکار)
- 🌍 تشخیص خودکار پرچم کشور بر اساس آی‌پی هر نود
- 📊 پنل نتایج با تب‌بندی بر اساس پروتکل، شمارنده‌ی هر دسته
- 📱 تولید آنی **QR Code** برای هر کانفیگ
- 📤 خروجی کلی به‌صورت لینک ساده یا فایل **Base64** فشرده
- 📋 کپی تکی یا کپی‌همه با یک کلیک

### 🛡️ مبدل پروتکل WireGuard

<img src="https://raw.githubusercontent.com/DarknessShade/DarknessShade/main/Image/Win98/wireguardconv.jpg" width="500" alt="WireGuard Converter Screenshot">

- 📂 آپلود چندفایلی `.conf` یا Paste مستقیم محتوا (Drag & Drop هم پشتیبانی می‌شود)
- 🔐 سازگار با کانفیگ‌های اختصاصی **Proton VPN**
- 🔄 خروجی به سه فرمت: **Clash / Meta** · **AmneziaWG / WG Tunnel** · **Wiresock**
- 📦 تولیدکننده‌ی **پکت‌های هرز (Junk Packets)**: حالت‌های آماده‌ی Light و Heavy یا تنظیم کاملاً دستی `jc` / `jmin` / `jmax`
- 🧪 پشتیبانی کامل از پارامترهای نسخه‌ی **Amnezia 1.5** (`i1` تا `i5`) با دکمه‌ی تولید تصادفی
- 🗂️ پردازش دسته‌ای (Batch) چند پروفایل با خروجی مجزا برای هرکدام
- 📋 کپی و دانلود مجزا برای هر پروفایل تبدیل‌شده

### ⚡ مبدل پیشرفته Clash ⇄ Sing-box

<img src="https://raw.githubusercontent.com/DarknessShade/DarknessShade/main/Image/Win98/clashsingconv.jpg" width="500" alt="Clash / Sing-box Converter Screenshot">

- 🔁 تبدیل **دوطرفه** بین سه فرمت: لینک‌های پروکسی خام، **Clash YAML** و **Sing-box JSON**
- 🤖 تشخیص خودکار فرمت ورودی (Auto Detect)
- 📥 دریافت از لینک سابسکریپشن یا آپلود فایل (`.txt` / `.yaml` / `.json`)
- 🇮🇷 برای خروجی Clash: انتخاب بین حالت **«قانون ایران»** (مسیریابی هوشمند داخلی/خارجی) یا حالت **Minimal**
- 🛰️ برای خروجی Sing-box: انتخاب بین حالت **TUN + Mixed** یا **Mixed/Socks Only**
- 🔄 دکمه‌ی **Swap** برای جابه‌جایی آنی ورودی و خروجی
- ⚠️ گزارش هوشمند نودهای ناسازگار با فرمت مقصد (مثلاً عدم پشتیبانی SSR در Sing-box)
- 📋 کپی و 💾 دانلود مستقیم خروجی با پسوند صحیح فایل

<br>

## 🎨 ویژگی‌های مشترک

- 🌐 **کاملاً دو زبانه** (فارسی / English) با تشخیص خودکار جهت متن (RTL / LTR)
- 🖥️ دو تم متفاوت: ظاهر کلاسیک **ویندوز ۹۸** و یک تم مخفی **هکری/Matrix** (از منوی Theme Mode)
- 🚫 بدون نیاز به نصب، اکانت، سرور یا بک‌اند — فقط یک فایل HTML!
- 🔒 حریم‌خصوصی‌محور: تمام پردازش‌ها لوکال و داخل مرورگر شما انجام می‌شود
- 💯 رایگان و متن‌باز

<br>

## 🧰 ساخته‌شده با

| تکنولوژی | کاربرد |
|---|---|
| HTML5 / CSS3 / Vanilla JavaScript (ES6+) | هسته‌ی اصلی برنامه، بدون فریم‌ورک |
| [Vazirmatn](https://github.com/rastikerdar/vazirmatn) | فونت فارسی |
| [QRious](https://github.com/neocotic/qrious) | تولید QR Code |
| [JSZip](https://stuk.github.io/jszip/) | خروجی فشرده‌ی فایل‌ها |
| [js-yaml](https://github.com/nodeca/js-yaml) | پردازش فایل‌های Clash YAML |

<br>

## 🚀 شروع به کار

هیچ نصب یا وابستگی‌ای لازم نیست. کافیست مخزن را کلون کنید و فایل اصلی را در مرورگر باز کنید:

```bash
git clone https://github.com/DarknessShade/Config-Converter.git
cd Config-Converter
# فایل index.html را با هر مرورگر مدرنی باز کنید 😄
```

یا به‌سادگی فایل HTML پروژه را دانلود کرده و با دابل‌کلیک در مرورگر اجرا کنید.

<br>

## 🤝 مشارکت

پیشنهادها، گزارش باگ و Pull Request شما با آغوش باز پذیرفته می‌شود. اگر ایده‌ای برای بهبود این ابزار دارید، یک Issue باز کنید یا مستقیماً PR بزنید.

## 📜 لایسنس

برای جزئیات مجوز استفاده از این پروژه، فایل `LICENSE` مخزن را بررسی کنید.

<br>

---

<br>

# 🇬🇧 English

## 📖 About

**Config Converter** is a **single-file, fully client-side** web app — nothing ever leaves your browser, and every conversion happens locally and instantly. It's wrapped in a nostalgic **Windows 98** desktop look (plus a hidden hacker/Matrix theme 🟢) and bundles three powerful tools in one place:

| Tool | Purpose |
|---|---|
| ✨ **V2Ray Converter** | Edit, merge, and batch-rewrite VLESS / VMess / Trojan / Shadowsocks configs and more |
| 🛡️ **WireGuard Converter** | Convert `.conf` files (including ProtonVPN) into Clash, AmneziaWG, and Wiresock |
| ⚡ **Clash / Sing-box Converter** | Bi-directional conversion between proxy links, Clash YAML, and Sing-box JSON |

<br>

## 🧩 Tools & Features

### ✨ Advanced V2Ray Protocol Converter

<img src="https://raw.githubusercontent.com/DarknessShade/DarknessShade/main/Image/Win98/V2rayconv.jpg" width="500" alt="V2Ray Converter Screenshot">

- 📥 Fetch configs directly from a **subscription link**
- 📋 Accepts raw text, **Base64**, or **JSON** input with automatic format detection
- 🔌 Supports `vless://` `vmess://` `trojan://` `ss://` `ssr://` `hysteria://` `hysteria2://` `http://` `socks5://`, and Telegram proxy links
- ✏️ Bulk editing: mass-replace **IP/domain** and **port** across every config at once
- 🏷️ Batch rename configs with auto-numbering
- 🌍 Automatic country-flag detection per node
- 📊 Tabbed results panel filtered by protocol, with live counters
- 📱 Instant **QR Code** generation for any config
- 📤 Export everything as plain links or a compressed **Base64** bundle
- 📋 One-click copy (single config or all at once)

### 🛡️ WireGuard Protocol Converter

<img src="https://raw.githubusercontent.com/DarknessShade/DarknessShade/main/Image/Win98/wireguardconv.jpg" width="500" alt="WireGuard Converter Screenshot">

- 📂 Multi-file `.conf` upload or direct paste (drag & drop supported)
- 🔐 Full support for **Proton VPN**'s WireGuard config quirks
- 🔄 Converts to three formats: **Clash / Meta** · **AmneziaWG / WG Tunnel** · **Wiresock**
- 📦 Built-in **Junk Packet** generator: ready-made Light/Heavy presets or fully custom `jc` / `jmin` / `jmax` values
- 🧪 Full support for **Amnezia 1.5** parameters (`i1`–`i5`) with a one-click randomizer
- 🗂️ Batch processing of multiple profiles, each with its own output
- 📋 Per-profile copy & download

### ⚡ Advanced Clash ⇄ Sing-box Converter

<img src="https://raw.githubusercontent.com/DarknessShade/DarknessShade/main/Image/Win98/clashsingconv.jpg" width="500" alt="Clash / Sing-box Converter Screenshot">

- 🔁 **Bi-directional** conversion across raw proxy links, **Clash YAML**, and **Sing-box JSON**
- 🤖 Automatic input-format detection
- 📥 Fetch from a subscription link or upload a file (`.txt` / `.yaml` / `.json`)
- 🇮🇷 Clash output: choose **"IR Rule"** mode (smart local/foreign routing) or **Minimal** mode
- 🛰️ Sing-box output: choose **TUN + Mixed** or **Mixed/Socks Only** inbound mode
- 🔄 One-click **Swap** button to instantly flip input and output
- ⚠️ Smart warnings for nodes unsupported by the target format (e.g. SSR isn't supported in Sing-box)
- 📋 Copy & 💾 download output with the correct file extension automatically applied

<br>

## 🎨 Shared Features

- 🌐 **Fully bilingual** (Persian / English) with automatic text direction (RTL / LTR)
- 🖥️ Two themes: the classic **Windows 98** look and a hidden **hacker/Matrix** theme (via the Theme Mode menu)
- 🚫 No install, no account, no server, no backend — just one HTML file
- 🔒 Privacy-first: every conversion runs locally in your browser
- 💯 Free and open-source

<br>

## 🧰 Built With

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / Vanilla JavaScript (ES6+) | Core app, zero frameworks |
| [Vazirmatn](https://github.com/rastikerdar/vazirmatn) | Persian typeface |
| [QRious](https://github.com/neocotic/qrious) | QR Code generation |
| [JSZip](https://stuk.github.io/jszip/) | Compressed file export |
| [js-yaml](https://github.com/nodeca/js-yaml) | Clash YAML parsing |

<br>

## 🚀 Getting Started

No installation or dependencies required. Just clone the repo and open the main file in your browser:

```bash
git clone https://github.com/DarknessShade/Config-Converter.git
cd Config-Converter
# Open index.html in any modern browser 😄
```

Or simply download the project's HTML file and double-click it to run in your browser.

<br>

## 🤝 Contributing

Suggestions, bug reports, and pull requests are all very welcome. Got an idea to make this better? Open an Issue or send a PR directly.

## 📜 License

Check the repository's `LICENSE` file for usage terms.

<br>

---

<br>

🙏 Acknowledgments 
* [Wireguard DPI Circumvention Converter](https://github.com/fevid/wireguard-dpi-circumvention-converter)

<br>

<div align="center">

### 📡 ارتباط با ما | Get in Touch

[![Telegram](https://img.shields.io/badge/Telegram-Paradise__Of__Freedom-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Paradise_Of_Freedom)
[![Telegram](https://img.shields.io/badge/Telegram-ConfigWireguard-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ConfigWireguard)
[![X](https://img.shields.io/badge/X-mansor427-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/mansor427)
[![GitHub](https://img.shields.io/badge/GitHub-DarknessShade-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DarknessShade)

**ÐΛɌ₭ᑎΞ𐒡𐒡** | Config Converter

</div>
