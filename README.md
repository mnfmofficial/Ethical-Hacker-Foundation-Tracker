# HackTracker

A minimal PWA for tracking progress through an ethical hacking study plan. Runs offline, installs on Android, saves progress locally per device.

**Live:** ://mnfmofficial.github.io/Ethical-Hacker-Foundation-Tracker/

---

## Modules

| Module | Tasks |
|---|---|
| Networking | 10 |
| Programming | 10 |
| Linux | 10 |
| Security | 10 |

---

## Install on Android

Open the link in Chrome → three-dot menu → Add to Home Screen.

---

## Run locally

```bash
git clone https://github.com/your-username/hacktracker.git
cd hacktracker
python3 -m http.server 8080
```

Visit `http://localhost:8080`

---

## Structure

```
hacktracker/
├── index.html
├── manifest.json
├── sw.js
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## Notes

- Progress is stored in localStorage — per device, no backend
- Clearing browser data resets progress
- Streak resets if a day is missed

---

## Roadmap

- [ ] Custom task editor
- [ ] Cloud sync
- [ ] Push reminders
- [ ] Weekly summary view

---

## License

MIT
