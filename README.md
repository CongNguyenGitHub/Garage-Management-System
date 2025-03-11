# 🚗 QuanLyGarage - Garage Management System  

## 📌 Project Overview  
**QuanLyGarage** is a garage management software developed by **Team 20 (SE104.N23)** as part of the **Introduction to Software Engineering** course. The system automates garage management processes, including:  

- 📋 **Vehicle reception & tracking**  
- 🛠 **Repair order & billing**  
- 📦 **Spare parts inventory management**  
- 📊 **Garage performance reporting**  

The goal of the system is to enhance **transparency, accuracy, and efficiency** for garage staff.  

📅 **Version**: 1.0 (Approved)  
📆 **Last Updated**: 06/25/2023  
👨‍💻 **Developed by**: Team 20 - SE104.N23  
📩 **Contact**: 21521200@gm.uit.edu.vn  

---

## ❓ Problem Statement  
The **QuanLyGarage** system addresses common issues in garage operations:  

✅ **Minimizes errors** in data entry and repair management.  
✅ **Boosts work efficiency** through process automation.  
✅ **Supports decision-making** with detailed revenue and inventory reports.  
✅ **Ensures data security**, preventing unauthorized access.  

---

## 🚀 Development Methodology  
**Development Model**: **Waterfall Model** with the following phases:  

1️⃣ **Requirement Analysis**: Gathering requirements via Google Meet, developing **SRS, Business Rules, and Use Cases**.  
2️⃣ **System Design**: 3-tier architecture, database design, UI/UX (Class Diagram, Sequence Diagram, ER Diagram).  
3️⃣ **Implementation**: Developing the system based on the design.  
4️⃣ **Testing**: Writing test cases, software testing.  
5️⃣ **Deployment & Maintenance**: Releasing version 1.0, collecting feedback, and updating.  

---

## 🔑 Key Features  
### 🔹 Vehicle Management  
- Register and search vehicles by license plate and model.  
- Track vehicle status in the garage.  

### 🔹 Repair & Billing  
- Create repair orders and invoices.  
- Check spare parts availability before creating an order.  

### 🔹 Inventory Management  
- Control spare parts stock levels, reduce entry errors.  

### 🔹 Reports & Statistics  
- Generate monthly revenue reports.  
- Detailed inventory reports *(No visual charts yet).*  

### 🔹 User Management  
- Role-based access control (Manager, Staff).  

---

## 📂 Project Structure  

📂 **docs/** (Project Documentation)  
&nbsp;&nbsp;&nbsp;&nbsp;📂 **Requirements/** (Requirements Documents)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **Vision_and_Scope.docx** (Vision & Scope)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **Business_Rules.docx** (Business Rules)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **List_of_Requirements.xlsx** (Requirements List)  

&nbsp;&nbsp;&nbsp;&nbsp;📂 **Design/** (System Design)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📂 **Diagrams/** (Architecture, UML, ERD diagrams, etc.)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **Software_Detail_Design.docx** (Detailed Software Design)  

&nbsp;&nbsp;&nbsp;&nbsp;📂 **Specifications/** (System Specifications)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **Use_Case_Specification.docx** (Use Case Specification)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **SRS_Document.docx** (Software Requirements Specification - SRS)  

&nbsp;&nbsp;&nbsp;&nbsp;📂 **Testing/** (System Testing)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📂 **Test_Cases/** (Test Case List)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **Tasksheet.docx** (Testing Task Assignment)  

&nbsp;&nbsp;&nbsp;&nbsp;📂 **Reports/** (Project Reports)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📄 **Short_Summary_Report.docx** (Short Summary Report)  

📂 **src/** (Project Source Code)  
&nbsp;&nbsp;&nbsp;&nbsp;📂 **BUS/** (Business Logic)  
&nbsp;&nbsp;&nbsp;&nbsp;📂 **DAO/** (Data Access)  
&nbsp;&nbsp;&nbsp;&nbsp;📂 **Database/** (Database structure & scripts)  
&nbsp;&nbsp;&nbsp;&nbsp;📂 **GUI/** (Graphical User Interface)  
&nbsp;&nbsp;&nbsp;&nbsp;📄 **QuanLyGarage.sln** (Visual Studio Solution File)  

📄 **README.md** (Project Documentation)  

---

## 🖥️ Getting Started  
### 🔧 System Requirements  
- **Windows 10/11**  
- **.NET Framework 4.7+**  
- **SQL Server 2019+**  
- **Visual Studio 2022**  

### ⚙️ Installation  
1️⃣ Clone repository:  
   ```sh  
   git clone <repository-url>  
   cd QuanLyGarage  
   ```  
2️⃣ Open **QuanLyGarage.sln** in Visual Studio.  
3️⃣ Set up the database:  
   - Open **src/Database/QuanLyGarage.sql** in SQL Server Management Studio.  
   - Run the script to create tables and sample data.  
4️⃣ Build & run the application.  
5️⃣ **Default login credentials**:  
   - **Manager**: `admin / admin123`  
   - **Staff**: `employee / emp123`  

---

## 🚀 Future Plans  
- ✅ Complete testing & fix bugs before official release.  
- ✅ Monitor performance, troubleshoot, and optimize the system.  
- ✅ Enhance features based on user feedback.  

---

## 👨‍💻 Contributors  
- **Nguyen Cong Nguyen** - 21521200@gm.uit.edu.vn  
- **Ho Duc Truong** - 21522730@gm.uit.edu.vn  
- **Nguyen Phuong Tung** - 21520524@gm.uit.edu.vn  
- **Le Minh Nguyet** - 21521211@gm.uit.edu.vn  

---

## 📜 License  
**QuanLyGarage** is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.  

---

## ❤️ Contributions  
We welcome all contributions! If you would like to participate, please submit a **pull request** or open an **issue** on GitHub.  

📩 **Contact**: If you have any questions or feedback, please open an issue on GitHub.  

Thank you for your interest in **QuanLyGarage**! 🚗💨

