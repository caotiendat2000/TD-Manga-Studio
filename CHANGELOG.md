# Nhật Ký Cập Nhật — TD Manga Studio

Tất cả các bản phát hành chính thức của **TD Manga Studio** cho Windows (64-bit).

---

## [v1.3.4 PRO] — 26/11/2026

### Cải thiện & Sửa lỗi nổi bật
- **Cọ Phục hồi (`Y`):**
  - Sửa lỗi không phục hồi được khi tô đè lên nét vẽ từ Cọ vẽ Manga (`R`) và tẩy; đồng bộ chính xác kể cả khi kích thước ảnh gốc khác ảnh làm việc.
  - Khắc phục hoàn toàn lỗi xem trước vùng cọ bị lem ra ngoài mép tranh khi rê chuột quá biên.
  - Tối ưu mạnh tốc độ xử lý khi thả chuột cho **Cọ Phục hồi (`Y`)**, **Dấu sao chép (`S`)** và **Lấp dải màu (`P`)**: giảm rõ rệt độ trễ trên trang truyện độ phân giải cao và Webtoon dài.
  - Hỗ trợ **Hoàn tác / Làm lại (`Ctrl+Z` / `Ctrl+Y`)** và nút hoàn tác nét vẽ ổn định, chính xác từng bước.
- **Phím `Space` soi ảnh gốc:**
  - Sửa lỗi nhấn giữ phím `Space` để đối chiếu ảnh gốc sau khi chuyển trang hoặc chỉnh sửa bị tự động nhảy sang trang khác.
- **Bộ cài đặt trực tuyến (`Online Setup v1.3.4`):**
  - Chuyển nguồn tải chính sang **GitHub Releases** tốc độ cao, không giới hạn băng thông, giữ nguyên cơ chế tạm dừng/tiếp tục và kiểm tra nguyên vẹn `SHA-256`.

---

## [v1.3.3 PRO] — 25/11/2026

### Tính năng & Cải thiện
- Nâng cấp giao diện Studio Rust Native mượt mà hơn khi phóng to/thu nhỏ và cuộn trang Webtoon dài.
- Hoàn thiện bộ 22 hiệu ứng chữ SFX (tan biến, uốn cong theo đường dẫn, Gradient 360°, Clipping Mask).
- Tối ưu tính năng ghép/cắt trang Webtoon né bóng thoại, đóng dấu logo hàng loạt (`F12`) và xuất file Photoshop `.PSD` nhiều layer.

---

## [v1.3.2 PRO] — 19/11/2026

### Tính năng & Cải thiện
- Ra mắt trình cài đặt trực tuyến gọn nhẹ `TD_Manga_Studio_Online_Setup.exe` với giao diện Dark Mode và xác thực `SHA-256` tự động.
- Bổ sung Từ điển nhân vật & Xưng hô cố định (`F6`), lồng thoại siêu tốc phong cách TyperTools, xuất/nhập kịch bản Excel & Word và bộ kiểm tra lỗi QC toàn chương (`F7`/`F8`).
