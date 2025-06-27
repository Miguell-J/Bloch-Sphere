# Quantum Bloch Sphere Visualization

A cutting-edge, interactive web application for visualizing two-level quantum states on a Bloch sphere, built with modern web technologies for a seamless and immersive experience.

## 🌟 Features

- **Interactive Bloch Sphere**: Real-time 3D visualization of quantum states with smooth animations.
- **Quantum Parameters**: Adjust polar (θ) and azimuthal (φ) angles to explore quantum state space.
- **Fundamental States**: Easily switch between basis states like |0⟩, |1⟩, |+⟩, |-⟩, |+i⟩, and |-i⟩.
- **Quantum Operators**: Apply Pauli-X, Pauli-Y, Pauli-Z, Hadamard, Phase, and T gates to manipulate states.
- **Visual Controls**: Customize blur, rotation velocity, toggle auto-rotation, wireframe mode, and reset or randomize states.
- **State Information**: Displays real-time coordinates (X, Y, Z), probabilities P(|0⟩) and P(|1⟩), and state purity.

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, or Safari recommended).
- No additional dependencies required—runs entirely in the browser!

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quantum-bloch-sphere.git
   ```
2. Navigate to the project directory:
   ```bash
   cd quantum-bloch-sphere
   ```
3. Open `bloch.html` in a web browser:
   ```bash
   open bloch.html
   ```
   Alternatively, serve the file using a local server (e.g., with Python):
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000/bloch.html`.

## 🎮 Usage

1. **Adjust Angles**: Use sliders to modify θ (polar) and φ (azimuthal) angles to explore quantum states.
2. **Select States**: Click on fundamental states (|0⟩, |1⟩, etc.) to set the Bloch sphere to predefined quantum states.
3. **Apply Operators**: Use quantum operator buttons (Pauli-X, Hadamard, etc.) to transform the quantum state.
4. **Customize Visualization**: 
   - Adjust blur and rotation velocity for visual effects.
   - Toggle auto-rotation or wireframe mode.
   - Reset the view or randomize the quantum state for experimentation.
5. **Monitor State**: View real-time updates of the state vector |ψ⟩, coordinates, probabilities, and purity.

## 🛠️ Technologies Used

- **HTML5/CSS3**: For structure and styling of the interface.
- **JavaScript**: For interactivity and quantum state calculations.
- **WebGL (assumed)**: For rendering the 3D Bloch sphere.
- **MathJax (assumed)**: For rendering quantum state notation (e.g., |ψ⟩).

## 📂 Project Structure

```plaintext
quantum-bloch-sphere/
├── bloch.html        # Main HTML file with the application
├── css/              # (Optional) Stylesheets for custom styling
├── js/               # (Optional) JavaScript for logic and rendering
└── README.md         # This file
```

## 🤝 Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Please ensure your code follows the project's coding style and includes appropriate documentation.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments

- Inspired by quantum mechanics and the need for intuitive visualization tools.
- Built with love for the open-source community and quantum computing enthusiasts.