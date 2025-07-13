Frontend Developer Intern Test
PT Aksamedia Mulia Digital
📝 Deskripsi Aplikasi
Aplikasi ini dikembangkan sebagai bagian dari proses seleksi magang Frontend Developer di PT Aksamedia Mulia Digital. Dibangun dengan teknologi modern, aplikasi ini mencakup berbagai fitur penting untuk menguji kemampuan pengembangan frontend, termasuk:

🔐 Sistem Autentikasi (Login/Logout)

🌓 Dark/Light Mode (termasuk dukungan preferensi OS)

📊 Operasi CRUD dengan fitur pencarian, filter, dan paginasi

👤 Manajemen Profil Pengguna

💾 State Persistence menggunakan localStorage dan URL query parameters

📱 Desain Responsif dengan Tailwind CSS

✨ Fitur yang Diimplementasikan
🔐 Authentication
✔ Login menggunakan username & password statis
✔ Nama pengguna ditampilkan di navbar
✔ Dropdown menu untuk logout (custom tanpa library)
✔ Protected routes (hanya bisa diakses setelah login)

🌓 Dark/Light Mode
✔ Toggle antara dark/light mode
✔ Mendeteksi preferensi sistem OS secara otomatis
✔ State tetap terjaga meskipun halaman di-refresh

📊 CRUD Operations
✔ Create, Read, Update, Delete data
✔ Fitur pencarian & filter
✔ Pagination custom (tanpa library pihak ketiga)
✔ State tersimpan di URL (halaman & keyword tetap setelah refresh)

👤 User Profile
✔ Edit nama pengguna
✔ Perubahan langsung ter-refresh di navbar

⚙️ Teknologi yang Digunakan
React.js (Vite)

Tailwind CSS

React Router

LocalStorage (tanpa API eksternal)

🚀 Cara Menjalankan Aplikasi
📋 Prerequisites
Node.js (v16 atau lebih baru)

npm atau yarn

⚙️ Instalasi
Clone repository:

bash
git clone [URL_REPOSITORY]
cd nama-folder-project
Install dependencies:

bash
npm install
atau

bash
yarn install
🖥️ Menjalankan Development Server
bash
npm run dev
atau

bash
yarn dev
Aplikasi akan berjalan di http://localhost:5173 (default Vite).

🔧 Build untuk Produksi
bash
npm run build
Hasil build akan tersedia di folder dist.

🔑 Credential Login
Untuk mengakses aplikasi, gunakan salah satu kombinasi berikut:

Username	Password	Nama Pengguna
admin	admin123	Administrator
user	user123	Regular User
📂 Struktur Folder
text
src/
├── components/    # Komponen reusable (Navbar, Dropdown, dll)
├── pages/         # Halaman utama (Login, CRUD, Profile)
├── utils/         # Fungsi utility (auth, crud operations)
├── App.jsx        # Main App component
├── main.jsx       # Entry point React
└── index.css      # Global styles
🌐 Deployment
Aplikasi dapat di-deploy di berbagai platform seperti:

Vercel

Netlify

GitHub Pages

Firebase Hosting

Contoh Deployment dengan Vercel
Install Vercel CLI:

bash
npm install -g vercel
Login:

bash
vercel login
Deploy:

bash
vercel
📌 Catatan Penting
🔒 Tidak menggunakan API – Semua data disimpan di localStorage.

🎨 Tidak menggunakan library UI (Material UI, Chakra UI, dll).

🛠️ Full custom components (dropdown, pagination, dll).

⚡ State management menggunakan React hooks dan localStorage.

📬 Kontribusi
Jika ingin berkontribusi atau memperbaiki bug, silakan buka Pull Request.

© 2024 | Dibuat untuk Tes Magang PT Aksamedia Mulia Digital
🔗 Deployed Link: https://your-deployment-link.com
📁 GitHub Repo: https://github.com/your-repo
