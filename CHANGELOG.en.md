# Changelog

[한국어](CHANGELOG.md) · **English**

## 1.7.2 — 2026-11-03

- The drive video on the monitors is sharp in the normal view too
  - Before: the view from the eye was first drawn into a 360° picture (1024 px a side, 2048 px with high quality) and then put on the monitors, so in the normal view, where a monitor fills much of the screen, it was stretched 1.5–3x and looked blurry
  - Now: every point of a monitor takes its colour straight from the drive video, in the direction it is seen from the eye, at the video's own resolution
  - Layout and angles are the same as before (triple, ultrawide, single, wide view, Showroom, your own video)
  - Lighter: no 360° picture is drawn every frame

## 1.7.1 — 2026-11-03

- Motion base in the driver's view: feels like sitting on a real motion rig
  - The rig now tilts in the driver's view too, the same as in the room view (braking and throttle forward and back, corners side to side)
  - The seat carries your eye (under braking your head moves toward the screens)
  - Your head stays closer to level than the seat: it takes about a third of the tilt, a little later
  - Rig-mounted monitors and the wheel move with you; monitors on a floor stand or a desk stay put (before, only the view tilted, so the wheel and monitors swayed in front of you)
- The person model in the light test tilts with the seat too

## 1.7.0 — 2026-11-03

- Setup gallery: post with just a nickname, no sign-in
  - Nickname field when posting (2–12 characters, remembered in this browser), shown on cards and in the detail view
  - Posting without signing in runs a Cloudflare Turnstile bot check (usually invisible), then creates an anonymous account for this browser
  - A setup posted without signing in can only be deleted from the browser that posted it; Google sign-in still works (delete from any device)
  - My Library and reporting still need a Google account
- Server: nickname required for anonymous accounts, 30 anonymous posts per hour in total, anonymous accounts with no posts deleted after 30 days
- Privacy policy: nickname, anonymous accounts and Cloudflare (bot check) added

## 1.6.2 — 2026-11-02

- Phones: windows taller than the screen now scroll
  - Setup gallery and the guide video list scroll inside the window
  - Menu › Settings opened: the menu ends on screen and scrolls (Reset all and the open-source notice are reachable)
- Rig step Rig/Monitor tabs: at the phone's normal panel height they scroll away with the list instead of covering it; pinned at the top when the panel is pulled all the way up

## 1.6.1 — 2026-11-02

- Inches by default only in the US: English page + US English browser + a US time zone (Hawaii, Alaska and US territories included)
  - Browsers set to US English outside the US start in cm
  - A unit chosen in Menu › Settings still wins

## 1.6.0 — 2026-11-02

- New address: https://naebangfit.com (English: https://naebangfit.com/en/)
  - The old address (rlacksgur06.github.io/naebangfit) forwards to the new one; old share links still open
  - New share links, setup card QR codes and link previews use the new address
- Rooms and settings saved in the browser belong to each address, so the new address starts fresh (setups saved to an account are unchanged)

## 1.5.3 — 2026-11-02

- English videos on the English page: 22 how-to videos (PC 12, phone 10), Getting started, and the intro video
  - Recorded from the English app, with English captions and titles
  - The video list shows the English lengths
- The Korean page is unchanged; the start screen loop is shared by both

## 1.5.2 — 2026-11-02

- iPhone Safari (iOS 26)
  - The app now fits the visible area, so the floating bottom bar no longer covers the panel
  - No more blur at the top: a strip in the page colour under the clock and battery
  - Tab and history icons: PNG icons first
- Tablets: the how-to video follows the layout (PC screens in landscape → PC video)
- Integrity checks on outside code (3D engine, sign-in library, QR): a changed CDN file is not run
- Values screen for checking a device: Menu › Open source & credits, tap the version five times

## 1.5.1 — 2026-11-02

- New intro video (new cut, 42 s)
- New start screen loop (7 s, 4.3 MB → 1.3 MB)
- Site icon: browser tab, add to home screen, next to link previews
- New link preview image: example room 1, laid out in the centre so Naver Cafe and KakaoTalk no longer crop it
- Copyright line now includes the GitHub account
- Docs: README and changelog split into Korean and English

## 1.5.0 — 2026-11-01

- Inch units: Menu › Settings › Units (cm · mm · in)
  - Rooms in feet and inches (e.g. 11′ 6″), furniture and gaps in inches, area in ft², cables in lengths you can buy (3 · 6 · 10 · 15 ft…)
  - Rig Garage profiles, game FOV values and part specs stay in mm
  - The English version opens in inches in US browsers
- Cleaner start screen: one link, "Browse other rooms ›" ("Start over" too when continuing); the intro video moves to ▶ under the sound button
- Setup gallery: "Naebangfit examples" on top, with the Showroom and 3 example rooms (open in view mode; your own room stays as it is)
- One help button: the separate "How this step works" is gone; the written guide is under "Read instead" in the video window
- Toolbar ···: "How to" (the view tools and menu video)
- Menu: "Load from share code" moves into the Share window; "Language" moves into Settings

## 1.4.0 — 2026-11-01

- How-to videos: "▶ How to" next to each step's title (landscape on PC, portrait on phones, 1× · 1.5× · 2×, music ducks while playing)
- "Getting started" video plays once on the first start
- Menu › How to use: the intro video and every step's video
- Start screen: silent background loop (a still frame with data saver, slow connections or reduced motion), intro video link
- Rig Garage video ends with "Next: Garage handles ›"

## 1.3.0 — 2026-11-01

- Setup gallery: browse rooms and rigs shared by others and open them as they are (newest, most opened)
  - After signing in: post your setup (title, one-line note, room picture) and delete your own posts
  - Names and emails are never shown; posts with enough reports are hidden automatically
  - Also from "Post to gallery" in the Result step and the start screen link
- Privacy Policy: setup gallery section (Korean and English)

## 1.2.0 — 2026-11-01

- Short share links: `…/naebangfit/?s=AbCd2345`. Simpler QR on the setup card. Falls back to a long link with the whole setup when the server can't be reached
- Phone sharing: the Share button opens the phone's share sheet (KakaoTalk, Messages)
- Link previews: pasting a link in KakaoTalk, messengers or social media shows a card with a picture, title and description
- English version (`/en/`): browsers not set to Korean open it first; switch any time from the menu
- Privacy Policy: share link section, English version (`privacy-en.html`)

## 1.1.1 — 2026-11-01

- Privacy Policy link in the sign-in window uses the app colour
- Scheduled job wakes the sign-in server (Supabase free plan) twice a day so it doesn't pause

## 1.1.0 — 2026-11-01

- Sign-in and My Library: save rooms and rigs as setups with a Google account (up to 50) and open them again on PC or phone
  - Save under a new name, overwrite, delete, delete account (account and setups removed at once)
  - Everything still works without signing in
- Privacy Policy ([privacy-en.html](privacy-en.html)), linked at the bottom of the menu

## 1.0.1 — 2026-11-01

- Anonymous usage stats: app version, browser language and time zone; no IP location
  - What is sent is listed on the start screen and in Menu › Open source & credits; turn it off in Menu › Settings

## 1.0.0 — 2026-11-01

First public version.

- Room: width, depth, ceiling height, doors and windows (hinged, sliding, opening side), example rooms, draw your own layout on PC
- Furniture: by category, drag to move and rotate, snaps to walls and other furniture
- Rigs: aluminium profile, foldable and fixed seat rigs, desk clamp, compare several, design your own on PC
- Monitors: single, ultrawide, triple (curved too), rig-mounted, floor stand or desk monitor arm
- Verdict: does it fit, can the door open, room to get in and out, screen distance
- Driver's seat: seated view, 200° wide view, day and night driving footage with engine sound, FOV values per game
- Tools: cable lengths, lighting preview (light bar), Showroom (10 monitor setups), setup card (QR), share links
- Display: phone support, light and dark, cm and mm units
