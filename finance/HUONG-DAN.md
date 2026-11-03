# Ví Của Tôi – Quản lý thu chi & tiết kiệm

App web (PWA) một trang, không cần máy chủ, hoạt động offline. Mở `finance/index.html` qua một địa chỉ http(s) (Netlify Drop, GitHub Pages…) để cài lên màn hình chính.

## Tính năng
- **Thu / Chi**: ghi nhanh bằng nút **+**, gõ tắt số tiền (`50k`, `1.5tr`, `2 triệu`), chọn danh mục, ngày, ghi chú. Nhấn vào giao dịch để sửa/xóa (có Hoàn tác).
- **Tổng quan theo thời gian thực**: số dư, thu/chi/tiết kiệm của tháng, tỷ lệ tiết kiệm, so sánh với tháng trước, biểu đồ 6 tháng, đường chi tiêu tích lũy trong tháng kèm dự báo và gợi ý "được chi bao nhiêu mỗi ngày".
- **Ngân sách**: hạn mức cho từng danh mục; cảnh báo khi dùng 80% và khi vượt.
- **Mục tiêu tiết kiệm**: số tiền, hạn chót, biểu tượng; góp / rút tiền; tính số cần để dành mỗi tháng/ngày và trạng thái *đúng tiến độ / chậm tiến độ / hoàn thành*.
- **Thời gian thực**: mọi thay đổi tự lưu và tính lại ngay; đồng bộ tức thì giữa các tab/cửa sổ đang mở; tự chuyển ngày/tháng lúc nửa đêm.
- **Dữ liệu**: lưu trên thiết bị (localStorage). Xuất/nhập sao lưu JSON, xuất CSV mở bằng Excel. Có nút tạo dữ liệu mẫu để dùng thử.
- Giao diện sáng/tối, tối ưu cho điện thoại.

## Cách tính
- Số dư khả dụng = Tổng thu − Tổng chi − Tiền đã chuyển vào mục tiêu.
- Tài sản ròng = Số dư khả dụng + Tổng đã để dành.
- Tỷ lệ tiết kiệm tháng = (Thu − Chi) / Thu.
