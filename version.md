## v5.3.1 - July 27, 2026

**New Features & Improvements**
- Enforced permanent Cyber Dark Mode across the entire app (XML Dashboard & SMB Compose UI), ignoring system light mode overrides
- Applied deep space navy background (`#090C15`) and dark blue-slate card surfaces (`#111625`) with subtle border strokes (`#1C253B`)
- Redesigned station cards with vibrant dark avatar chips (purple, gold, indigo) and styled online/offline status displays
- Restored dynamic superscript RSSI signal text (`-57`) in neon purple (`#A855F7`) next to the main header title
- Extended the Cyber Dark theme to SMB Files Jetpack Compose UI (`OpenWrtSmbTheme`, `Glassmorphism`, `Color.kt`)
- Redesigned Background Wi-Fi Monitor widget into a clean horizontal card row with active status indicators and purple toggles
- Reconstructed the bottom navigation bar with a floating dark container and active purple capsule highlights (`#261B4E` / `#A855F7`)
- Enhanced text legibility by fixing dark mode contrast for station MB/GB data usage values

**Coming Soon**
- Configurable Game Mode duration (approximately 1 hour)
- Temporary user kick functionality
- Local voice calls over the same network
- Sound-system integration

---




## v5.2.1 - July 26, 2026

**New Features & Improvements**
- Added persistent background Wi-Fi Monitor Foreground Service (continuous 15s station polling when app is closed)
- Added Background Wi-Fi Monitor dashboard toggle switch with automatic boot recovery restart
- Added high-priority heads-up system notifications for instant device connection alerts
- Formatted connection notifications to `[Device Name] Connected` with details `IP: [Address] | Total [X] Times`
- Integrated live system log parsing (`calculateConnectCountFromLogs`) to accurately match in-app connection counts
- Redesigned station list cards: 16dp rounded corners, soft pastel avatar containers, network accent bars, and pure IP subtitles
- Redesigned bottom control cards (Guest Mode, Full Speed, Wi-Fi Monitor) into sleek, compact layouts with clean white backgrounds and pastel icon tints
- Increased station card typography sizes (IP subtitle `13.5sp`, uptime `12.5sp`, total data `13.5sp`) for enhanced legibility
- Fixed notification small icon to use official app vector icon (`ic_notification_app_icon`)
- Enforced strict toggle state checking so no notifications trigger when the monitor switch is OFF


---

## v5.0.2 - June 24, 2026, 10:41 PM

**New Features & Improvements**
- Swapped Router tab for SMB FILES in bottom navigation
- Redesigned sidebar with a premium glassmorphic layout and vibrant RSSI stats
- Changed sidebar stats to show WiFi Channel instead of duplicate frequency details
- Added settings to customize Default Start Tab (Dashboard, Movies, or Anime)
- Fixed SMB explorer crashes from stale/closed DiskShare handles
- Fixed bottom nav Dashboard tab navigation when default start tab is set to Movies/Anime


---

## v5.0.1 - June 18, 2026, 07:48 PM

**New Features & Improvements**
- Replaced the "Router" tab with a new "SMB FILES" tab featuring dynamic routing
- Redesigned the sidebar with a premium glassmorphic UI and deep navy gradient
- Added a settings option to customize the default start tab for the SMB view (Dashboard, Movies, or Anime)
- Added a dynamic "New Version Available" badge to the sidebar footer
- Removed the "Force Clear Data" option to streamline the app experience



---


## v4.0.7 - April 25, 2026, 08:30 PM

**New Features & Improvements**
- Added a new hostname
- Updated splash screen credit

---

## v4.0.5 - March 31, 2026, 09:00 PM

**New Features & Improvements**
- Added 'Reupdate' button on the sidebar



---

## v4.0.4 - March 25, 2026, 09:00 PM

**New Features & Improvements**
- Added device grouping
- Make the manu bar more slick
- Remake the settings menu options

---

## v4.0.2 - March 22, 2026, 09:00 PM

**New Features & Improvements**
- Device sorting fixed


---

## v4.0.0 - March 21, 2026, 09:00 PM

**New Features & Improvements**
- Redesign with new UI
- Manu bar added for fast access to spped-test
- Setting to change speed test , router endpoints


---

## v3.9.5 - March 20, 2026, 07:00 PM

**New Features & Improvements**
- Added Strict Game-Mode On Sidebar 
- Fix the sidebar width
- Extensive code cleanup


---

## v3.9.4 - March 17, 2026, 07:00 PM

**New Features & Improvements**
- Added Jio 5G backup internet mode on the sidebar
- On Jio 5G backup mode intternet up/down speed is limited to 100/500 Kbps
- Removed that unneccessary wifi-off splash screen & pop-up
- Fixed icon visibility issue of the Terminal screen 

---

## v3.9.2 - March 12, 2026, 11:00 AM

**New Features & Improvements**
- Redesigned the debug screen
- Redesigned the App Info screen
- Designed the signal strength indicator

---

## v3.9.1 - March 10, 2026, 12:37 AM

**New Features & Improvements**
- Auto rotation issue fixed
- Unsupported router issue fixed

---

## v3.9.0 - March 9, 2026, 09:41 PM

**New Features & Improvements**
- Delay splash screen and device delay fixed
- Debug logs are removed
- Duplicate device entries fixed

---

## v3.8.5 - March 5, 2026, 10:17 AM

**New Features & Improvements**
- Splash version info now fixed

---

## v3.8.3 - March 4, 2026, 09:00 PM

**New Features & Improvements**
- Updated splash screen design
- Improved splash loading transition

---

## v3.8.2 - February 28, 2026, 09:00 PM

**New Features & Improvements**
- Re-optimized the entire layout
- Reduced scan range
- Revamped app launch splash

---

## v3.7.8 - February 18, 2026, 06:00 PM

**New Features & Improvements**
- Introduced auto-scan
- Rearranged Quick Access button layout
- Added debug network log info to the sidebar
- Hid status cards when router is unsupported
- Kept Speed Test and Data Usage accessible in unsupported mode
- Added copy-on-hold for log lines
- Properly aligned device popups
- Fixed dark mode display on the debug screen
- Fixed App Info popup dimensions
- Aligned sidebar panel height
- Improved the App Info and Changelog popups
- Added color coding for two more stations

---

## v3.6.3 - v3.6.6 - January 31, 2026, 01:30 AM

**New Features & Improvements**
- Added device info card
- Fixed device card dark mode
- Aligned device card time range
- Optimized App Info screen dark mode

---

## v3.6.2 - January 24, 2026, 01:30 PM

**New Features & Improvements**
- Show only numeric connected-time values
- Offline device cards now show first connected time and disconnected time
- Active device cards now show first connected time
- Fixed router endpoint links

---

## v3.5.9 - January 13, 2026, 09:30 PM

**New Features & Improvements**
- Added one more endpoint
- Added admin login privilege

---

## v3.5.2 - v3.5.6 - December 11, 2025, 01:30 PM

**New Features & Improvements**
- Massive redesign

---

## v3.5.1 - December 09, 2025, 12:30 PM

**New Features & Improvements**
- Removed voice command
- Added status button to view SSID speeds
- Optimized the App Info screen

---

## v3.5.0 - December 08, 2025, 08:30 PM

**New Features & Improvements**
- New card design

---

## v3.4.7 - v3.4.9 - December 02, 2025, 08:30 PM

**New Features & Improvements**
- Fixed station name color in dark mode
- Station name is now blank for DHCP devices

---

## v3.4.6 - November 26, 2025, 11:00 PM

**New Features & Improvements**
- Redesigned table rows for smaller screens
- Snow Game effect between 10:00 PM and 12:30 AM
- Improved speed calculation accuracy
- Refined About Info page
- Relaxed refresh interval to 3 seconds

---

## v3.4.1 - v3.4.4 - November 19, 2025, 09:00 AM

**New Features & Improvements**
- Improved table row styling

---

## v3.4.0 - November 18, 2025, 11:00 AM

**New Features & Improvements**
- Added Weather Panel option in sidebar
- Added force-clear app data from sidebar menu
- Added Delsgade splash screen between 10:30 PM and 5:00 AM
- Disabled internet on Delsgade between 10:30 PM and 5:00 AM
- App is now downgrade-capable

---

## v3.3.9 - November 9, 2025, 08:00 PM

**New Features & Improvements**
- Added a sidebar weather screen
- Removed the clock widget for now (weather widget planned later)

---

## v3.3.6 - v3.3.8 - November 9, 2025, 08:00 PM

**New Features & Improvements**
- Added a clock widget
- Fixed widget layout
- Added sound on connect and disconnect events

---

## v3.3.4 - November 7, 2025, 06:00 PM

**New Features & Improvements**
- Fixed log visibility
- Removed debug logs to reduce CPU and memory usage

---

## v3.3.2 - November 7, 2025, 11:00 AM

**New Features & Improvements**
- Endpoint connected-time cooldown improvements

---

## v3.3.1 - November 5, 2025, 08:00 PM

**New Features & Improvements**
- Detailed WiFi signal stats now shown for current device
- Automatically removes speed limit when not at home
- Waits 60 seconds to remove speed limit; re-enforcement time is 10 seconds when home
- Added footer in sidebar

---

## v3.2.9 - November 1, 2025, 06:00 PM

**New Features & Improvements**
- Properly aligned all endpoints

---

## v3.2.8 - October 31, 2025, 08:00 PM

**New Features & Improvements**
- Real-time device connection notifications
- Usage duration tracking per connected device
- Notification channel support for Android 8.0+
- Notification permission request for Android 13+
- Improved notification skip logic during initial data load
- Improved notification content with hostname, IP, MAC, and station name
- Fixed crash when hostname/IP is unavailable

---

## v3.2.7 - October 30, 2025, 08:00 PM

**New Features**
- Voice command support for all WiFi controls
- Voice-controlled network speed limits (max 70 Mbps)
- Voice-activated status dashboard
- Multi-endpoint support for better reliability
- Enforced maximum speed limit of 70 Mbps for all networks

**Improvements**
- Enhanced voice command recognition
- More intuitive voice feedback
- Better error handling for voice commands
- Visual feedback during voice recognition
- Client-side validation for speed limits

---

## v3.2.6 - October 29, 2025, 01:15 PM

**New Features**
- Added alliance control with forced desktop mode

---

## v3.2.5 - October 28, 2025, 10:15 PM

**Improvements**
- Fixed reload button issue
- Added more default endpoints

---

## v3.2.4 - October 27, 2025, 02:15 PM

**Improvements**
- Fixed reload mode with button support

---

## v3.2.3 - October 21, 2025, 08:15 PM

**New Features**
- Added WebView reload

**Improvements**
- Enhanced dark mode for About Info

---

## v3.2.2 - October 21, 2025, 01:05 PM

**Improvements**
- Enhanced skip and refresh logic for better reliability

---

## v3.2.0 - October 21, 2025, 11:31 AM

**New Features**
- Added WiFi signal strength indicator next to app title

---

## v3.1.9 - October 21, 2025, 09:31 AM

**New Features**
- App information panel
- Game Mode scheduling (10:00 PM - 12:30 AM)

**Improvements**
- Full user visibility across all devices
- Game Mode event notifications

**Known Issues**
- Clear app data if users are not displaying correctly

---

## v3.1.8 - October 20, 2025, 11:10 AM

**New Features**
- Introduced navigation sidebar

**Coming Soon**
- Event notifications for Game Mode and Night Mode

---

## v3.1.7 - October 19, 2025, 09:10 PM

**Improvements**
- Refreshed app icon design

---

## v3.1.6 - October 19, 2025, 12:10 AM

**Improvements**
- Optimized changelog display
- Fixed header positioning

---

## v3.1.5 - October 18, 2025, 01:10 AM

**Improvements**
- Corrected button text spacing
- Enhanced WebView back navigation

---

## v3.1.4 - October 18, 2025, 12:10 AM

**New Features**
- Router management through admin WebView
- Built-in speed testing
- Data usage tracking

**Improvements**
- Resolved auto-rotation crashes
- Fixed dark mode toggle stability

**Known Issues**
- Direct update from v3.1.2 is not supported (v3.1.3+ required)
- Clean installation required for v3.1.3 and earlier versions

---

## v3.1.1 - October 17, 2025, 08:30 AM

**New Features**
- Automatic update system
- Expanded default endpoint options
- Quick endpoint addition button
- Floating window mode
- Active/total device statistics
- Update validation (requires v3.1.2+)

**Improvements**
- Corrected log display rendering
- Better error messaging
- Optimized overall performance
- Refined user interface

---

## v2.0 - October 16, 2025, 12:10 AM

**New Features**
- WiFi device management dashboard
- Visual usage charts
- Comprehensive activity logs

**Notes**
- First public release

---

## v1.0 - October 16, 2025, 01:10 AM

**Initial Release**
- Foundation UI framework
- WiFi network discovery
- Basic scanning and connection features
