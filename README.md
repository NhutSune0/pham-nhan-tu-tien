# Phàm Nhân Tu Tiên

Fan game tu tiên **phi lợi nhuận** — hành trình từ một thiếu niên phàm nhân thôn quê bước lên con đường tu tiên: luyện khí, trúc cơ, kết đan, nguyên anh.

- Server: Node.js + WebSocket (server-authoritative, 20 tick/s)
- Client: Canvas 2D, pixel art
- Lưu nhân vật tự động (file JSON)

## Chạy local

```bash
npm install
npm start   # hoặc: node server.js (PORT mặc định 3000)
```

Mở http://localhost:3000

## Deploy Render

- Build: `npm install`
- Start: `node server.js`

## Tính năng (v1)

- 4 đạo tu luyện: Kiếm Tu, Phù Tu, Khôi Lỗi Sư, Đan Đỉnh (+ Phàm Nhân khởi đầu)
- Cảnh giới: Luyện Khí → Trúc Cơ → Kết Đan → Nguyên Anh
- **Bình thần bí**: kỳ ngộ đầu game — tăng sản lượng linh thảo, tăng tỉ lệ luyện đan
- **Luyện đan**: thu thập linh thảo → luyện Tụ Khí Đan, Trúc Cơ Đan, Hồi Xuân Đan
- Độ kiếp: Cửu Cửu Lôi Kiếp 9 đợt để đột phá Trúc Cơ
- Trang bị 6 ô, 4 phẩm chất, cường hóa
- Chuỗi nhiệm vụ chính 10 quest, chế độ Auto

Fork/retheme từ engine Thiên Kiêu Lộ. Mọi nhân vật, cốt truyện trong game là sáng tạo mới lấy cảm hứng từ thể loại phàm nhân tu tiên.
