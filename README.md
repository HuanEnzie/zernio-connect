# Zernio Connect

Công cụ một file HTML cho Zernio: dán nhiều API key để tạo link kết nối TikTok, Facebook, YouTube, Instagram; quét profile ID và account ID có nút copy; quét thông số video theo kênh.

## Dùng

Mở `index.html` bằng Chrome (bấm đúp). Dán API key vào Kho API, key chỉ nằm trong bộ nhớ trang và mất khi tải lại.

- Mỗi key nối được tối đa 2 kênh. Kênh chưa có profile sẽ được tạo mới trên Zernio khi bấm Tạo link.
- Link kết nối hết hạn sau khoảng 1 giờ.
- Quét thông số lấy tối đa 500 bài mới nhất mỗi key.

Trang gọi trực tiếp `https://zernio.com/api/v1` từ trình duyệt, không có máy chủ trung gian.
