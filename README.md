# 🔐 AI-Powered Smart Door Surveillance System

A next-generation smart surveillance prototype that **uses AI to describe what’s at your door** — in real-time and in natural language. Instead of just detecting faces or sending raw camera footage, this system captures images when motion is detected and uses **GPT-4 Vision** to describe the scene like a human would.

## 📸 Example Output

- `"A delivery person holding a brown package is standing at the door."`
- `"A stray dog is sitting on the welcome mat."`
- `"Two unknown individuals are talking near the front gate."`

---

## 🎯 Features

✅ Motion detection via webcam or Raspberry Pi camera  
✅ Real-time object and person description using **GPT-4 Vision**  
✅ Accurate multi-person, multi-object interpretation  
✅ Logs all image descriptions with timestamps  
✅ Easily extendable with Home Assistant or smart lock integration

---

## 🛠 Tech Stack

| Component        | Description                                      |
|------------------|--------------------------------------------------|
| **Python 3.11+** | Core programming language                        |
| **OpenCV**       | Used for real-time motion detection              |
| **OpenAI API**   | GPT-4 Vision model for scene understanding       |
| **Flask** *(opt)*| Web interface for logs/images                    |
| **Home Assistant** *(opt)* | Integration for smart home automation |

---

## 🚀 Getting Started

### 1. Clone the Repository
bash
git clone https://github.com/yourusername/smart-door-ai.git
cd smart-door-ai

### 2. Install Dependencies
pip install -r requirements.txt

## 3. Add Your OpenAI API Key
Create a .env file in the root directory:
OPENAI_API_KEY=your-api-key-here

## 4. Run the System
python main.py

### 🧠 How It Works
- Motion Detection
When the system detects motion at the door, it captures an image using the webcam or Raspberry Pi camera.

- AI Image Analysis
The image is sent to GPT-4 Vision via OpenAI’s API.

- Natural Language Description
The response is a detailed, human-like description of what's seen at the door.

- Logging & Alerts (optional)
Descriptions can be stored locally and pushed to a mobile app, Home Assistant, or Telegram bot.

### 📦 Folder Structure
<pre> smart-door-ai/ ├── captured/ # Stores captured images ├── logs/ # Stores AI descriptions and timestamps ├── main.py # Core script ├── vision.py # Handles image processing and API call ├── motion.py # Handles motion detection ├── .env # OpenAI API key (not pushed to GitHub) └── requirements.txt # Python dependencies </pre>

### 🔐 Use Cases
- Home security system with smart alerts
- Accessibility tool for visually impaired individuals
- IoT-based visitor logbook
- AI-powered smart locks or access control

### 📲 Future Plans
 - Face recognition + object detection hybrid
 - Home Assistant integration via MQTT
 - Flutter-based mobile notifications
 - Live video streaming and audio response

### 📄 License
This project is licensed under the MIT License.


### 🤝 Contributing
Pull requests and feature suggestions are welcome! Please fork the repo and create a new branch for any changes.


### 🙋‍♂️ Maintainer
Developed by 31241979
If you like this project, consider giving it a ⭐ on GitHub!

