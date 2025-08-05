# Quatle Game - Τεχνικές Αποφάσεις

## 📌 Περιγραφή
Online παιχνίδι τύπου "Quiz Battle" όπου οι χρήστες ανταγωνίζονται σε ερωτήσεις γνώσεων σε πραγματικό χρόνο.

---

## ⚙️ Τεχνολογίες

- **Frontend**: HTML, CSS, JavaScript (με δυνατότητα επέκτασης σε React)
- **Backend**: Node.js με Express.js
- **Real-time**: Socket.IO (για σύνδεση παικτών σε μάχες)
- **Database**: MongoDB ή Firebase (για χρήστες, στατιστικά, ερωτήσεις)

---

## 📁 Δομή Project

```
quatle-game/
├── client/              → Frontend (HTML/JS/CSS)
│   ├── index.html
│   ├── style.css
│   └── main.js
├── server/              → Backend (Node.js)
│   ├── server.js
│   └── socket.js
├── data/                → Ερωτήσεις, χρήστες, στατικά αρχεία
├── README.md
├── notes.md             → Τεχνικές σημειώσεις & αποφάσεις
└── package.json         → Εξαρτήσεις Node.js
```

---

## ✅ Στόχος επόμενων βημάτων

- [ ] Καταγραφή κανόνων παιχνιδιού
- [ ] Δημιουργία βασικού frontend
- [ ] Ρύθμιση server & sockets
- [ ] Matchmaking μεταξύ παικτών
- [ ] Στατιστικά & αποθήκευση προόδου

