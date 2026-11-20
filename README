# 🐝 BeeWise - Gamified Student Productivity App

**BeeWise** adalah aplikasi pelacak produktivitas interaktif berbalut gamifikasi berbasis iOS yang dirancang khusus untuk membantu mahasiswa mengelola aktivitas harian, mengatasi prokrastinasi, dan membangun kebiasaan produktif melalui pengalaman merawat lebah peliharaan virtual.

---

## 📸 Preview App

| Home & Task List | Pet Room (Gamifikasi) | Share Achievement |
| :---: | :---: | :---: |
| Kategori tugas harian (**Hari Ini**) & mendatang (**Terjadwal**) | Rawat lebah virtual dengan **Pet Points (Nektar)** | Kartu apresiasi eksklusif siap bagikan ke media sosial |

---

## 🌟 Fitur Utama

* **📝 Smart Task Management:**
  * Pengelompokan tugas berdasarkan **Hari Ini** dan **Terjadwal**.
  * Penjadwalan tanggal dan waktu yang presisi.
  * *Checklist* interaktif untuk memantau progres tugas harian.

* **🎮 Virtual Pet Gamification (Lebah):**
  * Pengguna mendapatkan **Pet Points (Nektar)** setiap kali menyelesaikan tugas.
  * Poin nektar digunakan untuk memberi makan lebah di *Pet Room* agar berevolusi ke tahap berikutnya (Level 1–5).
  * Pengurangan poin jika tugas terabaikan untuk mendorong konsistensi harian.

* **🎵 Sound & Visual Effects:**
  * Animasi interaktif (Lottie) saat menyelesaikan tugas dan menaikkan level lebah.
  * Efek suara (*shimmer*, *check*, dan *fanfare*) saat berinteraksi dengan aplikasi.

* **📲 Social Share Achievement:**
  * Membuka **Kartu Pencapaian Eksklusif** setelah mengumpulkan 10 Pet Points.
  * Fitur berbagi langsung ke Instagram Stories atau media sosial lain menggunakan *iOS Native Share Sheet*.

---

## 🛠️ Arsitektur & Teknologi

Aplikasi ini dikembangkan secara native untuk ekosistem iOS menggunakan arsitektur modular yang rapi:

* **Language:** Swift 5+
* **UI Framework:** SwiftUI
* **Persistence & State Management:** SwiftData / CoreData & `@Environment`
* **Audio & Effects:** AVFoundation (SoundManager)
* **Animations:** Lottie Framework (Airbnb)
* **Architecture Pattern:** MVVM (Model-View-ViewModel)

---

## 📂 Struktur Folder Proyek

```text
BeeWise/
├── BeeWise/
│   ├── MyApp.swift                # App Entry Point
│   ├── BuildConfig.swift          # Konfigurasi Build
│   ├── Models/                    # Data Model
│   │   ├── ReminderModel.swift
│   │   └── NoteModel.swift
│   ├── Views/                     # Tampilan Utama (UI Screen)
│   │   ├── HomeView.swift
│   │   ├── HariIniView.swift
│   │   ├── Terjadwal.swift
│   │   ├── PetRoomView.swift
│   │   ├── ShareModalView.swift
│   │   ├── NotesView.swift
│   │   ├── NoteDetailView.swift
│   │   ├── AddReminderSheet.swift
│   │   └── ContentView.swift
│   ├── Components/                # Komponen UI Reusable
│   │   ├── FloatingToolbar.swift
│   │   ├── SuccessModalView.swift
│   │   ├── EmptyStateView.swift
│   │   ├── LottieView.swift
│   │   └── Theme.swift
│   ├── Managers/                  # Logic & Services Manager
│   │   ├── SoundManager.swift
│   │   ├── NotificationManager.swift
│   │   └── EventStoreManager.swift
│   ├── Resources/                 # Animasi & Audio Assets
│   │   ├── happy-bee.json
│   │   ├── confetti.json
│   │   ├── trophy.json
│   │   ├── empty-box.json
│   │   └── Sounds/                # Audio (.wav)
│   └── Assets.xcassets/           # Image assets, Icon & Color Set
└── BeeWise.xcodeproj              # File Proyek Xcode
```

---

## 🚀 Cara Menjalankan Proyek

1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/0Yukine/BeeWise.git
   ```
2. Buka file `BeeWise.xcodeproj` menggunakan **Xcode 15** atau versi yang lebih baru di Mac.
3. Tunggu hingga Xcode selesai memverifikasi *Package Dependencies* (`Lottie`).
4. Pilih *Target Simulator* (misalnya: **iPhone 15 Pro** atau **iPhone 16 Pro**).
5. Tekan tombol **Run** atau `Cmd + R` untuk menjalankan aplikasi.

---

## 👥 Tim Pengembang (Development Team)

Proyek ini dikembangkan sebagai bagian dari **Challenge-Based Learning (CBL)**:

* **Nama Proyek:** BeeWise
* **Repositori GitHub:** [0Yukine/BeeWise](https://github.com/0Yukine/BeeWise)

---

*BeeWise: Produktivitasmu, Keseruanmu!* 🍯🐝
