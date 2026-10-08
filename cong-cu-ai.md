# Công cụ AI & quy tắc an toàn dữ liệu

> Đọc phần **Quy tắc an toàn** trước khi dùng bất kỳ công cụ AI nào cho công việc.

[← Về trang chính](README.md)

---

## 1. Dùng loại công cụ nào cho việc gì?

| Loại công cụ | Dùng tốt cho | Lưu ý |
|---|---|---|
| **Trợ lý chat AI** (ChatGPT, Gemini, Claude, Copilot…) | Lên ý tưởng, viết caption, tóm tắt, dịch, soạn brief, phân tích bảng số liệu đơn giản | Có thể trả lời sai mà nghe rất tự tin. Luôn kiểm tra lại |
| **Tạo hình ảnh bằng AI** | Moodboard, phác ý tưởng, hình nền, minh họa concept | Không dùng để tạo hình sản phẩm thật hoặc logo thương hiệu |
| **AI trong công cụ thiết kế** (ví dụ Figma) | Gợi ý bố cục, tạo nhanh nhiều phiên bản, đổi chữ hàng loạt | Tính năng AI có thể khác nhau tùy gói tài khoản. Designer vẫn chốt bản cuối |
| **AI cho bảng tính** (Google Sheets) | Viết công thức, làm sạch dữ liệu, gợi ý cách trình bày bảng | Thử công thức trên **bản sao** trước khi áp vào file thật |
| **AI xử lý video / giọng nói** | Phụ đề, cắt ghép nhanh, kịch bản | Kiểm tra bản quyền nhạc, hình ảnh, giọng đọc trước khi đăng |

**Danh sách công cụ team đang được phép dùng:** `[Chủ repo cập nhật danh sách tại đây]`

---

## 2. Quy tắc an toàn dữ liệu

### Đèn xanh – được đưa vào AI

- Thông tin sản phẩm **đã công bố** (tên, chất liệu, màu, size).
- Nội dung đã đăng công khai trên fanpage, website.
- Số liệu **tổng hợp, đã bỏ tên** (ví dụ: doanh số theo nhóm hàng, không có tên khách).
- Bản nháp caption, ý tưởng, brief.

### Đèn vàng – hỏi trưởng nhóm trước

- Kế hoạch ra mắt sản phẩm **chưa công bố**.
- Số liệu bán hàng, tồn kho chi tiết theo cửa hàng.
- Ngân sách và báo cáo quảng cáo chi tiết.
- → Chỉ dùng công cụ AI **được team cho phép**, và bỏ bớt chi tiết không cần thiết.

### Đèn đỏ – tuyệt đối không đưa vào AI

- **Dữ liệu cá nhân khách hàng:** họ tên, số điện thoại, địa chỉ, email, ảnh chụp tin nhắn có thông tin khách.
- **Giá nhập, chiết khấu, điều khoản hợp đồng** với hãng, đối tác, nhà cung cấp.
- **Tài liệu mật** của hãng (Puma, Adidas…) chưa được phép chia sẻ.
- **Mật khẩu, mã đăng nhập**, thông tin tài khoản quảng cáo, thông tin thanh toán.

---

## 3. Quy tắc trước khi đăng

1. **Kiểm tra sự thật:** tên sản phẩm, công nghệ, giá bán, thời gian khuyến mãi phải khớp với nguồn chính thức.
2. **Không để AI tự bịa** tính năng sản phẩm, số liệu, lời chứng thực của khách.
3. **Đúng guideline thương hiệu:** với Puma, Adidas – đối chiếu hướng dẫn của hãng (tên gọi, hashtag, cách dùng logo).
4. **Hình ảnh:** không dùng AI tạo hình giả sản phẩm thật, logo, hoặc người nổi tiếng.
5. **Đọc lại bằng mắt người:** chính tả, giọng văn, từ ngữ nhạy cảm.

> Không chắc? Hỏi trưởng nhóm trước khi đăng. Đăng nhầm khó gỡ hơn hỏi thêm một câu.

---

## 4. Mẹo dùng AI hiệu quả

- **Cho bối cảnh:** thương hiệu, khách hàng, mục tiêu. Xem khối bối cảnh mẫu trong [prompts/README.md](prompts/README.md).
- **Yêu cầu nhiều phương án** (3–5), rồi chọn và sửa.
- **Sửa từng bước:** "ngắn lại", "trẻ trung hơn", "bỏ emoji"… thay vì viết lại từ đầu.
- **Đưa ví dụ** bài viết tốt cũ để AI bắt chước giọng văn.
- **Lưu lại prompt hiệu quả** và đóng góp vào repo → [Hướng dẫn đóng góp](huong-dan-dong-gop.md).
