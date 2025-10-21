# 3D Car Simulation

A realistic 3D car simulation built with React, Three.js, and Cannon.js physics engine.

## 🚗 Features

- Realistic vehicle physics and handling
- Dynamic lighting system with headlights
- Engine vibration effects
- Turbo boost mode
- Interactive speedometer
- Sound effects for engine start, acceleration, and braking
- Responsive controls
- HDR skybox environment 
- Textured ground surface

## 🎮 Controls

- **E**: Toggle engine on/off
- **W/↑**: Accelerate
- **S/↓**: Reverse
- **A/←**: Turn left
- **D/→**: Turn right
- **Space**: Brake
- **Shift**: Activate turbo mode (6 seconds duration)

## 🛠️ Technologies Used

- React.js
- Three.js
- Cannon.js
- GLTF Loader
- RGBE Loader

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/Unnati-Gupta24/Car-game.git
```

2. Navigate to the project directory:

```bash
cd car-simulation
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

## 🗂️ Project Structure

```
car-simulation/
├── public/
│   ├── car-body/
│   ├── textures/
│   └── sky/
├── src/
│   ├── lib/
│   ├── App.jsx
│   ├── Speedometer.jsx
│   └── App.css
└── package.json
```

## 🔧 Dependencies

- three
- cannon-es
- react
- @react-three/fiber
- @react-three/drei

## 🎨 Customization

The simulation can be customized by:

- Modifying physics parameters in the vehicle setup
- Adjusting lighting intensity
- Changing car model and textures
- Tweaking control sensitivity

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/3D-Car-Simulation/issues).

## 📝 License

This project is [MIT](LICENSE) licensed.
