# Pomodoro Timer

A simple desktop Pomodoro timer built with Python and Tkinter. It alternates focused work sessions with short breaks and takes a longer break after four work sessions. The timer and session progress are displayed in a small graphical interface.

## Timer schedule

- Work: 25 minutes
- Short break: 5 minutes
- Long break: 20 minutes, after four work sessions

When a session finishes, the next session starts automatically. Select **Reset** to stop the current countdown and return the display and progress to the beginning.

## Requirements

- Python 3
- Tkinter (usually included with Python; on some Linux distributions it may need to be installed separately)

## Run

Open a terminal in this project directory and run:

```bash
python3 main.py
```

Keep `tomato.png` in the project directory alongside `main.py`; the app loads the image using a relative path.
