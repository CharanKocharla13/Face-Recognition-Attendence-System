# Face Recognition Attendance System

## Overview

The Face Recognition Attendance System is a Python-based application designed to automate attendance tracking using facial recognition technology. The system leverages OpenCV and face recognition libraries to identify and log the presence of individuals in real-time, providing an efficient and reliable method for managing attendance.

## Features

- **Real-Time Face Detection:** Utilizes pre-trained deep learning models to detect and recognize faces in real-time.
- **Attendance Logging:** Automatically records attendance by matching recognized faces against a pre-defined database.
- **User Management:** Add, update, and delete user profiles with associated facial images.
- **Attendance Reports:** Generate and export attendance reports in various formats (CSV, Excel).
- **User-Friendly Interface:** Simple and intuitive GUI for ease of use and navigation.

## Installation

To set up and run the Face Recognition Attendance System, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/CharanKocharla13/Face-Recognition-Attendence-System.git
   cd Face-Recognition-Attendence-System
   ```

2. **Create a Virtual Environment (Optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   Ensure you have `pip` installed, then run:

   ```bash
   pip install -r requirements.txt
   ```

4. **Download Pre-Trained Models:**

   Follow the instructions in `models/README.md` to download and place pre-trained models needed for face detection and recognition.

5. **Configure the System:**

   Edit `config/config.json` to set up your database and user management options.

6. **Run the Application:**

   ```bash
   python main.py
   ```

## Usage

- **Adding New Users:** Use the `add_user` function to capture and save new user faces.
- **Starting Attendance:** Run the main application to start face detection and attendance tracking.
- **Viewing Reports:** Access the generated reports through the `reports` directory.

## Contributing

Contributions are welcome! Please follow these guidelines:

- Fork the repository and create a feature branch.
- Write tests for your changes.
- Ensure all tests pass and run `lint` to check code quality.
- Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License - see the [LICENCE](LICENCE) file for details.

## Contact

For any questions or support, please open an issue on the GitHub repository or contact the repository owner at `charankocharla13@example.com`.
