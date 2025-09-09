# 🚀 TaskFlow - Advanced To-Do App

![TaskFlow Banner](https://via.placeholder.com/800x200/667eea/ffffff?text=TaskFlow+-+Advanced+To-Do+App)

A modern, feature-rich to-do application with multiple list management, smart timers, and a beautiful responsive design inspired by FreeCodeCamp's aesthetic.

## ✨ Features

### 📋 **Multi-List Management**
- Create unlimited to-do lists with custom titles
- Visual progress tracking for each list (e.g., "3/7 completed")
- Beautiful progress bars with gradient fills
- Easy list switching with sidebar navigation

### ⏰ **Smart Timer System**
- Customizable timer duration for each list (1-480 minutes)
- Real-time countdown display
- Start, pause, and reset functionality
- **3-minute warning notification** system
- Timer persistence while working on tasks

### ✅ **Advanced Task Management**
- Quick task addition with Enter key support
- One-click task completion toggle
- Visual completion states with smooth animations
- Hover-to-reveal delete functionality
- Task statistics and progress tracking

### 🎨 **Stunning Design**
- **Glassmorphism UI** with blur effects and transparency
- Gradient backgrounds and smooth animations
- FreeCodeCamp-inspired clean aesthetic
- Responsive design for all devices
- Dark/light theme compatibility

### 📱 **Mobile-Optimized**
- Fully responsive layout
- Touch-friendly interface
- Collapsible sidebar for mobile devices
- Optimized for both portrait and landscape orientations

## 🔧 Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with gradients, animations, and glassmorphism
- **Vanilla JavaScript** - No frameworks, pure JS functionality
- **Responsive Design** - Mobile-first approach
- **Local Storage** - Data persistence (can be easily implemented)

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installations required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/taskflow-todo-app.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd taskflow-todo-app
   ```

3. **Open the application**
   ```bash
   # Simply open index.html in your browser
   open index.html
   # Or use a local server
   python -m http.server 8000
   ```

4. **Start using TaskFlow!**
   - Open your browser and navigate to the file or `http://localhost:8000`

## 📖 How to Use

### Creating Your First List
1. Click the **"✨ Create New List"** button
2. Enter a descriptive title for your list
3. Set the timer duration (in minutes)
4. Click **"Create List"** to start

### Managing Tasks
- **Add Task**: Type in the task field and press `Enter` or click "Add Task"
- **Complete Task**: Click the circular checkbox next to any task
- **Delete Task**: Hover over a task and click the red "Delete" button
- **View Progress**: Check the sidebar for completion status (e.g., "3/7 completed")

### Using the Timer
- **Start Timer**: Click "Start" to begin your focused work session
- **Pause Timer**: Click "Pause" to temporarily stop the timer
- **Reset Timer**: Click "Reset" to return to the original duration
- **Warning System**: Get notified when only 3 minutes remain!

## 🎯 Key Features Showcase

### Smart Notifications
```javascript
// 3-minute warning system
function checkTimeWarning() {
    const remainingTime = timerDuration - currentTime;
    if (remainingTime <= 180 && !notificationShown) {
        showNotification();
        notificationShown = true;
    }
}
```

### Progress Tracking
- Real-time completion percentages
- Visual progress bars with smooth animations
- Task counters (completed/total)

### Responsive Design
- Mobile-first approach
- Flexible grid system
- Touch-optimized controls

## 🎨 Design Philosophy

TaskFlow follows modern web design principles:

- **Minimalism**: Clean, uncluttered interface
- **Accessibility**: High contrast ratios and semantic HTML
- **Performance**: Lightweight, fast-loading application
- **User Experience**: Intuitive navigation and feedback
- **Visual Hierarchy**: Clear typography and spacing

## 🔮 Future Enhancements

- [ ] **Data Persistence**: Local storage implementation
- [ ] **Categories/Tags**: Organize tasks with labels
- [ ] **Dark/Light Theme**: Toggle between themes
- [ ] **Export/Import**: Backup and restore functionality
- [ ] **Collaboration**: Share lists with team members
- [ ] **Analytics**: Track productivity metrics
- [ ] **Notifications**: Desktop and push notifications
- [ ] **Calendar Integration**: Due dates and scheduling

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style and conventions
- Write descriptive commit messages
- Test thoroughly across different browsers
- Update documentation as needed

## 📁 Project Structure

```
taskflow-todo-app/
├── index.html              # Main HTML file
├── README.md              # Project documentation
├── assets/                # Images and media files
│   └── screenshots/       # App screenshots
├── css/                   # Stylesheets (if separated)
├── js/                    # JavaScript files (if separated)
└── docs/                  # Additional documentation
```

## 📱 Browser Support

| Browser | Version |
|---------|---------|
| Chrome  | 60+ ✅  |
| Firefox | 55+ ✅  |
| Safari  | 11+ ✅  |
| Edge    | 79+ ✅  |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

## 🙏 Acknowledgments

- **FreeCodeCamp** - Design inspiration
- **Glassmorphism.com** - UI design trends
- **Google Fonts** - Typography
- **CSS Gradient Generator** - Beautiful gradients

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/taskflow-todo-app?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/taskflow-todo-app?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/taskflow-todo-app)
![GitHub license](https://img.shields.io/github/license/yourusername/taskflow-todo-app)

---

<div align="center">
  <h3>🌟 If you found this project helpful, please give it a star! 🌟</h3>
  <p>Made with ❤️ and lots of ☕</p>
</div>