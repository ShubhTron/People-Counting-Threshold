# People Counting Threshold
![Screenshot (337)](https://github.com/user-attachments/assets/1877686b-d694-497a-a7af-5baca1bae24c)



![Screenshot (339)](https://github.com/user-attachments/assets/79dc4b7a-96e4-49a9-9f33-f994e564045e)

## 📋 Description
This project is a real-time people counting system using YOLOv5, capable of detecting and counting individuals from video streams or uploaded files. It includes automatic email alerts when more than three people are detected.

🔗 **GitHub Repository:** [People-Counting-Threshold](https://github.com/ShubhTron/People-Counting-Threshold)

---

## 🚀 Features
- Real-time video inference
- Upload video files for processing
- Email alerts when the threshold is exceeded
- Downloadable reports
- Live stream inference using IP camera

---

## 💾 Installation
1. Clone the repository:
```bash
git clone https://github.com/ShubhTron/People-Counting-Threshold.git
```
2. Navigate to the project directory:
```bash
cd People-Counting-Threshold
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 💻 Usage
### Start the Application
```bash
python app.py
```

### Web Interface
- Access the web interface at [http://127.0.0.1:5000](http://127.0.0.1:5000)

### Operations
- **Upload Video:** Choose a video file and upload it for processing.
- **Inference on Video:** Click to process the uploaded video using YOLOv5.
- **Live Inference:** Enter the IP camera URL for real-time people counting.
- **Download Report:** Download a detailed report of detections.
- **Email Alert:** Enable email alerts by entering an email and toggling the switch.

---

## 📧 Email Alerts
The system automatically sends an email alert when more than three people are detected in the video.

- Sender: `csaiml22149@glbitm.ac.in`
- Recipient: Customizable via web interface
- Subject: `More than 3 people detected`

---

## 📦 Folder Structure
```
People-Counting-Threshold
├── app.py
├── send_mail.py
├── static
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   └── scripts.js
│   └── video
├── templates
│   └── index.html
└── requirements.txt
```

---

## 🤖 YOLOv5 Integration
- Model: `yolov5s` (pre-trained)
- Framework: PyTorch

---

## 🌐 Web Technologies
- Flask (Backend)
- HTML, CSS, JS (Frontend)
- jQuery (AJAX for asynchronous requests)

---

## 📨 Email Integration
- Uses SMTP for sending emails
- Configured in `send_mail.py`

---

## 📝 License
This project is licensed under the MIT License.

---

**Contributors:**
- [ShubhTron](https://github.com/ShubhTron)

---

**Feel free to contribute, report issues, or suggest improvements!**

