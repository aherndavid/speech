# dPaul Text-to-Speech

A professional, hardware-styled text-to-speech application with a realistic silver unit design and green LED display.

![dPaul TTS Unit](https://img.shields.io/badge/Status-Active-brightgreen) ![Version](https://img.shields.io/badge/Version-1.0-blue)

## 🎙️ Live Demo

**Access the tool here:** [https://dpaul.studio/speech/speak7.html](https://dpaul.studio/speech/speak7.html)

---

## ✨ Features

### Professional Hardware Design
- **Realistic silver metal finish** - Brushed aluminum aesthetic
- **Green LED display** - Subtle, readable monospace text entry
- **3D metallic controls** - Realistic buttons and sliders
- **Studio-grade interface** - Clean, professional layout

### Voice Synthesis Controls
- **Google Voices** - High-quality voice selection
- **Speed Control** - Adjust speaking rate (0.5x - 2x)
- **Pitch Adjustment** - Modify voice tone (0.5 - 2.0)
- **Volume Control** - Fine-tune output level
- **Playback Controls** - Speak, Pause/Resume, Stop

### Use Cases
- 🎬 **Video narration** - Professional voiceovers for automotive showcases
- 📝 **Script testing** - Preview text before recording
- 🎓 **Content creation** - Quick voice generation for projects
- ♿ **Accessibility** - Text-to-speech for reading content aloud

---

## 🚀 Quick Start

1. Open [https://dpaul.studio/speech/speak7.html](https://dpaul.studio/speech/speak7.html)
2. Type or paste your script into the green LED display
3. Select a voice from the dropdown
4. Adjust speed, pitch, and volume as needed
5. Click **SPEAK** to generate audio

---

## 🎛️ Controls Guide

### Script Display
- **Green LED text area** - Enter your text here
- Monospace font for easy reading
- Resizable text area (drag bottom-right corner)

### Voice Settings

| Control | Range | Default | Description |
|---------|-------|---------|-------------|
| **Voice** | Google voices | First available | Select synthesis voice |
| **Speed** | 0.5x - 2.0x | 1.0x | Speaking rate |
| **Pitch** | 0.5 - 2.0 | 1.0 | Voice tone/frequency |
| **Volume** | 0% - 100% | 100% | Output level |

### Buttons

| Button | Function |
|--------|----------|
| **SPEAK** | Generate and play audio |
| **PAUSE** | Pause/Resume playback |
| **STOP** | Stop and reset playback |

---

## 💡 Tips & Best Practices

### For Vehicle Narration
1. **Use slower speeds** (0.8x - 0.9x) for detailed technical descriptions
2. **Lower pitch slightly** (0.9 - 1.0) for authoritative, professional tone
3. **Test multiple voices** - Different voices suit different vehicle types
4. **Break long scripts** - Pause between sections for natural pacing

### Voice Selection
- **UK Male voices** - Best for luxury/classic vehicles (Ferrari, Bentley)
- **US Male voices** - Good for American muscle cars
- **Female voices** - Can work well for modern/electric vehicles

### Script Formatting
- Add **commas** for natural pauses
- Use **periods** for longer breaks
- Write **numbers as words** for better pronunciation (e.g., "five hundred twelve" instead of "512")
- Spell out **abbreviations** (e.g., "Berlinetta Boxer" instead of "BB")

---

## 🔧 Technical Details

### Technology Stack
- **HTML5** - Structure
- **CSS3** - Hardware-styled interface with gradients and shadows
- **Vanilla JavaScript** - No dependencies
- **Web Speech API** - Browser-native text-to-speech

### Browser Compatibility
✅ **Chrome/Edge** - Full support (recommended)  
✅ **Safari** - Full support  
⚠️ **Firefox** - Limited voice selection  
❌ **IE** - Not supported

### Requirements
- Modern web browser (2020+)
- Internet connection (for Google voices)
- No installation required

---

## 📱 Mobile Support

The interface is fully responsive and works on:
- 📱 **iOS** - Safari (iPhone/iPad)
- 🤖 **Android** - Chrome/Samsung Internet
- 💻 **Tablets** - All major browsers

*Note: Voice selection may vary by device/OS*

---

## 🎨 Design Philosophy

Inspired by professional audio equipment from recording studios, the interface mimics:
- **Vintage hardware units** - Realistic metal construction
- **LED displays** - Classic green monochrome screens
- **Tactile controls** - Physical-style sliders and buttons
- **Minimalist layout** - No distractions, pure functionality

---

## 🛠️ Development

### File Structure
```
speech/
├── speak7.html          # Main application (standalone)
└── README.md            # This file
```

### Standalone Application
This is a **single-file application** - everything (HTML, CSS, JavaScript) is contained in `speak7.html`. No external dependencies, frameworks, or build process required.

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/aherndavid/speech.git
   cd speech
   ```

2. Open `speak7.html` in your browser:
   ```bash
   open speak7.html
   ```

3. Make changes directly to the HTML file

4. Refresh browser to see updates

---

## 📝 License

© 2026 dPaul Technologies. All rights reserved.

This tool is provided for personal and professional use. Feel free to use it for:
- ✅ Video production and content creation
- ✅ Accessibility purposes
- ✅ Personal projects
- ✅ Commercial voiceover work

---

## 🤝 Credits

**Created by:** David Paul  
**Domain:** [dpaul.studio](https://dpaul.studio)  
**GitHub:** [@aherndavid](https://github.com/aherndavid)  

**Part of the dPaul Technologies suite** - Professional tools for creative professionals.

---

## 📞 Support & Feedback

- **Issues:** [GitHub Issues](https://github.com/aherndavid/speech/issues)
- **Website:** [dpaul.studio](https://dpaul.studio)
- **AutoFacts:** [autofacts.uk](https://autofacts.uk)

---

## 🔄 Version History

### v1.0 (February 2026)
- ✨ Initial release
- 🎨 Silver hardware design with green LED display
- 🎙️ Google voice integration
- 🎛️ Speed, pitch, and volume controls
- ⏯️ Full playback control (speak, pause, stop)
- 📱 Mobile-responsive design

---

## 🚧 Roadmap

Future enhancements under consideration:
- [ ] Voice presets (save favorite settings)
- [ ] Export audio to file
- [ ] Batch processing multiple scripts
- [ ] SSML markup support for advanced control
- [ ] Custom voice upload (AI voice cloning)

---

**Made with ❤️ for automotive content creators**
