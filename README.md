# BÀI TẬP 3
**Họ và Tên: Lương Bảo Ngọc**

**Lớp: K59KMT-K01**

**MSV: K235480106051**

## THIẾT KẾ VÀ CÀI ĐẶT CSDL QUẢN LÝ CẦM ĐỒ
### 1: Thiết kế CSDL

Tạo Data Base QuanLyCamDo

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/02d30f18-145d-4a04-a856-107801ba9e30" />

Tạo bảng thành công trong SSMS
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ad6bbc67-47c3-42ac-9065-74a2cc84cbaa" />

Chèn dữ liệu vào các bảng
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/4c98db21-cb5b-4094-99a8-e13ee0f676c2" />

### 2: Cài đặt SQL (Yêu cầu viết Scripts)

#### Event 1: Đăng ký hợp đồng mới

Tạo sp_TiepNhanHopDong**Cách gọi Store Procedure:**
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/17e083b7-919e-4902-a2e4-dac8643d4924" />

Kết quả chạy sp_TiepNhanHopDong trong SSMS
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/0e9063bd-a2d9-409a-82a6-661b6cae835b" />

#### Event 2: Tính toán công nợ

Tính Toán công nợ 
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/cb9b0393-0fc6-4a88-99c9-675c9cffa19d" />

Tạo function tính dư nợ thực tế
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/79eb38cb-882f-40ac-9d74-285681baca7e" />

Kiểm thử hai function:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/84c693c0-fa27-49c8-bf86-45fcafebfba0" />

#### Event 3: Xử lý trả nợ & Hoàn trả tài sản

Tạo sp sp_XuLyTraNo
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/14647d18-5727-409b-96fa-a9d1e06d2560" />

 sp_XuLyTraNo - Trường hợp trả góp và Danh sách tài sản gợi ý rút về
 <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/776e7933-939f-4d29-b285-58be1abf4f8a" />

#### Event 4: Truy vấn nợ xấu

query danh sách nợ xấu
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9e307c26-e8e7-4fd7-9134-ce4f6723d5c8" />

#### Event 5: Quản lý thanh lý tài sản (Triggers)

Tạo trigger  Tự động chuyển hợp đồng sang "Qua han"
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/aecc3727-b2c5-4812-865b-74c6e1892224" />

Trigger 2: Tự động chuyển tài sản sang "San sang thanh ly"
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/535a28db-428d-40b1-83ba-5a8090b54465" />

**Kiểm thử Triggers:**
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/4af21017-4461-40bd-b498-f3ebb58183b1" />

### 3: Các sự kiện bổ sung

#### 3.1 Gia hạn hợp đồng

Tạo sp Gia hạn hợp đồng **Cách gọi:**
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/68f08b17-1b46-4986-b101-e7d63f44a594" />

Kết quả gia hạn hợp đồng
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d0ca2cd6-8c2a-4dee-b394-552feb90ffd0" />

#### 3.2 Lịch sử hợp đồng (Audit Log)

Query xem lịch sử một hợp đồng:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/26544a80-f4d0-4d63-bec3-d54c9e4cbb64" />
