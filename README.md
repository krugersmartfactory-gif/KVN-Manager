KVN Improvement — Manager GitHub Pages
Bộ 3 file này tạo trang GitHub Pages trung gian để mở trang quản lý duyệt Apps Script.
URL trang quản lý
https://script.google.com/a/macros/krugersf.com/s/AKfycbzNcaqO9EyuHjcKuE-RFkfgcGQG5Q4rqUSH5BETzaEFTzaD6nGsRIsMuv_TD-VGHvMIQA/exec?page=manager
URL GitHub Pages
https://krugersmartfactory-gif.github.io/KVN-IMPROVEMENT/
Ba file
- index.html: trang trung gian, tự chuyển đến trang quản lý (?page=manager).
- 404.html: chuyển đường dẫn không hợp lệ về trang chính.
- README.md: hướng dẫn triển khai.
Cài đặt
1. Mở repository krugersmartfactory-gif/KVN-IMPROVEMENT.
2. Upload/replace index.html, 404.html, README.md tại thư mục gốc trên nhánh main.
3. Commit changes.
4. Vào Settings → Pages, chọn Deploy from a branch, branch main, folder /(root), Save.
5. Chờ GitHub Pages cập nhật rồi mở https://krugersmartfactory-gif.github.io/KVN-IMPROVEMENT/ để kiểm tra.
Lưu ý
Trang này chuyển thẳng đến trang Manager, không phải form nhân viên. Nếu muốn dùng cùng repository cho cả nhân viên và Manager, cần tạo trang riêng như manager.html thay vì đổi trang index.html này.
