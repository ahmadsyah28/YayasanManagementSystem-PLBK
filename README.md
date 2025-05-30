# 🏢 Sistem Manajemen Yayasan - Spesifikasi Komponen OCL

Repository ini berisi **Spesifikasi Komponen Object Constraint Language (OCL)** untuk *Sistem Manajemen Yayasan* yang dikembangkan sebagai bagian dari tugas akhir mata kuliah **Perangkat Lunak Berbasis Komponen (PLBK)**.

## 📌 Gambaran Umum

Tujuan dari proyek ini adalah untuk memodelkan komponen-komponen utama dari Sistem Manajemen Yayasan menggunakan **spesifikasi OCL** yang tepat dan formal. Komponen-komponen ini merupakan bagian dari arsitektur sistem modular yang dirancang untuk mengelola operasi yayasan secara efisien, termasuk manajemen pengurus, donasi, dan pelaporan keuangan.

## 🧩 Komponen OCL

Proyek ini mencakup tiga spesifikasi interface OCL utama:

| ID Interface          | Deskripsi                                |
|-----------------------|--------------------------------------------|
| `IKetuaYayasanMgt`    | Menangani operasi yang berkaitan dengan manajemen pengurus yayasan oleh ketua yayasan, termasuk menambah, memperbarui, dan menghapus data pengurus. |
| `IPengurusYayasanMgt` | Mengelola operasi donasi dan pelaporan keuangan oleh pengurus yayasan, termasuk pencatatan donasi dan alokasi dana. |
| `ILaporanDanaMgt`     | Mengelola operasi laporan keuangan, termasuk pembuatan, pembaruan, dan penghapusan laporan dana. |

Setiap interface berisi signature method, precondition, postcondition, dan invariant sesuai dengan standar OCL.

---

## 🎥 Link Presentasi

Anda dapat mengakses presentasi proyek di sini:  
👉 [Video](https://youtu.be/oar_JJEry0c?feature=shared)
👉 [Slide](https://www.canva.com/design/DAGo4frD1EE/fDdNVYJ_HnpYoQ_71EoDVw/edit?utm_content=DAGo4frD1EE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## 👨‍💻 Penulis

Proyek ini dikembangkan oleh:

- **Ahmad Syah Ramadhan** (NPM: 2208107010033)  
- **Hidayat Nur Hakim** (NPM: 2208107010063)

> Diserahkan sebagai tugas akhir untuk mata kuliah **Perangkat Lunak Berbasis Komponen**.
