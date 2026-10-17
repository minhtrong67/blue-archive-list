# blue-archive-list
Danh sách học sinh Blue Archive — HTML/CSS/JS thuần, không backend, hỗ trợ PWA (offline).
- Chạy local: mở `index.html` (PWA/Service Worker cần http, vd `npx serve .` hoặc `python3 -m http.server`).
- Deploy: sửa `og:image`/thêm `canonical` thành URL tuyệt đối của bạn trong `index.html`.
- `data.js`: 278 nhân vật (nguồn bluearchive.wiki). Cú pháp tìm kiếm: `school:abydos`, `role:tank`, `cv:...`, `age>16`, `height<=155`.
- Phím tắt: `/` tìm kiếm, `Esc` xóa, `←/→` chuyển nhân vật khi xem chi tiết.
