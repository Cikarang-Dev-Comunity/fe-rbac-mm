📌 Deskripsi

Service frontend untuk Role Based Access Control (RBAC), mengatur hak akses user (admin, member).

⚙️ Tech Stack
- React.js
- Webpack 5

🔗 Integrasi
Diekspos ke fe-host-mm sebagai remote module.

📝 Catatan
- Centralisasi role di backend, FE hanya konsumsi data & enforce UI.
- Gunakan HOC / ProtectedRoute agar halaman sesuai hak akses.

🏗 Arsitektur
- Microfrontend: independen, di-load via host.
- Microservices: komunikasi ke service RBAC backend.