# 📊 ASP.NET MVC PivotGrid with Date Range Filter

[![License](https://img.shields.io/badge/license-SEE%20LICENSE%20IN%20license-blue.svg)](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf)
[![Visual Studio 2022](https://img.shields.io/badge/Visual%20Studio-2022-blue.svg)](https://visualstudio.microsoft.com/)
[![.NET Framework](https://img.shields.io/badge/.NET%20Framework-Supported-brightgreen.svg)](https://dotnet.microsoft.com/)
[![Syncfusion EJ2](https://img.shields.io/badge/Syncfusion%20EJ2-Latest-green.svg)](https://www.syncfusion.com/aspnet-core-ui-controls/pivot-table)

> An ASP.NET MVC application demonstrating **Syncfusion EssentialJS2 PivotGrid** with interactive date range filtering, dynamic data aggregation, and responsive UI—perfect for business intelligence and analytical reporting scenarios.

---

## ✨ Key Features

- 📊 **Dynamic PivotGrid Rendering** — Flexible rows, columns, and value field configuration
- 📅 **Interactive Date Range Filter** — Intuitive date picker for temporal data filtering
- 🔢 **Real-time Data Aggregation** — Automatic summarization with instant updates
- 📱 **Responsive Design** — Bootstrap-based layout for desktop, tablet, and mobile
- 🎨 **EssentialJS2 Components** — Rich Syncfusion UI elements for professional appearance
- 🗄️ **SQL Server Compact Support** — Embedded database for easy deployment

---

## 📋 Prerequisites

- **Visual Studio 2022** or later
- **.NET Framework 4.7.2+**
- **NuGet Package Manager** (bundled with Visual Studio)
- **SQL Server Compact** (database engine)
- **Modern browser** (Chrome, Firefox, Safari, Edge)

---

## 🧭 Quick Start

### 1️⃣ Checkout the Repository
```bash
git clone https://github.com/SyncfusionExamples/aspnetcore-render-PivotGrid-by-using-date-range-filter
cd Render pivotgrid using date range filter
```

### 2️⃣ Open in Visual Studio
- Launch Visual Studio 2022
- Open `EssentialJS2MvcApplication1.sln`

### 3️⃣ Restore Dependencies
- Visual Studio automatically restores NuGet packages
- If needed, use **Tools → NuGet Package Manager → Manage Packages for Solution**

### 4️⃣ Build & Run
- Right-click the solution and select **Build**
- Press **F5** to start the application
- The browser automatically opens at `http://localhost:xxxx`
- Navigate to **PivotGrid** from the menu

---

## 🎯 Usage Guide

1. **Access the PivotGrid** — Click the PivotGrid menu item in the navigation
2. **Set Date Range** — Use the date range picker to filter data by time period
3. **View Results** — Pivot grid automatically updates with aggregated data
4. **Explore Data** — Interact with rows, columns, and value fields

---

## 🗂️ Project Structure

```
Render pivotgrid using date range filter/
├── Controllers/              # MVC controllers (PivotGridController)
├── Views/
│   └── PivotGrid/           # Pivot grid view (PivotGridFeatures.cshtml)
├── Models/                  # Data models and view models
├── App_Data/
│   └── ReportsTable.sdf     # SQL Server Compact database
├── Content/                 # CSS stylesheets
├── Scripts/                 # JavaScript libraries
├── App_Start/               # Configuration files
└── EssentialJS2MvcApplication1.csproj
```

---

## 🛠 Technologies Used

| Technology | Version | Purpose |
|------------|---------|---------|
| ASP.NET MVC | 5.x | Web framework |
| Syncfusion EJ2 | Latest | UI components |
| Bootstrap | 3.x+ | Responsive styling |
| jQuery | 3.1.1+ | DOM manipulation |
| SQL Server Compact | 4.0 | Data persistence |

---

## ⚙️ Configuration

### Database Connection
- Database file: `App_Data/ReportsTable.sdf`
- Connection string configured in `Web.config`
- Ensure file permissions allow read/write access

### PivotGrid Settings
- Customize in `PivotGridController.cs`
- Modify field arrangements, aggregations, and filters
- Extend with calculated fields or custom formatting

---

## 📖 Documentation & Resources

- 📚 [Syncfusion ASP.NET Core Documentation](https://ej2.syncfusion.com/aspnetcore/documentation/pivot-table/getting-started)
- 💬 [Syncfusion Support Forum](https://www.syncfusion.com/forums/aspnetcore-js2)

---

## 📄 License

This project is licensed under the **Syncfusion Community License**. See [Syncfusion License](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf) for details.

---

## 🤝 Support

For issues, questions, or suggestions:
- 📧 Email: support@syncfusion.com
- 💬 [GitHub Discussions](https://github.com/SyncfusionExamples)
- 📞 [Syncfusion Support Portal](https://support.syncfusion.com/)
