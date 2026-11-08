# Bookstore RESTful API (NestJS - UTS)

Proyek Ujian Tengah Semester (UTS) Pemrograman Web / API menggunakan framework **NestJS**, mengimplementasikan arsitektur modular, validasi data DTO, serta operasi CRUD lengkap untuk manajemen data buku.

## 🛠️ Tech Stack
- **Framework:** NestJS (TypeScript)
- **Architecture:** Modular Architecture (Controller, Service, DTO, Module)
- **Validation:** `class-validator` & `class-transformer`
- **Testing Tool:** Postman

---

## 🚀 Endpoints API (/books)

Base URL: `http://localhost:3000`

| Method | Endpoint | Deskripsi | Request Body / Parameter |
| :--- | :--- | :--- | :--- |
| **POST** | `/books` | Menambahkan data buku baru | `{ "title": "string", "author": "string", "year": number }` |
| **GET** | `/books` | Menampilkan seluruh daftar buku | - |
| **GET** | `/books/:id` | Menampilkan detail buku berdasarkan ID | Parameter URL `:id` |
| **PATCH** | `/books/:id` | Memperbarui data buku berdasarkan ID | `{ "title": "string", ... }` |
| **DELETE** | `/books/:id` | Menghapus data buku berdasarkan ID | Parameter URL `:id` |

---

## ⚙️ Cara Menjalankan Project

1. Clone repository ini atau download foldernya.
2. Install dependencies:
   ```bash
   npm install
