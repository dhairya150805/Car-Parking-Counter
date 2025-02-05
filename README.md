# 🚗 Car Parking Counter

This project utilizes **OpenCV** to **detect and count available parking spaces** from a video feed. The system dynamically updates parking spot statuses in **real-time**, distinguishing between occupied and free spaces.

---

## 📌 Project Overview

This application leverages **image processing techniques** to analyze parking areas and provide a live count of available spaces. It includes:

✅ **Parking Spot Selection** – Manually mark parking spots on an image.
✅ **Real-time Parking Spot Detection** – Analyze a video feed to detect occupied and free spots.
✅ **Visual Representation** – Green highlights indicate available spots, while red denotes occupied ones.

---

## 🛠️ Installation & Setup

The project consists of two key components:

### 1️⃣ **Parking Spot Selection**
This allows users to **define parking spots manually**:
- Run the script:
  ```bash
  python ParkingSpacePicker.py
  ```
- **Left-click** to add a spot, **right-click** to remove.
- Coordinates are stored in **'assets/positions.pkl'** for later use.

### 2️⃣ **Parking Spot Detection**
To start detecting parking spots from a video feed:
- Run the detection script:
  ```bash
  python main.py
  ```
- The system will highlight available and occupied spots **in real time**.

---

## 🔧 Key Dependencies
Ensure you have the following libraries installed:
```bash
pip install opencv-python cvzone pickle
```

### 🏗️ Libraries Used:
- **OpenCV** – For image processing and video analysis.
- **Pickle** – Saves and loads the selected parking spot coordinates.
- **cvzone** – Simplifies OpenCV tasks like drawing shapes and adding overlays.

---

## 📸 Screenshots (Optional: Add Images)
- **Parking Spot Selection Mode**
- **Real-time Detection Output**

*(You can add relevant images to visualize the project.)*

---

## 💡 Future Improvements
🔹 Support for **automatic spot detection** using deep learning.
🔹 Integration with **IoT sensors** for enhanced accuracy.
🔹 Mobile App Integration for remote monitoring.

---

## 🎯 Contributing
Feel free to fork this project, open issues, or submit pull requests. Contributions are always welcome!

---

## 📜 License
This project is open-source and available under the **MIT License**.

🔗 **GitHub Repository:** [Your Repo Link Here]  
👨‍💻 Developed by: **[DHAIRYA ISOTIYA & DEEP KAKADIYA]**
                  

---

🚀 **Happy Coding!** 🚀

