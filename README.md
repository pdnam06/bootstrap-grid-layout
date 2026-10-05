# Bootstrap Containers và Grid System

Mở `index.html` bằng trình duyệt có Internet để tải Bootstrap 5.3.0 qua CDN.

## Bố cục

- Header có tiêu đề và mô tả.
- Navbar có dropdown Chủ đề, các liên kết dẫn tới phần nội dung thật.
- Container giới hạn chiều rộng; row g-4 tạo lưới và khoảng cách.
- Main Content: col-12 col-lg-8.
- Sidebar: col-12 col-lg-4.
- Footer hiển thị bản quyền.

## Giải quyết điểm chưa thống nhất trong đề

Đề vừa nói sidebar chỉ xuất hiện trên màn hình lớn, vừa yêu cầu sidebar nằm dưới nội dung chính ở màn hình nhỏ. Bài theo yêu cầu cụ thể thứ hai: sidebar vẫn hiển thị và nằm dưới nội dung khi nhỏ hơn 992px.

Đề ghi col-md-8/col-md-4 nhưng yêu cầu breakpoint 992px. Bootstrap md bắt đầu từ 768px, nên bài dùng col-lg-8/col-lg-4 để chuyển đúng ở 992px.

## Ảnh kết quả

- desktop.png: bố cục hai cột và dropdown mở.
- mobile.png: menu mở, sidebar nằm dưới nội dung chính.
