# QuanLyGarage - Garage Management System

## 📌 Project Overview
**QuanLyGarage** là một phần mềm quản lý gara ô tô, được phát triển bởi **Nhóm 20 (SE104.N23)** trong khuôn khổ môn **Nhập môn Công nghệ Phần mềm**. Hệ thống giúp tự động hóa các quy trình quản lý gara, bao gồm:

- **Tiếp nhận và theo dõi xe**
- **Tạo phiếu sửa chữa và hóa đơn thanh toán**
- **Quản lý kho phụ tùng**
- **Thống kê báo cáo hoạt động của gara**

Hệ thống hướng đến **sự minh bạch, chính xác và tối ưu hóa công việc** cho nhân viên gara.

📅 **Phiên bản**: Beta (Chưa phát hành chính thức)  
📆 **Ngày cập nhật gần nhất**: 11/03/2025  
👨‍💻 **Phát triển bởi**: Nhóm 20 - SE104.N23  
📩 **Liên hệ**: [Cập nhật nếu cần]  

---

## ❓ Problem Statement
Hệ thống QuanLyGarage giúp giải quyết các vấn đề phổ biến trong gara ô tô:
✅ **Giảm thiểu sai sót** trong việc nhập liệu và quản lý thông tin sửa chữa.  
✅ **Tăng hiệu quả làm việc** thông qua quy trình tự động hóa.  
✅ **Hỗ trợ ra quyết định** với báo cáo chi tiết về doanh thu, tồn kho.  
✅ **Đảm bảo bảo mật dữ liệu**, hạn chế truy cập trái phép.  

---

## 🚀 Development Methodology
**Mô hình phát triển**: **Waterfall Model** với các giai đoạn chính:
1️⃣ **Phân tích yêu cầu**: Họp với stakeholders qua Google Meet (e.g., 29/03/2023) để thu thập và tài liệu hóa yêu cầu (SRS, Business Rules, Use Case).
2️⃣ **Thiết kế**: Xây dựng kiến trúc hệ thống (3-tier), thiết kế database, UI/UX, sử dụng Class Diagrams, Sequence Diagrams, ER Diagrams.
3️⃣ **Phát triển**: Hiện thực hóa hệ thống dựa trên thiết kế.
4️⃣ **Kiểm thử**: Viết test case và chạy thử nghiệm.
5️⃣ **Triển khai & Bảo trì**: Hiện hệ thống đang trong giai đoạn thử nghiệm nội bộ.

---

## 🔑 Key Features
- **Quản lý phương tiện**: Tiếp nhận, tìm kiếm (biển số, model), theo dõi tình trạng.
- **Xử lý sửa chữa & thanh toán**: Tạo phiếu sửa chữa, hóa đơn, kiểm tra tồn kho.
- **Quản lý kho**: Theo dõi phụ tùng, hạn chế nhập liệu sai.
- **Báo cáo & Thống kê**: Xuất báo cáo doanh thu (chưa có trực quan hóa dữ liệu).
- **Quản lý người dùng**: Phân quyền (Quản lý, Nhân viên).

---

## 📂 Project Structure
📂 **docs/**: Chứa tài liệu của dự án.
  📂 **DiagramsAndModels/**: Mô hình và sơ đồ trực quan.
  📂 **Test_case/**: Các trường hợp kiểm thử và tài liệu liên quan (VD: Vision and Scope, SRS, Business Rules).
  - **Short Summary Report.docx**: Báo cáo tóm tắt.

📂 **src/**: Mã nguồn được tổ chức thành các module.
  📂 **BUS/**: Tầng xử lý logic nghiệp vụ.
  📂 **DAO/**: Tầng truy cập dữ liệu.
  📂 **Database/**: Lược đồ và script cơ sở dữ liệu.
  📂 **GUI/**: Thành phần giao diện người dùng.
  - **QuanLyGarage.sln**: Tệp solution của dự án.
- **README.md**: Tệp này.

---

## 🖥️ Getting Started
### 🔧 Yêu cầu hệ thống
- **Windows 10/11**
- **.NET Framework 4.7+**
- **SQL Server 2019+**
- **Visual Studio 2022**

### ⚙️ Cài đặt
1️⃣ Clone repository:
   ```sh
   git clone <repository-url>
   cd QuanLyGarage
   ```
2️⃣ Mở **QuanLyGarage.sln** trong Visual Studio.
3️⃣ Thiết lập cơ sở dữ liệu:
   - Mở file **src/Database/QuanLyGarage.sql** trong SQL Server Management Studio.
   - Chạy script để tạo bảng và dữ liệu mẫu.
4️⃣ Build và chạy ứng dụng.
5️⃣ **Thông tin đăng nhập mặc định**:
   - **Quản lý**: `admin / admin123`
   - **Nhân viên**: `employee / emp123`

---

## 📊 Models & Diagrams
Hệ thống sử dụng các mô hình sau:
- **Phân tích yêu cầu**: Business Processes Model, Business Rules Model, Use Case Diagram.
- **Thiết kế**: Class Diagram, Sequence Diagram, State Diagram, Activity Diagram, Entity Relationship Diagram.

---

## 🤝 Customer Collaboration
Chúng tôi thường xuyên làm việc với khách hàng qua các cuộc họp Google Meet, tiếp thu phản hồi và cải tiến sản phẩm.

---

## 🎯 Lessons Learned
✅ Bám sát mô hình phát triển giúp quá trình triển khai suôn sẻ.  
✅ Quản lý thời gian và teamwork là yếu tố quan trọng để hoàn thành đúng tiến độ.  
✅ Phản hồi từ khách hàng giúp hoàn thiện sản phẩm.  
✅ Kiên trì và trách nhiệm là chìa khóa để giải quyết các bài toán phức tạp.  

---

## 🚀 Future Plans
- **Hoàn thiện kiểm thử và sửa lỗi trước khi phát hành phiên bản chính thức**.
- **Theo dõi hiệu suất, sửa lỗi và tối ưu hệ thống**.
- **Nâng cấp tính năng theo phản hồi từ người dùng**.

---

## 👨‍💻 Contributors
- **Nguyễn Văn A** - [GitHub](https://github.com/nguyenvana)  
- **Trần Thị B** - [GitHub](https://github.com/tranb)  
- **Lê Văn C** - [GitHub](https://github.com/levanc)  

---

## 📜 License
**QuanLyGarage** được cấp phép theo **MIT License**. Xem chi tiết tại [LICENSE](LICENSE).

---

## ❤️ Contributions
Chúng tôi hoan nghênh mọi đóng góp! Nếu bạn muốn tham gia phát triển, vui lòng gửi pull request hoặc mở issue trên GitHub.

---

## 📢 Contact
📩 Nếu bạn có bất kỳ câu hỏi hoặc phản hồi nào, hãy liên hệ với chúng tôi qua email: [Insert Contact Here]

Cảm ơn bạn đã quan tâm đến **QuanLyGarage**! 🚗💨

