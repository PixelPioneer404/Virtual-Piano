# 🎹 Virtual Piano

A beautiful, interactive virtual piano that you can play using your computer keyboard! Experience the joy of making music right from your browser with realistic piano sounds and smooth animations.

![Virtual Piano Banner](https://img.shields.io/badge/Virtual-Piano-ff6b6b?style=for-the-badge&logo=music&logoColor=white)

## ✨ Features

- 🎵 **24 Piano Keys** - Complete two-octave range (C3 to B4)
- ⌨️ **Keyboard Controls** - Play using your computer keyboard
- 🎨 **Beautiful UI** - Modern design with smooth animations
- 🔊 **High-Quality Audio** - Realistic piano sound samples
- 📱 **Responsive Design** - Works on desktop and tablet devices
- ⚡ **Zero Latency** - Instant sound playback with audio pooling

## 🎮 How to Play

### White Keys (Natural Notes)
| Key | Note | Key | Note | Key | Note | Key | Note |
|-----|------|-----|------|-----|------|-----|------|
| Q   | C3   | W   | D3   | E   | E3   | R   | F3   |
| T   | G3   | Y   | A3   | U   | B3   | I   | C4   |
| O   | D4   | P   | E4   | Z   | F4   | X   | G4   |
| C   | A4   | V   | B4   |     |      |     |      |

### Black Keys (Sharp Notes)
| Key | Note | Key | Note | Key | Note | Key | Note | Key | Note |
|-----|------|-----|------|-----|------|-----|------|-----|------|
| 1   | C#3  | 2   | D#3  | 3   | F#3  | 4   | G#3  | 5   | A#3  |
| 6   | C#4  | 7   | D#4  | 8   | F#4  | 9   | G#4  | 0   | A#4  |

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/virtual-piano.git
   cd virtual-piano
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your favorite browser
   open index.html
   ```
   
   Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. **Start playing!** 🎹
   - Press any key to hear the corresponding piano note
   - Watch the visual feedback as keys light up when pressed
   - Combine keys to create chords and melodies

## 🛠️ Technology Stack

- **HTML5** - Semantic structure and audio elements
- **CSS3** - Modern styling with Tailwind CSS
- **Vanilla JavaScript** - Interactive functionality and audio management
- **Audio API** - High-quality sound playback with pooling for zero latency

## 📁 Project Structure

```
virtual-piano/
├── index.html          # Main HTML file
├── script.js           # JavaScript functionality
├── output.css          # Tailwind CSS styles
├── media/              # Audio files directory
│   ├── key1.mp3       # Piano sound samples
│   ├── key2.mp3       # (24 total audio files)
│   └── ...
└── README.md          # Project documentation
```

## 🎨 Design Features

- **Realistic Piano Layout** - Authentic piano key arrangement with proper spacing
- **Visual Feedback** - Keys change color when pressed for better user experience
- **Smooth Animations** - CSS transitions for polished interactions
- **Modern Typography** - Clean, readable fonts with proper hierarchy
- **Gradient Background** - Beautiful visual design that doesn't distract from functionality

## 🔧 Technical Highlights

### Audio Management
- **Audio Pooling**: Multiple audio instances per key to prevent sound cutting
- **Zero Latency**: Instant playback without delays
- **Memory Efficient**: Optimized audio loading and management

### Performance Optimizations
- **Event Delegation**: Efficient keyboard event handling
- **CSS Transforms**: Hardware-accelerated animations
- **Responsive Grid**: Flexible layout that adapts to different screen sizes

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Report bugs** - Found an issue? Let us know!
2. **Suggest features** - Have ideas for improvements?
3. **Improve documentation** - Help make the README even better
4. **Add new features** - Submit a pull request!

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes and test thoroughly
4. Commit your changes: `git commit -m 'Add some feature'`
5. Push to the branch: `git push origin feature-name`
6. Submit a pull request

## 🐛 Known Issues

- Audio may not work on some mobile browsers due to autoplay restrictions
- Safari may require user interaction before audio plays

## 📱 Browser Compatibility

| Browser | Supported | Notes |
|---------|-----------|-------|
| Chrome  | ✅ Yes    | Full support |
| Firefox | ✅ Yes    | Full support |
| Safari  | ✅ Yes    | May require user interaction for audio |
| Edge    | ✅ Yes    | Full support |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Rajbeer Saha**
- Created with ❤️ in 2025
- Feel free to reach out for collaborations or questions!

## 🙏 Acknowledgments

- Piano sound samples from high-quality recordings
- Tailwind CSS for the beautiful styling framework
- Inspiration from real piano interfaces

---

<div align="center">
  <p>
    <strong>🎹 Made with ❤️ for music lovers everywhere! 🎵</strong>
  </p>
  <p>
    <em>Turn your keyboard into a piano and let the music flow!</em>
  </p>
</div>