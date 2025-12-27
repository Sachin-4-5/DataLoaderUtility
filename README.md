# DataLoader Application  

## 📖 Overview  
DataLoader (Legacy) is a .NET Framework 4.7.2 legacy based console application that reads XML files and loads the data into a database using ADO.NET technique. This tool is designed to automate XML processing and database insertion efficiently.

---
<br />



## 🚀 Features  
✅ Reads structured XML files from a specified directory  
✅ Parses and validates XML content  
✅ Inserts data into the configured SQL Server database  
✅ Logs processing details for troubleshooting to a logs folder <br />
✅ Moves processed files to an archive folder <br />
✅ Sends success/failure email notification after processing 

---
<br />



## 🛠 Tech stack
- C#
- MS SQL Server
- ADO.NET

---
<br />



## Project structure
```
│── DataLoader\
    │── DataLoader\
        │── \bin
        │── \obj
        │── \Properties
        │── App.config
        │── Program.cs
        │── PreProcessor.cs
        │── DataLoadTemplate.cs
        │── DataLoadInfo.cs
        │── DataLoader.cs
        │── Enumeration.cs
        │── Archive.cs
        │── DataLoader.csproj
    │── ErrorLogger
    │── Mailer
    │── DataLoader.sln

│── ProdData\  
    │── Archive
    │── Incoming
    │── Logs
    
│── ProdApps\
    │── Executable
    │── Maestro
    │── Templates
    
│── script.sql
│── Readme.md
```

---
<br />



## 💡 Future Enhancements
🔹 Implement multi-threading for faster processing <br />
🔹 Add support for multiple data sources like - excel, json, etc. <br />
🔹 Add support for multiple database types (MySQL, PostgreSQL) <br />
🔹 Implement unit testing using NUnit Framework. <br />

---
<br />



## 🤝 Contribution
Pull requests are welcome! To contribute:

1️⃣ Fork the repo <br />
2️⃣ Create a feature branch (git checkout -b feature-xyz) <br />
3️⃣ Commit changes (git commit -m "Added feature xyz") <br />
4️⃣ Push to your branch (git push origin feature-xyz) <br />
5️⃣ Create a pull request 

---
<br />
<br />



















