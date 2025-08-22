# 🌐 Hệ thống quản lý hồ sơ hợp đồng nhân sự thông minh

<img width="1616" height="558" alt="image" src="https://github.com/user-attachments/assets/3df79942-afd0-4f7b-b899-b78e4c882d4b" />

---

## 🏫 Thông tin dự án
- **Đề tài:** Hệ thống quản lý hồ sơ hợp đồng nhân sự thông minh  
- **Đơn vị thực hiện:** Khoa Công Nghệ Thông Tin - Trường Đại học Đại Nam  
- **Phòng Lab:** AIoT Lab  
- **Mục tiêu:** 
  - Số hóa và quản lý hợp đồng nhân sự.  
  - Lưu trữ, tra cứu, tìm kiếm thông minh.  
  - Tích hợp OCR để nhận diện văn bản từ hợp đồng scan.  
  - Ứng dụng Web thân thiện, dễ triển khai.  

---

## ⚙️ Công nghệ sử dụng
### 🔹 Frontend
- **Next.js 13+ (React framework)**  
- **Tailwind CSS**  
- **PostCSS**  

### 🔹 Backend
- **Python 3.10+**  
- **FastAPI / Flask** (tùy framework bạn dùng)  
- **Tesseract OCR** (xử lý ảnh văn bản)  

### 🔹 Database
- **SQLite / PostgreSQL / MySQL** (tùy cấu hình bạn chọn)  

---

## 🚀 Cách chạy dự án

### 🔹 1. Chạy Frontend (Next.js)
```bash
cd app
npm install
npm run dev
cd python-backend
python -m venv .venv
source .venv/bin/activate   # (Linux/Mac)
.venv\Scripts\activate      # (Windows)

pip install -r requirements.txt
uvicorn main:app --reload   # Nếu dùng FastAPI
# hoặc: flask run           # Nếu dùng Flask
