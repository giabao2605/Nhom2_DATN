Giới Thiệu Project
Đây là project frontend được phát triển theo nhóm. Hiện tại project đã hoàn thành khoảng 70%, các thành viên sẽ tiếp tục hoàn thiện các phần còn lại theo sự phân công.

Phân Chia Công Việc
Lên Trello lấy task về làm.

Hướng Dẫn Làm Việc Với GitHub (Pull Request Workflow - Không Cần Cấp Quyền)
1. Fork Repo
Vào link repo:
https://github.com/giabao2605/Nhom2_DATN

Nhấn nút Fork (góc phải trên) để tạo bản sao repo về tài khoản GitHub của bạn.

2. Clone Repo Từ Fork Về Máy
git clone https://github.com/tai-khoan-cua-ban/Nhom2-DATN.git

3. Tạo Nhánh Riêng
git checkout -b ten-nhanh-rieng
Ví dụ:
git checkout -b giaodiengiohang

4. Làm Việc Trên Nhánh Riêng
Thực hiện code trên nhánh của bạn.

5. Lưu Thay Đổi Và Đẩy Lên GitHub
git add .
git commit -m "Mô tả phần đã làm"
git push origin ten-nhanh-rieng

6. Tạo Pull Request
Vào repo Fork của bạn trên GitHub.

Chọn Compare & Pull Request.

Gửi Pull Request về repo chính để Leader kiểm tra và gộp vào main.

Cập Nhật Code Mới Nhất Từ Repo Chính
Bước 1: Thêm remote của repo chính
git remote add upstream https://github.com/giabao2605/Nhom2_DATN.git

Bước 2: Lấy code mới nhất
git checkout main
git pull upstream main

Bước 3: Cập nhật nhánh riêng
git checkout ten-nhanh-rieng
git merge main

Lưu Ý
Luôn làm việc trên nhánh riêng của bạn.

Không sửa trực tiếp trên nhánh main.

Luôn cập nhật code mới nhất từ repo chính trước khi làm việc.

Pull Request sẽ được Leader xem xét và merge.

Nếu có thắc mắc, hãy trao đổi với Leader sớm.

Liên Hệ
Mọi thắc mắc vui lòng liên hệ Leader.
