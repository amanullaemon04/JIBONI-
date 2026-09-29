# 🩸 JIBONI — Smart Blood Donor Management Platform

> *"অচেনা কাউকে বাঁচার আশা দিয়ে, লিখে যাও এক নিঃস্বার্থ জীবনী।"*

**JIBONI** is a modern, responsive, and privacy-focused blood donor directory and management platform designed to connect blood seekers with eligible donors instantly. Engineered with a mobile-first philosophy, it streamlines emergency donor discovery, verification, and donor profile self-management.

---

## 🌟 Key Features

* 🔍 **Smart Filter & Real-Time Discovery:** Find donors instantly by blood group, district, university/hall location, and availability status.
* 📝 **Streamlined Donor Registration:** Smooth onboarding flow collecting critical details, donation history, and contact credentials.
* 🔒 **Secure PIN Management & DOB Verification:** Donors can update their availability and profile using a 4-digit secret PIN, backed by Date of Birth (DOB) authentication for secure PIN recovery.
* 🛡️ **Multi-Tier Admin Control Panel:**
  * **Super Admin Control:** Manage global settings, register sub-admins, review reports, and export donor directories to CSV.
  * **Sub-Admin Portal:** Dedicated panel to verify pending donors, toggle real-time availability, and moderate directory records with role-based permissions.
* 💬 **Integrated Feedback System:** Built-in communication channel for platform users to submit feedback and suggestions, directly reviewable from the admin interface.
* 📖 **Blood Donation Guidelines & Analytics:** Comprehensive eligibility checklist, medical intervals, and real-time donation metric tracking.

---

## 🛠️️ Tech Stack

* **Frontend:** Semantic HTML5, Modern CSS3 (CSS Variables, Flexbox, CSS Grid), Vanilla JavaScript (ES6+).
* **Styling:** Mobile-first responsive UI with zero external dependencies to prevent layout shifts.
* **Database & Auth:** Supabase (PostgreSQL / Realtime REST APIs) with fallback local caching.
* **Hosting & CDN:** GitHub Pages / Cloudflare Pages & Cloudflare Workers (Custom Domain & Edge SSL Ready).

---

## 📂 Project Structure

```text
├── index.html            # Main donor discovery & directory search
├── register.html         # Donor onboarding with DOB & PIN protection
├── update-profile.html   # Donor self-service profile & status update
├── admin.html            # Role-based admin & sub-admin management panel
├── guidelines.html       # Donor eligibility, medical guidelines & rules
├── stats.html            # Real-time donation statistics & counts
├── feedback.html         # User feedback & suggestion collection form
├── developer.html        # Maintainer profile & social contact directory
└── bio.html              # Developer biography & background
