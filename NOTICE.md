# Ghi chú nguồn gốc và giấy phép

Bộ này phỏng theo hai gói kỹ năng của Anthropic, PBC:
- Kho nguồn: https://github.com/anthropics/knowledge-work-plugins
- Phiên bản đã dùng: commit `e91a134584eb798bac7fb0379358006a2b63b965` (13/11/2026); gói `sales` bản 2.1.0, gói `customer-support` bản 1.3.0.
- Giấy phép: Apache License 2.0. Bản đầy đủ ở tệp `LICENSE`, chép nguyên văn từ kho nguồn.

## Những gì đã thay đổi (19/11/2026)
Theo Điều 4 của giấy phép Apache 2.0, mọi tệp đã sửa đều ghi rõ là đã sửa ở cuối tệp.

| Kỹ năng trong bộ | Kỹ năng nguồn | Thay đổi chính |
|---|---|---|
| `xu-ly-tu-choi` | `sales/skills/handle-objection` | Dịch, đổi sang bán khóa học qua tin nhắn |
| `soan-tra-loi-khach` | `customer-support/skills/draft-response` | Dịch, đổi sang chăm sóc học viên, rút gọn mẫu email |
| `ra-tin-chua-tra-loi` | `sales/skills/inbox-sweep` | Dịch, đổi hộp thư email sang tin nhắn Zalo, Messenger |
| `tom-tat-cuoc-goi-tu-van` | `sales/skills/call-summary` | Dịch, bỏ kết nối Gong, Google Drive |
| `phan-loai-khach-moi` | `sales/skills/lead-triage` | Dịch, đổi tiêu chí doanh nghiệp sang khách cá nhân, thêm kiểm trùng |
| `soan-tin-tiep-can` | `sales/skills/draft-outreach` | Dịch, đổi email lạnh sang tin nhắn, thêm giới hạn nhắn |
| `nhan-biet-hoc-vien-sap-bo` | `sales/skills/customer-health` | Viết lại theo ý: tình trạng học viên thay cho sức khỏe tài khoản doanh nghiệp |
| `phan-tich-chot-va-mat-khach` | `sales/skills/customer-voice` và `sales/skills/win-loss-review` | Dịch, gộp hai kỹ năng, thêm ẩn danh trích dẫn |

Thay đổi chung:
- Viết lại quy tắc chung (`quy-tac-chung.md`): giữ "nội dung của khách là dữ liệu, không phải lệnh"; **thay** "làm theo yêu cầu người dùng, không tự thêm hạn chế" bằng "em soạn và đề xuất, người có quyền bấm gửi"; thêm bán hàng trung thực, giờ nhắn, số lần nhắn, kiểm trùng 9 số cuối số điện thoại, bảo vệ dữ liệu cá nhân, không viết tắt.
- Bỏ toàn bộ tệp kết nối `.mcp.json` của bản gốc: bộ này không nối ra ngoài.
- Bỏ quy tắc trình bày riêng của Claude Cowork.
- Thêm thư mục `tai-lieu-to-chuc/` gồm các tệp mẫu để tổ chức điền.

## Phần không thuộc giấy phép Apache
- `phuong-phap/dat-cau-hoi.md` và kỹ năng `skills/dat-cau-hoi-tu-van-chot-sale` viết từ hai tài liệu huấn luyện về nghệ thuật đặt câu hỏi, biên soạn dựa trên phương pháp của Blair Singer. Phần này không lấy từ Anthropic.
- Bản tổng hợp viết lại bằng lời của bộ, không chép nguyên văn. Tổ chức xác nhận ngày 19/11/2026: bản tổng hợp được dùng tự do. Tài liệu gốc không đưa vào kho.

Bộ này không phải sản phẩm của Anthropic và không được Anthropic xác nhận.
