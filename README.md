**Digital Clock App**

A lightweight and visually appealing **digital clock GUI** built using Python’s `tkinter` library. The clock updates every second and displays the current time and date in real-time.

---

**Features**

- Real-time hour, minute, second display  
- Current date in `MM/DD/YY` format  
- Clean GUI with custom font, colors, and alignment  
- Auto-refresh every second using `after()`

---

**Tech Stack**

- **Language:** Python 3  
- **GUI Toolkit:** `tkinter`  
- **Time Handling:** `time.strftime()`

---

**Getting Started**

**Prerequisites**

Make sure Python 3 is installed on your system:

```bash
python --version
```

**Run the Application**

Clone this repository and run the script:
```
git clone https://github.com/yourusername/digital-clock-app.git
cd digital-clock-app
python digital_clock.py
```

![image](https://github.com/user-attachments/assets/7d988ef0-10e2-4f9b-9c96-2470fb8becbe)

**How It Works**

- A GUI window is created using tk.Tk()
- A label widget is updated every 1000 milliseconds using after()
- The strftime() function displays time in HH:MM:SS AM/PM format and date as MM/DD/YY

**TODO / Improvements**

- Add support for multiple time zones
- Add background image or theme switcher
- Add stopwatch or timer mode
- Allow window resizing or full-screen toggle

**Contributing**

Contributions are welcome. Feel free to fork the repo and submit a pull request. Suggestions for new features are encouraged.
