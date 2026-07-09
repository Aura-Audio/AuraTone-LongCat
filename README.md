# AuraTone-LongCat

### Tone Generator 🎵

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-Supported-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Responsive](https://img.shields.io/badge/Responsive-Design-green.svg)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

A professional, browser-based tone generator web app that creates high-quality audio tones with customizable waveforms, frequencies, and volume controls. Built with vanilla JavaScript and the Web Audio API for optimal performance and compatibility.

## ✨ Features

- **Multiple Waveforms**: Choose from Sine, Triangle, Square, and Sawtooth waves
- **Precise Frequency Control**: Adjustable range from 20 Hz to 2000 Hz
- **Volume Management**: Fine-tune output volume with intuitive slider
- **Real-time Audio**: Instant playback with no latency
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean, dark-themed interface with smooth animations
- **Zero Dependencies**: Pure HTML, CSS, and JavaScript implementation

## 🚀 Quick Start

### Option 1: Direct Download
```bash
git clone https://github.com/yourusername/tone-generator.git
cd tone-generator
```

### Option 2: Direct Implementation
Simply copy the HTML code into a file named `index.html` and open it in any modern web browser.

## 📖 Usage

1. **Select Waveform**: Click on your desired waveform button (Sine, Triangle, Square, or Sawtooth)
2. **Adjust Frequency**: Use the slider to set frequency between 20-2000 Hz
3. **Control Volume**: Adjust the volume slider to your preference
4. **Play/Stop**: Click the "Play Tone" button to start or stop audio output

## 🛠️ Technical Implementation

### Core Technologies
- **Web Audio API**: For high-quality audio synthesis and control
- **HTML5/CSS3**: Modern, responsive user interface
- **Vanilla JavaScript**: Lightweight, dependency-free implementation

### Audio Architecture
```javascript
// Core audio processing chain
AudioContext → OscillatorNode → GainNode → Destination
```

### Key Components
- **OscillatorNode**: Generates periodic waveforms
- **GainNode**: Controls volume/amplitude
- **AudioContext**: Manages audio processing environment

## 🎯 Use Cases

- **Audio Testing**: Test speakers, headphones, and audio equipment
- **Hearing Tests**: Generate specific frequencies for hearing assessment
- **Music Education**: Demonstrate different waveform characteristics
- **Sound Design**: Create basic tones for audio projects
- **Scientific Experiments**: Generate controlled audio frequencies

## 📱 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 14+ | ✅ Full |
| Firefox | 25+ | ✅ Full |
| Safari | 6+ | ✅ Full |
| Edge | 12+ | ✅ Full |
| Opera | 15+ | ✅ Full |

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with the powerful Web Audio API
- Inspired by professional audio testing tools
- Designed for developers, musicians, and audio enthusiasts

---

<p align="center">
  Made with ❤️ for the audio community
</p>

<p align="center">
  <a href="https://github.com/yourusername/tone-generator/issues">Report Bug</a> •
  <a href="https://github.com/yourusername/tone-generator/issues">Request Feature</a> •
  <a href="https://github.com/yourusername/tone-generator/discussions">Discussions</a>
</p>
