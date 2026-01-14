# Pomodoro Timer (Tkinter)

A Pomodoro Timer built with Python and Tkinter to help improve focus and productivity.

## Features
- 25-minute work sessions
- 5-minute short breaks
- 20-minute long break after every 4 work sessions
- Visual checkmarks to track completed work sessions
- Clean and minimal GUI

## Technical Skills
- **Python Programming** – fundamental syntax, functions, variables, loops
- **Tkinter GUI Development** – labels, buttons, canvas, images, layouts
- **Event-driven programming** – using `after()` for timed events
- **State management** – tracking sessions and timer progress
- **Time calculations** – converting seconds to minutes and seconds

## Screenshot
![Pomodoro Screenshot](pomodoro-timer-preview.jpg)

## How It Works
- Click **Start** to begin the Pomodoro cycle
- The timer automatically switches between work and break sessions
- Each completed work session adds a ✓ checkmark
- Click **Reset** to stop the timer and clear progress

## Requirements
- Python 3.x
- Tkinter (included with standard Python installs)

## How to Run
1. Install **Python 3.x**
2. Clone this repository:
```bash
git clone https://github.com/MichelleRunning/pomodoro-timer.git
```
3. Navigate to the project folder:
```bash
cd pomodoro-timer
```
4. Make sure tomato.png is in the same folder as main.py.
5. Run the program:
```bash
python main.py
```
6. The GUI window will open. Click Start to begin the timer and Reset to reset progress.
