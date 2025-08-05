
# AMC LabVIEW Project 🎛️

![LabVIEW](https://img.shields.io/badge/Built%20with-LabVIEW-orange?style=for-the-badge&logo=NI)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## 📊 Project Overview
This is an **AMC Tracker Application** developed using LabVIEW. It helps track AMC (Annual Maintenance Contract) entries, manages statuses, and provides an admin dashboard for real-time monitoring with database connectivity.

## 🗂️ Project Structure
```
AMC TRACKER.lvproj
├── Controls/
│   ├── Enum.ctl
│   ├── SQL credential.ctl
│   └── ...
├── MAIN VI/
│   ├── AdminPanel.vi
│   └── Main.vi
├── SUB VI/
│   ├── DB Action Engine SubVI.vi
│   └── VI Ref FGV.vi
└── Screens/
    ├── Admin Dashboard.vi
    └── Login Screens.vi
```

## 🚀 Features
- User Authentication & Login Screens
- Admin Dashboard for AMC Entry Tracking
- Database Connectivity with MySQL
- Modular Controls and Enumerations
- Action Engines for Business Logic

## 🛠️ Technologies Used
- LabVIEW 2020+
- MySQL Database
- Functional Global Variables (FGVs)
- LabVIEW Action Engines

## 📥 How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/AmanKumar008/AMC-LabVIEW-Project.git
    ```
2. Open `AMC TRACKER.lvproj` in LabVIEW.
3. Configure MySQL Database with your credentials.
4. Run `Main.vi` to launch the application.

## 🧑‍💻 Author
**Aman Kumar Mahatha**  
Email: [Your Email Here]

## 📄 License
This project is licensed under the MIT License.
