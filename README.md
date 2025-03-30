# Expense-Tracker
C# learning project


Here's a basic `README.md` template for your Expense Tracker project. Modify it based on your specific setup.  

---

# **Expense Tracker** 💰  
A simple web-based application for tracking expenses, built with .NET and Entity Framework Core.

## **🚀 Getting Started**  

### **1️⃣ Prerequisites**  
Ensure you have the following installed on your system:  
- [.NET SDK 8.0+](https://dotnet.microsoft.com/en-us/download/dotnet)  
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)  
- [Git](https://git-scm.com/downloads)  
- [Visual Studio (2022+)](https://visualstudio.microsoft.com/)  

---

### **2️⃣ Clone the Repository**  
```sh
git clone https://github.com/DhruvPrabhu2001/Expense-Tracker.git
cd Expense-Tracker
```

---

### **3️⃣ Configure the Database**  
1. **Update the Connection String:**  
   - Open `appsettings.json` inside the project.  
   - Modify the `"ConnectionStrings"` section to match your SQL Server setup:  
     ```json
     "ConnectionStrings": {
       "DefaultConnection": "Server=YOUR_SERVER_NAME;Database=ExpenseTrackerDB;Trusted_Connection=True;MultipleActiveResultSets=true"
     }
     ```
   - Replace `YOUR_SERVER_NAME` with your actual SQL Server instance.  

2. **Apply Migrations and Seed the Database:**  
   Run the following commands in the project directory:  
   ```sh
   dotnet ef database update
   ```

---

### **4️⃣ Run the Application**  
To start the Expense Tracker app, use:  
```sh
dotnet run
```
or launch it in **Visual Studio** by pressing `F5`.

---

### **5️⃣ Access the Web App**  
Once running, open your browser and go to:  
```
http://localhost:5000
```
or  
```
http://localhost:5001
```
(for HTTPS)

---

## **🌟 Features**
- Add, edit, and delete expenses.
- Categorize transactions.
- View expense analytics.

---

