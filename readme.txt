##  Giới thiệu Project

Đây là project frontend được phát triển theo nhóm. Hiện tại project đã hoàn thành khoảng 70%, các thành viên sẽ tiếp tục hoàn thiện các phần còn lại theo sự phân công.

##  Phân Chia Công Việc: Lên trello lấy task về làm

##  Hướng Dẫn Làm Việc Với GitHub

### 1. Clone Project Về Máy

git clone https://github.com/giabao2605/DATN_Nhom2

### 2. Tạo Nhánh Riêng

Mỗi bạn tự tạo nhánh riêng theo phần việc:

git checkout -b ten-nhanh-rieng

Ví dụ:

git checkout -b giaodiengiohang

### 3. Làm Việc Trên Nhánh Riêng

* Thực hiện code trên nhánh của mình.
* Thường xuyên kiểm tra các file đã sửa:

git status

### 4. Lưu Thay Đổi Và Đẩy Lên GitHub

git add .
git commit -m "Mô tả phần đã làm"
git push origin ten-nhanh-rieng

### 5. Tạo Pull Request

* Vào GitHub → Chọn nhánh của bạn → Nhấn **Compare & Pull Request**
* Gửi Pull Request để Leader kiểm tra và merge vào nhánh `main`

## Cập Nhật Code Mới Nhất

Trước khi làm việc hoặc sau khi Leader đã merge code:

git checkout main
git pull origin main

Nếu bạn đang ở nhánh riêng:

git checkout ten-nhanh-rieng
git merge main

## Lưu Ý

* Luôn làm việc trên nhánh riêng, không sửa trực tiếp trên nhánh `main`.
* Trước khi bắt đầu công việc mới, nhớ cập nhật code mới nhất từ nhánh `main`.
* Thường xuyên trao đổi với team nếu gặp vấn đề.

---

## Liên Hệ

Mọi thắc mắc vui lòng liên hệ Leader
