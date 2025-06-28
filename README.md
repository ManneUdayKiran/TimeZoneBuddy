
# 🕒 TimeZoneBuddy

**TimeZoneBuddy** is a web-based tool that helps users from different time zones find a common overlapping time for virtual meetings. It assumes each participant is available between **9:00 AM and 8:00 PM local time** and suggests a suitable 1-hour meeting window.

---

## screenshots
![image](https://github.com/user-attachments/assets/8d0076d3-2886-4563-9aa0-d67d4b190093)



## 🌍 Features

- Accepts input of 2 or more city names.
- Calculates overlapping time windows based on each participant's local availability.
- Suggests a meeting time that works for everyone.
- Displays the meeting time in each city's **local time**.
- Works entirely in the browser (no external APIs required).

---

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript
- [Luxon](https://moment.github.io/luxon/) (for timezone and datetime operations)

---

## 🚀 How It Works

1. User enters at least two cities (e.g., `New York`, `London`, `Tokyo`).
2. Each city is mapped to an IANA timezone (e.g., `America/New_York`).
3. Availability window (9 AM – 8 PM) is calculated for each city in UTC.
4. The overlapping window is determined.
5. A suggested 1-hour time block is displayed for each city in local time.

---

## 📦 Installation & Usage

No installation required. Just open `index.html` in your browser.

Alternatively, host it on GitHub Pages or any static hosting provider.

---

## ✅ Example Cities Supported

| City           | Timezone ID           |
|----------------|------------------------|
| New York       | America/New_York       |
| London         | Europe/London          |
| Tokyo          | Asia/Tokyo             |
| Mumbai         | Asia/Kolkata           |
| Sydney         | Australia/Sydney       |
| Paris          | Europe/Paris           |
| San Francisco  | America/Los_Angeles    |
| Dubai          | Asia/Dubai             |

> More cities can be added easily by extending the static mapping in JS.

---

## 📁 Files

- `index.html` – Main HTML page
- `style` – Embedded in HTML
- `script` – JavaScript logic for time calculations and UI

---

## 📌 Limitations

- Only supports cities included in the predefined mapping.
- Currently assumes 1-hour meeting duration.
- Does not yet support weekends, holidays, or calendar integration.

---

## 💡 Future Improvements

- Support for user-defined availability ranges
- Allow adding any city via time zone lookup API
- Dark mode and mobile-friendly layout
- Export to Google Calendar or Outlook

---

## 👤 Author

**ManneUdayKiran**  
GitHub: [@ManneUdayKiran](https://github.com/ManneUdayKiran)

---

## 📄 License

This project is open-source under the MIT License.

