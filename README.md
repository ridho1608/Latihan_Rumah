# 🎓 Aplikasi Absensi Kampus Inovatif (MVP)

Aplikasi presensi berbasis lokasi (GPS/Wi-Fi) untuk mahasiswa berbasis mobile (Android & iOS) serta portal Web Admin untuk dosen dan program studi.

## 🚀 Tech Stack
- **Mobile:** Flutter / React Native
- **Web Admin:** React.js / Vue.js / Laravel
- **Backend:** Node.js / Laravel / Go
- **Database:** MySQL

## 📁 Struktur Repository
- `/mobile` : Source code aplikasi mahasiswa
- `/web-admin` : Source code portal web admin
- `/backend` : REST API & Database Migration
- `/docs` : Dokumentasi UI/UX & Flowchart

## 🛠️ Cara Menjalankan Project
1. Clone repo ini: `git clone https://github.com/username/absensi-kampus.git`
2. Import file database di `/backend/database/schema.sql` ke MySQL.
3. Jalankan Backend API: `cd backend && npm start`
4. Jalankan Web Admin: `cd web-admin && npm run dev`
5. Jalankan Mobile App: `cd mobile && flutter run`
