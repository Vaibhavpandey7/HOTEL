# HOTEL — Heritage Hospitality & Smart QR Demo Website

A modern, responsive demo website built for **HOTEL** (Dehradun). Features a heritage deep-green & gold aesthetic, interactive room booking flow, restaurant dining showcase, lightbox photo gallery, guest reviews, and a **Smart QR Hospitality** suite with client-side scannable QR codes for in-room digital concierge, contactless table ordering with payment simulation, and review collection.

---

## 🚀 Quick Start — How to Run

Since this is a fast, lightweight, self-contained static web application (HTML/CSS/JavaScript with zero backend dependencies), you can run it using any static HTTP server.

### Option 1: Using Python 3 (Recommended)

Open your terminal in this directory (`/home/va1bhav/Desktop/HOTEL_SETUP`) and run:

```bash
python3 -m http.server 8080
```

Then open your browser and go to:
- **Local machine:** [http://localhost:8080](http://localhost:8080)
- **Phone on same Wi-Fi:** `http://<your-lan-ip>:8080` (e.g. `http://172.16.71.216:8080`)

*(To stop the server at any time, press `Ctrl + C` in the terminal).*

---

### Option 2: Using Node.js / npx (Alternative)

If you have Node.js installed:

```bash
npx serve .
# or
npx http-server -p 8080
```

---

### Option 3: VS Code / IDE Live Server

If using VS Code or an IDE, install the **Live Server** extension, right-click on `index.html`, and select **"Open with Live Server"**.

---

## 📱 Pages & Features

| Page | URL | Description |
|------|-----|-------------|
| **Main Website** | `index.html` | Hero, About, Amenities, Room Cards, Working Booking Form, Restaurant, 12-image Lightbox Gallery, Smart QR Showcase, Guest Reviews, Contact Form. |
| **Table QR Ordering** | `order.html?table=7` | Contactless restaurant dining: menu categories, item customization, cart with GST calculation, and simulated UPI/Card payment with order confirmation ID. |
| **In-Room Concierge** | `concierge.html?room=204` | Bedside digital concierge: requests for housekeeping, extra towels, laundry, late check-out, maintenance, and Wi-Fi access credentials. |
| **Review Collection** | `review.html?stay=recent` | Touchless guest review form: 5-star ratings, category breakdowns (Room, Cleanliness, Food, Staff), free-text comments, and confirmation screen. |

---

## 📲 How to Test QR Scanning on a Real Phone

1. Make sure your phone and laptop are connected to the **same Wi-Fi network**.
2. Run the server (`python3 -m http.server 8080`).
3. Open `http://localhost:8080` on your laptop and scroll down to the **Smart QR Hospitality** section (`#qr-tech`).
4. Point your iPhone or Android camera at any of the 4 on-screen QR codes — they automatically encode your local Wi-Fi IP and open the live demo immediately on your phone!
