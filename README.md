# DoseMate 💊

**Never Miss Your Medicines**

A smart medicine & health tracker with intelligent reminders, BMI-based water goals, diet plans, sleep tracking, and health analytics. Built with Flutter.

---

## 🌐 GitHub Pages Website

The project includes a complete GitHub Pages website in the `docs/` folder:

- **Landing Page:** [https://dosemate.github.io/dosemate/](https://dosemate.github.io/dosemate/)
- **Privacy Policy:** [https://dosemate.github.io/dosemate/privacy-policy.html](https://dosemate.github.io/dosemate/privacy-policy.html)

### Deploy to GitHub Pages

1. Go to your repository **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Under **Branch**, select `main` (or `master`) and `/docs`
4. Click **Save**

Your site will be live at `https://<your-github-username>.github.io/dosemate/`

---

## 📱 Features

- 💊 **Smart Medicine Reminders** — One-time, daily, or weekly schedules
- 💧 **Water Intake Tracker** — BMI-based personalized hydration goals
- 🌙 **Sleep Tracking** — Log sleep, set goals, get insights
- 📊 **Health Analytics** — BMI, adherence charts, weekly breakdowns
- 🍽️ **Diet Plans** — Meal logging and calorie tracking
- 🧠 **Behavioral Insights** — AI-powered habit analysis
- 🔒 **100% Private** — All data stored locally on your device
- 📦 **Backup & Restore** — Export and import your data

---

## 🔒 Privacy

DoseMate stores all health and medicine data **locally on your device**. No personal health data is transmitted to external servers. The only third-party service is Google AdMob for ads.

[View Privacy Policy](https://dosemate.github.io/dosemate/privacy-policy.html)

---

## 🚀 Getting Started

This project is a starting point for a Flutter application.

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
dosemate/
├── docs/                    # GitHub Pages website
│   ├── index.html           # Landing page
│   ├── privacy-policy.html  # Privacy policy
│   └── robots.txt           # Crawler rules
├── app-ads.txt              # AdMob publisher verification
├── lib/
│   ├── main.dart            # App entry point
│   ├── features/
│   │   ├── home/            # Dashboard
│   │   ├── medicine/        # Medicine management
│   │   ├── health/          # BMI, water, diet
│   │   ├── sleep/           # Sleep tracking
│   │   ├── insights/        # Behavioral insights
│   │   ├── stats/           # Analytics & charts
│   │   ├── history/         # Intake history
│   │   ├── settings/        # App settings & backup
│   │   └── onboarding/      # First-time setup
│   └── services/            # Notifications, ads, reminders
├── android/
├── ios/
├── pubspec.yaml
└── README.md
```

---

## 📄 License

Copyright © 2026 DoseMate. All rights reserved.

---

## 📧 Contact

- **Email:** [dosemate.app@gmail.com](mailto:dosemate.app@gmail.com)
- **Google Play:** [DoseMate on Play Store](https://play.google.com/store/apps/details?id=com.rudra.dosemate)
