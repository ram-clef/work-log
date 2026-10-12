# Local changes

Working hours are total elapsed shift time, including lunch: 09:00–18:30 with 13:30–14:30 lunch completes a 9h 30m day.

Confirming an action records it immediately and opens WhatsApp with the selected message. There is no second confirmation. WhatsApp still requires the user to send the message.

Lunch reminder: 13:00. Return reminder: ten minutes before lunch start plus configured break duration. Logout reminder: ten minutes before login plus configured working hours. Work and lunch timers run together.

Sessions are saved after every action. At midnight, or on reopening after an older day, unfinished sessions are closed at login plus their configured shift duration (09:00 + 9h 30m = 18:30), marked as automatic logout, and today's timers reset. A new day requires Reached office again.

Native notifications use one app icon. Browser notification layout is controlled by the operating system. Timed notifications require this client app to remain active; closed or suspended browsers cannot guarantee reminders without a push backend.

Run locally with Python from a parent directory containing this folder as work-log:
python -m http.server 8080
Then open http://localhost:8080/work-log/ . The /work-log/ path is required by the existing PWA configuration.

Verified: JavaScript syntax; inclusive completion example; lunch duration; expected logout; recovery of active and historical unfinished days; immediate login/lunch/back action transitions; local HTTP 200; dashboard renders in browser.
