# 🎓 SikshaVision — India's Smartest Education Comparison Platform

> Compare online courses, fees & eligibility from India's top universities. Real data, honest comparisons, zero confusion.

**🏆 Built for the Kreatif Atelier Hackathon Challenge**

---

## 🌐 Live Demo

Open `index.html` in any browser — no server, no setup, no dependencies. Just double-click and go.

---

## 📋 What is SikshaVision?

SikshaVision is a **lead-generation and education comparison platform** that helps Indian students explore, compare, and enroll in online degree programs from UGC-approved universities. It's designed as a single-file web application that runs entirely in the browser with zero backend requirements.

### Universities Covered

| University | Accreditation | NIRF Ranking | Courses |
|---|---|---|---|
| **Manipal University Jaipur** | NAAC A+, UGC-DEB | #14 Overall | 8 |
| **Sharda University** | NAAC A+, UGC-DEB | #86 University | 9 |
| **Amity University Noida** | NAAC A+, UGC-DEB | Top 50 | 10 |
| **upGrad** | NSDC, Global Partners | Partner-based | 9 |

All course data (fees, duration, eligibility) has been researched from official university websites.

---

## ✅ Hackathon Requirements — All Met

| Requirement | Status |
|---|---|
| Homepage introducing the platform | ✅ |
| Listing page displaying 4 universities | ✅ |
| Course display (Name, Duration, Eligibility, Fees) | ✅ |
| Lead Generation Popup ("Connect with a Counselor") | ✅ |
| Lead data stored locally (CSV / Excel) | ✅ |
| User Login & Registration | ✅ |
| CollegeVidya / CollegeSathi-style design | ✅ |

---

## ⭐ Bonus Features (Beyond Requirements)

| Feature | Description |
|---|---|
| 🔍 **Search & Filter** | Full-text search across courses and universities. Filter by UG / PG / Certifications |
| ★ **Course Bookmarking** | Bookmark any course with ★ for quick reference |
| ⚡ **Course Compare Tool** | Add up to 3 courses, get side-by-side comparison of fees, duration, eligibility |
| 📊 **Admin Dashboard** | Real-time stats (total leads, today's leads, registered users, bookmarks) |
| 📥 **Multi-Format Export** | One-click export leads to CSV, Excel (.xlsx), or JSON |
| 👥 **Registered Users Table** | View all registered users with join date |
| 🏷️ **Course Type Badges** | Color-coded UG / PG / CERT / DIPLOMA labels |
| 📢 **Scrolling Marquee** | Trust signals: UGC-DEB, NAAC A+, Free Counseling, etc. |
| 📊 **Scroll Progress Bar** | Gradient bar tracking page scroll position |
| 🔔 **Toast Notifications** | Non-intrusive alerts for every user action |
| 🧭 **Active Nav Tracking** | Nav links highlight based on scroll position |
| 👨‍💼 **Founders Section** | Team page with photos and bios |
| 💬 **Auto Counselor Popup** | Lead form auto-triggers after 12 seconds for engagement |

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| **Frontend** | HTML5 + CSS3 + Vanilla JavaScript |
| **Styling** | Custom CSS with CSS Variables (dark luxury theme) |
| **Typography** | Outfit + Instrument Serif + JetBrains Mono (Google Fonts) |
| **Data Storage** | `localStorage` (leads, users, bookmarks, compare list) |
| **Export** | CSV, Excel XML Spreadsheet (.xlsx), JSON |
| **Backend** | None — 100% client-side |
| **Build Tools** | None — single HTML file, zero dependencies |

---

## 📁 Project Structure

```
sikshavision/
├── index.html          # Complete application (single file)
├── README.md           # This file
```

The entire application is contained in a **single HTML file** — CSS, JavaScript, SVG logo, and base64-encoded founder images are all embedded inline. No external dependencies, no build step, no server.

---

## 🚀 How to Run

### Option 1: Local
1. Download `index.html`
2. Double-click to open in any browser
3. Done ✅

### Option 2: GitHub Pages (Free Hosting)
1. Push this repo to GitHub
2. Go to **Settings** → **Pages** → Select **main** branch → **Save**
3. Your site is live at `https://yourusername.github.io/sikshavision`

### Option 3: Netlify Drop
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the project folder
3. Get an instant live URL

---

## 📊 Data Flow

```
User Visits → Browses (Search/Filter) → Explores (Course Modal)
    ↓
Bookmarks / Adds to Compare / Clicks Enquire
    ↓
Lead Form Submission → localStorage
    ↓
Admin Dashboard → Export (CSV / Excel / JSON)
```

### localStorage Keys

| Key | Data |
|---|---|
| `sv_leads` | All captured lead submissions |
| `sv_users` | Registered user accounts |
| `sv_bm` | Bookmarked courses |
| `sv_cmp` | Courses in compare tool |

---

## 🎨 Design Highlights

- **Dark luxury aesthetic** — deep midnight palette with violet & teal accents
- **Custom SVG logo** — SHIKSHAVISION.COM with pencil icon, book wings, and .COM pill
- **Animated floating orbs** — gradient orbs creating depth and atmosphere
- **Bento grid layout** — modern asymmetric grid for features section
- **Noise grain texture** — subtle SVG overlay for tactile depth
- **Premium typography** — Outfit (body) + Instrument Serif (headings) + JetBrains Mono (accents)
- **Fully responsive** — mobile, tablet, and desktop optimized
- **Smooth micro-interactions** — card hovers, modal transitions, staggered fade-ups

---

## 👨‍💼 Team

| Name | Role |
|---|---|
| **Narender Lamba** | Founder — 15+ years in education industry |
| **Dr. Kuldeep Yadav** | Co-Founder — Legal scholar, PhD in Law |
| **Jatin** | Co-Founder — Student counseling & digital growth |

---

## 📞 Contact

- **Website:** [shikshavision.com](https://shikshavision.com)
- **Email:** info@shikshavision.com
- **Phone:** +91 92569 25671
- **Address:** M-47, Mehrauli-Gurgaon Rd, Block M, Old DLF Colony, Sector 14, Gurugram, Haryana 122007

---

## 📜 License

Built for the **Kreatif Atelier Hackathon Challenge**. All rights reserved © 2026 SikshaVision.

---

## 🏆 Evaluation Criteria Mapping

| Criteria | How We Deliver |
|---|---|
| **Functional Implementation** | All required features + 13 bonus features |
| **UI Clarity & Usability** | Dark luxury theme, responsive, animated, premium fonts |
| **Course Data Accuracy** | All data from official university websites |
| **Lead Generation** | Popup form → localStorage → CSV/Excel/JSON export |
| **Code Organization** | Single-file SPA, CSS variables, modular JS functions |
