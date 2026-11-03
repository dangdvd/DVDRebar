# DVD Rebar — Triển khai cốt thép trên AutoCAD, ZWCAD, GstarCAD

DVD Rebar là bộ công cụ vẽ bản vẽ shop cốt thép và thống kê thép cho kỹ sư kết cấu, chạy ngay trong AutoCAD, ZWCAD và GstarCAD (một tab ribbon **DVD Rebar**, mọi lệnh bắt đầu bằng `DVD…`).

> **Phần mềm thương mại.** Kho này chỉ chứa bộ cài và tài liệu, không phát hành mã nguồn. Dùng thử 30 ngày đủ tính năng; sau đó cần mua bản quyền.

## Tải về và cài đặt

1. Vào [Releases](https://github.com/dangdvd/DVDRebar/releases/latest), tải **DVDRebar.rar**, giải nén ra `DVDRebar_Setup_<phiên bản>.exe`.
2. Đóng AutoCAD / ZWCAD / GstarCAD rồi chạy tệp `.exe` (mở từ File Explorer).
   - Cài cho riêng người dùng hiện tại không cần quyền quản trị; có thể chọn cài cho mọi người dùng.
   - Bộ cài chưa có chữ ký số của nhà phát hành: nếu Windows hiện "Windows protected your PC", bấm **More info › Run anyway**.
3. Mở lại CAD: tab **DVD Rebar** xuất hiện. ZWCAD / GstarCAD được bộ cài đăng ký tự nạp.
4. Gỡ cài đặt: **Settings › Apps › DVD Rebar**.

Cài ẩn (triển khai nhiều máy): `DVDRebar_Setup_<phiên bản>.exe /VERYSILENT /SUPPRESSMSGBOXES /CURRENTUSER`

### Yêu cầu hệ thống

| | |
|---|---|
| Hệ điều hành | Windows 10 / 11, 64-bit |
| AutoCAD | 2021 – 2027 |
| ZWCAD | 2025 – 2026 |
| GstarCAD | 2026 – 2027 |
| Bản quyền | Kết nối Internet khi đăng nhập / gia hạn (dùng ngoại tuyến tối đa 7 ngày giữa các lần kết nối) |

## Chức năng chính

- **Dầm:** lấy số liệu từ bảng bố trí thép / bảng mặt cắt dầm của bản vẽ thiết kế, từ mặt bằng hoặc Excel; bảng quản lý dầm; vẽ mặt dọc, mặt cắt, bản vẽ shop; chép dầm; dầm cong, console, dầm phụ, gia cường; sửa bảng rồi vẽ lại đúng chỗ.
- **Cột / vách:** quản lý cột nhiều tầng, vẽ thép cột, cắt nối so le, rải đai, vách lõi, lỗ mở vách, tường vây.
- **Sàn:** mô hình sàn, thép lớp trên / dưới, thép mũ, lỗ mở, chân kê, lưới thép hàn, gia cường tự động, mặt cắt sàn.
- **Móng:** quét mặt bằng lấy đài cọc, móng đơn, móng băng (kể cả bảng thống kê móng); quản lý móng; vẽ đài cọc (neo cọc bẻ xiên, lớp thép giữa), giằng móng, thép lưới, thép chờ.
- **Cầu thang:** 2 vế, chữ L, bậc rẻ quạt, xoắn ốc, dầm limon, bậc công xôn ngàm vách.
- **Cấu kiện hình bất kỳ:** khai báo hình tùy ý, thép chạy theo tuyến hoặc theo đường bao.
- **Thép:** vẽ thép theo 89 mã hình dạng hoặc vẽ tự do như PLINE; tag tự tránh đè; rải thép; nhóm thép; cắt nối tự động theo chiều dài cây thép; phối thép tối ưu giảm hao hụt.
- **Xuất bản:** thống kê thép (chi tiết, theo cấu kiện, tổng hợp), bê tông – cốp pha, BVBS cho máy cắt uốn; dàn trang, Layout hàng loạt, xuất PDF, xuất Excel.
- **Liên thông:** nhập mô hình và thép thiết kế ETABS (.e2k), xuất ETABS, IFC 2x3, mô hình 3D toàn bản vẽ, kiểm tra bản vẽ theo TCVN 5574.
- **Trợ lý AI** (tùy chọn, dùng khóa API của chính bạn — Claude, ChatGPT, Gemini…): hỏi đáp trên bản vẽ, đọc vùng mặt bằng để điền sẵn dầm / cột / móng, kết nối MCP với Claude Desktop / Claude Code, Codex, Antigravity.

Danh sách đầy đủ lệnh: gõ `DVDGIOITHIEU` hoặc ô **Tìm lệnh** trên ribbon. Hướng dẫn chi tiết: `DVDHUONGDAN` hoặc phím **F1** trong mọi hộp thoại.

## Bản quyền

- **Dùng thử 30 ngày** đủ tính năng trên mỗi máy.
- Mua, gia hạn, đăng nhập, đổi mật khẩu: nút **Tài khoản** (`DVDTAIKHOAN`). Bảng giá hiện hành và thanh toán chuyển khoản (VietQR) có ngay trong hộp mua bản quyền.
- Mỗi giấy phép dùng trên một máy tại một thời điểm; đổi máy: đăng xuất (`DVDDANGXUAT`) rồi đăng nhập ở máy mới.
- Tài khoản DVD Rebar có mật khẩu riêng, không dùng chung với DVD Addin trên Excel.

## Cập nhật

DVD Rebar tự kiểm tra bản mới mỗi ngày một lần (hoặc `DVDBANMOI`) và mở trang tải khi có bản mới — không tự tải hay tự cài. Những gì mới trong từng bản: `DVDCOGIMOI` hoặc trang [Releases](https://github.com/dangdvd/DVDRebar/releases).

## Hỗ trợ

- Email: support@dvdpm.net
- Trang sản phẩm: https://dvdpm.net/dvdrebar
- Khi báo lỗi, gửi kèm tệp `%APPDATA%\DVDRebar\error.log`.

© DVD. Bảo lưu mọi quyền.
