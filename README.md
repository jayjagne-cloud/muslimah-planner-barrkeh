# Premium Muslimah Interactive Digital Planner

A standalone, single-file interactive planner designed to help Muslimahs live intentionally, focusing on spiritual growth, goal setting, and daily organization with a foundation of Barakah (blessings).

This planner is built as a single `index.html` or `barrkeh-planner-standalone.html` file, making it extremely easy to deploy and use across multiple devices.

## ✨ Features

The planner is fully interactive and saves all your entries directly to your device's browser using **Local Storage**, ensuring your progress is persistent between sessions.

### Core Interactivity
* **Data Persistence:** All entries—including text fields, dates, checkboxes, and toggles—are automatically saved to the device's local storage upon input or clicking the "Save Progress" button.
* **Spiritual Progress Bar:** Visual progress tracking in the "Spiritual Hub" that updates dynamically as you complete the 5 daily Salah items and 4 Dhikr items.
* **Interactive Checklists:** Tap to track completion for:
    * 5 Daily Salahs (Fajr, Dhuhr, Asr, Maghrib, Isha).
    * 4 Daily Dhikr (SubhanAllah, Alhamdulillah, Allahu Akbar, Ayatul Kursi).
    * 6 Weekly Habits (Quran, Dhikr, Water, Movement, Learn, Kindness).
    * 4 Home Care tasks.
* **Time Blocking:** A unique feature allowing you to cycle through time blocks between **Worship (Gold)**, **Work (Blue)**, and **Rest (Purple)**.
* **Emotional Check-in:** Quick buttons linked to **Asma ul Husna (Names of Allah)** relevant to the emotion (e.g., Overwhelmed -> Al-Hakim, Anxious -> As-Salam), providing spiritual comfort.

### Planning Sections
* **Vision:** Define your Core Values, Spiritual Identity, and Barakah-Driven Purpose.
* **Daily:** Log your Ayah of the Day, Top 3 Priorities, and Energy Level.
* **Weekly:** Set priorities, track habits, and map out your schedule with Time Blocking.
* **Monthly:** Set high-level Spiritual, Personal, and Career Goals.
* **Career & Home Life:** Dedicated sections for focused planning in these key domains.

## 🚀 Deployment

This planner is designed for **zero-configuration** deployment. It requires no server, database, or complex backend setup.

1.  **Obtain the Code:** Ensure you have the complete, corrected `barrkeh-planner-standalone.html` file (or the full code provided in the fix).
2.  **Upload to Host:** Upload the single `.html` file to your preferred hosting service:
    * **Netlify/Vercel:** Drag and drop the file.
    * **Google Drive/Dropbox:** Share the HTML file (though Local Storage functionality may be limited on some mobile browsers when accessing files directly from cloud storage URLs).
    * **Local Use:** Simply double-click the file to open it in any modern browser (Chrome, Safari, Firefox).

## 💡 Usage and Data Management

### Saving Data
Data is automatically saved whenever you interact with a toggle, checkbox, slider, or when you click the **"Save Progress"** button at the bottom of a section. The data is stored solely in your browser's **Local Storage**.

### Data Location
Your data is stored under the domain/URL where the HTML file is accessed (e.g., your Netlify URL).

### Clearing Data / Starting a New Day
To clear all data and start fresh (e.g., at the beginning of a new month or year), you must manually clear the Local Storage for the URL you are viewing the planner on.

**How to Clear Local Storage (Desktop/Mobile):**

1.  **Open Developer Tools (Desktop):** Press `F12` or `Ctrl+Shift+I` (Windows/Linux) / `Cmd+Option+I` (Mac).
2.  Navigate to the **Application** tab (or **Storage** tab).
3.  Select **Local Storage** from the sidebar.
4.  Right-click the planner's URL and select **"Clear"** or **"Delete"**.
5.  Refresh the planner page.

## 💻 Technology

* **HTML5:** Structure and content.
* **CSS3:** Styling (Responsive, Mobile-First Design, Dark Mode Aesthetics).
* **Vanilla JavaScript (ES6+):** All interactive logic, data handling, and local storage management.

## ⚖️ Credit and License

**Creator:** Barrkeh DigiProducts

This project is intended for personal use by customers of Barrkeh DigiProducts.
