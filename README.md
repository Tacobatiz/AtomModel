# 🧪 3D Molecule Viewer

A real-time, interactive molecular visualization tool built in C++ using **OpenGL** and **GLUT**. This viewer supports over 20 predefined molecules and allows users to explore them with intuitive controls.

---

## ✨ Features

*  Realistic 3D rendering of atoms and bonds
*  Color-coded atoms by element (e.g., red for Oxygen, white for Hydrogen)
*  Mouse-based rotation and keyboard-controlled zoom
*  Preloaded with over 20 molecules (water, methane, ethanol, etc.)
*  Lighting and shading for visual depth
*  On-screen overlay with controls and color legend

---

## 📆 Predefined Molecules

| Key | Formula | Name (ES)           |
| --- | ------- | ------------------- |
| Q   | H₂O     | Agua                |
| W   | C₆H₆    | Benceno             |
| E   | CO₂     | Dióxido de Carbono  |
| R   | CH₄     | Metano              |
| T   | NH₃     | Amoníaco            |
| Y   | O₂      | Oxígeno             |
| U   | H₂      | Hidrogeno           |
| I   | N₂      | Nitrógeno           |
| O   | H₂SO₄   | Ácido Sulfúrico     |
| P   | C₂H₂    | Etilino             |
| A   | C₂H₄    | Eteno               |
| S   | NaCl    | Sal                 |
| D   | C₂H₅OH  | Etanol              |
| F   | CH₂O    | Formaldehído        |
| G   | NO      | Óxido Nítrico       |
| H   | CO      | Monóxido de Carbono |
| J   | NH₄⁺    | Ion Amonio          |
| K   | NaOH    | Hidroxido de Sodio  |
| L   | HCl     | Ácido Clorhídrico   |

---

## 🖾 Controls

| Action           | Input                     |
| ---------------- | ------------------------- |
| Rotate molecule  | Click and drag mouse      |
| Zoom in/out      | `+` / `-` keys            |
| Reset view       | `R` key                   |
| Change molecule  | Press key matching legend |
| Exit application | `ESC` key                 |

---

## 🚀 Getting Started

### 🔧 Prerequisites

* OpenGL development libraries
* FreeGLUT
* C++ compiler (e.g., `g++` or Visual Studio)

### 🛠️ Build Instructions

#### On Windows (MinGW):

```bash
g++ main.cpp -o MoleculeViewer -lOpenGL32 -lglu32 -lfreeglut
```

#### On Linux:

```bash
g++ main.cpp -o MoleculeViewer -lGL -lGLU -lglut
```

Then run:

```bash
./MoleculeViewer
```

---

## 📁 Project Structure

```plaintext
.
├── main.cpp         # Main application file
├── README.md        # Project documentation
```

---

## 🙌 Acknowledgements

* [OpenGL](https://www.opengl.org/)
* [FreeGLUT](http://freeglut.sourceforge.net/)
* [SIGGRAPH Paper Guidelines](https://www.siggraph.org/preparing-your-content/author-instructions/)
