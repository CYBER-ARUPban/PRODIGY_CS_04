Keylogger (Educational Use Only)
This is a basic Python keylogger designed for educational and testing purposes. It captures and logs keyboard input, writing the output to a local file.

Features:- 
Logs each keystroke with a timestamp

Recognizes and labels special keys (Enter, Space, Backspace, etc.)

Writes logs in batches for better performance

Clean, readable output format

Stops safely with the ESC key

Requirements:- Python 3.x & pynput library

How It Works
The keylogger listens to keyboard events in the background. When a key is pressed, it's recorded in memory. After a small number of keystrokes, the log is written to a file (key_log.txt). Pressing the ESC key will stop the program and save any remaining keystrokes.

Usage
Run the script in your terminal or editor.

Type as usual — everything is recorded.

Press ESC to stop logging.

Open key_log.txt to view the results.

Important Notes
Use this program only on machines you own or have permission to monitor.

Unauthorized use of keyloggers is illegal and unethical.

This tool is intended solely for learning, debugging, or local monitoring with consent.

