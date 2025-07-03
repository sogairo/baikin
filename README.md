# baikin

rune slayer gold ore macro lol

## Table of Contents

- [Setup](#setup)

## Setup

### 1. Install Python

  1. Go to the official Python site:  
     ➡️ [https://www.python.org/downloads/](https://www.python.org/downloads/)
  2. Download the latest version.
  3. **IMPORTANT:** On the first screen of the installer, check the box that says  
     ✅ **“Add Python to PATH”** — then click **Install Now**.


### 2. Install Tesseract OCR

  Tesseract is the program this script uses to read text from the screen.

  1. Download the Windows installer from this link:  
     ➡️ [https://github.com/UB-Mannheim/tesseract/wiki](https://github.com/UB-Mannheim/tesseract/wiki)
  2. Scroll down to **“Tesseract at UB Mannheim”**, and download the `.exe` file under “Latest installer”.
  3. Install it to the default location:  
     `C:\Program Files\Tesseract-OCR`


### 3. Add Tesseract to System PATH

  This lets your computer find `tesseract.exe` when the script runs.


#### 💻 How to do it:

  1. Press `Win + S`, search **“Environment Variables”**, and open  
   **“Edit the system environment variables”**.
  2. In the window that pops up, click **Environment Variables...** at the bottom.
  3. Under the **System variables** section, find and click on `Path`, then hit **Edit**.
  4. Click **New**, then paste this:
  5. Click OK on all windows to save and close.

### 4. Install Required Python Modules

  Open your terminal (Command Prompt or VS Code terminal), then run:

  ```bash
  pip install opencv-python pytesseract pyautogui pygetwindow keyboard pillow numpy
  ```
  If you get an error about pip, try this instead:
  ```
  python -m pip install opencv-python pytesseract pyautogui pygetwindow keyboard pillow numpy
  ```

(This is literally all gpted)
