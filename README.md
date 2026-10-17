# Wessy-Ka Nubian Guest House & Cultural Lounge | أسوان 🌴
### بيت الضيافة والمطعم النوبي بأسوان - "بيتك هنا - YOUR home is HERE"

A world-class, ultra-luxurious, production-ready single-file web application for **Wessy-Ka Nubian Guest House & Cultural Lounge** (بيت الضيافة والمطعم النوبي بأسوان), crafted with authentic Nubian aesthetics directly inspired by the real venue in Aswan, Egypt.

Designed for seamless hosting directly on **GitHub Pages**.

---

## 🌟 Key Architectural & Visual Features

### 1. Authentic Nubian Visual Identity (Grounding in Real Venue Photos)
- **Palette**: Nubian Nile Blue (`#0D6E6E` / `#1E3A8A`), Warm Sand & Desert Gold (`#F4A261` / `#FAEDCD` / `#E9C46A`), Terracotta Clay Red (`#D95C34`), and Pure Dome White.
- **Cultural Motifs**: Geometric Nubian triangle friezes, Nile water waves, mudbrick dome arches, celestial moon & stars, and the crocodile (*التمساح النوبي*).
- **Core Motto**: Proudly embedded slogan: *"بيتك هنا - YOUR home is HERE"*.

### 2. Full Dark / Light Mode (Starry Nubian Night vs. Sunlit Nile)
- **Night Mode**: Inspired by nighttime around the sand campfire under glittering Aswan stars (deep indigo/obsidian `#0B132B`, glowing lantern amber `#F59E0B`, starry sky canvas).
- **Light Mode**: Golden sun over desert sand and turquoise river breeze.
- LocalStorage state persistence.

### 3. Native Bi-Lingual Support (Arabic [RTL] & English [LTR])
- Instant one-click switcher with dynamic `dir="rtl"` / `dir="ltr"` and `lang` switching.
- High-grade, culturally warm copywriting in both Arabic and English.
- Uses Google Fonts: **Cairo** for Arabic warmth and **Plus Jakarta Sans** for modern luxury typography.

### 4. Multi-Step Room & Suite Reservation Engine
- **Step 1: Guest Information**: Name, international WhatsApp number, city/country, special arrival requests.
- **Step 2: Room Selection & Date Calculation**:
  - *Royal Nile Dome Suite* (جناح القبة الملكية المطل على النيل).
  - *Heritage Family Suite* (جناح العائلة التراثي المتسع).
  - *Standard Serenity Room* (غرفة السكينة النوبية الكلاسيكية).
  - *Nubian Stargazer Sand Camp* (مخيم السمر النوبي).
  - Live night calculation and real-time pricing.
  - Nubian cultural add-ons: Sunset Nile Felucca sailing, Live Tanbura & Oud concert, Organic Aswan breakfast tray, Private station/airport pickup.
- **Step 3: Boarding Pass / Luxury Voucher Preview**:
  - Automatically generates an itemized booking pass with reference code.
- **Instant WhatsApp Booking Dispatcher**:
  - Direct 1-click dispatch to Wessy-Ka's official WhatsApp number with a clean formatted summary.

### 5. Interactive Nubian Restaurant & Drink Lounge Menu
- Real items inspired by the venue:
  - *Signature Karkadeh & Yogurt Cocktail* (عصير الكركديه بالزبادي النوبي الشهير).
  - *Gabana Coffee with Fresh Ginger* (قهوة الجبنة الأسوانية).
  - *Cold-Pressed Doum Juice* & *Fresh Tamarind*.
  - *Charcoal Grilled Nile Tilapia* & *Nile Perch Claypot Tagine*.
  - *Nubian Beef Tagine with Caramelized Shallots & Bamia Weika*.
  - *Bedouin Charcoal Mixed Grill Platter*.
  - *Fresh Feteer Meshaltet with Country Ghee & Black Honey*.
- Category filtering & real-time live search.
- Interactive slide-out drawer cart with dining options (Table, Campfire Sand Lounge, Suite delivery, Takeaway).
- Formatted WhatsApp order dispatch directly to the kitchen.

### 6. Interactive Authentic Photo Gallery & Lightbox
- Features real photos of the venue (Campfire gathering, mudbrick dome murals, courtyard, official emblem, hibiscus-yogurt cocktail).
- Fullscreen modal lightbox with captions and keyboard navigation (Escape to dismiss).

### 7. Verified Guest Reviews & Testimonials
- Star rating cards with traveler feedback.
- Interactive "Share Your Experience" modal with localStorage persistence.

### 8. Footer & Location
- Direct Google Maps navigation link.
- Quick WhatsApp and phone contact buttons.

---

## 🚀 How to Deploy to GitHub Pages (in 2 Minutes)

1. **Initialize Git in the project folder**:
   ```bash
   git init
   git add .
   git commit -m "Launch Wessy-Ka Nubian Guest House & Cultural Lounge website"
   ```

2. **Create a GitHub Repository** (e.g. `wessy-ka-nubian-guesthouse`) and push:
   ```bash
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/wessy-ka-nubian-guesthouse.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click on **Settings** > **Pages** (under Code and automation).
   - Under **Build and deployment** > **Source**, select `Deploy from a branch`.
   - Choose `main` branch and `/ (root)` folder.
   - Click **Save**.
   - Your website will be live in 60 seconds at `https://<YOUR-USERNAME>.github.io/wessy-ka-nubian-guesthouse/`!

---

## ⚙️ Configuration & Customization

- **Official Contact Phone & WhatsApp**:
  Configured to `+20 10 04281545` (`https://wa.me/201004281545`).
- **Update Room Prices / Menu Items**:
  All menu items and rooms are defined cleanly in the `menuItems` and `state.selectedRoom` data structures inside `<script>`.
- **Assets**:
  Real venue images are stored in `./assets/` and have automatic online fallback handlers configured.

---
*Created with pride for Nubia and Aswan. بيتك هنا - YOUR home is HERE.*
