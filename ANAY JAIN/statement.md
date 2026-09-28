# 5.2 Project Statement

## Problem Statement

Many basic clock applications only display the current time and do not provide a simple, easy-to-use way to set an alarm. Users need an application that can continuously display the current time and date, allow them to set an exact alarm time, validate the entered values, and notify them when the selected time is reached.

The **Digital Alarm Clock** project addresses this problem by providing a lightweight Python desktop application with a graphical user interface. It displays the current time and date in real time and allows the user to set or cancel an alarm using the HH:MM:SS format. When the selected time is reached, the application provides both visual and audible notifications.

## Scope of the Project

The project focuses on developing a simple desktop-based digital clock and alarm application using Python and Tkinter. The current scope includes:

- Real-time display of the current time in HH:MM:SS format.
- Display of the current day, date, month, and year.
- Setting a single active alarm.
- Validation of hour, minute, and second inputs.
- Setting and cancelling an alarm.
- Visual warning when the alarm is triggered.
- Audible alarm notification.
- Maintaining a responsive graphical interface during alarm playback.

Features such as snooze, multiple alarms, custom alarm sounds, persistent alarm storage, and advanced system notifications are outside the current scope and may be considered for future development.

## Target Users

The application is designed for:

- **Students** who need a simple alarm for study sessions, classes, or daily activities.
- **General computer users** who require a basic desktop clock with alarm functionality.
- **Beginners learning Python GUI development** who can use the project to understand event-driven programming, input validation, callbacks, and threading.
- **Users who prefer a simple desktop-based clock** without unnecessary features.

## High-Level Features

The major features of the Digital Alarm Clock are:

1. **Real-Time Digital Clock** – Continuously displays the current time and updates every second.
2. **Date Display** – Shows the current day, month, date, and year.
3. **Alarm Setting** – Allows users to enter an alarm time in HH:MM:SS format.
4. **Input Validation** – Checks that the entered hour, minute, and second values are within valid ranges.
5. **Set Alarm** – Activates and stores the selected alarm time.
6. **Cancel Alarm** – Allows users to disable and clear the active alarm.
7. **Alarm Notification** – Provides a visual warning when the alarm time is reached.
8. **Audible Alert** – Plays a system beep when the alarm is triggered.
9. **Alarm Status Display** – Shows whether an alarm is set, cancelled, or triggered.
10. **Responsive GUI** – Uses scheduled updates and a separate thread for sound playback to keep the interface responsive.
