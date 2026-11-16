# Speaking Notebook

Trang tự học IELTS Speaking bằng tiếng Việt, gồm 14 bài Part 2 và 12 câu Part 1. Có bài mẫu, dàn ý, cụm từ, giọng đọc của trình duyệt, đồng hồ và ghi chú lưu bằng localStorage.

## Triển khai trên Netlify

Kết nối repository này với Netlify, chọn nhánh `main`.

- Base directory: để trống.
- Build command: để trống (HTML/CSS/JavaScript thuần, không cần build).
- Publish directory: `dist` (đã cấu hình trong `netlify.toml`).

Hướng dẫn chính thức: https://docs.netlify.com/manage/projects/add-new-project/

## Chạy trên máy

Chạy `python -m http.server 8765 --directory dist` tại thư mục repository, sau đó mở http://localhost:8765.

Sửa nội dung trong `dist/lessons.js`; giao diện trong `dist/style.css`; tương tác trong `dist/app.js`.

Ghi chú và tiến độ lưu riêng trên từng trình duyệt, không đồng bộ giữa thiết bị. Giọng đọc phụ thuộc khả năng của trình duyệt. Trang không thu âm hoặc chấm band tự động.

Các bài trả lời được biên soạn mới để học cách diễn đạt, không phải bài mẫu được giám khảo chấm. Nguồn phương pháp và nguồn đề được ghi trong mục “Nguồn & phương pháp” trên trang.
