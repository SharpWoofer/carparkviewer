# 🚗 CarparkViewer: NTU Techfest Hackathon 2023, Team 49

![original](https://github.com/user-attachments/assets/8a53a0b8-f1d2-4672-a217-4404a1b911df)

Welcome to **CarparkViewer**, a Unity-based application designed to help you visualize and manage car park data. This project was developed as part of the NTU Techfest Hackathon 2023 by Team 49.

## 🏗️ Problem Statement

### **Housing Development Board (HDB) Challenge**

The Housing Development Board (HDB) manages over **2,000 carparks** with more than **660,000 parking spaces** and **7,000 pieces of equipment**. With **500,000 unique motorists** visiting these carparks and **2.5 million transactions** processed daily, overseeing the maintenance and operations of these facilities presents a significant challenge. 

Due to the **manpower crunch** exacerbated by an aging population, it’s not feasible for HDB to deploy staff to every carpark. Therefore, there is a need for a **technology-driven solution** to help residents actively monitor and improve the condition of their carparks.

### **Our Objective**

We aim to **leverage technology** to create an engaging and effective solution for carpark management. By using a mobile app or similar technology, we strive to:
- Enable residents to **check on carpark conditions**.
- **Monitor maintenance and rectification progress**.
- **Empower residents** to take ownership of their estate's well-being.

## 🎯 Features

- **JSON File Reader:** Displays car park information in an intuitive interface.
- **Interactive Visualization:** View details of car park occupancy and structure.
- **Data Editing:** Modify the sample JSON file to test different scenarios.

## 📸 Screenshots

![Carpark Viewer Screenshot]() <!-- Add a relevant screenshot -->

## 🚀 Getting Started

Follow these simple steps to start using CarparkViewer:

1. **Download and Run**: Open the [CarparkViewer.exe](path/to/CarparkViewer.exe) file.
2. **Bypass Windows Defender**: If prompted, click **Run Anyway** to proceed.
3. **Select JSON File**: The program will open a file explorer. Choose the `sample_carpark.json` file.
4. **View Information**: The car park information will be displayed.
5. **Edit JSON Data**: Modify the JSON file to test different scenarios (e.g., adding floors, changing occupancy numbers) and run the program again to see the updates.

## 📜 Sample JSON Structure

Here’s a basic example of the JSON file format:

```json
{
  "carpark": {
    "id": "CP1234",
    "name": "Carpark A",
    "floors": [
      {
        "floor": 1,
        "spaces": 100,
        "occupied": 50
      },
      {
        "floor": 2,
        "spaces": 100,
        "occupied": 30
      }
    ]
  }
}

```

## 🔗 File Integrity Check

Your safety is our priority. The [CarparkViewer.exe](path/to/CarparkViewer.exe) file has been checked for viruses and is **safe to use**.

[![VirusTotal Status](https://img.shields.io/badge/VirusTotal-Clean-brightgreen?style=flat&logo=virus-total)](https://www.virustotal.com/gui/file/e1722005c0a8222d7f8893b0399690dd760328ad5bfe5e892bd116d35d39521c)

## 🤝 Contributing

We welcome contributions to enhance this project! Please follow these steps:

1. **Fork** the repository.
2. **Create a new branch** for your feature or fix.
3. **Commit your changes** and push to your branch.
4. **Open a pull request** with a description of your changes.

We appreciate your interest in improving CarparkViewer! 🚀

## 📜 License

This project is licensed under the [MIT License](LICENSE). 

---

Thank you for exploring **CarparkViewer**! We hope you find it useful and engaging. 

Happy parking! 🚗✨
