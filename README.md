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
* **⚡ Cultivation:** A traditional countdown timer used for work, study or other practice.


* **Customization:** Set daily goals, target completion time, representative colors, and management categories.

### 2. Interaction Settings

In the meditation interface, tap the **setting** button to open interaction settings. The app supports haptic feedback vibration and helps you record two mental states simultaneously with 4 levels of mindfulness intensity.

* **👆 Tap = Mindfulness (Keeping the mind on the Object):**
Lightly tap the screen to record focus on your meditation object. For example: one tap for each full breath (in & out) counts as one mindfulness.
> ***Combo Mechanism:*** Every session starts at **Low** intensity. For every 15 consecutive entries with a time gap ≤ *Distraction Threshold*, the mindfulness level increases by one tier **(Low → Medium → Good → High)**. Exceeding the threshold resets the combo to Low.
> 
> **Manual control:** Allows you to **actively categorize** your focus level based on specific hand gestures:
>* ● 1 Tap: **Low**
>* ● 2 Taps: **Medium**
>* ● 3 Taps: **Good**

* **👆⏳ Hold = Alertness (Recognizing mental states, Detecting distractions):**
Press and hold the screen to record Alertness. Alertness is when you **realize** your current state of mind (e.g., catching your mind wandering, having stray thoughts, or losing focus on the object). This is the moment of recognition and returning.
> ***Reminder Mode:*** If you continue to hold longer after registering alertness **(exceeding distraction threshold)**, the system will trigger **random vibrations** to help you stay awake. Since this is system-assisted support, awareness points will not be awarded for these instances.

#### 🔔 Guided Meditation Mode

*Acts like a gentle tap from a Zen master to awaken your mindfulness.*

* The system utilizes your custom **Vibration Interval** to maintain a steady guiding rhythm for the meditation session.
* Haptic signals (gentle and varied) are **randomized** in both intensity and timing (varying slightly around your chosen setting). This keeps the mind alert and prevents the formation of "autopilot" or unconscious reflexes.
* **Your task:** Every time you feel the vibration, use it as an anchor — check where your mind is, gently pull it back to the present, and register a mindfulness touch.
  
#### ✔️ Confirmation Mode

*Designed for users who may tap unconsciously.* When enabled, the first tap won't be recorded immediately. You must tap a second time (within 1-3 seconds) to confirm it as a conscious action.

* Only the timestamp of the **first** tap is recorded.
* Confirmation mode only applies when the mindfulness level is at **Low**.
* **Note:** *Haptic feedback requires a device that supports vibration mode.*

<img width="345" height="450" alt="2en" src="https://github.com/user-attachments/assets/d30c6ed0-27d7-4a05-a579-e4732b79f0b1" />

* **Manual Entry:** Forgot to start the timer? You can manually log a session or edit previous records.

### 3. Statistics & Data Analysis

* **Dashboard:** View today's progress relative to your set goals.
* **Practice Calendar:** A grid heatmap showing daily practice intensity. More colors represent longer practice durations.
* **Visual Charts:**
* **Session Graph:** Review mindfulness levels *within a specific session* (line chart).
* **Weekly/Monthly Statistics:** Compare performance over real-time intervals.
* **Focus Level Chart:** The "Exploration" tab displays the distribution of focus level (High/Low) over weeks.

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

## ✨ The Pāramī System (Achievements)

The achievements system is organized into Pāramīs (Perfection) to encourage your diligence. Here are some key milestones:

**Consistency Milestones:**

| Streak | Pāramī | Significance |
| --- | --- | --- |
| 3 Days | Walking Path | Stepping onto the path. |
| 7 Days | Blessings | Generating wholesome roots. |
| 30 Days | Willpower | Determination becomes habit. |
| 100 Days | Lion’s Roar | Fearless consistency. |
| 365 Days | Timeless | Practice beyond time. |

**Mindfulness Milestones:**

| Count | Pāramī |
| --- | --- |
| 100 | One-Pointedness |
| 1,000 | Contentment |
| 10,000 | Offering |
| 50,000 | Bliss |
| 100,000 | Suchness |


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
