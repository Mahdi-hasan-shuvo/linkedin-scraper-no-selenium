<div align="center">

<!-- ANIMATED HEADER BANNER -->
<img src="https://github.com/user-attachments/assets/08ae80f8-3a13-4652-9a32-a8153b4b7127" width="100%" />

<!-- BADGES ROW -->
<p>
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LinkedIn-API-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-BSD--3-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/No-Selenium-red?style=for-the-badge&logo=selenium&logoColor=white"/>
  <img src="https://img.shields.io/github/stars/Mahdi-hasan-shuvo/linkedin-scraper?style=for-the-badge&color=ffd43b"/>
</p>

<!-- ONE-LINER -->
> ### 🚀 Blazing-fast LinkedIn data extractor — no browsers, no Selenium, just pure speed.
> Extract profiles, emails, posts, jobs, and more in **minutes** instead of hours.

<br/>

</div>

---

## 📌 Table of Contents

| # | Section |
|---|---------|
| 1 | [✨ What is this?](#-what-is-this) |
| 2 | [🆓 Free Version Features](#-free-version-features) |
| 3 | [💎 Paid PRO Features](#-paid-pro-features) |
| 4 | [⚡ Quick Start — Run in 3 Steps](#-quick-start--run-in-3-steps) |
| 5 | [🗂️ Output Formats](#%EF%B8%8F-output-formats) |
| 6 | [📊 Free vs PRO Comparison](#-free-vs-pro-comparison) |
| 7 | [🧠 How It Works](#-how-it-works) |
| 8 | [📁 Project Structure](#-project-structure) |
| 9 | [💡 Use Cases](#-use-cases) |
| 10 | [⚖️ Disclaimer](#%EF%B8%8F-disclaimer) |
| 11 | [🤝 Contributing](#-contributing) |
| 12 | [📬 Contact & Hire Me](#-contact--hire-me) |

---

## ✨ What is this?

**LinkedIn Scraper** is a **super-fast, lightweight Python tool** that extracts professional data from LinkedIn — without using Selenium, browsers, or heavy dependencies.

```
LinkedIn Profiles  ──►  Python Script  ──►  CSV / JSON / Excel
```

Whether you're a **recruiter**, **sales professional**, **marketer**, or **researcher**, this tool saves you hours of manual work by automating LinkedIn data collection at scale.

---

## 🆓 Free Version Features

> 📂 File: **`Leade_generation.py`**

The free version extracts the following from LinkedIn search results:

| Field | Description |
|-------|-------------|
| 🔗 **Profile Link** | Direct URL to the LinkedIn profile |
| 👤 **Full Name** | Person's full name |
| 💼 **Designation** | Current job title / headline |
| 📍 **Location** | City, Country |

### ✅ Sample Output

```json
{
  "name": "Md. Shohanur Rahaman",
  "designation": "Machine Learning | Data Science | NLP | Researcher",
  "location": "Dhaka, Bangladesh",
  "profile_link": "https://www.linkedin.com/in/md-shohanur-rahaman"
}
```

---

## 💎 Paid PRO Features

Unlock the **Pro version** for full automation power:

```
💎 PRO UNLOCK
├── 📧  Extract Emails (if publicly available)
├── 📞  Extract Phone Numbers
├── 📝  Scrape User Posts & Activity
├── 💼  Job Finder & Smart Search
├── 🔎  Filter by Keyword / Location / Industry
├── 🤝  Auto-Send Connection Requests
├── 📥  Read Inbox Messages
├── ✉️   Send Messages / SMS Automation
└── ⚡  And much more for Sales, Recruiting & Marketing
```

---

## ⚡ Quick Start — Run in 3 Steps

### Step 1 — Clone the Repository

```bash
git clone https://github.com/Mahdi-hasan-shuvo/linkedin-scraper.git
cd linkedin-scraper
```

### Step 2 — Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3 — Run the Scraper

```bash
python Leade_generation.py
```

> 🎉 That's it! Your leads will be saved automatically.

---

## 🗂️ Output Formats

The scraper exports your data in **3 formats** out of the box:

```
📊 leads.csv      ← Open in Excel / Google Sheets
📋 output.json    ← Use in any app or API
📘 leads.xlsx     ← Fully formatted spreadsheet
```

### CSV Preview

| Profile Link | Name | Designation | Location |
|---|---|---|---|
| linkedin.com/in/example | John Doe | Software Engineer at Google | USA |
| linkedin.com/in/example2 | Jane Smith | Data Scientist | Canada |
| linkedin.com/in/example3 | Ali Hassan | Full Stack Developer | Bangladesh |

---

## 📊 Free vs PRO Comparison

| Feature | 🆓 Free | 💎 PRO |
|---------|:-------:|:------:|
| Profile Scraping | ✅ | ✅ |
| Name, Designation, Location | ✅ | ✅ |
| CSV / JSON / Excel Export | ✅ | ✅ |
| Contact Info (Email / Phone) | ❌ | ✅ |
| User Posts Scraping | ❌ | ✅ |
| Job Finder | ❌ | ✅ |
| Filter by Location / Industry | ❌ | ✅ |
| Auto Connection Requests | ❌ | ✅ |
| Inbox Reader | ❌ | ✅ |
| Message / SMS Automation | ❌ | ✅ |
| Priority Support | ❌ | ✅ |

---

## 🧠 How It Works

```
┌─────────────────────────────────────────────────────┐
│                   LinkedIn Scraper                   │
│                                                     │
│  1️⃣  You provide search keywords / filters           │
│       ↓                                             │
│  2️⃣  Script sends clean API / HTTP requests          │
│       ↓                                             │
│  3️⃣  LinkedIn returns profile data                   │
│       ↓                                             │
│  4️⃣  Data parsed → structured into clean format      │
│       ↓                                             │
│  5️⃣  Exported to CSV / JSON / Excel automatically    │
└─────────────────────────────────────────────────────┘
```

**Key technical advantages:**
- ✅ No Selenium, no browser automation
- ✅ No memory-heavy headless Chrome
- ✅ Pure Python `requests` + API calls
- ✅ Extremely fast — thousands of profiles in minutes
- ✅ Lightweight — runs on any machine

---

## 📁 Project Structure

```
linkedin-scraper/
│
├── 📄 Leade_generation.py     ← Main scraper script (FREE version)
├── 📄 location_geoId.json     ← LinkedIn GeoID location mapping
├── 📄 leads.csv               ← Sample output file
├── 📂 output/                 ← Auto-generated output folder
├── 📂 user_scrap/             ← User profile scraping module
├── 📄 requirements.txt        ← Python dependencies
├── 📄 .gitignore
└── 📄 README.md
```

---

## 💡 Use Cases

| Who | How They Use It |
|-----|----------------|
| 🎯 **Sales Teams** | Build targeted lead lists by industry, location & title |
| 🔍 **Recruiters** | Find candidates matching specific skills and roles |
| 📈 **Marketers** | Research prospects for B2B campaigns |
| 🎓 **Researchers** | Collect professional data for academic studies |
| 🤖 **Automation Engineers** | Integrate LinkedIn data into CRMs and pipelines |

---

## ⚖️ Disclaimer

> ⚠️ **For Educational & Research Purposes Only**
>
> This tool is intended for learning and research purposes.
> Scraping LinkedIn may violate their [Terms of Service](https://www.linkedin.com/legal/user-agreement).
> The author is **not responsible** for any misuse.
> **Use at your own risk and responsibility.**

---

## 🤝 Contributing

Contributions are always welcome! Here's how:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/amazing-feature

# 3. Commit your changes
git commit -m "Add amazing feature"

# 4. Push to the branch
git push origin feature/amazing-feature

# 5. Open a Pull Request 🎉
```
<img width="1255" height="929" alt="image" src="https://github.com/user-attachments/assets/f1c822cc-2a84-42ff-bd0e-d787950a5a53" />
For major changes, please open an **Issue** first to discuss what you'd like to change.

---

## 📬 Contact & Hire Me

<div align="center">

Have a project in mind? Need custom scraping, automation, or data pipeline work?
I'm available for **freelance collaborations and paid projects**.

| Channel | Details |
|---------|---------|
| 📩 **Email** | [shuvobbhh@gmail.com](mailto:shuvobbhh@gmail.com) |
| 💬 **WhatsApp / Telegram** | [+8801616397082](https://wa.me/8801616397082) |
| 🌐 **Portfolio** | [mahdi-hasan-shuvo.github.io](https://mahdi-hasan-shuvo.github.io/Mahdi-hasan-shuvo/) |
| 💼 **GitHub** | [@Mahdi-hasan-shuvo](https://github.com/Mahdi-hasan-shuvo) |

</div>

---

<div align="center">

> *"Quality work speaks louder than words. Let's build something remarkable together."*

**⭐ Star this repo if you found it useful — it means the world!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7b2ff7,50:00c8ff,100:0a66c2&height=120&section=footer&animation=fadeIn" width="100%"/>

**Made with ❤️ and ☕ by [Mahdi Hasan Shuvo](https://mahdi-hasan-shuvo.github.io/Mahdi-hasan-shuvo/)**

</div>
# API DAMO
https://github.com/user-attachments/assets/597fb18e-1dfa-4a03-b4a5-181fef976484


