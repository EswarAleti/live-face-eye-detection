# Live Face and Eye Detection

This repository contains a web framework developed using OpenCV and Flask for real-time face and eye detection in live video streams. The project leverages the powerful image processing capabilities of OpenCV and the simplicity of Flask to create a responsive and efficient web application.

## Features

- **Real-time Face Detection**: Detects faces in live video streams using OpenCV's pre-trained models.
- **Real-time Eye Detection**: Detects eyes within detected faces to enhance facial detection accuracy.
- **Web Interface**: Provides a simple and user-friendly web interface for accessing the live video stream and detection results.
- **Cross-Platform**: Works on various operating systems including Windows, macOS, and Linux.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.6 or higher
- pip (Python package installer)

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/EswarAleti/live-face-eye-detection.git
    cd live-face-eye-detection
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv_name
    source venv_name/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Flask application**:
    ```bash
    python app.py
    ```

2. **Access the web interface**:

    Open your web browser and navigate to `http://127.0.0.1:5000`. You should see the live video stream with real-time face and eye detection.

## Project Structure

```bash
live-face-eye-detection/
│
├── app.py              # Main Flask application including detection logic using OpenCV
├── templates/
│   └── index.html      # HTML template for the web interface
├── static/
│   └── css/
│       └── styles.css  # CSS styles for the web interface
└── requirements.txt    # Python dependencies
```

## Output
![alt text](https://github.com/EswarAleti/live-face-eye-detection/blob/main/output.png?raw=true)

---

Enjoy detecting faces and eyes in real-time with this web application!
