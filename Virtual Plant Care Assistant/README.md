# 🌿 Virtual Plant Care Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![.NET](https://img.shields.io/badge/.NET-6.0%2B-blueviolet)](https://dotnet.microsoft.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)](https://www.mysql.com/)

A modern desktop application built to simplify indoor plant management. This project focuses on providing a seamless user experience for tracking plant health, scheduling maintenance tasks, and maintaining a digital history of your botanical collection.

---

## ✨ Key Features

- **🔐 Secure User Accounts**: Full authentication system with secure login and registration.
- **🪴 Interactive Dashboard**: A centralized view to manage all plants in your collection at a glance.
- **📅 Smart Care Scheduling**: Automated tracking for watering, fertilizing, and repotting tasks.
- **📜 Maintenance History**: Comprehensive logging system to monitor growth trends and health over time.
- **🎨 Modern Botanical UI**: A custom-designed XAML interface featuring a professional botanical aesthetic, responsive layout, and **custom plant image support**.
- **🗄️ Relational Database**: Optimized MySQL schema for persistent data storage and efficient querying.

---

## 🛠️ Built With

- **Frontend**: C# WPF (Windows Presentation Foundation)
- **Backend Logic**: .NET Core / C#
- **Database**: MySQL 8.0
- **UI Design Principles**: HCI (Human-Computer Interaction) focused layout

---

## 🚀 Installation & Setup

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (6.0 or higher)
- [MySQL Server](https://dev.mysql.com/downloads/installer/)

### Setup Instructions

1. **Clone the Project**:
   ```bash
   git clone https://github.com/yourusername/VirtualPlantCareAssistant.git
   cd VirtualPlantCareAssistant
   ```

2. **Initialize Database**:
   - Execute the following SQL scripts in your MySQL environment to create the schema and optionally add sample data:
     ```sql
     SOURCE setup_database.sql;
     SOURCE sample_data.sql;  -- Optional: Adds a test user and sample plants
     ```

3. **Configure Connection**:
   - Ensure your database credentials are correctly set in the `DatabaseHelper.cs` file.

4. **Launch Application**:
   ```bash
   dotnet run --project VirtualPlantCareAssistantVSC
   ```

---

## 📸 Interface Preview

| Feature | Preview |
| :--- | :--- |
| **Login System** | ![Login Placeholder](https://via.placeholder.com/400x250?text=Login+View) |
| **Dashboard** | ![Dashboard Placeholder](https://via.placeholder.com/400x250?text=Dashboard+View) |
| **Care History** | ![History Placeholder](https://via.placeholder.com/400x250?text=Care+History+View) |

---

## 📁 Project Architecture

```text
VirtualPlantCareAssistantVSC/
├── DB VSC Project Images/ # User-uploaded plant images
├── Assets/
│   └── Images/         # UI resources, backgrounds, and icons
├── Models/             # Business logic and data structures
├── Views/              # XAML UI Components and Windows
├── Utilities/          # Database connectivity and Session management
├── Data/               # Data access layer
└── App.xaml            # Global styles and application entry
```

---

## 📄 License

This project is licensed under the MIT License.

---

**Developed by [Your Name]** 🌿
