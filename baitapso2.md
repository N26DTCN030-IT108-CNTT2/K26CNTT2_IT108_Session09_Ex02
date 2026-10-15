# BÀI TẬP SỐ 2
## 1 PHÂN TÍCH
### Lỗi khoảng trắng trong cú pháp hình ảnh (Image):

Đoạn mã gốc: [Logo PTIT] (https://ptit.edu.vn/logo.png)

Nguyên nhân: Có một khoảng trắng xuất hiện giữa cặp ngoặc vuông [...] và cặp ngoặc tròn (...). Theo chuẩn Markdown, cú pháp hình ảnh phải viết liền nhau hoàn toàn ([Alt text](url)). Khoảng trắng này làm cho trình biên dịch hiểu nhầm đây là hai phần tử riêng biệt (một cặp ngoặc vuông và một cặp ngoặc tròn), khiến ảnh hoàn toàn không hiển thị mà giữ nguyên dạng văn bản.

### Lỗi vi phạm phân cấp tiêu đề (Heading Hierarchy):

Đoạn mã gốc: Sử dụng # Tiêu đề 1 sau đó nhảy cóc ngay xuống ### Giới thiệu dự án.

Nguyên nhân: Trình tự phân cấp tiêu đề bị đứt quãng (từ H1 nhảy thẳng xuống H3 mà không qua H2). Mặc dù vẫn render ra đúng kích thước thẻ, nhưng điều này vi phạm quy tắc cấu trúc ngữ nghĩa kỹ thuật (mất tính logic của tài liệu và tối ưu SEO/AI đọc hiểu).

### Lỗi định dạng chữ in đậm (Bold):

Đoạn mã gốc: Đây là đoạn văn bản in đậm. nhưng lại viết dưới dạng văn bản thô (Plain Text) mà không bao quanh bởi dấu ** hoặc __.

Nguyên nhân: Thiếu cặp ký tự đặc trưng nhận diện định dạng, khiến hệ thống chỉ hiển thị đây là một dòng chữ bình thường chứ không áp dụng hiệu ứng in đậm.
