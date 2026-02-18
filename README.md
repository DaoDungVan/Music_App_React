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
* MongoDB (Cloud)

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

# 🚀 Cách chạy project (Local)

### 1️⃣ Clone repo

```
git clone <repo_url>
cd Music_App
git checkout develop
```

---

### 2️⃣ Cài thư viện

```
cd backend
npm install

cd ../frontend
npm install
```

---

### 3️⃣ Setup Environment Variables

Tạo file:

```
backend/.env
```

Copy nội dung từ:

```
.env.example
```

Ví dụ:

```
PORT=5000
MONGO_URI=your_database_url
JWT_SECRET=your_secret
```

---

### 🌐 Database (MongoDB Cloud)

Project sử dụng MongoDB Cloud (Atlas) để toàn bộ team dùng chung database.

Bước setup:

1. tạo file:

```
backend/.env
```

2. thêm dòng:

```
MONGO_URI=link_database
```

3. nếu chưa có link database → hỏi người làm database

⚠ **Không commit file `.env` lên GitHub**

---

### 4️⃣ Chạy Backend

```
cd backend
node server.js
```

Server chạy tại:

```
http://localhost:5000
```

---

### 5️⃣ Chạy Frontend

```
cd frontend
npm run dev
```

Frontend chạy tại:

```
http://localhost:5173
```

---

# 👨‍💻 Hướng dẫn cho thành viên mới tham gia team

Sau khi clone repo:

```
git checkout develop
```

---

### Khi bắt đầu làm task mới

```
git checkout develop
git pull origin develop
git checkout -b feature/tên-task
```

Ví dụ:

```
feature/player-ui
feature/login-api
feature/song-list
```

---

### Sau khi code xong

```
git add .
git commit -m "feat: mô tả chức năng"
git push origin feature/tên-task
```

---

### Sau đó

➡ Lên GitHub → tạo **Pull Request → merge vào develop**

---

### Sau khi merge xong phải update code mới

```
git checkout develop
git pull origin develop
```

---

# 🌿 Git Workflow Team

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

## 👥 Quy tắc làm việc nhóm

* Pull code trước khi code
* Mỗi task = 1 branch
* Không sửa code người khác khi chưa trao đổi
* Code xong → tạo Pull Request
* Không commit code lỗi

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

| Name             | Role     |
| ---------------- | -------- |
| Văn và Khoa      | Frontend |
| Anh Long và Tuấn | Backend  |
|                  | UI       |

---

## ⭐ Ghi chú

Project phục vụ mục đích học tập — không dùng cho thương mại.
