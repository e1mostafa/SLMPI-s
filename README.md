<div align="center">

<img src="app/src/main/res/mipmap-xxxhdpi/ic_launcher.png" width="120" alt="TitanBeats Logo"/>

# SLMPI's 🎵

**Offline anime-inspired music player for Android**

*"The only thing we're allowed to do is believe that we won't regret the choice we made."*
*— Levi Ackerman*


## ✨ Features

- 🎧 **Offline playback** — plays all local music files, no internet needed
- 🌸 **Anime-soft UI** — Attack on Titan aesthetic, soft pastel dark theme
- 🎨 **Dynamic colors** — background adapts to album art using Palette API
- 🔁 **Full controls** — repeat, shuffle, favorites, playlists, queue
- 🔒 **Lock screen & notification** controls
- ⚡ **Samsung optimized** — smooth on 2–4GB RAM devices
- 💤 **Sleep timer** — auto-stop after 15/30/45/60 minutes
- 🎚️ **Equalizer** — built-in audio tuning
- ⏩ **Playback speed** — 0.5x to 2.0x
- 📁 **Auto-scan** — finds all music on your device automatically

---

## 📲 Download & Install

### Direct Install (Easiest)
1. Go to [**Releases**](https://github.com/e1mostafa/SLMPI-s.git)
2. Download `SLMPI's.apk`
3. On your phone: **Settings → Apps → Special Access → Install Unknown Apps**
4. Allow your browser or file manager
5. Open the APK and tap Install

### Requirements
| | |
|---|---|
| Android version | 5.0 (Lollipop) and above |
| RAM | 2GB minimum, 3GB+ recommended |
| Storage | ~25MB for the app |
| Permissions | Storage access (to read your music files) |

---


## 🛠️ Built With

| Technology | Purpose |
|-----------|---------|
| **Kotlin** | Main language |
| **Media3 / ExoPlayer** | Audio playback engine |
| **Room Database** | Local storage for songs, playlists, favorites |
| **Glide** | Album art loading & caching |
| **Palette API** | Dynamic colors from album art |
| **Navigation Component** | Fragment navigation |
| **LiveData + ViewModel** | State management |
| **Coroutines** | Background threading |
| **Material Design 3** | UI components |

---

## 📁 Project Structure

```
TitanBeats/
├── app/src/main/java/com/titanbeats/
│   ├── data/
│   │   ├── database/        # Room DB + DAOs
│   │   ├── models/          # Song, Playlist data classes
│   │   └── repository/      # MediaStore scanner
│   ├── service/
│   │   └── MusicService.kt  # Background playback
│   ├── ui/
│   │   ├── activities/      # Main, Player, Equalizer, Splash
│   │   ├── adapters/        # RecyclerView adapters
│   │   ├── fragments/       # Home, Library, Favorites, Playlists
│   │   └── viewmodels/      # PlayerViewModel, LibraryViewModel
│   └── utils/               # Extensions, WavyProgress
└── app/src/main/res/
    ├── layout/              # XML layouts
    ├── drawable/            # Icons & backgrounds
    ├── values/              # Colors, themes, strings
    └── font/                # Nunito font family
```

---

## 🚀 Build From Source

```bash
# Clone the repo
git clone https://github.com/e1mostafa/SLMPI-s.git

# Open in Android Studio Hedgehog or newer
# Wait for Gradle sync to finish

# Build debug APK
./gradlew assembleDebug

# Output:
# app/build/outputs/apk/debug/app-debug.apk
```

---

## 🔮 Roadmap

- [ ] Lyrics support (offline `.lrc` files)
- [ ] Light pastel mode
- [ ] Home screen widget
- [ ] Custom themes (5+ color palettes)
- [ ] Artist & album detail pages
- [ ] Tag editor (edit song metadata)
- [ ] Stats screen (listening time, top songs)
- [ ] Android Auto support

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

1. Fork the repo
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit: `git commit -m "Add your feature"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

```
MIT License — feel free to use, modify, and distribute.
See LICENSE file for details.
```

---

<div align="center">

Built with ♡ using Kotlin

*SLMPI's original sin — Your music. Your world. No limits.*

⭐ **Star this repo if you like it!** ⭐

</div>
