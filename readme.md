📌 Deskripsi

Service backend untuk mengatur autentikasi user (register, login, refresh token, logout).

⚙️ Tech Stack

Java Quarkus

🔗 Integrasi

Digunakan oleh fe-host-mm.

Berhubungan erat dengan be-rbac-mm untuk mapping user ↔ role.

📝 Catatan

Gunakan JWT untuk authentication.

Refresh token harus disimpan dengan aman.

🏗 Arsitektur

Microservices: expose REST API.