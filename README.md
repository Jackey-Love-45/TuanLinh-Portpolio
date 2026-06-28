# TuanLinh Portfolio V3 WOW

Bản nâng cấp tập trung vào cảm giác mở website phải có “wow” và cá tính riêng của Phan Tuan Linh.

## Preview

Vì nội dung được load từ JSON, nên nên mở bằng local server thay vì double-click trực tiếp file HTML.

Preview hiện tại:

- http://127.0.0.1:4291/

Chạy lại sau này từ thư mục này:

- Python: `python -m http.server 4291`
- Node.js: `npx serve .`
- VS Code: mở thư mục bằng Live Server.

## Điểm đã nâng cấp

- Đổi logo thành `TuanLinh.Profile` và logo cá nhân `PTL`.
- Thêm backend background: API graph, request flow, Kafka, Redis, PostgreSQL, Docker, Queue, Event.
- Tăng hiệu ứng “wow”: subtle gradient, glow, glass effect, floating blur, depth.
- Tăng chiều sâu card: border glow, shadow, hover animation.
- Avatar/tên nổi bật hơn; tên `Phan Tuan Linh` có hiệu ứng gõ-xóa vòng lặp, dừng 2 giây.
- Thêm slogan/signature cá nhân để site không còn cảm giác generic.
- Thêm Engineering Philosophy section.
- Làm rõ metrics cho từng project ngay trên card và trong modal.
- Journey Timeline được giữ và tăng visual depth.
- Modal case study đóng được bằng Esc.
- Chatbot đổi thành `TL Assistant`.
- Giữ chức năng chuyển Việt/Anh và đổi tone màu; text/tone vẫn giữ độ tương phản dễ đọc.

## File chính

- Layout: `index.html`
- Style/animation: `assets/styles.css`
- Tương tác: `assets/app.js`
- Nội dung EN/VI: `data/content.en.json`, `data/content.vi.json`


## Minimal content patch

- Giữ nguyên giao diện WOW gốc.
- Chỉ đổi link CV PDF cũ sang `resume/index.html`.
- Chỉ thay các câu CTA/footer theo yêu cầu.
- Bổ sung nội dung TL Assistant, không đổi layout assistant.
- Giữ các dự án đã bổ sung trong bản WOW: Smart Parking, Primary School, Shoe Shop và các case study hiện có.
