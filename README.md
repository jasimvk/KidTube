KidTube 🎥👶

A safe and curated React Native mobile app for kids to watch only the YouTube videos parents select.
No distractions, no related videos, and no unsafe searches — just the content you approve.

⸻

📌 Features
	•	✅ Curated Playlist: Add your own YouTube playlist, only those videos are visible.
	•	🔍 Safe Search: Kids can search only inside your playlist.
	•	🎨 Clean UI: Inspired by YouTube’s familiar layout but simplified for kids.
	•	🚫 No Ads / No Recommendations: Avoid unwanted content.
	•	👨‍👩‍👦 Parental Control: Parents manage playlists; kids can only watch.
	•	📱 Cross-platform: Works on both iOS & Android.

⸻

🛠️ Tech Stack
	•	React Native
	•	Expo (optional) or React Native CLI
	•	YouTube iFrame API / react-native-youtube-iframe
	•	React Navigation
	•	AsyncStorage (to save user preferences)
	•	Tailwind CSS / NativeWind for styling

📂 Project Structure
kidtube/
│── src/
│   ├── components/      # UI components (VideoCard, SearchBar, etc.)
│   ├── screens/         # App screens (Home, Player, Settings)
│   ├── navigation/      # React Navigation setup
│   ├── hooks/           # Custom hooks
│   ├── utils/           # Helpers (playlist filter, search, etc.)
│   ├── assets/          # Images, icons
│── App.js               # Entry point
│── package.json
│── README.md

🎯 Usage
	1.	Parent sets up their YouTube Playlist ID in the app’s settings.
	2.	App fetches only those videos.
	3.	Child can:
	•	Browse the approved playlist
	•	Search videos within that playlist
	•	Watch videos safely inside the app

🔒 Parental Controls
	•	Playlist ID & settings are protected behind a simple parent lock (e.g., math question or PIN).
	•	Kids cannot add/remove videos.
	•	No external links or suggestions.

⸻

🧩 Roadmap
	•	Multi-playlist support
	•	Offline downloads (for travel)
	•	Custom parental PIN system
	•	Daily time limits
	•	Dark mode
