# Push-messages_deadlines

## Description
**Push-messages_deadlines** is a background desktop application developed with C# and WinForms that allows users to manage and be reminded of important deadlines. The program minimizes to the background and can be toggled with a custom hotkey (`Alt + D`).

The main functionality revolves around scheduling custom deadline notifications, each of which is displayed as a system-style pop-up message with accompanying sound alerts. The reminders are non-intrusive but effective — appearing in a custom notification form that includes a close button for user dismissal.

All deadlines and reminder settings are stored persistently in an `DeadLineList.xml` file, ensuring that data is preserved between sessions.

## Features
- Background application with quick access via `Alt + D`.
- Simple and intuitive UI for adding/editing deadline entries.
- Adjustable reminder intensity (frequency/visibility).
- Custom-built message pop-up form styled like a native notification.
- Integrated audio alerts when a deadline reminder appears.
- XML-based storage of all deadlines (`DeadLineList.xml`).

## Technologies Used
- **Language:** C#
- **Framework:** WinForms
- **Data Storage:** XML

## How It Works
1. Launches in the background and can be opened/hidden with `Alt + D`.
2. Users add new deadlines via the interface.
3. Each deadline is stored in `DeadLineList.xml`.
4. At the appropriate time, a pop-up notification form appears with:
   - The deadline message
   - A close (X) button
   - An audio alert to get the user’s attention
5. Notifications will respect the user-defined intensity settings.

## Example Use Case
A student managing multiple coursework deadlines sets reminders:
- “Submit lab report” at 3pm, reminder intensity: High
- “Math test on Friday” reminder every 12 hours

Each will result in a clean notification form with sound, reducing the chance of missing it.

## Setup & Usage
1. Download the solution and open the `.sln` file in Visual Studio.
2. Build and run the application.
3. Press `Alt + D` to open the interface and start adding deadlines.

## Notes
- Runs silently in the background.
- Does not use external libraries — only WinForms and standard .NET features.

---
This tool is ideal for personal productivity, coursework tracking, or any recurring deadlines.

