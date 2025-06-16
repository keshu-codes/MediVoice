# 💊 MediVoice – Voice-Activated Medication Reminder

*MediVoice* is a modern voice-activated medication reminder web app designed for social impact. It allows users to set daily reminders for their medications using voice commands or manual input. The app sends timely alerts through speech and sound. No login is required — all data is stored securely in your browser.

---

## 🚀 Features

- 🎙 Voice-controlled reminder creation
- 📝 Manual entry for:
  - Medicine name
  - Time (hour, minutes, AM/PM)
  - Priority (High / Medium / Low)
  - Daily repeat toggle
- ⏰ Real-time countdown until next dose
- 🔊 Voice alert + alarm sound when it's time
- 🧾 Reminder confirmation popup
- 🗃 Deleted history with:
  - Restore option
  - Clear-all option
- 🧠 Remembers reminders using localStorage
- 📱 Mobile responsive UI
- 🔐 No sign-up, no backend, 100% private

---

## 🧠 Voice Command Format

Just say your medicine and time in this format:


[Medicine Name] at [Hour] [Minutes] [AM/PM]


✅ Examples:
- “Paracetamol at 9 30 AM”
- “Insulin at 7 45 PM”

---

## 📋 How It Works

1. The app listens to your voice using the Web Speech API.
2. It extracts the medicine name and time.
3. The reminder is saved in your browser using localStorage.
4. When the time comes:
   - A voice alert announces the medicine.
   - An alarm sound plays.
   - A popup asks for confirmation.

---

## 🗂 Project Structure


📁 mediVoice/
├── index.html
├── style.css
├── script.js
├── alarm.mp3
├── README.md


---

## 🛠 Tech Stack

- HTML, CSS, JavaScript
- Web Speech API (voice input + speech output)
- localStorage (data persistence)
- Mobile-first responsive design

---

## 🚨 Permissions

On mobile, you must grant microphone access for voice commands. If not allowed, a message will appear asking for it.

---

## 🧪 Testing Voice Input

Make sure to:
- Use Chrome or any browser that supports Web Speech API.
- Click the mic button.
- Say something like: Paracetamol at 8 15 PM.
- The app will set and announce the reminder.

---

## 🧹 Reminder Management

- Reminders can be deleted manually.
- Deleted reminders are moved to History.
- History can be cleared individually or completely.

---

## 🧾 License

This project is licensed under the MIT License.

---

## 👤 Created By

*Keshu* – for the [Hack The Vibe 2025](https://hackthevibe.dev) hackathon.  
Made with ❤ for real-world social impact.
