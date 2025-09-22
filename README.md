KidTube

A safe and curated React Native web/mobile app for kids to watch only the YouTube videos parents select.
No distractions, no related videos, and no unsafe searches — just the content you approve.

🌐 Live Demo

⸻

📌 Features
	•	✅ Curated Playlist: Add your own YouTube playlist; only those videos are visible
	•	🔍 Safe Search: Kids can search only inside your playlist
	•	🎨 Clean UI: YouTube-like familiar layout but simplified and safe for kids
	•	🚫 No Ads / No Recommendations: Avoid unwanted content and external links
	•	🛡️ Branding Removal: Hide “Watch on YouTube,” share buttons, and external navigation
	•	👨‍👩‍👦 Parental Control: Parents manage playlists; kids can only watch approved content
	•	📱 Cross-platform: Works on Web, iOS & Android
	•	🌐 Web Deployment: Deployed on Vercel for instant access
	•	🎬 Fullscreen Support: Native fullscreen playback on all platforms
	•	📐 Responsive Design: Optimized for mobile, tablet, and desktop
	•	⚡ Smooth Scrolling: Enhanced scrolling performance on web and mobile
	•	🔒 Advanced Security: Iframe sandboxing & strict link blocking

⸻

🛠️ Tech Stack
	•	React Native – Cross-platform development
	•	Expo – Development platform & deployment
	•	React Native Web – Web compatibility
	•	YouTube iFrame API / react-native-youtube-iframe – Video playback
	•	React Navigation – Navigation between screens
	•	AsyncStorage – Local storage for preferences
	•	NativeWind / Tailwind CSS – Styling
	•	Vercel – Web deployment

⸻

📂 Project Structure

kidtube/
├── src/
│   ├── components/      # UI (VideoCard, SearchBar, WebVideoPlayer, etc.)
│   ├── screens/         # Screens (Home, Player, Settings)
│   ├── navigation/      # Navigation setup
│   ├── hooks/           # Custom hooks (usePlaylist)
│   ├── utils/           # Helpers (API, storage, config)
│   └── assets/          # Images, icons
├── App.js               # Entry point
├── app.json             # Expo config
├── package.json         # Dependencies
├── vercel.json          # Vercel deployment config
└── README.md


⸻

🚀 Getting Started

Prerequisites
	•	Node.js v16+
	•	npm or yarn
	•	Expo CLI (optional but recommended)

Installation

git clone https://github.com/yourusername/kidtube.git
cd kidtube
npm install

Configure your environment:
	•	Copy .env.example → .env
	•	Add your YouTube API key to src/utils/config.js

Run in Development

Web:

npm run web
# or
expo start --web

Mobile:

npm start
# or
expo start

Build & Deploy

Web Build:

npm run build
# or
npx expo export --platform web

Deploy to Vercel:

vercel --prod


⸻

🎯 Usage

Parent Setup:
	•	Set up YouTube Playlist ID in app settings
	•	Manage approved playlists

Kid Experience:
	•	Browse only approved videos
	•	Search within playlist only
	•	Watch videos safely with no external links

Safety Features:
	•	No “Watch on YouTube” or share buttons
	•	No external navigation
	•	Clean & distraction-free interface
	•	Secure fullscreen playback

⸻

🔒 Security & Safety
	•	Branding Removal: CSS & JS injection to block YouTube elements
	•	Iframe Sandboxing: Restricted permissions
	•	Link Blocking: Prevents navigation to YouTube.com
	•	Fullscreen Security: Safe fullscreen handling
	•	Overlay Protection: Prevents hidden clickable elements
	•	Clean Controls: Only essential video buttons visible

⸻

🧩 Recent Updates
	•	✅ Complete removal of YouTube branding & links
	•	✅ Fullscreen support on all platforms
	•	✅ Enhanced web player with sandboxing
	•	✅ Responsive layouts for all devices
	•	✅ Smooth scrolling & FlatList optimizations
	•	✅ Improved VideoCard with hover effects

⸻

🚦 Roadmap

Completed ✅
	•	Branding removal
	•	Fullscreen video support
	•	Cross-platform compatibility
	•	Smooth scrolling optimization

In Progress 🚧
	•	Parental PIN system
	•	Video progress tracking

Planned 📋
	•	Multi-playlist categories
	•	Daily time limits
	•	Offline downloads
	•	Dark mode toggle
	•	Video bookmarks & favorites
	•	Sleep timer
	•	Parental dashboard with stats

⸻

🏗️ Technical Notes
	•	HomeScreen → Playlist grid
	•	PlayerScreen → Secure player
	•	WebVideoPlayer → Web-optimized
	•	VideoCard → Thumbnail UI
	•	SearchBar → Playlist search

Optimizations: Lazy loading, memory-efficient lists, responsive thumbnails.

⸻

🔧 Troubleshooting
	•	Video not loading → Check internet & playlist privacy
	•	Scrolling issues → Clear cache or use incognito
	•	Fullscreen not working → Enable browser/device fullscreen
	•	YouTube elements visible → Refresh or clear cache

⸻

🤝 Contributing
	1.	Fork repo
	2.	Create branch (feature/AmazingFeature)
	3.	Commit changes
	4.	Push branch
	5.	Open Pull Request

⸻

📄 License

MIT License – see LICENSE.

⸻

🙏 Acknowledgments
	•	YouTube iFrame API
	•	React Native & Expo community
	•	Vercel hosting

⸻

Made with ❤️ for safer kids’ content consumption
