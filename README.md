# Bài 2 : Ngăn chặn rò rỉ dữ liệu do chia sẻ sai quyền

Phần 1: Phân tích lỗi "Cờ Đỏ Bảo mật"

Chia sẻ sai đối tượng: Dùng **Anyone with the link** làm mất kiểm soát danh tính; ai có link cũng vào được ẩn danh.

Thừa quyền hạn: Cấp quyền Editor cho dữ liệu nhạy cảm (SĐT) vi phạm nguyên tắc đặc quyền tối thiểu (Least Privilege).

Hậu quả: Khi link bị phát tán, kẻ xấu dễ dàng truy cập ẩn danh để đánh cắp và xóa sạch dữ liệu mà không thể truy vết.

Phần 2: Thiết lập lại phân quyền chuẩn
(1) Mức quyền cho CTV:

Commenter (nếu chỉ duyệt/góp ý).

Editor có giới hạn (nếu cần nhập liệu: chỉ mở khóa cột/ô cần sửa, khóa các cột dữ liệu gốc).

(2) Chế độ chia sẻ an toàn:

Chuyển sang Restricted (Bị giới hạn) và chỉ chia sẻ đích danh qua Email của cộng tác viên.

(3) Tính năng cần bật/tắt để chặn mời người lạ:

Vào Cài đặt chia sẻ (biểu tượng răng cưa) -> Tắt (bỏ tích): "Editors can change permissions and share" (Người chỉnh sửa có thể thay đổi quyền và chia sẻ).
