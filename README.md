# TinhTienPOS - Ứng dụng Tính Tiền Bán Hàng Android

Dự án đóng gói ứng dụng Web POS (hỗ trợ tính tiền theo số lượng cái/ly/phần, cân nặng `kg` và `lạng`, chèn hình ảnh món hàng, tính tiền thừa trả khách và lưu lịch sử đơn hàng offline) thành file `.apk` tự động qua GitHub Actions.

## Cách build file APK tự động trên GitHub
1. Tải toàn bộ thư mục này lên repository GitHub của bạn (nhánh `main` hoặc `master`).
2. Chuyển sang tab **Actions** trên GitHub -> chọn workflow **Build Android APK** (nếu chưa tự chạy thì bấm **Run workflow**).
3. Chờ khoảng 1–2 phút cho biểu tượng chuyển sang màu xanh.
4. Cuộn xuống mục **Artifacts** ở cuối trang và tải về **TinhTienPOS-APK**, giải nén lấy file `app-debug.apk` để cài lên điện thoại Android.
