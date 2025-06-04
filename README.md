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

```bash
git clone https://github.com/yourusername/smart-door-ai.git
cd smart-door-ai
