# ✨ Meditator's Journal

**Meditator's Journal** is an application designed to support both spiritual practice and daily work. The app helps practitioners track progress in their professional tasks as well as meditation sessions, recording levels of awareness through "Mindfulness" counts, and visualizing mental states via real-time charts and graphs.

<img width="499" height="344" alt="image" src="https://github.com/user-attachments/assets/05414d1d-f9cf-4e29-8b38-4600df2940da" />


## ✨ Core Concepts

To use the app effectively, you should understand the following indicators:

* **Mindfulness (Sati):** A unit for measuring awareness. Every time you recognize your breath or mental state and touch the screen, one "Mindfulness" point is recorded.
* **Mindful State:** A state where the frequency of recording (Sati) remains stable and regular.
* **Unmindful:** A state where the mind is distracted or drowsy, resulting in few or no recordings over a period of time.
* **Diligence Streak:** The number of consecutive days you have maintained your practice.

## ✨ Key Features

### 1. Diverse Goal Management

* **Two main types of goals:**
* **ॐ Meditation:** Tracks meditation duration and counts mindfulness ("Sati") recognitions. The interface features a breathing circle to support focus.
* **⚡ Work (Standard):** A traditional countdown timer used for work, study (similar to Pomodoro), or other habits.


* **Customization:** Set daily goals (minutes), target completion time, representative colors, and management categories.

#### 2. Interaction Settings & Pro Mode (New)

In the meditation interface, click the ⚙️ button to open interaction settings. The system supports haptic feedback (vibration) & 4 recording modes:

* **Tap:** Basic mode. Lightly tap the screen to count. You can set it to require 1, 2, 3, or 4 taps to register as 1 mindfulness count (helps filter accidental touches).
* **Hold:** Press and hold the screen for a set duration (default 0.4s) to record. Helps keep the mind grounded and steady.
* **✨ Auto:** Automatically detects both Tap and Hold gestures.
* **💎 Pro Mode (Grading):** Assess the focus quality at the moment of noting. The system saves a "quality score" based on your hand gesture:
>* ● Hold: **High**
>* ● 1 Tap: **Low**
>* ● 2 Taps: **Medium**
>* ● Hold: **Good**
>* ● 10+ Good*: **High**
* **10+ Good:** *Focus at 'Good' level for 10 consecutive times or more; each consecutive subsequent will be counted as 'High' level.*
* **Note:** *Haptic feedback requires a device that supports vibration mode.*

<img width="345" height="450" alt="2en" src="https://github.com/user-attachments/assets/d30c6ed0-27d7-4a05-a579-e4732b79f0b1" />

* **Manual Entry:** Forgot to start the timer? You can manually log a session or edit previous records.

### 3. Statistics & Data Analysis

* **Dashboard:** View today's progress relative to your set goals.
* **Practice Calendar:** A grid heatmap showing daily practice intensity. More colors represent longer practice durations.
* **Visual Charts:**
* **Session Graph:** Review mindfulness levels *within a specific session* (line chart).
* **Weekly/Monthly Statistics:** Compare performance over real-time intervals.
* **💎 Pro Chart:** The "Advanced" tab displays the distribution of focus quality (High/Low) over weeks.

### 4. Meditation Analytics

The **"Analytics"** tab helps you reflect on the quality of your mind during meditation sessions with higher precision.

* **Goal-specific analysis:** You can view data for specific goals (e.g., "Sitting Meditation" or "Walking Meditation") to compare the progress of different practices.
* **Distraction Threshold:**
This is the most important concept for calculating your "Meditation Quality."
> *"Distraction Threshold" is the maximum allowed gap between two mindfulness logs; if this time is exceeded, the system considers you were distracted.*


* **How it works:** For example, if you set the threshold to **12 seconds**:
* If you tap after **5 seconds**: The entire duration is counted as Mindful.
* If you tap after **20 seconds**: The system calculates that you were distracted or drowsy for **8 seconds** (20 - 12 = 8).


* **Individual Customization:** Different practices require different paces. You can set a low threshold (e.g., 5s) for fast-noting exercises, or a higher threshold (e.g., 30s) for deep concentration. The system remembers these settings for each goal individually.

### 5. Privacy & Data Security

* **Fully Offline:** 100% of data is stored directly in your browser. No data is sent to any server.
* **Backup & Restore:** Easily export data to a `.json` file for safekeeping or to transfer to another device.

---

## 🚀 Usage Guide

### Basic Steps

#### 1. Create a New Goal

* Click the **"New Goal"** button on the main screen.
* Select the type: **Meditation** or **Work**.
* Enter a name, choose a color, and set the goal time (e.g., 30 mins/day) and the total time required to finish the goal.

#### 2. Start a Session

* On the goal card, click the **Play (▶)** button (for Work) or the **ॐ** button (for Meditation).
* **During Meditation:** Tap the screen whenever you find yourself mindfully returning to the meditation object.
* At the end of the session, a summary panel will appear for you to add journal notes.

#### 3. View Statistics

* Select the **"Statistics"** tab on the sidebar to view charts.
* Select the **"Calendar"** tab to see your history. Click on a specific date to see details of sessions for that day.

---

## ✨ Practice Achievement System

The app recognizes your diligence through the following milestones:

### Consistency Milestones (Streak)

| Title | Condition | Meaning |
| --- | --- | --- |
| **Effort** | 3 consecutive days | Initially overcoming inertia. |
| **Striving** | 10 consecutive days | Starting to form a habit. |
| **Diligence** | 30 consecutive days | Habit is becoming stable. |
| **Ardor** | 60 consecutive days | Practice becomes firm and steady. |
| **Viriya-sambojjhanga** | 365 consecutive days | Extraordinary perseverance for one year. |

### Mindfulness Milestones

| Level | Mindfulness Points (Sati) |
| --- | --- |
| **Beginner** | 5,000 |
| **Practitioner** | 10,000 |
| **Yogi** | 20,000 |
| **Meditator** | 50,000 |
| **Clear Mirror** | 80,000 |
| **Still Lake** | 100,000 |
| **Mountain** | 200,000 |
| **Heir of the Dhamma** | 500,000 |

---

## ⚠️ Important Data Notice

Your data is stored in the browser's **IndexedDB** (Secure & Large capacity).

1. **Do not clear browser history/cache** without backing up, or your data will be lost.
2. **How to Backup:** Go to the left sidebar, select **"Backup"** to download the file to your computer/phone.
3. **How to Restore:** Select **"Restore"** and choose the previously downloaded backup file.
4. If an error occurs, use the copy/paste data option.

---

## 💡 Technologies Used

* **Core:** HTML5, CSS3, JavaScript (ES6+).
* **Storage:** IndexedDB API.
* **Third-party Libraries (via CDN):**
* [Chart.js](https://www.chartjs.org/) - For data visualization.
* [FontAwesome](https://fontawesome.com/) - Interface icons.



---

## 📄 Copyright

This project is open-source. You are free to modify and personalize it to suit your own practice and work needs. Wishing you peace and diligence!
