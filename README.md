# 🎓 Joki Platform — Multi-Role Service Marketplace

Joki Platform adalah website marketplace jasa joki berbasis web yang memungkinkan pengguna memesan jasa dari penjoki profesional, melakukan pembayaran manual, berkomunikasi, serta mengikuti sesi meeting online. Sistem ini dibangun menggunakan Laravel dengan arsitektur yang aman, scalable, dan mendukung multi-role: User, Penjoki, dan Admin.

Project ini dirancang sebagai implementasi fullstack marketplace service dengan sistem autentikasi, manajemen order, verifikasi pembayaran, komunikasi, dan workflow layanan end-to-end.

---

# 🚀 Features

## 👤 User (Client)
- Register & Login
- Browse layanan jasa penjoki
- Filter layanan berdasarkan kategori dan harga
- Order jasa
- Upload bukti pembayaran manual
- Tracking status order
- Chat dengan penjoki
- Join meeting (Zoom / Google Meet)
- Memberikan rating dan review

## 🧑‍💻 Penjoki (Freelancer)
- Register & login sebagai penjoki
- Kelola profil dan portofolio
- CRUD layanan jasa
- Terima atau tolak order
- Upload link meeting
- Update status pengerjaan
- Chat dengan user
- Riwayat order dan penghasilan

## 🛡️ Admin
- Dashboard admin
- Verifikasi bukti pembayaran
- Approve / reject transaksi
- Kelola user dan penjoki
- Suspend akun
- Monitoring aktivitas platform

---

# 💳 Payment System

Metode pembayaran menggunakan manual transfer:

1. User melakukan transfer
2. User upload bukti pembayaran
3. Admin memverifikasi pembayaran
4. Order diaktifkan
5. Penjoki memulai pengerjaan

---

# 🧱 Built With

- Laravel
- PHP
- MySQL / PostgreSQL
- Blade Template
- Tailwind CSS
- JavaScript

---

# 🔐 Security Features

- Authentication system
- Role-based access control (RBAC)
- Password hashing
- CSRF protection
- Input validation
- Secure file upload handling

---

# 🔄 Workflow

User Order Service  
→ Upload Payment Proof  
→ Admin Verify Payment  
→ Order Activated  
→ Penjoki Provide Meeting Link  
→ Service Completed  
→ User Gives Review  

---

# 🎯 Purpose

Project ini dibuat untuk:

- Portfolio Fullstack Developer
- Implementasi marketplace system
- Learning advanced Laravel architecture
- Simulasi platform freelance service

---

# 🌟 Future Improvements

- Payment gateway integration
- Realtime chat system
- Email notification
- Escrow payment system
- Admin analytics dashboard

---

# 👨‍💻 Author

**Abdul Kader**  
Fullstack Web Developer  
Laravel • System Analyst • Web Developer

---

# 📄 License

This project is open-source and available under the MIT License.
