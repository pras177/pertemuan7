# 📱 MyTaskList App

> Aplikasi task manager sederhana berbasis React Native (Expo) yang mengintegrasikan konsep P01–P06.

---

## 👤 Identitas

| Field | Isi |
|-------|-----|
| **Nama** | [Prasetya Amal Dinata] |
| **NIM** | [243303621248] |
| **Kelas** | [4 Pagi A] |

---

## 📝 Deskripsi App

MyTaskList adalah aplikasi to-do list yang memungkinkan pengguna menambah, menandai selesai, dan menghapus task harian. Setiap task dilengkapi dengan tingkat prioritas (Tinggi / Sedang / Rendah) dan filter tampilan berdasarkan status task. App ini dibangun menggunakan React Native + Expo sebagai mini project integrasi pertemuan 1–6.

---

## ✅ Fitur yang Diimplementasikan

### Requirement Wajib
- [x] **Setup & Running di HP Fisik** — Dibuat dengan `npx create-expo-app`, berjalan via Expo Go (QR scan)
- [x] **Komponen Dasar** — `View`, `Text`, `TouchableOpacity`, `StyleSheet.create`, Flexbox layout
- [x] **State Management (useState)** — 2 state utama: `inputText` dan `tasks` (array)
- [x] **Conditional Rendering** — Badge "Selesai", empty state berbeda per filter, counter
- [x] **Form Input + Validasi** — `TextInput`, `KeyboardAvoidingView`, validasi kosong & minimal 3 karakter, pesan error
- [x] **FlatList + ListEmptyComponent** — List dinamis dengan `keyExtractor`, tampilan empty state custom
- [x] **CRUD Minimal** — Add task ✅ + Delete task ✅ (dengan konfirmasi Alert)

### Fitur Bonus
- [x] **+5 Mark as Done** — Tap checkbox untuk centang/uncentang task
- [x] **+5 Prioritas Task** — Tinggi (merah) / Sedang (kuning) / Rendah (hijau) dengan warna berbeda
- [x] **+5 Counter** — "X dari Y task selesai" di header & footer
- [x] **+5 Filter View** — Tab Semua / Aktif / Selesai dengan counter per kategori
- [x] **+10 UI Rapi & Profesional** — Desain konsisten, card layout, priority stripe, badge, warna semantik

---

## 📸 Screenshot

> *(Ganti bagian ini dengan screenshot dari HP fisik kamu)*

| Home (Empty) | 
|:---:|
| ![empty](.assets/ss7.jpeg) | 

---

## 🚀 Cara Menjalankan

```bash
# 1. Clone repo
git clone https://github.com/pras177/pertemuan7.git
cd MyTaskList-App

# 2. Install dependencies
npm install

# 3. Jalankan Expo
npx expo start

# 4. Scan QR Code dengan Expo Go di HP
```

**Requirement:**
- Node.js ≥ 18
- Expo Go app (Android / iOS)
- npm / npx

---

## 🔗 Links

- **GitHub:** https://github.com/pras177/pertemuan7
- **Expo Snack:** https://snack.expo.dev/@prasetya-amal-dinata/pertemuan7

---

## 🛠 Tech Stack

| Tech | Versi |
|------|-------|
| React Native | via Expo SDK |
| Expo | Latest |
| JavaScript | ES2022 |

---

## 📁 Struktur Project

```
MyTaskList-App/
├── App.js          # Komponen utama (single-file)
├── app.json        # Konfigurasi Expo
├── package.json
└── README.md
```
