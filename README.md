# 🚗 Autonomous Vehicle System

An autonomous vehicle prototype developed using C++ and Python, integrating real-time camera sensing, object detection, and obstacle avoidance. This project was created as part of McMaster University's 4DS4 Winter 2025 course.

---

## 📌 Project Overview

This system enables a vehicle to:

- Navigate autonomously using camera input.
- Detect and respond to obstacles in real-time.
- Execute basic driving maneuvers based on sensor data.

---

## 🛠️ Technologies Used

- **C++**: Core system logic and performance-critical components.
- **Python**: Camera interfacing and image processing.
- **OpenCV**: Real-time computer vision tasks.
- **Arduino**: Hardware control and sensor integration.

---

## 📁 Project Structure

```
Autonomous_Vehicle_System/
├── CameraSensorCode.py       # Python script for camera operations
├── hello_p0.cpp              # Initial C++ implementation
├── hello_p1.cpp              # Enhanced C++ version with added features
├── hello_p2.cpp              # Final C++ version with full functionality
├── 4DS4 Project 2 Report.pdf # Detailed project report
└── README.md                 # Project documentation
```

---

## 🧪 Getting Started

### Prerequisites

- C++ compiler (e.g., GCC)
- Python 3.x
- OpenCV library for Python
- Arduino IDE (if using Arduino for hardware control)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Aaron-Rajan/Autonomous_Vehicle_System.git
   cd Autonomous_Vehicle_System
   ```

2. **Set up the Python environment:**

   ```bash
   pip install opencv-python
   ```

3. **Compile the C++ code:**

   ```bash
   g++ hello_p2.cpp -o autonomous_vehicle
   ```

---

## 🚀 Usage

1. **Run the camera sensor script:**

   ```bash
   python CameraSensorCode.py
   ```

2. **Execute the autonomous vehicle program:**

   ```bash
   ./autonomous_vehicle
   ```

Ensure all hardware components are properly connected before running the programs.

---

## 📄 Documentation

For a comprehensive understanding of the project, refer to the [4DS4 Project 2 Report.pdf](./4DS4%20Project%202%20Report.pdf).

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📫 Contact

For any inquiries or feedback, please contact [Aaron Rajan](mailto:aaron.rajan@example.com).

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
