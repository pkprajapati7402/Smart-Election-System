# 🎉 Smart Election System 🎉

Welcome to the Smart Election System project! This Python-based application uses facial recognition and Aadhar number verification to securely register voters and store votes. The system captures face data via a primary webcam and saves votes in CSV files.

## 📑 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## 🌟 Introduction
The Smart Election System is designed to streamline and secure the voting process by leveraging facial recognition technology and Aadhar number verification. This system ensures that only verified individuals can vote, and it records votes in a tamper-proof manner.

## 🚀 Features
- **Face Registration**: Capture and store face data using the primary webcam.
- **Aadhar Verification**: Verify voter identity using their Aadhar number.
- **Voting**: Securely cast and record votes in CSV files.
- **Data Persistence**: Use of pickle for data serialization and storage.
- **Cross-platform Compatibility**: Works on Windows with win32com.client library support.

## 🛠️ Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pkprajapati7402/smart-election-system.git
   cd smart-election-system
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 🚦 Usage
1. **Run the Application**:
   ```bash
   python give_vote.py
   ```

2. **Register Voter**:
   - Follow the on-screen instructions to capture face data using the webcam.
   - Enter the Aadhar number for verification.

3. **Cast Vote**:
   - Verified users can cast their vote, which will be saved in a CSV file.

## 📁 Project Structure
```
smart-election-system/
│
├── data/
│  
│   ├── faces_data.pkl
│   ├── names.pkl
│
├── src/
│   ├── background.png
│   ├── votes.csv
│   ├── add_faces.py
│   ├── give_vote.py
│
├── README.md
├── requirements.txt
└── LICENSE
```

## 📦 Dependencies
- `cv2` (OpenCV): For capturing and processing face images.
- `pickle`: For serializing and deserializing Python object structures.
- `numpy`: For numerical operations.
- `os`: For interacting with the operating system.
- `csv`: For reading and writing CSV files.
- `time`: For time-related functions.
- `win32com.client`: For Windows-specific COM client operations.
- `sklearn`: For machine learning algorithms and data processing.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## 🤝 Contributing
Contributions are welcome!

## 🙏 Acknowledgements
- The OpenCV library for providing the tools necessary for computer vision tasks.
- The developers of sklearn for providing robust machine learning utilities.
- All contributors and users who help improve this project.

Feel free to create an issue or pull request if you have any questions or improvements. Happy coding! 🎨✨
