\# 🚗 DVLD - Driving \& Vehicle Licensing Department System



!\[C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge\&logo=c-sharp\&logoColor=white)

!\[.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)

!\[SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge\&logo=microsoft-sql-server\&logoColor=white)



\---



\### 🇹🇷 Proje Hakkında

\*\*DVLD\*\*, bir devlet dairesinin ehliyet ve araç lisanslama süreçlerini uçtan uca yönetmek için tasarlanmış، kurumsal düzeyde bir \*\*N-Tier (Katmanlı Mimari)\*\* masaüstü uygulamasıdır. Bu proje, karmaşık iş mantığı (Business Logic), veritabanı yönetimi ve kullanıcı yetkilendirme süreçlerini profesyonel standartlarda ele almaktadır.



\### 🇬🇧 About The Project

\*\*DVLD\*\* is an enterprise-level \*\*N-Tier Architecture\*\* desktop application designed to manage the end-to-end operational processes of a driving and vehicle licensing department. The project demonstrates a mastery of complex business logic, relational database management, and role-based access control (RBAC).



\---



\## 🛠️ Tech Stack \& Architecture (Teknoloji ve Mimari)



\* \*\*Language:\*\* C# (.NET Framework)

\* \*\*Database:\*\* Microsoft SQL Server (ADO.NET)

\* \*\*Architecture:\*\* N-Tier Architecture (Layered)

&#x20;   \* \*\*Presentation Layer:\*\* Windows Forms (WinForms)

&#x20;   \* \*\*Business Logic Layer (BLL):\*\* Handles all validation and business rules.

&#x20;   \* \*\*Data Access Layer (DAL):\*\* Direct communication with SQL Server via ADO.NET.

\* \*\*Design Principle:\*\* Separation of Concerns (SoC) \& Encapsulation.



\---



\## 🌟 Key Features (Öne Çıkan Özellikler)



\### 👤 1. Person \& User Management

\- \*\*Detailed Profiles:\*\* Unified person management system for both staff and citizens.

\- \*\*RBAC:\*\* Secure login system with role-based permissions and activity logging.



\### 📝 2. Application Tracking

\- \*\*Multi-Type Applications:\*\* New driving licenses, renewals, replacements (lost/damaged), and international licenses.

\- \*\*Status Workflow:\*\* Real-time tracking of application status (New, Completed, Cancelled).



\### 🎓 3. Comprehensive Test System

\- \*\*Three-Stage Testing:\*\* Management of Vision, Theory, and Practical tests.

\- \*\*Appointment Scheduling:\*\* Automated slot management for candidate tests.



\### 💳 4. License Management

\- \*\*Issuing \& Printing:\*\* Generating local and international driving licenses.

\- \*\*Detain \& Release:\*\* Managing blacklisted licenses and penalty payments.

\- \*\*History Tracking:\*\* Full history of a driver’s licenses and violations.



\---



\## 🗄️ Database Structure (Veritabanı Yapısı)

Proje, ilişkisel veritabanı prensiplerine göre normalize edilmiş onlarca tablo içermektedir. 

> 💡 \*\*Setup:\*\* You can find the full database schema and seed data in the `/Database` folder.



\---



\## 🚀 Installation \& How to Run (Kurulum)



1\.  \*\*Database:\*\* \* Open SQL Server Management Studio (SSMS).

&#x20;   \* Run the `DVLD\_Setup.sql` file located in the `Database` directory.

2\.  \*\*Configuration:\*\* \* Update the connection string in the `DVLD\_DataAccess` layer to point to your local SQL instance.

3\.  \*\*Run:\*\* \* Navigate to the `DVLD` folder.

&#x20;   \* Open `DVLD.sln` with Visual Studio and press \*\*F5\*\*.



\---



\## 📸 Project Structure (Klasör Yapısı)

```text

├── Database/               # SQL Script for Schema \& Data

├── DVLD/                   # Presentation Layer (UI)

├── DVLD\_Business/          # Business Logic Layer (BLL)

├── DVLD\_DataAccess/        # Data Access Layer (DAL)

├── .gitignore              # Git ignore rules

└── README.md               # Project documentation

