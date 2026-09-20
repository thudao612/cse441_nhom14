# DỰ ÁN MÔN PHÁT TRIỂN ỨNG DỤNG CHO CÁC THIẾT BỊ DI ĐỘNG - CSE441 - NHÓM 14

## 📌 1. Giới thiệu dự án
- Tên dự án:
- Công nghệ sử dụng:Flutter, Dart, Git/GitHub.

## 👥 2. Thành viên & Phân công vai trò
|STT| Họ và Tên       | Username GitHub     | Vai trò                                 |
| 1 | Đào Hà Thu      | `thudao612`         | **Nhóm trưởng** - Quản lý Repo |
| 2 | Phạm Kim Anh    | `kimanh19-p`        | **Thành viên** - |
| 3 | Vương Tiến Dũng | `vuongtiendung257`  | **Thành viên** -  |
| 4 | Trần Đức Trung  | `DuckTrun`          | **Thành viên** -  |

## 🚀 3. Hướng dẫn cài đặt và chạy dự án
```bash
###1. Clone repository về máy:
   git clone https://github.com/thudao612/cse441_nhom14.git
###2. Di chuyển vào thư mục dự án
  cd cse441_nhom14
###3.Cài đặt thư viện:
   flutter pub get
###4. Chạy ứng dụng trên trình duyệt Web:
  flutter run -d chrome

## 🔄 4. Quy trình làm việc nhóm & Nộp code
Để đảm bảo không bị xung đột code, các thành viên trong nhóm bắt buộc tuân thủ quy trình các bước sau:
```bash
###Bước 1: Đồng bộ (Pull) code mới nhất về máy trước khi làm
git checkout main
git pull origin main

###Bước 2: Tạo nhánh (Branch) riêng để làm nhiệm vụ
git checkout -b feature/ten-tinh-nang-cua-ban
(Ví dụ: git checkout -b feature/giao-dien-card)

###Bước 3: Đẩy nhánh riêng lên GitHub
git add .
git commit -m "Mô tả ngắn gọn công việc đã làm"
git push origin feature/ten-tinh-nang-cua-ban

###Bước 4: Tạo Yêu cầu gộp code (Pull Request - PR)
1. Truy cập vào trang web Repository của nhóm trên GitHub (https://github.com/thudao612/cse441_nhom14)
2. Nhấn vào nút Compare & pull request xuất hiện ở thông báo màu vàng phía trên màn hình.
3. Kiểm tra thông tin, ghi mô tả công việc đã hoàn thành và bấm Create pull request.
4. Chờ Nhóm trưởng (Leader) kiểm tra code và bấm Merge (gộp code) vào nhánh main.
