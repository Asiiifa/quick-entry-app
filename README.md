# 📝 QuickEntry App

QuickEntry is a simple and modern visitor logging system built using Python and Tkinter. Designed to replace manual registers with a clean and intuitive GUI, this app helps log Name, Date, Time In, Time Out, and Reason of visitors.

## Features

- 🕒 Auto-fills current Date and Time In on startup.
- ⏳ Time Out auto-fills when the visitor submits the entry.
- 🧾 Search functionality to filter logs by keyword.
- 📤 Export logs to CSV (Excel-compatible).
- 🔐 Admin options: Login & change password.
- 🎨 Clean UI with splash screen and centered layout.
- 📅 Calendar date picker integration.
- 🔍 Search icon-based navigation.
- ✨ Modern font and styling.

## Tech Stack

- Python 3.10+
- Tkinter (GUI)
- tkcalendar (for Date Picker)
- Pillow (for image/logo handling)
- CSV for data storage

## Installation

1. **Clone this repository**

```bash
git clone https://github.com/your-username/quickentry.git
cd quickentry
```

2. **Install required packages**

```bash
pip install tkcalendar Pillow
```

3. **Run the app**

```bash
python main.py
```

## Executable (.exe) Build

If you'd like to share this as a standalone `.exe` file (no Python install needed):

```bash
pip install pyinstaller
pyinstaller --onefile --windowed main.py
```

The `.exe` will be inside the `dist/` folder.

## Screenshot

![Screenshot](screenshot.png)

## Usage

1. Open the app — you'll see a splash screen.
2. On the main screen, enter visitor details.
3. Click **Submit** to save the entry. Time Out is auto-filled.
4. Use the 🔍 **search icon** to look up entries.
5. Click **Export to Excel** to download logs.

## Admin Features

- Three-dot menu (⋮) > **Admin Login**
- Default Password: `admin123`
- Option to change the password.

## Upcoming Enhancements

- 🌙 Dark Mode toggle in settings
- 🖨️ PDF export support
- 🎞️ Animated transitions between screens

## Author
Asifa Hamid Khan    
🔗 GitHub: [github.com/asiiifa](https://github.com/asiiifa)
