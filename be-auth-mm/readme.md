📌 Deskripsi
Service backend untuk mengatur Role Based Access Control (RBAC), menentukan hak akses user seperti admin, member, viewer.

⚙️ Tech Stack
Laravel 10

🔗 Integrasi
- Digunakan oleh fe-rbac-mm.
- Terhubung dengan be-auth-mm untuk mengaitkan user dengan role.

📝 Catatan
- Semua endpoint harus dilindungi middleware auth.
- Role dikelola terpusat agar konsisten di seluruh aplikasi.

🏗 Arsitektur
Microservices: independen, expose REST API.
Bisa diakses service lain melalui API Gateway.