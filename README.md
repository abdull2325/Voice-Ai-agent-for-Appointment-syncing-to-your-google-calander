
# 🤖 n8n Automated Appointment Confirmation System with Retell AI & Google Calendar

This project is an intelligent **n8n workflow** that automates the process of confirming appointments scheduled in **Google Calendar**. It uses **Retell AI** to place natural-sounding, human-like phone calls to attendees, asking if they are available for their upcoming meeting—eliminating the need for manual calls by HR or administrative staff.

---

## 🚀 Features

- 📅 **Reads Appointments from Google Calendar**
- 📞 **Calls Attendees via Retell AI** to confirm availability
- 🗣️ **Natural Voice Conversation** — sounds human, not robotic
- ✅ **Updates Calendar** based on user response
- 📨 **Sends Notification to Attendee** confirming the appointment
- 🔄 **Checks for Slot Conflicts** to avoid double-booking
- 🧘 **Hassle-Free Automation** — no manual intervention required

---

## 🎯 Use Case

Perfect for companies or professionals who need to:
- Reduce workload on HR or admin teams
- Ensure better attendance for scheduled meetings
- Maintain real-time updated calendars
- Enhance user experience with conversational AI

---

## 🔧 Tech Stack

- **[n8n](https://n8n.io/)** – Workflow automation tool
- **[Retell AI](https://retellai.com/)** – Human-like AI voice calling service
- **Google Calendar API** – For fetching and updating calendar events

---

## 🛠️ How It Works

1. The workflow fetches upcoming events from Google Calendar.
2. Retell AI places a phone call to the listed attendee.
3. The AI asks whether they’re available for the scheduled meeting.
4. If confirmed, the appointment remains and a notification is sent.
5. If declined or unanswered, the calendar is updated accordingly.
6. The system also checks for time slot conflicts before booking.

---

---

## ⚠️ Disclaimer

- Ensure that your **Retell AI account has an active subscription** (trial limits may restrict functionality).
- **Do not commit actual credentials**. Use `.env.example` to show structure and keep `.env` in `.gitignore`.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📬 Contact

For queries or suggestions, feel free to reach out via GitHub Issues or create a discussion thread.



