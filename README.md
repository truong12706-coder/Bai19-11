# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN

- **Họ và tên:** Đinh Xuân Trường
- **Mã số sinh viên:** 24810310234
- **Lớp:** D19CNPM3
- **Tên môn học:** Lập trình .NET
- **Tên bài tập:** Bài 6.3 – 6.5: Hệ thống quản lý công việc & tiến độ dự án, quản lý Garage ô tô và quản lý đặt phòng Karaoke.

---

# KẾT QUẢ THỰC HÀNH

## BÀI 6.3: HỆ THỐNG QUẢN LÝ CÔNG VIỆC & TIẾN ĐỘ DỰ ÁN
**(PROJECT & TASK MANAGEMENT)**

### 1. Ảnh màn hình giao diện chính
![Giao diện chính]<img width="907" height="645" alt="image" src="https://github.com/user-attachments/assets/50888fb4-abb0-4f08-9a59-85b5ded18f2d" />

### 2. Ảnh màn hình quản lý dự án và công việc (CRUD)
![Quản lý dự án và công việc]<img width="907" height="530" alt="image" src="https://github.com/user-attachments/assets/d3b390bf-66cd-48b1-8537-c0f6c0b7dffb" />



### 3. Ảnh màn hình phân công công việc và cập nhật tiến độ
![Phân công và cập nhật tiến độ]<img width="912" height="526" alt="Ảnh chụp màn hình 2026-11-19 135913" src="https://github.com/user-attachments/assets/aba4f58c-f610-4b31-b124-0417c9a89ac4" />



### 4. Ảnh màn hình cảnh báo trễ hạn và thống kê
![Báo cáo thống kê]<img width="912" height="567" alt="image" src="https://github.com/user-attachments/assets/d8cae5a6-984c-4c68-8e22-2fde13dc65b1" />


## BÀI 6.4: HỆ THỐNG QUẢN LÝ GARAGE VÀ BẢO DƯỠNG XE Ô TÔ
**(GARAGE MANAGEMENT SYSTEM)**

### 1. Ảnh màn hình giao diện chính
![Giao diện chính Garage]<img width="942" height="582" alt="Ảnh chụp màn hình 2026-11-19 140647" src="https://github.com/user-attachments/assets/12909e0c-b79e-46c8-8a4a-c02c099c7e33" />


### 2. Ảnh màn hình quản lý khách hàng, xe và phụ tùng
![Quản lý khách hàng và phụ tùng]<img width="937" height="575" alt="Ảnh chụp màn hình 2026-11-19 140741" src="https://github.com/user-attachments/assets/7d43dadb-7f3b-4272-8678-dc03e4886e35" />


### 3. Ảnh màn hình lập phiếu sửa chữa và thay thế phụ tùng
![Phiếu sửa chữa]<img width="906" height="563" alt="Ảnh chụp màn hình 2026-11-19 125722" src="https://github.com/user-attachments/assets/5926b3af-70bb-4250-ac27-dfdc9c653ff7" />


### 4. Ảnh màn hình thanh toán và xuất hóa đơn
![Thanh toán và hóa đơn]<img width="939" height="570" alt="image" src="https://github.com/user-attachments/assets/3660a7d3-cc4b-4fa8-9772-b4b5c290606c" />

---

## BÀI 6.5: HỆ THỐNG QUẢN LÝ ĐẶT PHÒNG & DỊCH VỤ KARAOKE
**(KARAOKE MANAGEMENT SYSTEM)**

### 1. Ảnh màn hình giao diện chính và sơ đồ phòng hát
![Giao diện phòng hát](images/11_karaoke_main.png)

### 2. Ảnh màn hình quản lý dịch vụ và đồ uống
![Quản lý dịch vụ](images/12_karaoke_service.png)

### 3. Ảnh màn hình mở phòng và gọi dịch vụ
![Mở phòng và gọi dịch vụ](images/13_karaoke_booking.png)

### 4. Ảnh màn hình tính tiền và thanh toán hóa đơn
![Thanh toán hóa đơn](images/14_karaoke_payment.png)

### 5. Ảnh màn hình kiểm tra lỗi và xử lý giao dịch
![Kiểm tra lỗi giao dịch](images/15_karaoke_error.png)

---

# CẤU TRÚC THƯ MỤC DỰ ÁN

```text
ProjectName/
│
├── Database/
│   └── ScriptDB.sql
│
├── ProjectTaskManagement/
│   ├── DTO/
│   ├── DAL/
│   ├── BUS/
│   ├── GUI/
│   ├── App.config
│   └── Program.cs
│
├── GarageManagement/
│   ├── DTO/
│   ├── DAL/
│   ├── BUS/
│   ├── GUI/
│   ├── App.config
│   └── Program.cs
│
├── KaraokeManagement/
│   ├── DTO/
│   ├── DAL/
│   ├── BUS/
│   ├── GUI/
│   ├── App.config
│   └── Program.cs
│
├── images/
│   ├── 01_main_screen.png
│   ├── 02_crud_screen.png
│   ├── 03_task_management.png
│   ├── 04_report_screen.png
│   ├── 05_error_handling.png
│   ├── 06_garage_main.png
│   ├── 07_garage_crud.png
│   ├── 08_repair_transaction.png
│   ├── 09_invoice.png
│   ├── 10_garage_error.png
│   ├── 11_karaoke_main.png
│   ├── 12_karaoke_service.png
│   ├── 13_karaoke_booking.png
│   ├── 14_karaoke_payment.png
│   └── 15_karaoke_error.png
│
├── README.md
└── ProjectName.sln
```

---

# CÔNG NGHỆ SỬ DỤNG

- Ngôn ngữ lập trình: C#
- Nền tảng: Windows Forms (.NET)
- Cơ sở dữ liệu: Microsoft SQL Server
- Công nghệ truy cập dữ liệu: ADO.NET
- Kiến trúc phần mềm: 3-Tier Architecture (DTO, DAL, BUS, GUI)
- Giao dịch dữ liệu: SqlTransaction
- Truy vấn dữ liệu: SqlCommand, SqlDataReader, SqlDataAdapter, DataTable
- Quản lý mã nguồn: Git và GitHub

---

# KẾT LUẬN

Thông qua các bài tập 6.3, 6.4 và 6.5, sinh viên đã vận dụng kiến thức lập trình .NET để xây dựng các ứng dụng quản lý thực tế bằng C# Windows Forms và SQL Server.

Các hệ thống được xây dựng nhằm thực hành:
- Thiết kế và quản lý cơ sở dữ liệu SQL Server.
- Xây dựng ứng dụng theo kiến trúc 3-Tier.
- Thực hiện các chức năng thêm, sửa, xóa và tìm kiếm dữ liệu.
- Quản lý công việc, tiến độ và phân công nhân sự.
- Quản lý sửa chữa xe và phụ tùng trong Garage.
- Quản lý phòng hát, dịch vụ và thanh toán Karaoke.
- Sử dụng SqlTransaction để đảm bảo tính nhất quán dữ liệu.
- Kiểm tra dữ liệu đầu vào và xử lý ngoại lệ.

**Sinh viên:** Đinh Xuân Trường

**Lớp:** D19CNPM3
