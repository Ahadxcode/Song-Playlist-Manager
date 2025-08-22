# Song-Playlist-Manager
A simple command-line **Music Playlist Manager** built with Python. This project allows you to add, search, list, shuffle, and remove songs. Playlists are saved automatically in **JSON** format and can also be exported to **CSV** for use in Excel/Google Sheets.   ---
---


## ✨ Features
- ➕ Add new songs with details (title, artist, album, duration)
- 📋 List all songs in the playlist
- 🔍 Search songs by title or artist
- 🔀 Shuffle play (random song)
- ❌ Remove songs by title
- 💾 Save and load playlist automatically (JSON)
- 📂 Export playlist to CSV


---


## 🚀 Getting Started


### 1. Clone the Repository
```bash
git clone https://github.com/your-username/playlist-manager.git
cd playlist-manager
```


### 2. Install Requirements
This project uses only Python’s standard library, so no extra dependencies are needed. Just ensure you have **Python 3.7+** installed.


### 3. Run the App
```bash
python playlist_manager.py
```


---


## 📖 Usage
When you run the program, you’ll see a menu:
```
Music Playlist Manager
1. Add Song
2. List Songs
3. Search Songs
4. Shuffle Play
5. Remove Song
6. Export to CSV
7. Exit
```


Simply enter the number for the action you want to perform.


---


## 📂 Project Structure
```
playlist-manager/
│-- playlist_manager.py # Main program
│-- playlist.json # Auto-saved playlist data (created after first run)
│-- playlist.csv # Exported CSV file (if chosen)
│-- README.md # Project documentation
```


---


## 🛠 Requirements
- Python 3.7+
- No external libraries needed (uses `json`, `csv`, and `random`)


---


## 🤝 Contributing
Pull requests are welcome! If you’d like to add features (e.g., playlist sorting, duration calculator, multiple playlists), feel free to fork and submit PRs.


---
