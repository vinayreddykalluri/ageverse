# 🎂 AgeVerse – Your Life, Calculated

**AgeVerse** is a smart, AI-powered age calculator and birthday assistant built using Flutter. It lets users calculate their exact age, track upcoming birthdays, generate personalized AI tips based on age, and even share beautiful birthday cards. Designed with clean UI/UX, contact integration, health calculators, and milestone reminders — AgeVerse turns time into a celebration.

---

## 📲 App Preview

> Coming soon: Screenshots, Reels & Demo Video

---

## ✨ Features

| Feature                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| 🕰️ **Exact Age Calculator**        | Calculate real-time age in years, months, days, hours, minutes, seconds    |
| 🎂 **Birthday Countdown**         | Countdown to your next birthday + show weekday + age you’ll turn           |
| 📇 **Smart Contact Sync**         | Access contacts with DOBs to auto-track birthdays                          |
| 🤖 **AI-Powered Insights**         | Weekly life tips, motivational prompts, and age facts using AI             |
| 💌 **Sharable Cards**             | Create and share AI-generated birthday wishes and age stats                |
| 💪 **Health Calculators**         | BMI, BMR, water intake, fitness suggestions based on age                   |
| 🧠 **Milestone Tracking**         | See when you hit 10K days, 1B seconds, and more                            |
| 🎨 **Beautiful UI & Themes**      | Supports Light, Dark, Neon themes with Lottie animations                   |

---

## 🛠️ Built With

- **Flutter 3.x**
- **Provider** – State management
- **Firebase** – Firestore, Messaging, Analytics
- **Lottie** – Animations
- **Contacts Service** – Access user birthdays
- **Permission Handler** – Safe runtime permissions
- **OpenAI API (planned)** – For advanced AI messages
- **Custom Utilities** – Age, health, and milestone logic

---

## 📂 Folder Structure

```plaintext
lib/
├── main.dart
├── app.dart
├── constants/
├── core/
│   ├── utils/
│   └── services/
├── models/
├── providers/
├── screens/
│   ├── onboarding/
│   ├── home/
│   ├── agecalculator/
│   ├── birthday/
│   ├── insights/
│   ├── health/
│   ├── profiles/
│   ├── settings/
│   └── comparison/
├── widgets/
├── data/
├── l10n/
├── generated/

Check the folder design structure for details and maintainability tips.

⸻

🚧 Roadmap
	•	Version 1 – Age calculator + birthday features
	•	Provider state management
	•	Smart birthday sync with contacts
	•	Shareable AI-generated wishes
	•	AI-driven life tracker (v2)
	•	Health dashboard with charts
	•	Premium themes and monetization

⸻

🔐 Permissions

Platform	Permission	Reason
Android	contacts	To access saved birthdays
Android	notification	To send birthday and milestone reminders

App never uploads contacts or personal data to a server without consent.

⸻

👨‍💻 Developer

Vinay Reddy Kalluri
📍 Atlanta, GA
💼 Java Backend Lead | Mobile App Developer | AI Enthusiast
📧 vinayreddykalluri@gmail.com
⸻

🚀 Getting Started Locally

git clone https://github.com/vinayreddykalluri/ageverse.git
cd ageverse
flutter pub get
flutter run

Make sure you run flutter doctor and have the Flutter SDK installed.

⸻

📄 License

This project is under the MIT License. Feel free to fork, extend, or contribute.

⸻

❤️ Support This Project

If you like the idea of turning age into celebration, insight, and fun:
	•	⭐ Star this repo
	•	📨 Share the app with friends
	•	📬 Contribute to the features roadmap

⸻

“Age is just a number. But your story behind it is everything.” – AgeVerse