# Mission Control Dashboard

Real-time monitoring for AFKwarrior squad.

## Features
- ✅ Live agent status (online/working/idle)
- ✅ Session count
- ✅ Cron job monitoring
- ✅ Auto-refresh every 10 seconds
- ✅ Real data from Gateway API
- ✅ **PWA Support** — Install on mobile/desktop!

## Access

### Option 1: GitHub Pages (Recommended - HTTPS + PWA Support)
```
https://ahmed123alemadi-arch.github.io/mission-control-afkwarrior/
```
✅ Works from anywhere  
✅ HTTPS enabled  
✅ PWA install works perfectly on iOS  

### Option 2: Direct File (Local Only)
```bash
open /Users/ahmedalemadi/.openclaw/workspace/mission-control/index.html
```

### Option 2: HTTP Server
```bash
cd /Users/ahmedalemadi/.openclaw/workspace/mission-control
python3 -m http.server 8080
# Then open: http://localhost:8080
```

### Option 3: From Network (PWA Install)
Access from any device on your network:
```
http://192.168.100.18:8080
```

## Install as PWA (Mobile App)

### iPhone/iPad:
1. Open `https://ahmed123alemadi-arch.github.io/mission-control-afkwarrior/` in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"
5. ✅ Mission Control now works like a native app!

### Android:
1. Open `https://ahmed123alemadi-arch.github.io/mission-control-afkwarrior/` in Chrome
2. Tap the menu (three dots)
3. Tap "Add to Home Screen" or "Install App"
4. Tap "Add"
5. ✅ Mission Control now works like a native app!

### Desktop (Chrome/Edge):
1. Open `https://ahmed123alemadi-arch.github.io/mission-control-afkwarrior/`
2. Click the install icon in the address bar (⊕ or computer icon)
3. Click "Install"
4. ✅ Mission Control now runs as a desktop app!

## Configuration
The dashboard connects to:
- Gateway: `http://192.168.100.18:18789`
- Token: Auto-configured

## What It Shows
1. **Stats Cards**: Online agents, working agents, total sessions, cron jobs
2. **Squad Overview**: All 17 agents with real-time status
3. **Cron Jobs**: Active cron jobs and last run times

## Status Logic
- **WORKING**: Active within last 5 minutes
- **ONLINE**: Session exists but not recently active  
- **IDLE**: No session found

---
Built by Joseph 🐺
