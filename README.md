# HAVEN SCSS Project

## 📌 Giới thiệu
Dự án web tĩnh sử dụng **HTML** và **SCSS** để học responsive design.

---

## 🚀 Hướng dẫn cài đặt

### 1. Cài Node.js và npm
- Vào trang [https://nodejs.org](https://nodejs.org) → tải bản **LTS** (Long Term Support).  
- Cài đặt như phần mềm bình thường.  
- Kiểm tra đã cài thành công chưa:
  ```bash
  node -v
  npm -v
Nếu hiện phiên bản (ví dụ v20.x, 10.x) là OK.

2. Clone repo về máy
bash
Copy code
git clone https://github.com/phuonggg312/SCSS.git
cd SCSS
3. Cài đặt dependencies (thư viện cần thiết)
bash
Copy code
npm install
4. Chạy ở chế độ phát triển (theo dõi SCSS → CSS)
bash
Copy code
npm run dev
5. Build ra CSS nén (dùng cho production)
bash
Copy code
npm run build
6. Mở dự án
Mở file index.html bằng trình duyệt
(có thể dùng extension Live Server trong VS Code để chạy nhanh).

📂 Cấu trúc thư mục
arduino
Copy code
assets/
  scss/   # chứa file .scss
  css/    # chứa file .css được biên dịch
index.html
package.json
