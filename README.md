Daily Work Activity Tracker
A simple, private, and intuitive web-based tool to log and organize your daily work activities. Track tasks hour by hour, manage pending items, utilize recurring templates, and secure your data with a local PIN/password, all within your browser.

✨ Features
Hourly Activity Logging: Log tasks and their statuses for each hour of your workday.
Customizable Work Hours: Adjust your daily work start and end times in the settings.
Daily & Weekly Summaries: Get a quick overview of your activities and status distribution for the selected day and week.
Global Pending Tasks: Keep an eye on uncompleted tasks from previous days, with visual cues for aging tasks.
Dismissed Tasks List: Manage and un-dismiss tasks you've previously chosen to hide from the pending list.
Recurring Tasks / Templates: Define reusable activity templates with daily or weekly recurrence, which can be automatically added to your log.
Local User Profiles with PIN/Password Protection:
Secure your data locally with a username and optional PIN/password.
Switch between multiple local users on the same browser, each with their own private data.
Reset your password if needed.
Autosave: All your data (activities, settings, templates, user credentials) is automatically saved every 5 minutes and upon closing the browser tab.
Data Export: Export your entire activity log as a JSON file for backup or external analysis.
12-Hour (AM/PM) Time Display: All hourly slots and time references are shown in an easy-to-read 12-hour format.
Modern & Responsive UI: Clean, intuitive design built with native browser features (CSS variables, Flexbox), adapting well to different screen sizes.
🚀 How to Use
This is a standalone HTML file. No installation, internet connection (after initial download), or complex setup is required.

Download the File:

Right-click on the index.html file (or the link to it if shared via cloud storage).
Select "Save link as..." or "Save page as..."
Save the file to a location on your computer (e.g., your Desktop or a dedicated "Apps" folder).
Open the Application:

Navigate to where you saved the index.html file.
Double-click the index.html file. It will open automatically in your default web browser (Chrome, Firefox, Edge, Safari, etc.).
Login / Create Profile:

On first launch, you'll be prompted to enter a username.
If it's a new username, you'll be asked to set a password/PIN (minimum 4 characters) or leave it blank for no password.
If it's an existing username with a password, you'll need to enter the correct password to log in.
Start Tracking!

Select a Date: Use the date picker to choose the day you want to log activities for.
Add Activities: In each hourly slot, type in your activity description, select its status, and add optional notes.
"Add Activity" Button: Use the green "Add Activity" button at the bottom of each hour to add new tasks.
"Carry Over" Tasks: Utilize the "Carry Over" button on pending tasks to quickly add them to the current day's log.
Settings: Explore the "Work Hours" to customize your daily schedule and the "Data Management" section for export and password reset options.
🔒 Security & Data Privacy
Your data is stored locally in your browser's Local Storage. This means:

Private to Your Device: Your activities are only accessible on the computer and browser where you use the application. No data is sent to any external server.
No Central Server: This application does not connect to any online database or cloud service.
PIN/Password as a Deterrent: The implemented PIN/password system provides a barrier against casual access to your data on the same computer. However, as it's a client-side solution, it's not designed to withstand sophisticated hacking attempts. Do not use highly sensitive passwords or confidential information if you have concerns about advanced security.
🛠️ Development & Contribution
This project is a single HTML file containing all HTML, CSS, and JavaScript.

Structure: All code is self-contained within index.html.
Data Persistence: Utilizes localStorage for all data storage.
Hashing: Employs the browser's native Web Crypto API (SHA-256) for password hashing.
UI: Built with modern CSS (variables, Flexbox) for a responsive and clean design.
Feel free to inspect the code, modify it, or extend its functionality!
