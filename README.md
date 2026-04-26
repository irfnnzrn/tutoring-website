# LearnHub - Starter Template
Final Sem Project | Web Development

---

## 📁 Folder Structure
```
learnhub/
├── index.html          → Home Page          (Member 1 / Leader)
├── listing.html        → Tutor Listing Page  (Member 2)
├── profile.html        → Tutor Profile Page  (Member 3)
├── booking.html        → Booking Page        (Member 4)
├── chat.html           → Chat Page           (Member 4)
├── css/
│   └── styles.css      → Shared CSS — colour variables & reset
├── js/
│   └── main.js         → Shared JavaScript functions
├── data/
│   └── tutors.json     → Data tutors (JSON)
└── images/             → Letak semua gambar sini
```

---

## ⚠️ Rules untuk Semua Members

1. **SELALU `git pull` dulu** sebelum start kerja
2. **SELALU `git push`** lepas habis kerja
3. **JANGAN edit** `styles.css` tanpa bagitau leader dulu
4. Letak semua gambar dalam folder `/images/`
5. Setiap page ada `<!-- TODO -->` comments — ikut tu sebagai guide

---

## 🎨 Color Variables (dalam styles.css)

```css
--primary       → #7C3AED  (Purple)
--primary-light → #A78BFA  (Purple muda)
--accent        → #F59E0B  (Yellow)
--lavender      → #EDE9FE  (Background)
--text          → #1F2937  (Text gelap)
--text-light    → #6B7280  (Text muda)
```

Guna variables ni dalam CSS korang supaya design consistent!

---

## 📦 tutors.json Structure

Bila korang nak tambah tutor baru dalam JSON, ikut structure ni:

```json
{
  "id": 1,
  "name": "Nama tutor",
  "subject": "Subjek",
  "level": "SPM / PT3 etc",
  "rating": 4.5,
  "reviews": 20,
  "price": 35,
  "location": "KL",
  "image": "images/tutor1.jpg",
  "about": "Bio tutor",
  "pwdFriendly": true,
  "instantBooking": true,
  "tutorAge": 28
}
```

---

## 👥 Task Division

| Member | Page | File |
|--------|------|------|
| Member 1 (Leader) | Home Page + Setup | index.html |
| Member 2 | Tutor Listing | listing.html |
| Member 3 | Tutor Profile | profile.html |
| Member 4 | Booking + Chat | booking.html, chat.html |

---

## 🔗 Links between Pages

```
index.html → listing.html       (button "View All Tutors")
listing.html → profile.html     (click tutor card) ?id=1
profile.html → booking.html     (button "Book Session") ?id=1
profile.html → chat.html        (button "Chat Now") ?id=1
```
