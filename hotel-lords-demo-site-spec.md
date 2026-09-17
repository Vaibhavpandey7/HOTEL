# Hotel Lords — Demo Website Build Spec

**Purpose:** A polished, working demo website to show the owner of Hotel Lords (Dehradun) during a sales pitch. This is a proof-of-concept demo — not the final production site — built to demonstrate what a modern booking-enabled hotel website could look like for their property.

**Built by:** Hardik, Vaibhav Saxena, Arush, Vaibhav Pandey — student founders, hospitality-tech startup, Dehradun.

---

## 1. Project Context

- Target: an independent hotel called **Hotel Lords** in Dehradun.
- No real hotel content (rooms, rates, photos, address) has been supplied yet — use **realistic, clearly placeholder** content that can be swapped out later. Do not invent real customer names or attribute quotes to real people; label testimonials as illustrative sample content in a code comment.
- This must look credible and finished enough to impress a first-time visitor on a laptop or phone during a live pitch — not a rough wireframe.
- No backend, no payment processing, no real data persistence required. Everything can run client-side.

---

## 2. Design Direction

**Aesthetic:** Warm, traditional / heritage hotel feel — think established, trustworthy, inviting. Not sterile, not startup-generic.

**Color palette:**
- Primary: Deep green (e.g. `#1B4332` / `#2D5A3D` range)
- Accent: Gold (e.g. `#C9A227` / `#D4AF37` range)
- Background/neutral: Warm ivory / cream (`#FAF6EE` range), soft off-white
- Text: Near-black or deep charcoal for body copy, not pure black

**Typography:**
- Headings: an elegant serif (e.g. Playfair Display, Cormorant, or similar Google Font) to convey heritage/luxury
- Body: a clean, readable sans-serif (e.g. Inter, Lato) for contrast and legibility

**Imagery:** Warm, traditional hotel photography style — use tasteful stock/placeholder images (interiors, rooms, dining) rather than generic startup illustrations. Rounded-corner cards and generous whitespace over sharp, dense layouts.

**Layout:** Mobile-first and fully responsive — assume it will often be shown on a phone during the actual pitch.

---

## 3. Required Pages / Sections

Single-page site with anchor navigation is fine, or a small multi-page site — pick whichever renders more reliably. Sticky header nav with the sections below.

### 3.1 Home
- Hero section: hotel name, a short warm tagline, a background hero image, and a primary CTA ("Book Your Stay")
- Brief "About Hotel Lords" paragraph (2–3 sentences, warm and heritage-toned)
- Quick highlights row: 3–4 amenity icons (e.g. Free WiFi, Restaurant, Parking, 24/7 Room Service)

### 3.2 Rooms & Booking (working demo)
- Show 3–4 room types as cards: name, short description, a placeholder nightly rate, and a photo
  - Example room names: "Heritage Deluxe Room", "Premium Garden View", "Lords Suite", "Executive Room"
- A **working booking form** (client-side only, dummy data):
  - Check-in date, check-out date (date pickers)
  - Room type (select, populated from the room list above)
  - Number of guests
  - Name, phone, email
  - "Book Now" button
  - On submit: show a confirmation state/message (e.g. "Booking request received — our team will confirm shortly") with the submitted details echoed back. No real backend, no payment gateway — this is a **demo of the flow**, not a live booking system.

### 3.3 Restaurant / Dining
- Short intro paragraph about the in-house restaurant
- 4–6 sample menu highlights (dish name + one-line description), grouped loosely (e.g. Signature Dishes, Local Favorites)
- One or two dining-area placeholder photos

### 3.4 Photo Gallery
- A responsive grid of placeholder images: rooms, lobby, restaurant, exteriors, grounds (8–12 images is enough)
- Lightbox/click-to-enlarge is a nice-to-have, not required

### 3.5 Reviews / Testimonials
- 3–4 short sample guest quotes with a first-name-only or initials format (e.g. "A. Sharma") — mark these clearly in a code comment as illustrative placeholder content, not real reviews
- Simple star rating display

### 3.6 Location / Contact
- Placeholder address in Dehradun, phone number, email
- Embedded map (a static map placeholder or a generic Google Maps embed centered on Dehradun is fine)
- Simple contact form (name, message, send button — can be non-functional/decorative for the demo)

---

## 4. Functional Requirements

- Booking form must be genuinely interactive (state updates, validation on required fields, a visible confirmation step) even though nothing is persisted or sent anywhere real.
- Site must be fully responsive — test at mobile width (~375px) as the primary target, then tablet/desktop.
- Fast, lightweight — this needs to load instantly on a phone during a live pitch, possibly on so-so hotel wifi. Avoid heavy unoptimized assets.
- Smooth scroll / clean section transitions if single-page.
- No console errors, no broken links, no lorem-ipsum left visible anywhere in the final build.

---

## 5. Tech Stack

No strong preference — build with whatever stack Antigravity defaults to for a fast, clean static/demo site (plain HTML/CSS/JS or a lightweight React setup are both fine). Requirements:
- Self-contained, no paid third-party APIs, no required backend/database.
- Should run and be viewable locally or deployed as a static site with no extra setup.

---

## 6. What NOT to Do

- No real payment integration of any kind.
- No claims of real guest reviews, press mentions, or awards — everything is illustrative placeholder content.
- Don't add a visible "DEMO" watermark across the design — keep it clean and presentation-ready, but any placeholder content (address, phone, reviews) should be realistic-sounding rather than obviously fake (avoid "Lorem Ipsum" or "123 Test Street").

---

## 7. Deliverable

A single, polished, mobile-friendly demo website for **Hotel Lords** that the founders can pull up on a laptop or phone mid-pitch to show a hotel owner what a modern booking-enabled site for their property could look like — heritage aesthetic, deep green & gold palette, and a working (dummy-data) room booking flow as the centerpiece.
