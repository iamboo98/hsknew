# Ví Của Tôi – Quản lý thu chi & tiết kiệm

App web (PWA) một trang, không cần máy chủ, hoạt động offline.

## Link
- **App (GitHub Pages):** https://iamboo98.github.io/hsknew/finance/ — chỉ hoạt động sau khi bật GitHub Pages (xem bên dưới).
- **Mã nguồn:** https://github.com/iamboo98/hsknew/tree/claude/income-expense-tracker-app-ir2l64/finance
- **Bản xem trên Claude (riêng tư):** https://claude.ai/artifact/Cquhj7xTEfwzPfXdbFsXo7

## Bật GitHub Pages
1. Mở https://github.com/iamboo98/hsknew/settings/pages
2. **Source** → *Deploy from a branch*.
3. **Branch** → `main` (sau khi gộp) hoặc `claude/income-expense-tracker-app-ir2l64`, thư mục `/ (root)` → **Save**.
4. Đợi 1–2 phút rồi mở https://iamboo98.github.io/hsknew/finance/

## Cài lên điện thoại
- **iPhone:** mở link bằng Safari → Chia sẻ → *Thêm vào MH chính*.
- **Android:** mở bằng Chrome → menu ⋮ → *Cài đặt ứng dụng / Thêm vào màn hình chính*.

Lưu ý: dữ liệu thu chi lưu trong trình duyệt của từng thiết bị, không đồng bộ giữa các máy. Dùng nút *Xuất sao lưu* / *Nhập từ file sao lưu* trong tab **Ngân sách** để chuyển dữ liệu.

## Tính năng
- **Thu / Chi**: ghi nhanh bằng nút **+**, gõ tắt số tiền (`50k`, `1.5tr`, `2 triệu`), chọn danh mục, ngày, ghi chú. Nhấn vào giao dịch để sửa/xóa (có Hoàn tác).
- **Tổng quan theo thời gian thực**: số dư, thu/chi/tiết kiệm của tháng, tỷ lệ tiết kiệm, so sánh với tháng trước, biểu đồ 6 tháng, đường chi tiêu tích lũy trong tháng kèm dự báo và gợi ý "được chi bao nhiêu mỗi ngày".
- **Ngân sách**: hạn mức cho từng danh mục; cảnh báo khi dùng 80% và khi vượt.
- **Mục tiêu tiết kiệm**: số tiền, hạn chót, biểu tượng; góp / rút tiền; tính số cần để dành mỗi tháng/ngày và trạng thái *đúng tiến độ / chậm tiến độ / hoàn thành*.
- **Thời gian thực**: mọi thay đổi tự lưu và tính lại ngay; đồng bộ tức thì giữa các tab/cửa sổ đang mở; tự chuyển ngày/tháng lúc nửa đêm.
- **Lưu ngay sau khi nhập**: mỗi lần thêm/sửa/xóa đều tự lưu vào trình duyệt; góc trên hiện chữ **"Đã lưu"** (đổi thành "⚠️ Chưa lưu" nếu trình duyệt chặn bộ nhớ). Dữ liệu vẫn còn khi tắt app, tải lại trang hay khởi động lại máy.
- **Tải về & tải lên lại (sao lưu / khôi phục)**: bấm nút ⬇️ trên thanh trên cùng (hoặc tab **Ngân sách → Sao lưu & khôi phục**):
  - *Tải bản sao lưu về máy* → file `vi-cua-toi-NGÀY-GIỜ.json`.
  - *Tải lên file sao lưu để khôi phục* → chọn **Gộp** (thêm phần chưa có, giữ dữ liệu hiện tại) hoặc **Thay thế** (dùng hoàn toàn dữ liệu trong file). Có nút *Hoàn tác* nếu chọn nhầm.
  - App hiển thị thời điểm lưu và sao lưu gần nhất, và nhắc tải sao lưu nếu đã quá 7 ngày.
  - Xuất thêm file CSV để mở bằng Excel. Có nút tạo dữ liệu mẫu để dùng thử.
- Giao diện sáng/tối, tối ưu cho điện thoại.

## Cách tính
- Số dư khả dụng = Tổng thu − Tổng chi − Tiền đã chuyển vào mục tiêu.
- Tài sản ròng = Số dư khả dụng + Tổng đã để dành.
- Tỷ lệ tiết kiệm tháng = (Thu − Chi) / Thu.

## Logo
Logo riêng của app: chiếc **ví** màu trắng với chữ **V** (Ví) màu vàng vút lên thành **mũi tên tăng trưởng**, nghĩa là tiền vào ví và tài chính đi lên.
- File gốc dạng vector: `finance/icon.svg` (phóng to bao nhiêu cũng nét).
- Ảnh PNG: `finance/icon-512.png`, `icon-192.png`, `icon-180.png`.
- Bảng nhận diện (logo, cách ghép với tên app, mã màu): `finance/logo-preview.png`.
- Màu chính: Teal `#14918a`, Deep teal `#0b4f5c`, Gold `#ffd76e`, Amber `#f0a92e`, White `#ffffff`.
