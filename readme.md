# Krita Auto Perspective

A Krita plugin for applying perspective transformations to drawn or imported elements, 
featuring mesh-based warping and intuitive skew/rotate controls.

---

## Goals

- Provide an intuitive perspective transformation tool directly inside Krita
- Support mesh-based warping for fine-grained control over elements
- Enable skew and rotate operations that respect perspective rules
- Mirror functionality similar to Adobe Photoshop perspective warp/transform tools
- Remain fully open-source and community-driven

---

## Dependencies

### Runtime
- Krita (version X.X or higher)
- Python 3.X
- PyQt5 - UI components (bundled with Krita)
- NumPy - Matrix and transformation math
- OpenCV (opencv-python) - Image warping and perspective transforms

### Development
- pytest - Unit testing
- black - Code formatting
- flake8 - Linting

---

## Installation

1. Clone this repository:

   git clone https://github.com/yourusername/krita-auto-perspective.git

2. Copy the plugin folder into your Krita pykrita directory:
   - Linux: ~/.local/share/krita/pykrita/
   - Windows: %APPDATA%\krita\pykrita\
   - macOS: ~/Library/Application Support/krita/pykrita/

3. Enable the plugin in Krita under Settings > Configure Krita > Python Plugin Manager

---

## Roadmap

- [ ] Basic perspective skew/rotate on selected layers
- [ ] Mesh warp grid overlay UI
- [ ] Control point dragging for mesh deformation
- [ ] Undo/redo integration with Krita's history
- [ ] Preset perspective angles (e.g., 1-point, 2-point, 3-point)
- [ ] Export transformed layer as flat image

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
Before contributing, read through the Contributing Guidelines (CONTRIBUTING.md).

---

## License

This project is licensed under the GNU General Public License v3.0 -
see the LICENSE file for details.

---

## Acknowledgements

- Inspired by Adobe Photoshop Perspective Warp and Free Transform tools
- Built on top of the Krita Scripting API (https://api.kde.org/krita/html/index.html)
