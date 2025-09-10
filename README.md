TaskFlow - Advanced To-Do App
Overview
TaskFlow is a modern, feature-rich to-do list application built with HTML, CSS, and JavaScript. It provides an intuitive interface for managing tasks and lists, complete with a timer feature to enhance productivity. The application is designed with a sleek, responsive UI and includes advanced features like notifications, modals, and sound alerts.
Features

Task Management: Create, edit, complete, and delete tasks within multiple to-do lists.
Timer Functionality: Set timers for each list to track work sessions, with automatic notifications for time warnings.
Responsive Sidebar: Toggleable sidebar that fully collapses to maximize workspace.
Notifications: Auto-dismissing notifications for time warnings (3 minutes and 5% time remaining) with sound alerts.
Modals:
New list creation modal.
Time-up modal displaying session duration and task completion stats.
Confirmation modal for list deletion to prevent accidental data loss.


Progress Tracking: Visual progress bars for task completion in each list.
Responsive Design: Optimized for both desktop and mobile devices with adaptive layouts.
Keyboard Shortcuts: Press Enter to quickly add tasks or create new lists.
Visual Feedback: Smooth animations and hover effects for an engaging user experience.

Installation

Clone or Download: Download the project files or clone the repository to your local machine.
Open index.html: Place the index.html file in a web server directory or open it directly in a modern web browser (e.g., Chrome, Firefox, Edge).
Dependencies: No external dependencies are required; the app uses vanilla JavaScript and embedded audio files for notifications.

Usage

Create a List:

Click the "Create New List" button in the sidebar.
Enter a list title and optional timer duration (in minutes) in the modal.
Press "Create List" or hit Enter to add the list.


Manage Tasks:

Select a list from the sidebar to view its tasks.
Add tasks using the input field and "Add Task" button or Enter key.
Check tasks to mark them as completed or click "Delete" to remove them.


Timer Controls:

Start, pause, or reset the timer using the buttons in the list header.
Receive notifications when 3 minutes or 5% of the time remains.
A modal appears when the timer ends, showing session duration and completed tasks.


Delete Lists:

Click the "×" button on a list in the sidebar to open a confirmation modal.
Confirm or cancel the deletion.


Toggle Sidebar:

Use the ☰ button to show/hide the sidebar, which collapses fully when hidden.



File Structure

index.html: The main application file containing HTML, CSS, and JavaScript.
Embedded audio files (base64-encoded WAV) for warning and urgent notifications.

Technical Details

Frontend: Built with HTML5, CSS3, and vanilla JavaScript.
Styling: Uses CSS Flexbox for layout, CSS animations for transitions, and a gradient-based theme.
Audio: Utilizes Web Audio API for notification sounds with fallback to embedded WAV files.
Storage: Currently uses in-memory storage (data is not persisted across sessions). Future enhancements could include localStorage or a backend database.
Responsive Design: Media queries ensure compatibility with mobile devices (below 768px).

Limitations

Data Persistence: Task and list data are not saved between sessions. Consider adding localStorage or a backend for persistence.
Browser Compatibility: Tested on modern browsers; older browsers may not support all features (e.g., Web Audio API).
Timer Accuracy: Relies on JavaScript's setInterval, which may have minor drift over long periods.

Future Enhancements

Add localStorage or backend integration for persistent data storage.
Implement task prioritization and categories.
Add user authentication for personalized task lists.
Enhance accessibility with ARIA attributes and keyboard navigation.
Include task due dates and reminders.

Contributing
Contributions are welcome! Please fork the repository, make changes, and submit a pull request with a clear description of your improvements.
