# PocketLab - Science Lab in Your Pocket

Transform your smartphone into a portable science laboratory with real-time sensors and interactive chemistry experiments.

## 🌟 About the Project

PocketLab addresses UN Sustainable Development Goal 4 (Quality Education) by making hands-on science education accessible to underprivileged communities with limited resources. Using built-in smartphone sensors and offline-first technology, students can conduct physics experiments and chemistry reactions without expensive lab equipment or reliable internet access.

### Inspiration
Traditional science education requires expensive equipment, dedicated lab spaces, and reliable internet - resources many students lack. With over 6 billion smartphones worldwide, we saw an opportunity to democratize science education by leveraging devices students already have.

### What it does
- **Real-time Physics Experiments**: Uses accelerometer, gyroscope, and sound sensors for hands-on learning
- **Interactive Chemistry Lab**: 180+ chemical reactions with drag-and-drop elements and realistic visuals
- **Offline-First Design**: Works without internet after initial visit
- **Educational Content**: Built-in learning objectives, sample activities, and real-time tips
- **Data Export**: CSV export for analysis and scientific method practice

### How we built it
Built as a single HTML file with vanilla JavaScript, CSS, and Web APIs. Uses DeviceMotion, DeviceOrientation, and MediaDevices APIs for sensor access. Chemistry engine simulates realistic reactions with temperature effects and visual feedback. Progressive Web App features enable offline functionality and home screen installation.

### Challenges we ran into
- iOS sensor permission handling required DeviceMotionEvent.requestPermission()
- Chemistry reaction system needed complex state management to prevent repeats
- Offline functionality required Service Worker implementation
- Visual effects needed careful optimization for mobile performance

### Accomplishments that we're proud of
- Created a fully functional science lab accessible on any smartphone
- Implemented 180+ unique chemical reactions with educational content
- Built offline-first design for communities with limited internet
- Made complex physics concepts accessible through interactive visualizations
- Achieved open-source, reproducible codebase for continued development

### What we learned
- Web Sensor APIs have different implementations across platforms
- Progressive Web Apps can provide native-like experiences
- Chemistry education can be gamified while maintaining scientific accuracy
- Offline-first design is crucial for accessibility in underprivileged communities

### What's next for PocketLab
- Expand chemistry reactions and add more elements
- Implement collaborative features for classroom use
- Add AR features for enhanced visual learning
- Create teacher dashboard for lesson planning
- Develop curriculum integration guides

## 🚀 Quick Start

1. **Visit the app**: Open [PocketLab](https://your-deployment-url.com) in any modern web browser
2. **Add to Home Screen**: Tap the install prompt or manually add to home screen for app-like experience
3. **Grant Permissions**: Allow sensor access when prompted for full functionality
4. **Start Exploring**: Navigate between physics sensors and chemistry lab

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Sensors**: Web Sensor APIs (Accelerometer, Gyroscope, DeviceMotion)
- **Audio**: Web Audio API, MediaDevices API
- **Offline**: Service Workers, Progressive Web App (PWA)
- **Data**: CSV export functionality
- **Deployment**: GitHub Pages, Vercel

## 📱 Features

### Physics Sensors
- **Accelerometer**: Real-time 3D motion tracking with educational experiments
- **Gyroscope**: Interactive level indicator with color-coded feedback
- **Sound Level**: Ambient noise monitoring with decibel scale education

### Chemistry Lab
- **180+ Reactions**: From basic acid-base to complex temperature-dependent processes
- **Drag & Drop**: Intuitive element and liquid interaction
- **Visual Effects**: Realistic flask, liquid animations, and reaction feedback
- **Educational Content**: Sample reactions guide and learning objectives

### Accessibility Features
- **Offline Functionality**: Works without internet after initial visit
- **No App Store**: Web-based, works on any device with a browser
- **Universal Design**: Responsive layout for all screen sizes
- **Educational Focus**: Built-in learning guides and sample activities

## 👥 Team Information

### Team Members

**Harsh Monga** - Lead Developer & Project Manager
- Role: Full-stack development, project architecture, hackathon coordination
- Background: Computer Science student with passion for educational technology
- Contributions: Core application development, sensor integration, chemistry engine

## 📖 User Guide

### Getting Started
1. Open PocketLab in your web browser
2. Grant sensor permissions when prompted
3. Navigate between sections using the menu buttons
4. For offline use, add to home screen when prompted

### Using Physics Sensors
1. **Accelerometer**: Tilt your device to see real-time motion data
2. **Gyroscope**: Rotate device to see level indicator change colors
3. **Sound**: Speak or make noise to see decibel level changes
4. **Recording**: Use the record button to capture data for analysis
5. **Export**: Download CSV files for further analysis

### Using Chemistry Lab
1. **Drag Elements**: Drag periodic table elements into the flask
2. **Add Liquids**: Pour different liquids to create reactions
3. **Use Tools**: Apply heat (matchstick) or cooling (ice) for temperature effects
4. **Watch Reactions**: Observe visual feedback and read educational explanations
5. **Try Samples**: Use the "Sample Reactions" guide for guaranteed reactions

### Offline Usage
1. Visit PocketLab while connected to internet
2. Tap "Add to Home Screen" when prompted
3. The app will work offline for future visits
4. All features remain available without internet connection

## 🔧 Technical Setup

### Prerequisites
- Modern web browser (Chrome, Safari, Firefox, Edge)
- HTTPS connection (required for sensor APIs)
- Smartphone with sensors (for full functionality)

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/hmonga/EduConnect.git
   cd EduConnect
   ```

2. Serve the files using a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Open `http://localhost:8000` in your browser

### Deployment
- **GitHub Pages**: Push to main branch for automatic deployment
- **Vercel**: Connect repository for automatic deployments
- **Netlify**: Drag and drop the index.html file

## 📊 Project Impact

- **Target Audience**: Students in underprivileged communities worldwide
- **Accessibility**: Works on any smartphone with a web browser
- **Educational Value**: Hands-on science learning without expensive equipment
- **Scalability**: Open source code allows global adoption and customization

## 🤝 Contributing

We welcome contributions to make PocketLab even better:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Live Demo**: [PocketLab](https://edu-connect-cyan.vercel.app/)
- **GitHub Repository**: [EduConnect](https://github.com/hmonga/EduConnect)
- **Hackathon**: Empower Hacks 3.0 - Project Empower

---

**Built with ❤️ for accessible science education**
