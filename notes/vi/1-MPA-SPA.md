# MPAs & SPAs

## MPA - Multiple Page Apps

Luôn trả về toàn bộ html, js, css của trang khi request xuống server. Mỗi lần redirect request đều bị Flashing Content, thay thế tòan bộ content của trang thành 1 content trang khác.

## SPA - Single Page Apps

Trả về react app để append vào trong html
Mỗi lần redirect request sẽ trả về data dạng khác html (có thể là JSON) để render ra html và chỉ flashing content cho phần content thay thế.
Những phần khác sẽ được giữ nguyên và không tải thêm tài nguyên để render.
