# Idol Live Show Line Edition

A dynamic Three.js-based interactive art piece featuring synchronized idol line art with beat-synchronized visual effects.

## Features

- **Beat-synchronized Visual Effects**: Dynamic line width, bloom, confetti, and camera shake synchronized with music
- **Interactive Spotlights**: Multiple thin spotlight stripes that cut-switch with random angles, colors, and sizes
- **Dynamic Background**: Geometric patterns with animated stripes and dots
- **Real-time Controls**: Adjustable parameters for line width, bloom intensity, spotlight brightness, zoom, and more
- **Touch Support**: Pinch-to-zoom functionality for mobile devices
- **Eye-friendly Design**: Optimized visual effects to reduce eye strain

## Technologies Used

- **Three.js**: 3D graphics rendering
- **WebGL**: Hardware-accelerated graphics
- **GLSL Shaders**: Custom background effects
- **HTML5 Audio**: Beat synchronization
- **CSS3**: Modern UI styling

## Setup

1. Clone the repository:
```bash
git clone [repository-url]
cd idol-live-show-line-edition
```

2. Start a local server (required for module imports):
```bash
python3 -m http.server 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000/idol_live_line.html
```

## Controls

- **Line Width**: Adjust the thickness of the idol line art
- **Idol Bloom**: Control the glow effect around the idol
- **Confetti Glow**: Adjust the brightness of the confetti particles
- **Spotlight Brightness**: Control the intensity of the spotlight effects
- **Spotlight Strobe**: Adjust the strobe effect intensity
- **Camera Shake**: Control the camera shake intensity
- **Zoom**: Adjust the camera zoom level

## File Structure

- `idol_live_line.html`: Main application file
- `bgm.wav`: Background music for beat synchronization
- `lines1.js` - `lines4.js`: Idol line art geometry data
- `LICENSE`: MIT License
- `README.md`: This file

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Credits

Created with ❤️ using Three.js and modern web technologies.
