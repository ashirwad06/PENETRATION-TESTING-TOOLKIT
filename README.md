# PENETRATION-TESTING-TOOLKIT
This is a complete penetration testing toolkit built in Python with a user-friendly GUI. 



# 🛡️ Penetration Testing Toolkit (GUI-Based)

This is a complete penetration testing toolkit built in Python with a user-friendly GUI. It allows ethical hackers and cybersecurity enthusiasts to:

- Perform WHOIS lookups
- Scan open ports
- Grab banners from services
- Lookup DNS records
- Find IP geolocation
- Perform basic brute force attempts

All tasks are handled through a simple GUI using Tkinter.


##  Features

* GUI input via Tkinter  
* All functionalities combined into a single file  
* Easily converted into a `.exe` for Windows systems  
* Clean and beginner-friendly code


## 🖥️ How to Run

###  Run from Python Script (`main.py`)

**Requirements:**

- Python 3.8 or higher installed
- Internet connection

**Steps:**

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/penetration-toolkit.git
   cd penetration-toolkit


2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the toolkit:

   ```bash
   python main.py
   ```



### 🧩 Run the `.exe` (Executable for Windows)
If you have downloaded or built the `.exe` file:

1. Go to the `/dist` folder where the `.exe` is located.
2. Double-click `main.exe` to run the GUI.
3. No need to install Python or any libraries.

> ⚠️ If Windows flags it, click **"More info → Run anyway"**.
## Go To Release Section 

##  Tools Used

* Python
* Tkinter (GUI)
* `whois`, `dnspython`, `requests`
* `PyInstaller` for packaging


##  Installation & Build

### To Create `.exe`:

Install PyInstaller:

```bash
pip install pyinstaller
```

Then package the project:

```bash
pyinstaller --onefile --noconsole main.py
```

The `.exe` will appear in the `dist/` folder.


## 📂 Project Structure

```
Penetration-Toolkit/
│
├── main.py                 ← Complete all-in-one Python script
├── README.md               ← This file
├── .gitignore              ← Ignore compiled, temp, and dist files
├── dist/                   ← Contains compiled .exe (after PyInstaller)
```


## License

MIT License – Free to use, modify, and distribute with attribution.


## Author
**Ashirwad Shukla**
Cybersecurity Enthusiast



