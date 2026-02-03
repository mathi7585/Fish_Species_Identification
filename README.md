# 🐟 Fish_Species_Identification

Fish_Species_Identification is a robust system that leverages cutting-edge computer vision to identify fish species from images or video feeds. By integrating the YOLO (You Only Look Once) object detection framework with a TensorFlow-based classification model, this project enables accurate and efficient fish species detection and classification — ideal for researchers, conservationists, and fisheries management.

---

## 🚀 Features

- **End-to-End Pipeline:** Detects and classifies fish species from images or video streams.
- **YOLOv8 Integration:** Fast and reliable object detection using the latest YOLO framework.
- **Deep Learning Classification:** Utilizes TensorFlow (ResNet50) for robust species recognition.
- **Real-Time Processing:** Suitable for live camera feeds or batch image processing.
- **Notification Support:** Integrates with Twilio to send notifications (e.g., for rare species detection).
- **Modular Design:** Easily extensible for additional features or use cases.

---

## 🛠️ Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/mathi7585/Fish_Species_Identification.git
    cd Fish_Species_Identification
    ```

2. **Create & Activate a Python Virtual Environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    ```

3. **Install Required Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    > **Note:** Dependencies include `torch`, `ultralytics`, `tensorflow`, `opencv-python`, `numpy`, and `twilio`.

4. **Download or Place Model Weights:**
    - Place your trained YOLOv8 weights (e.g., `best.pt`) and ResNet50 model in the designated paths as referenced in `fish.py`.

---

## 📖 Usage

1. **Prepare Input Data:**
    - Collect fish images or connect a video feed/camera.

2. **Run the Identification Script:**
    ```bash
    python fish.py --image path_to_image.jpg
    ```
    Or for video input:
    ```bash
    python fish.py --video path_to_video.mp4
    ```

3. **Results:**
    - The script will output detected fish species and can optionally send notifications via Twilio (configure your credentials in `fish.py`).

4. **Configuration:**
    - Modify model paths and Twilio credentials as necessary in `fish.py`.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes with clear messages.
4. Open a pull request describing your changes.

Feel free to open issues for suggestions, bugs, or feature requests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Happy fishing! 🐠🐡🐟**

## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/mathi7585/Fish_Species_Identification
