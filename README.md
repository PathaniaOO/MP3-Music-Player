# 🎵 Rainy Music Player  

A lightweight and modern **music player** built in **Python** using [DearPyGui](https://github.com/hoffstadt/DearPyGui) and [Pygame](https://www.pygame.org/).  
It supports adding songs, playlists, playback controls, and a neat UI.  

---

## ✨ Features
- 🎶 Play, Pause, Stop, Next, and Previous controls  
- 📂 Add **single files** or **entire folders**  
- 🔎 Search songs in your playlist  
- 💾 Persists songs in `songs.json` (so your list is saved)  
- 🔊 Volume and seek slider  
- 🎨 Custom theme with DearPyGui  
- ⏱️ Displays current state and "Now Playing" info  

---

## 🛠️ Installation

1. **Clone this repo**
   ```bash
   git clone https://github.com/PATHANIAOO/Rainy.git
   cd Rainy
   ```

2. **Create virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   venv\Scripts\activate   # Windows
   source venv/bin/activate  # Linux/Mac
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   *(If you don’t have `requirements.txt`, just run:)*  
   ```bash
   pip install dearpygui pygame mutagen
   ```

4. **Ensure project structure**
   ```
   Rainy/
   ├── main.py
   ├── icon.ico
   ├── data/
   │    └── songs.json
   ├── fonts/
   │    └── MonoLisa-Bold.ttf
   ```

5. **Run the app**
   ```bash
   python main.py
   ```

---

## 📂 songs.json
Make sure `data/songs.json` exists before running:  
```json
{
  "songs": []
}
```

---

## 🎯 Tech Stack
- **Python 3.x**
- **DearPyGui** – modern UI  
- **Pygame** – audio playback  
- **Mutagen** – MP3 metadata  
- **Tkinter** – file/folder selection  

---

## 📸 Screenshots
(Add screenshots of your player UI here, e.g. playing a song)  

---

## 📜 License
MIT License © 2025  
