# Trường Sơn Connect — Product Feed

Nguồn dữ liệu DÙNG CHUNG cho trang "Nhà phát triển" trong tất cả app 365
(NhaChoThue, Sàn Giá Gạo, Sell 365, Bán hàng 365, Kế toán 365…).

**Cập nhật sản phẩm mới:** sửa `products.json` → commit → mọi app tự cập nhật
(app fetch qua `raw.githubusercontent.com`, có cache ~5 phút).

App đọc URL: `https://raw.githubusercontent.com/hahoiabc/truongson-connect-brand/main/products.json`
