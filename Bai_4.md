# BÀI 4: ĐÁNH GIÁ CHẤT LƯỢNG GIẢI PHÁP TRÊN STACK OVERFLOW

*Sinh viên: Võ Xuân Thịnh – Lớp CNTT2-K26*

## 1. Tình huống của mình

Mình gặp lỗi **"Git Permission Denied"** và tìm được 2 giải pháp trên StackOverflow:

- **Giải pháp 1:** có tích xanh (Accepted), đăng năm **2014**, **500 upvotes**.
- **Giải pháp 2:** không có tích xanh, đăng năm **2023**, **50 upvotes**, nhưng có bình luận: *"This works for Windows 11"*.

Phải chọn một. Mình so sánh trước rồi mới quyết định.

## 2. Bảng so sánh ưu / nhược điểm

| Tiêu chí | Giải pháp 1 (tích xanh, 2014, 500 upvotes) | Giải pháp 2 (không tích xanh, 2023, 50 upvotes) |
|---|---|---|
| **Độ tin cậy lịch sử** | **Ưu:** nhiều người đã dùng, được người hỏi xác nhận, qua thời gian dài. <br> **Nhược:** độ tin cậy này là của năm 2014, chưa chắc còn đúng hôm nay. | **Ưu:** có bình luận xác nhận chạy được trên hệ thống thực tế. <br> **Nhược:** ít upvotes hơn, chưa có người hỏi chính thức xác nhận. |
| **Tính cập nhật với hệ điều hành mới** | **Nhược:** viết từ 2014, trước cả Windows 10 và 11, nhiều bước có thể đã cũ hoặc giao diện đã đổi. | **Ưu:** viết năm 2023, được xác nhận cho **Windows 11**, sát với máy hiện nay. |
| **Rủi ro làm hỏng thiết lập hiện tại** | **Nhược:** lệnh cũ có thể ghi đè cấu hình Git/SSH mà phiên bản mới xử lý khác, rủi ro cao hơn. <br> **Ưu:** nhiều người dùng nên ít lệnh nguy hiểm trá hình. | **Ưu:** hợp với hệ điều hành và phiên bản Git hiện tại nên rủi ro thấp hơn. <br> **Nhược:** ít người kiểm chứng nên cần tự đọc kỹ từng lệnh. |

## 3. Chốt lựa chọn

**Mình chọn Giải pháp 2.** Máy mình dùng Windows, mà giải pháp này đã được xác nhận chạy trên Windows 11, trong khi Giải pháp 1 có tuổi đời hơn 10 năm.

**Trước khi chạy**, mình vẫn đọc kỹ từng lệnh, và sao lưu cấu hình Git (hoặc thư mục `.ssh`) để có thể quay lại nếu hỏng.

## 4. Vì sao "tích xanh" đôi khi không còn là ưu tiên số 1?

- **Tích xanh chỉ là lựa chọn của người hỏi tại thời điểm đó**, không phải bảo chứng cho mọi thời điểm sau.
- **Công nghệ đổi nhanh:** hệ điều hành, phiên bản Git, cách đăng nhập đều thay đổi. Cách đúng năm 2014 có thể sai hoặc nguy hiểm năm 2026.
- **Upvotes cũ tích lũy theo thời gian**, nên câu trả lời cũ luôn có lợi thế về số lượng dù đã lỗi thời.
- **Bình luận xác nhận mới** ("works for Windows 11") là bằng chứng **thực tế và đúng ngữ cảnh** của mình.

**Quy tắc mình rút ra:** xét **cả 3 yếu tố**: tích xanh, upvotes **và ngày đăng/bình luận gần đây**. Với lỗi phụ thuộc hệ điều hành, **tính cập nhật** quan trọng hơn tích xanh.

## 5. Tóm tắt 3 dòng (để thuyết trình)

- Giải pháp 1 **uy tín nhưng cũ** (2014), Giải pháp 2 **mới và đúng hệ điều hành** (2023, Windows 11).
- Mình chọn **Giải pháp 2**, vì hợp máy mình, rủi ro làm hỏng thiết lập thấp hơn.
- Tích xanh **không phải lúc nào cũng đúng**: công nghệ đổi, câu trả lời cũ có thể lỗi thời.
