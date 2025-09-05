# Furniture Shop

Ứng dụng web bán đồ nội thất được xây dựng với **Node.js** và **Express.js**.  
Hệ thống hỗ trợ quản lý sản phẩm, giỏ hàng, đặt hàng và quản trị đơn hàng.

---

## Tính năng chính

### Người dùng
- Xem danh sách sản phẩm.  
- Thêm sản phẩm vào giỏ hàng.  
- Đặt hàng và thanh toán.  

### Quản trị viên
- Quản lý sản phẩm (CRUD).  
- Quản lý đơn hàng.  
- Quản lý người dùng.  

---

## Công nghệ sử dụng

- Node.js  
- Express.js  
- MongoDB / MySQL (tùy chọn)  
- EJS / React / Vue (nếu có frontend)  
- JWT / Bcrypt (xác thực và bảo mật)  
- RESTful API  

---

## Cài đặt và chạy ứng dụng

### 1. Clone repository
```bash
git clone https://github.com/nguyendat13/furniture-shop.git
cd furniture-shop
2. Cài đặt package
npm install

3. Chạy ứng dụng
npm start


Ứng dụng sẽ chạy tại http://localhost:3000 (hoặc theo cấu hình của bạn).

Cấu trúc dự án (tham khảo)
├── models/        # Định nghĩa schema và kết nối database
├── routes/        # Các route cho sản phẩm, giỏ hàng, đơn hàng, người dùng
├── controllers/   # Xử lý logic cho từng route
├── views/         # Giao diện (nếu dùng EJS)
├── public/        # File tĩnh (CSS, JS, images)
├── app.js         # Điểm khởi đầu ứng dụng
└── config/        # Cấu hình (database, JWT, v.v.)
