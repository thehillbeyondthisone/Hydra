# 🐍 HYDRA  
### _The many-headed observer._

---

## What is Hydra?

Hydra is a real-time, multi-sensor monitoring system.  
Each sensor watches, reports, and reacts — combining their input into a single, living feed.

---

## 🧩 Core Function

-  **Sensors** — Each character with a Hydra log enabled becomes a sensor. Each one tails live output using the browser’s File System API.  
-  **Aggregation** — Hydra merges all streams into one view, grouped by sensor label and channel. Be anywhere, hear everything.
-  **Alerts** — Detects tower activity, world bosses, Tarasque states, AI30/220 dings, and custom tells.  
-  **Search** — Live regex/text search with highlight, filters, and navigation.  
-  **Persistence** — Save and reload sensors with stored file handles (Chromium only).
-  **Settings** toggle combat, tower/world-boss alerts, or tell/team notifications.
-  **Live Ticker**  With local / UTC time and latest events (🗡️ Tower battle • 🐉 Boss spawn • ⭐ 220 ding • 🏆 AI30)  

*Lovely for players with toons spread across multiple orgs and factions.*

---

## 🚀 Quick Setup

⚙️ **Add Buddy Alerts**
   - In game, open the chat panel and create a new window.
   - Name it Hydra and enable logging.
   - Open the folder containing the log on your local computer.
   - Subscribe to chat channels. (Enabling all chat channels is recommended, as you can filter the feed in Hydra itself)

🖥️ **Open Hydra**  
   Launch `Hydra.html` in a Chromium-based browser.  
   _(Chrome/Edge recommended — Firefox lacks persistent handle support.)_

🧠 **Deploy a Sensor**  
   - Click **“Deploy New Sensor.”**  
   - Give it a label (e.g. `Main Toon`, `Borealis`).  
   - Locate to your log file, typically:  
     ```
     C:\Users\<You>\AppData\Local\Funcom\Anarchy Online\...\Chat\Windows\Window#\Log.txt
     ```
  Drag and drop the log on the new sensor's drop zone. OR locate the log manually (not recommended).
  
  Hydra back-reads the last ~200 lines and begins live tailing.

⚔️ **Add More Heads**  
   Each additional sensor (character) becomes a new “head.”  
   Hydra merges their output into one coherent feed.
   Per-sensor toggles for system messages and XP to prevent spam.

⚙️ **Add Buddy Alerts**  
   Under ⚙️ > _Buddy List_, add names for 📨 tell notifications.

🔍 **Search Everything**  
   Regex or plain text. Filter by channel.  
   Use “Show only matches” + ⟨ / ⟩ navigation to slice through the noise.

💾 **Save Sensors** *(optional)*  
   Save tiles to remember file handles → reload via **Saved Logs → Load**.

🔍 **Use Log Finder**  
   On the next open, load your previously saved sensors from the menu.

---
Contact: YellowUmbrellaGroup#8576
---

<img width="420" height="640" alt="HYDRA" src="https://github.com/user-attachments/assets/370a63bc-adad-4d03-86df-d5cf9f6adcb5" />


