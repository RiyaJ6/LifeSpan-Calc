<div align="center">
<img width="850" height="466" alt="image" src="https://github.com/user-attachments/assets/6e39bb3c-b1c7-48b2-b5f9-415db5a78875" />


<div align="center">

  # ⏳ LifeSpan-Calc

  ### **Stop counting years. Start counting seconds.**
  
  <p>
    <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" />
    <img src="https://img.shields.io/badge/Frontend-PyWebIO-orange?style=for-the-badge&logo=html5" />
    <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
    <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
  </p>

  <p>
    <a href="#-features">Features</a> •
    <a href="#-how-it-works">How It Works</a> •
    <a href="#-installation">Installation</a>
  </p>

</div>

---

## 🚀 Overview

**LifeSpan-Calc** is a sleek, web-based tool built entirely in Python (no HTML/CSS required!). It takes your Date of Birth and instantly calculates exactly how long you've been on this planet—down to the very second. 

Whether you're curious about your "Total Days" high score or just want to feel old by seeing your age in hours, this tool has the stats.

## ✨ Features

* **📅 Precise Date Picker:** Easy-to-use calendar input powered by PyWebIO.
* **⏱️ Granular Stats:** Calculates Years, Months, Days, Hours, Minutes, and Seconds.
* **📈 Total Days Counter:** See the raw number of days you've survived.
* **⚡ Instant Web UI:** Runs in the browser but written 100% in Python.

---

## 🧠 How It Works

Here is the logic behind the magic. The application follows a simple Input-Process-Output flow:

1.  **The Trigger:** The app launches a local web server and opens your default browser.
2.  **The Input:** A `pywebio.input.date` widget asks for your Birthday.
3.  **The Math:**
    * It captures `datetime.now()`.
    * It calculates the `delta` (difference) between *Now* and *Then*.
    * It accounts for leap years and varying month lengths to ensure accuracy.
4.  **The Display:** The results are formatted into a markdown table and pushed to the UI using `pywebio.output`.



---

## 🛠️ Installation

Get your life stats running in less than 2 minutes.

### 1. Clone the Repo
```bash
git clone [https://github.com/YOUR_USERNAME/LifeSpan-Calc.git](https://github.com/YOUR_USERNAME/LifeSpan-Calc.git)
cd lifespan-calc


### 2. Install Dependencies
You only need PyWebIO (and standard Python libs).
pip install pywebio

### 3. Run the App
python main.py
The app will automatically open in your browser at http://localhost:8080
```
## 📸 Preview
![ezgif com-animated-gif-maker](https://github.com/user-attachments/assets/1b3f7a62-5b2a-48c1-b47c-d98fb6b5bebe)

<div align="center"> <sub>Handy tool to know about your existence. Enjoy.</sub> </div>
