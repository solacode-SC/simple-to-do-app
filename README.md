# TaskFlow - Advanced To-Do App

**Created by:** solacode-sc

A modern, feature-rich task management application with built-in timers, persistent data storage, and beautiful UI design. TaskFlow helps you organize your tasks efficiently while keeping track of time with both list-specific timers and a standalone timer feature.

## ✨ Features

### 🗂️ **Task Management**
- Create multiple to-do lists with custom titles
- Add, edit, and delete tasks within each list
- Mark tasks as complete with smooth animations
- Visual progress tracking with progress bars
- Task completion statistics for each list

### ⏰ **Advanced Timer System**
- **List Timers**: Set custom timer durations for each to-do list
- **Simple Timer**: Standalone timer for general use (Pomodoro technique, etc.)
- Start, pause, and reset functionality
- Real-time countdown display
- Timer state preservation across page refreshes

### 🔔 **Smart Notifications**
- 3-minute warning when time is running low
- 5% remaining time urgent alert (auto-disappears after 5 seconds)
- Visual and audio alarm when timer reaches zero
- Different notification styles for regular and urgent alerts

### 💾 **Persistent Data Storage**
- Automatic localStorage integration
- All data persists through browser refreshes
- Real-time synchronization across multiple browser tabs
- Error handling with user feedback
- Auto-save every 30 seconds while timer is running

### 🎨 **Modern UI/UX**
- Beautiful gradient backgrounds and glassmorphism effects
- Smooth animations and hover effects
- Responsive design for desktop and mobile
- Collapsible sidebar for better screen utilization
- Dark theme with vibrant accent colors

### 🔊 **Audio Feedback**
- Custom alarm sound generation using Web Audio API
- Repeating alarm until manually stopped
- No external audio files required

## 🚀 Quick Start

1. **Clone or Download**: Get the project files to your local machine
2. **Open**: Launch `index.html` in any modern web browser
3. **Start**: Create your first to-do list or use the simple timer
4. **Enjoy**: Your data automatically saves as you work!

## 📋 How to Use

### Creating To-Do Lists
1. Click "✨ Create New List" in the sidebar
2. Enter a list title and timer duration (in minutes)
3. Click "Create List" to save

### Managing Tasks
1. Select a list from the sidebar
2. Type your task in the input field and press Enter or click "Add Task"
3. Click the circle next to a task to mark it complete
4. Use the "Delete" button to remove tasks

### Using Timers
**List Timer:**
- Each list has its own timer based on the duration you set
- Use Start/Pause/Reset buttons in the main content area
- Timer automatically stops when it reaches zero

**Simple Timer:**
- Click "⏰ Simple Timer" in the sidebar
- Set your desired minutes and click Start
- Perfect for Pomodoro sessions or general timing needs

### Managing Lists
- Click on any list in the sidebar to switch to it
- Hover over a list and click "Delete" to remove it
- Lists show progress (completed/total tasks) and remaining time

## ⚡ Technical Features

### Browser Compatibility
- Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- Uses standard HTML5, CSS3, and vanilla JavaScript
- No external dependencies or frameworks required

### Data Persistence
- Uses localStorage for client-side data storage
- Handles storage errors gracefully
- Automatic data validation and repair
- Cross-tab synchronization

### Performance
- Lightweight single-file application
- Efficient DOM manipulation
- Smooth 60fps animations
- Minimal memory footprint

### Responsive Design
- Mobile-first approach
- Adaptive layouts for different screen sizes
- Touch-friendly interface elements
- Optimized for both desktop and mobile use

## 🛠️ Customization

The application is built with customization in mind:

### Timer Durations
- List timers: 1 minute to 8 hours
- Simple timer: 1 minute to 8 hours
- Default simple timer: 25 minutes (Pomodoro)

### Notification Timing
- 3-minute warning for all timers
- 5% remaining time urgent alert
- Auto-disappearing notifications after 5 seconds

### Visual Themes
- Easily customizable CSS variables
- Gradient backgrounds and glassmorphism effects
- Smooth animations and transitions

## 📁 File Structure

```
TaskFlow/
├── index.html          # Main application file (HTML, CSS, JS)
├── README.md           # This file
└── ...                 # Any additional assets
```

## 🔧 Technical Implementation

### Core Technologies
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with flexbox, gradients, and animations
- **Vanilla JavaScript**: No frameworks, pure ES6+ code
- **Web Audio API**: Custom alarm sound generation
- **LocalStorage API**: Persistent data storage

### Key JavaScript Features
- ES6+ modern syntax (arrow functions, destructuring, etc.)
- Async/await for better code readability
- Custom event handling and DOM manipulation
- Efficient timer management with setInterval
- Error handling and user feedback systems

### CSS Features
- CSS Grid and Flexbox layouts
- Custom CSS animations and keyframes
- Responsive design with media queries
- CSS backdrop-filter for glassmorphism effects
- Smooth transitions and hover effects

## 📱 Mobile Support

TaskFlow is fully responsive and optimized for mobile devices:
- Touch-friendly buttons and interactions
- Adaptive sidebar that can be hidden on mobile
- Optimized font sizes and spacing
- Gesture-friendly interface elements

## 🔒 Privacy & Security

- All data stored locally in your browser
- No external servers or data transmission
- No tracking or analytics
- Complete privacy and offline functionality

## 🐛 Troubleshooting

### Common Issues

**Data not saving:**
- Ensure your browser supports localStorage
- Check if you're in private/incognito mode (localStorage may be disabled)
- Clear browser cache if experiencing issues

**Timer not working:**
- Refresh the page and try again
- Ensure JavaScript is enabled in your browser
- Check browser console for any error messages

**Audio not playing:**
- Some browsers require user interaction before playing audio
- Check browser audio permissions and settings
- Audio uses Web Audio API (supported in all modern browsers)

## 🔄 Updates & Changelog

### Current Version: 1.0.0
- Initial release with full feature set
- Persistent localStorage integration
- Simple timer functionality
- Smart notification system
- Mobile-responsive design

## 💡 Tips & Best Practices

1. **Pomodoro Technique**: Use the 25-minute simple timer for focused work sessions
2. **Task Batching**: Group similar tasks in the same list with appropriate time limits
3. **Regular Breaks**: Use the timer alerts as reminders to take breaks
4. **Mobile Use**: Hide the sidebar on mobile for more screen space
5. **Data Backup**: Consider occasionally exporting your tasks (feature coming soon)

## 🤝 Contributing

This is an open-source project created by solacode-sc. Feel free to:
- Report bugs or suggest improvements
- Submit pull requests with enhancements
- Share your customizations and modifications
- Use it as a learning resource for web development

## 📄 License

This project is open source and available under standard web development practices. Feel free to use, modify, and distribute as needed.

---

**Created with ❤️ by solacode-sc**

*TaskFlow - Where productivity meets simplicity*