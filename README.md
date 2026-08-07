# Routinix ⏰

**Your personal reminder & habit tracker — stay organized, build healthy routines.**

Routinix is an all-in-one reminder, habit & health tracker built with Flutter. It pairs reliable reminders for medicines, water and tasks with a complete productivity hub — habits, routines, goals, focus sessions, step tracking, sleep logs, smart insights and gamification. Everything is stored **100% locally on your device**.

---

## 🌐 GitHub Pages Website

The project includes a complete GitHub Pages website:

- **Landing Page:** [https://Routinix.github.io/Routinix/](https://rudra6370.github.io/routinix.github.io/))
- **Privacy Policy:** [[https://Routinix.github.io/Routinix/privacy-policy.html](https://rudra6370.github.io/routinix.github.io/privacy-policy.html)



---

## 📱 Features

### Productivity Hub
- ✅ **Habit Tracker** — Daily/weekly habits with completion logs and streaks
- 📋 **Tasks** — To-dos with priorities, due dates and notes
- 🔄 **Routines** — Multi-step routines with daily completion tracking
- 🎯 **Goals** — Measurable targets with progress tracking and deadlines
- ⏱️ **Focus Timer** — Focus sessions and daily deep-work minutes
- 📔 **Journal & Mood** — Daily reflections and mood check-ins
- 🏃 **Step Counter** — On-device step tracking with daily goals
- 📅 **Calendar & Year Heatmap** — Visualize consistency over time
- 🏆 **Gamification** — XP, levels, badges, achievements and streaks
- 📊 **Productivity Score** — A daily score with trends and insights
- 🔍 **Search & Smart Insights** — Search everything, get personalized insights

### Reminders & Health
- 💊 **Smart Reminders** — One-time, daily or weekly schedules with exact alarms and voice notifications
- 💧 **Water Intake Tracker** — BMI-based personalized hydration goals with reminders
- 🩺 **Health & BMI** — Health profile, BMI category and tracking
- 🍽️ **Diet Plans** — Meal logging and calorie tracking
- 🌙 **Sleep Tracking** — Log sleep, view stats and insights

### Privacy & Control
- 🔒 **100% Private** — All data stored locally on your device, no account needed
- 📦 **Backup & Restore** — Export and import your data anytime

---

## 🔒 Privacy

Routinix stores all reminders, habit, productivity and health data **locally on your device**. No personal data is transmitted to external servers. The only third-party service is Google AdMob for ads (banner, interstitial and rewarded), governed by Google's privacy policy.

[View Privacy Policy](https://Routinix.github.io/Routinix/privacy-policy.html)

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK ≥ 3.2.0
- Dart SDK ≥ 3.2.0

### Run the app

```bash
flutter pub get
flutter run
```

### Build for release

```bash
flutter build apk --release
```

---

## 📁 Project Structure

```
Routinix/
├── Routinix-website/         # Website source (index.html, privacy policy, README)
├── docs/                     # GitHub Pages deployment copy
│   ├── index.html
│   ├── privacy-policy.html
│   └── robots.txt
├── app-ads.txt               # AdMob publisher verification
├── lib/
│   ├── main.dart             # App entry point, themes, startup
│   ├── core/                 # Hive storage setup
│   ├── features/
│   │   ├── productivity/     # Habits, tasks, routines, goals, focus, journal,
│   │   │                     # mood, calendar, achievements, insights, export
│   │   ├── reminder/         # Reminders (medicines, water, tasks)
│   │   ├── health/           # BMI, water intake, diet plans
│   │   ├── sleep/            # Sleep tracking
│   │   ├── steps/            # Step counter
│   │   ├── stats/            # Analytics & charts
│   │   ├── history/          # Intake history
│   │   ├── notes/            # Notes
│   │   ├── onboarding/       # First-time setup
│   │   ├── settings/         # App settings & backup
│   │   └── home/             # Root dashboard (Productivity Hub)
│   └── services/             # Notifications, voice, reminders, ads
├── android/
├── ios/
├── pubspec.yaml
└── README.md
```

---

## 📄 License

Copyright © 2026 Routinix. All rights reserved.

---

## 📧 Contact

- **Email:** [rudraprakashmajhi@gmail.com](mailto:rudraprakashmajhi@gmail.com)
- **Google Play:** [Routinix on Play Store](https://play.google.com/store/apps/details?id=com.rudra.dosemate)
