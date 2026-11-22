# Web/app học tập — Hóa học 9, Ôn tập kiểm tra cuối kì II

**Ôn tập kiểm tra cuối kì II (Bài 29–35)** — Môn Khoa học tự nhiên 9
(phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Hệ thống kiến thức, Mô phỏng,
Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Phạm vi ôn tập (theo PDF gốc): Bài 29–30 Carbohydrate, tinh bột và cellulose;
Bài 31 Protein; Bài 32 Polymer; Bài 33–34 Vỏ Trái Đất, đá vôi và công nghiệp
silicate; Bài 35 Nhiên liệu hoá thạch, chu trình carbon, hiệu ứng nhà kính.

Mô phỏng gồm (hình SVG thay đổi theo từng bước):
1. Phản ứng tráng bạc của glucose (Bài 29).
2. Hồ tinh bột tác dụng với iodine (Bài 30).
3. Đốt để phân biệt tơ tự nhiên với tơ tổng hợp (Bài 31).
4. Nung đá vôi và tôi vôi (Bài 34).

## Khóa đáp án trắc nghiệm

1A 2D 3B 4C 5A 6D 7B 8C 9A 10D

(Key gốc trong PDF: 1B 2B 3C 4B 5B 6B 7C 8B 9C 10B — 7 đáp án B, 3 đáp án C;
đã xáo vị trí các phương án, giữ nguyên nội dung đáp án đúng.)

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm
  rồi nộp bài để tự chấm điểm.

## Trạng thái gửi điểm về Google Sheets: CHỜ /exec

Link Web App Apps Script (/exec) của bài này chưa được deploy (registry chưa
có webAppUrl cho khóa hoa9-ontap-ckii). File `index.html` hiện tại KHÔNG chứa
code gửi điểm về Sheets — điểm trắc nghiệm chỉ lưu trên máy học sinh
(localStorage). Khi deploy xong, bổ sung fetch vào hàm `doSubmit()` trong
`index.html` (và cập nhật bản `.md` tương ứng). File `Code.gs` trong thư mục
này là code phía Apps Script đã chuẩn bị sẵn cho Sheet kết quả của bài.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_OnTap_CKII.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — code Apps Script ghi điểm về Google Sheets (chờ deploy /exec).
- `assets-flow/` — 3 ảnh nền gốc (JPG 1376×768, tạo bằng Gemini) + logo giáo viên.
