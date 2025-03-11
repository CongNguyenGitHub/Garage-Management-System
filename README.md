# QuanLyGarage - Garage Management System

## 📌 Project Overview
**QuanLyGarage** is a garage management software developed by **Team 20 (SE104.N23)** as part of the **Introduction to Software Engineering** course. The system automates garage management processes, including:

- **Vehicle reception and tracking**
- **Creating repair orders and invoices**
- **Managing spare parts inventory**
- **Generating activity reports for the garage**

The system aims to enhance **transparency, accuracy, and workflow efficiency** for garage staff.

📅 **Version**: 1.0 (Approved)  
📆 **Last Updated**: 25/06/2023  
👨‍💻 **Developed by**: Team 20 - SE104.N23  
📩 **Contact**: 21521200@gm.uit.edu.vn  

---

## ❓ Problem Statement
The QuanLyGarage system addresses common issues in automotive garages:

✅ **Reduces errors** in data entry and repair management.  
✅ **Increases work efficiency** through automated processes.  
✅ **Supports decision-making** with detailed revenue and inventory reports.  
✅ **Ensures data security**, preventing unauthorized access.  

---

## 🚀 Development Methodology
**Development Model**: **Waterfall Model** with the following main phases:

1️⃣ **Requirement Analysis**: Stakeholder meetings via Google Meet (e.g., 29/03/2023) to gather and document requirements (SRS, Business Rules, Use Cases).  
2️⃣ **Design**: System architecture (3-tier), database design, UI/UX, using Class Diagrams, Sequence Diagrams, and ER Diagrams.  
3️⃣ **Development**: Implementing the system based on design specifications.  
4️⃣ **Testing**: Writing test cases and conducting test executions.  
5️⃣ **Deployment & Maintenance**: Releasing version 1.0, gathering feedback, and updating accordingly.  

---

## 🔑 Key Features
- **Vehicle Management**: Receive, search (license plate, model), and track vehicle status.
- **Repair & Payment Processing**: Generate repair orders, invoices, and check inventory.
- **Inventory Management**: Monitor spare parts, minimize input errors.
- **Reporting & Statistics**: Generate revenue reports (no data visualization yet).
- **User Management**: Role-based access control (Manager, Employee).

---

## 📂 Project Structure
📂 **docs/**: Project documentation.  
  📂 **DiagramsAndModels/**: Visual models and diagrams.  
  📂 **Test_case/**: Test cases and related documents (e.g., Vision and Scope, SRS, Business Rules).  
  - **Short Summary Report.docx**: Summary report.  

📂 **src/**: Source code organized into modules.  
  📂 **BUS/**: Business logic layer.  
  📂 **DAO/**: Data access layer.  
  📂 **Database/**: Database schema and scripts.  
  📂 **GUI/**: User interface components.  
  - **QuanLyGarage.sln**: Project solution file.  
- **README.md**: This file.  

---

## 🖥️ Getting Started
### 🔧 System Requirements
- **Windows 10/11**
- **.NET Framework 4.7+**
- **SQL Server 2019+**
- **Visual Studio 2022**

### ⚙️ Installation
1️⃣ Clone the repository:
   ```sh
   git clone <repository-url>
   cd QuanLyGarage
   ```
2️⃣ Open **QuanLyGarage.sln** in Visual Studio.
3️⃣ Set up the database:
   - Open **src/Database/QuanLyGarage.sql** in SQL Server Management Studio.
   - Run the script to create tables and sample data.
4️⃣ Build and run the application.
5️⃣ **Default login credentials**:
   - **Manager**: `admin / admin123`
   - **Employee**: `employee / emp123`

---

## 📊 Models & Diagrams
The system utilizes the following models:
- **Requirement Analysis**: Business Processes Model, Business Rules Model, Use Case Diagram.
- **Design**: Class Diagram, Sequence Diagram, State Diagram, Activity Diagram, Entity Relationship Diagram.

---

## 🤝 Customer Collaboration
We regularly collaborate with customers through Google Meet meetings, incorporating feedback to improve the product.

---

## 🎯 Lessons Learned
✅ Following the development model ensures smooth implementation.  
✅ Time management and teamwork are crucial for meeting deadlines.  
✅ Customer feedback is essential for product enhancement.  
✅ Persistence and responsibility are key to solving complex problems.  

---

## 🚀 Future Plans
- **Complete testing and fix bugs before official release**.
- **Monitor performance, fix issues, and optimize the system**.
- **Upgrade features based on user feedback**.

---

## 👨‍💻 Contributors
- **Nguyen Cong Nguyen** - 21521200@gm.uit.edu.vn  
- **Ho Duc Truong** - 21522730@gm.uit.edu.vn  
- **Nguyen Phuong Tung** - 21520524@gm.uit.edu.vn  
- **Le Minh Nguyet** - 21521211@gm.uit.edu.vn  

---

## 📜 License
**QuanLyGarage** is licensed under the **MIT License**. See details at [LICENSE](LICENSE).

---

## ❤️ Contributions
We welcome all contributions! If you wish to participate in development, please submit a pull request or open an issue on GitHub.

---

## 📢 Contact
📩 If you have any questions or feedback, please create an issue on the project's GitHub repository.

Thank you for your interest in **QuanLyGarage**! 🚗💨

