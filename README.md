## 🚀 Technologies Used

- **Python 3.11**  
  Recommended version to ensure compatibility with MediaPipe binaries on Windows.

- **MediaPipe Pose**  
  Used for robust body tracking, calculating the relationship between the nose position and the shoulder line.

- **OpenCV**  
  Responsible for video capture and rendering real-time visual feedback elements.

- **Tkinter & Pillow**  
  Used for the popup window interface and handling GIF frame animations.

- **Pygame**  
  Manages the audio engine to execute persistent sound loops.

---

## 🛠️ How to Run

### 1. Environment Setup

```bash
# Create the environment
python -m venv .venv

# Activation (Windows)
.venv\Scripts\activate

pip install -r requirements.txt

python main.py

focus_booster/
├── assets/
│   ├── gif/
│   │   ├── skeleton_war.gif
│   │   └── the_rock.gif
│   └── audios/
│       ├── skeleton.mp3
│       └── the_rock.mp3
├── main.py
└── requirements.txt
