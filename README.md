# 🎧 Music App — Fullstack Project

## 📌 Giới thiệu

Music App là web nghe nhạc mini được xây dựng nhằm mục đích học tập và thực hành Fullstack Development.
Project gồm frontend (React) và backend (Node.js + Express) tách riêng.

---

## 🧠 Tech Stack

### Frontend

* React + Vite
* Axios
* React Router
* CSS / Tailwind (nếu dùng)

### Backend

* Node.js
* Express
* MongoDB (dự kiến)

---

## 📂 Cấu trúc Project

```
Music_App
│
├── frontend   → React app
├── backend    → API server
├── .env.example
├── .gitignore
└── README.md
```

---

## 🚀 Cách chạy project (Local)

### 1️⃣ Clone repo

```
git clone <repo_url>
cd Music_App
```

---

### 2️⃣ Chạy Backend

```
cd backend
npm install
node server.js
```

Server chạy tại:

```
http://localhost:5000
```

---

### 3️⃣ Chạy Frontend

```
cd frontend
npm install
npm run dev
```

Frontend chạy tại:

```
http://localhost:5173
```

---

## 🌿 Git Workflow Team

⚠ Không push trực tiếp vào `main` hoặc `develop`

Flow chuẩn:

```
feature branch → Pull Request → develop → main
```

---

## 🏷 Quy tắc đặt tên branch

```
feature/frontend-player
feature/backend-auth
bugfix/audio-error
```

---

## 📝 Quy tắc commit

```
feat: thêm tính năng
fix: sửa lỗi
style: chỉnh giao diện
refactor: tối ưu code
docs: cập nhật tài liệu
```

Ví dụ:

```
feat: add music player
fix: login bug
```

---

## 🔐 Environment Variables

Tạo file `.env` trong thư mục backend:

```
PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
```

---

## 👥 Quy tắc làm việc nhóm

* Pull code trước khi code
* Mỗi task = 1 branch
* Không sửa file người khác khi chưa trao đổi
* Code xong → tạo Pull Request

---

## 📡 API dự kiến

```
GET /api/songs
POST /api/login
POST /api/upload
GET /api/playlists
```

---

## 🎯 Mục tiêu project

* Xây dựng web nghe nhạc hoạt động thật
* Áp dụng kiến thức frontend + backend
* Làm quen workflow team dev

---

## 👨‍💻 Contributors

| Name | Role     |
| ---- | -------- |
|   Văn và Khoa  | Frontend |
|   Anh Long và Tuấn   | Backend  |
|      | UI       |

---

## ⭐ Ghi chú

Project phục vụ mục đích học tập — không dùng cho thương mại.
