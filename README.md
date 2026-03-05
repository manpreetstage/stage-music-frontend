# 🎵 Stage Music - Frontend

Mobile-first music streaming web app with YouTube Music inspired design.

## 🚀 Features

- 📱 **Mobile App** - Progressive Web App with offline support
- 🎨 **YouTube Music Design** - Modern, clean UI
- 🎵 **Music Player** - Mini & Full player with queue management
- 🔍 **Search** - Real-time search with debouncing
- 📝 **Playlists** - Create, manage, and share playlists
- 👤 **User Profiles** - Authentication and personalization
- 📊 **Analytics** - RudderStack event tracking (45 events)

## 📁 Structure

```
public/
├── mobile/          # Mobile PWA
│   ├── index.html   # Main mobile app
│   ├── mobile.js    # App logic (85KB)
│   └── mobile.css   # Mobile styles
├── admin/           # Admin panel
│   ├── sections.html
│   ├── sections.js
│   └── custom-sections.html
├── js/
│   └── simple-tracker.js  # RudderStack tracking (16KB)
└── assets/          # Images, logos, covers
```

## 🎯 Analytics

**Total Events:** 45 (41 active)

See [EVENTS-DOCUMENTATION.md](./EVENTS-DOCUMENTATION.md) for complete events list.

### Categories:
- 🎵 Music Player (8 events)
- 🔍 Search (4 events)
- 🔐 Authentication (6 events)
- 📝 Playlists (7 events)
- 📱 Navigation (7 events)
- 🎼 Sections (5 events)
- 💿 Albums (2 events)
- 🕐 Session Tracking (3 events)
- 🎯 Traffic Source (1 event)

## 🛠️ Tech Stack

- **Vanilla JavaScript** - No frameworks
- **CSS3** - Modern responsive design
- **RudderStack** - Analytics & event tracking
- **Media Session API** - Lock screen controls
- **Progressive Web App** - Installable on mobile

## 📊 Event Tracking

All user interactions are tracked via RudderStack:

```javascript
// Example: Song played
window.tracker.trackSongPlay(song, source, position);

// Example: Session tracking
window.tracker.trackSessionHeartbeat(); // Every 30s
```

## 🚀 Deployment

Frontend is deployed at:
- **Mobile:** https://3-111-168-236.nip.io/mobile/
- **Admin:** https://3-111-168-236.nip.io/admin/
- **Desktop:** https://3-111-168-236.nip.io/

## 📝 Key Files

- **mobile.js** (85KB) - Complete mobile app logic
- **simple-tracker.js** (16KB) - Analytics tracking
- **mobile.css** - Mobile app styles
- **EVENTS-DOCUMENTATION.md** - Complete events reference

## 🔧 Backend API

Frontend connects to backend API at same domain.

See backend repo: `stage-music-backend`

## 📄 License

Proprietary - Stage Music App

---

**Version:** 1.2.0
**Last Updated:** March 5, 2024
