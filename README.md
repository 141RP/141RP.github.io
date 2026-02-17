# 141RP.github.io
# Rohin Patel

A modern animated hero section built with Three.js, custom shaders, and interactive effects.
---

## Libraries & External Resources

### Three.js (r128)
- Loaded via CDN
- Used for:
  - WebGL rendering
  - Scene, camera, and renderer setup
  - ShaderMaterial for animated gradient
  - Plane geometry for fullscreen background
  - Texture handling for touch distortion

### Google Fonts
- Montserrat (700)
- Work Sans (300, 400, 500)

Used for hero title and UI typography.

---

## Technologies Used

- HTML5
- CSS3 (Variables, Animations, Backdrop Filter, Mix-blend-mode)
- JavaScript (ES6 Classes)
- WebGL
- GLSL Shaders

---

## Main Features

### Animated Gradient Background
- Built with custom GLSL shaders
- Multi-point animated color blending
- Grain/noise effect
- Ripple distortion on mouse/touch

### Touch Interaction
- Tracks mouse and touch movement
- Generates a dynamic distortion texture
- Creates fluid ripple effects

### Text Scramble Effect
- Custom JavaScript animation
- Random character transitions
- Runs on page load

### Custom Cursor
- Animated ring + dot
- Smooth interpolation movement
- Hover scaling effects
- Disabled on mobile

### Dark / Light Mode Support
- Detects system preference
- Updates shader colors dynamically
- Adjusts UI styling

### Pause / Play Button
- Toggles background animation
- Smooth icon transition

---

## Project Structure

- `index.html` – Markup and layout
- `styles.css` – Styling and responsive design
- `script.js` – Three.js logic and animations

---

## Design Style

- Modern
- Minimal
- High-contrast dark theme
- Interactive and motion-focused
- Glassmorphism-inspired UI elements
