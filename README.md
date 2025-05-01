# BeAware – Women's Health Tracker

BeAware is a menstrual and wellness tracking app designed to empower women with insights into their cycle, daily symptoms, affirmations, and lifestyle tips.

## 🚀 Features

- Period and ovulation tracking with calendar view
- Cycle phase predictions and fertility insights
- Notification preferences for reminders and affirmations
- Daily health tips and motivational affirmations
- Wellness hub with social links and resources
- Profile tracking of moods, symptoms, and streaks

---

## 🛠️ Getting Started

### ⚡ Open in [Bolt.new](https://bolt.new)

1. Go to [https://bolt.new](https://bolt.new)
2. Click "Import ZIP" and upload this project
3. Set your `.env` variables using Bolt's UI
4. Run and preview the app instantly

### 🧪 Run Locally with Expo CLI

```bash
npm install
npx expo start
```

> Ensure you have Expo CLI installed: `npm install -g expo-cli`

---

## 🌐 Environment Variables

Create a `.env` file based on `.env.example`:

```env
SUPABASE_URL=https://your-project.supabase.co
SUPABASE_ANON_KEY=your-anon-key
```

---

## 📁 Folder Structure

```
.
├── app/                # All screens and routes
│   ├── (tabs)/         # Tab screens (Home, Cycle, Profile, Wellness)
│   └── _layout.tsx     # Shared layout & navigation
├── lib/                # Auth, fonts, notifications, Supabase client
├── hooks/              # Custom hooks for Supabase and cycle data
├── types/              # Supabase types
├── assets/             # Images and sound files
├── .env.example        # Env structure
├── app.json            # Expo config
├── package.json        # Dependencies and scripts
```

---

## 📦 Built With

- [Expo](https://expo.dev/)
- [React Native](https://reactnative.dev/)
- [Supabase](https://supabase.com/)
- [Lucide Icons](https://lucide.dev/icons)
- [React Native Calendars](https://github.com/wix/react-native-calendars)
- [date-fns](https://date-fns.org/)

---

## 💖 Author

Made with purpose by the BeAware Team
