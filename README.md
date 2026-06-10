# Tuan Nguyen
### Flutter / Mobile Application Developer

📧 nguyenvantuan4034@gmail.com · 📱 +84 987 620 174 · 📍 Da Nang, Vietnam
🔗 [linkedin.com/in/maengseojin](https://www.linkedin.com/in/maengseojin/) · 💻 [github.com/Bow-T](https://github.com/Bow-T)

> 🖥️ **Printable / styled version:** [cv-tuan-nguyen.html](cv-tuan-nguyen.html) — open in a browser, then Print → *Save as PDF*.

---

## Professional Summary

Flutter / Mobile Application Developer with **6+ years of experience** (since 2020) designing, building and shipping **production mobile apps end-to-end** — from architecture and UI to backend integration, payments, CI/CD and store release. Lead or sole developer on **30+ Flutter applications**, several **live on the App Store and Google Play** — including a **carpooling app with ~37,000 App Store ratings (4.9★)** and a **safety app with 10,000+ downloads and national press coverage** — across ride-hailing & delivery, food, healthcare, mental wellness, personal safety, beauty, dating, music, sports, events and drone logging. **Authored the company's shared Flutter base architecture** that 20+ client apps are built on. Strong at integrating Flutter apps with **Firebase** and **Supabase** backends and **Stripe** payments, and delivering **multilingual (EN/FR)**, real-time, payment-enabled apps for iOS and Android.

---

## Core Technical Skills

| Area | Technologies & Libraries |
| --- | --- |
| **Languages** | Dart (primary), TypeScript, JavaScript, SQL, Kotlin & Swift (platform channels), C/C++ (FFI) |
| **Mobile** | Flutter (iOS & Android), Material/Cupertino, responsive & adaptive UI, custom animations (Lottie, animate_do), platform channels, push & local notifications; React Native (cross-platform) |
| **State / Architecture** | MVVM (BaseViewModel + page mixins), Clean Architecture, MVC, MVP, modular monorepo; Provider, GetX, BLoC, Stacked; dependency injection (get_it, injectable); code generation (build_runner, json_serializable, auto_route, intl_utils) |
| **Navigation** | auto_route |
| **Networking** | dio + retrofit, REST, interceptors / smart retry; WebSocket / Socket.IO |
| **Realtime / Comms** | Agora (RTC/RTM/Chat), WebRTC (ConnectyCube), SignalR, Socket.IO, OpenAI Realtime (voice/WebRTC) |
| **Backend (integration)** | Firebase (Auth, Firestore, Storage, Messaging, Dynamic Links, Analytics), Supabase (Postgres, Row-Level Security, Edge Functions), REST API integration |
| **Maps & Location** | Google Maps, geolocator, geocoding, marker clustering, static maps, maps_toolkit |
| **Payments / Monetization** | Stripe (flutter_stripe), RevenueCat subscriptions (purchases_flutter), PayPal, in-app review |
| **AI / Media** | OpenAI realtime voice assistant, speech-to-text / TTS, Unity 3D embed; camerawesome, image/video pickers & editors, just_audio, audio_waveforms, video_player/chewie |
| **Auth** | Email/OTP, Google, Apple, Facebook Sign-In, Firebase Auth, secure storage |
| **i18n** | intl / intl_utils (ARB), full English & French localization |
| **Growth / Analytics** | AppsFlyer, Firebase Analytics, Branch & Firebase Dynamic Links, Facebook & TikTok event SDKs |
| **Tooling / DevOps** | Git & GitLab/GitHub CI/CD, Fastlane, FVM, Figma, Jira, Trello, Conventional Commits, App Store Connect & Google Play Console |

---

## Professional Experience

### Flutter / Mobile Developer — Digital Unicorn
*2022 – Present · Mobile app & web agency (France / Vietnam)*

- **Lead developer of the DUOCT "Octopus" super-app** — a multi-service platform (ride booking, multi-category express delivery, courier dispatch) built as a **Flutter + Next.js + Supabase** monorepo with Stripe payments and Row-Level-Security multi-tenant data isolation.
- **Sole or lead developer on 25+ production Flutter apps**, several **published to the App Store & Google Play** — including **SecuMap (10,000+ downloads, covered by French national press)**, ProtectU, Octopush, Carter, Nila Sphere, Docteur Sirop and Mentalia.
- **Authored and maintained the company's shared Flutter base architecture / starter template** (MVVM BaseViewModel + page mixins, shared models/services/theme/i18n package, `auto_route` + Provider + `get_it`, `build_runner` codegen) — adopted by **20+ client apps**, turning weeks of project setup into a same-day start and standardizing engineering quality across the company.
- **Integrated advanced, varied capabilities** across apps: real-time location & messaging (SignalR, Socket.IO, Agora), AI voice assistants (OpenAI Realtime + Unity 3D), Stripe / PayPal / RevenueCat monetization, and crowd-sourced mapping.
- **Delivered full EN/FR localization** and store-compliant builds (App Tracking Transparency, permissions, privacy) for the French and international markets.
- **Owned end-to-end delivery**: requirements (Jira) → Flutter UI → backend integration (Firebase / Supabase) → CI/CD (Fastlane) → store submission.

### Flutter Developer — Freelance / Independent
*2020 – 2022*

- Built mobile apps as **independent projects** before joining Digital Unicorn — including a **medical / clinic management app** — plus a range of Flutter prototypes, while establishing the **MVVM base architecture** later reused at scale.

---

## Selected Projects

### 🚩 Flagship platform

**Octopus / DUOCT — Multi-service super-app** · *Lead Mobile Developer · 2026 – Present*
Multi-service super-app with separate **customer and driver/partner apps**: ride/trip booking, multi-category **express delivery** (food, flowers, high-tech, home services) and courier order handling. Drivers get onboarding (documents, vehicle info), trip & order handling and **earnings dashboards with weekly payouts**; customers get category search, delivery estimates/offers, in-app payments & receipts, **premium subscriptions** and partner applications.
**Tech:** Flutter · auto_route, Provider, get_it · supabase_flutter · **flutter_stripe** + RevenueCat · **flutter_map** + geolocator + latlong2 (live tracking) · Firebase Messaging · camerawesome · AppsFlyer · custom in-house **OCR** package · intl (EN/FR) · Next.js / React / TypeScript admin.

### 🏗️ Foundation & architecture

**Digital Unicorn Flutter Base — In-house starter & architecture** · *Author & Maintainer · 2022 – Present*
The company's shared Flutter foundation that **every new client app is forked from**. Established the **MVVM** scaffold (BaseViewModel + page mixins), a shared package for models/services/theme/localization, and pre-wired layers for networking, auth, navigation, i18n, push, analytics, monetization and CI — turning new-project setup from weeks into a same-day bootstrap, and standardizing engineering quality across **20+ apps (2022 → 2026)**.
**Tech:** Flutter · auto_route · Provider · get_it · dio + retrofit + dio_smart_retry · json_serializable + build_runner · intl_utils (EN/FR) · Firebase · AppsFlyer · RevenueCat · SignalR.

### 📱 Published apps — live on the App Store & Google Play

**Ynstant — Carpooling / ridesharing app** · *Flutter Developer · 2023* · ⭐ **~37,000 App Store ratings (4.9★) · ~14,500 Google Play ratings**
🍏 [App Store](https://apps.apple.com/us/app/ynstant-carpooling/id1610500828) · 🤖 [Google Play](https://play.google.com/store/apps/details?id=dev.ynstant.moove)
France-focused daily carpooling for weekend getaways and holidays with **0% service fees**: drivers post a ride in under 30 seconds and get bookings from verified passengers, while passengers book instantly or set alerts for matching rides — with in-app messaging and automatic distance-based pricing. The most-rated app in this portfolio.
**Tech:** Flutter (iOS & Android) · Google Maps + geolocation · real-time ride matching · in-app messaging · payments.

**SecuMap — Safety navigation app** · *Sole Developer · 2023 – 2025* · ⭐ **10,000+ downloads · featured in French national press (Le JDD)**
🍏 [App Store](https://apps.apple.com/fr/app/secumap/id6447151691) · 🤖 [Google Play](https://play.google.com/store/apps/details?id=com.du.secumap)
Free French safety-GPS to walk safely across France: a **real-time interactive map** crowd-sourced from thousands of users that flags dangerous and poorly-lit streets and **automatically re-routes** you around reported dangers; report incidents anonymously and save favourite addresses, with nationwide coverage. The most-adopted app in this portfolio.
**Tech:** Flutter · Google Maps + **maps_toolkit** + geocoding (routing/geofencing) · WebSocket (live reports) · Firebase Dynamic Links · deep links.

**KEYM — Musical social network** · *Flutter Developer · 2023* · **5,000+ downloads**
📦 [apkcombo](https://apkcombo.com/keym-reseau-social-musical/keymmusic.com.keym/)
A music social network *"by artists, for artists"* connecting musicians, singers, producers, sound engineers, photographers and videographers: build a **multi-format (visual + audio) portfolio**, search talent by skills and artistic universe, and connect with complementary professionals to collaborate and grow your music career.
**Tech:** Flutter · audio/video media portfolio · in-app messaging · REST / Firebase.

**ProtectU — Personal-safety app** · *Sole Developer · 2025* · **1,000+ downloads**
🍏 [App Store](https://apps.apple.com/us/app/protectu/id6743616393) · 🤖 [Google Play](https://play.google.com/store/apps/details?id=com.protectu.fr)
French citizen-safety app to **see, understand and act on risky situations in real time**: an interactive incident map, guidance to nearby safe places (hospitals, police, defibrillators), nearby ProtectU users on the map, live-location sharing and secure messaging to trusted contacts — turning your surroundings into an active protection network.
**Tech:** Flutter · **SignalR** (real-time) · Google Maps + geolocator · Firebase · crypto · AppsFlyer + Facebook + TikTok event SDKs · RevenueCat.

**Octopush — Business messenger** · *Lead Developer · 2024 – 2026*
🍏 [App Store](https://apps.apple.com/us/app/octopush/id6711331710) · 🤖 [Google Play](https://play.google.com/store/apps/details?id=com.du.octopush)
Customer-conversation **messenger** for the Octopush (Marseille) multichannel/SMS platform: the team handles all customer conversations and live chat from one app, with push notifications — improving response time and customer relationships.
**Tech:** Flutter · adaptive_theme · flutter_libphonenumber + multi-formatter · dio + retrofit · Firebase Messaging · shimmer.

**Carter — Basketball club-management app** · *Lead Developer · 2022 – 2024*
🍏 [App Store](https://apps.apple.com/fr/app/carter-coaching/id6443718007) · 🤖 [Google Play](https://play.google.com/store/apps/details?id=com.du.carter)
Basketball app for **managers, coaches and players**: a team-management tool that saves time on season organisation — rosters, player positions, events, training sessions, attendance, standings, an exercise library and tactical boards — and boosts player progression through coach feedback and a **play-to-earn** gamified reward system, with club/team creation, individual coaching and subscriptions.
**Tech:** Flutter · dio + retrofit · Firebase Messaging + **Dynamic Links** · Google Maps + geocoding · **Socket.IO** (realtime) · pie_chart · scrollable_positioned_list.

**Beauty Squad — On-demand beauty booking** · *Sole Developer · 2024 – 2025*
📦 [apkcombo](https://apkcombo.com/beauty-squad/com.beautysquaduser/)
On-demand **at-home beauty** marketplace (client + salon): book experienced pros for hair, makeup, skincare, massage, nails, coaching and even a photographer; browse and filter services, multi-step booking & checkout (**Stripe / PayPal / wallet**), salon profiles, availability and galleries, with in-app chat — while pros manage their salon, services and schedule.
**Tech:** Flutter · date_picker_timeline · Firestore + Firebase Storage · Google Maps · flutter_stripe · PayPal · booking & chat modules.

**Mentalia — Mental-wellness app** · *Lead Developer · 2023 – 2024*
🤖 [Google Play](https://play.google.com/store/apps/details?id=com.mentalia.app) *(Digital Unicorn account)*
AI-powered **mental-preparation & well-being** app: chat with a caring **AI virtual coach** for constant support toward your goals; a question-driven flow suggests the right content from an audio, PDF and video library, and **generative-AI recommendations** evolve with your progress.
**Tech:** Flutter · just_audio (meditation audio) · Socket.IO + WebSocket (chat) · Syncfusion PDF viewer · animated_text_kit · Firebase Auth · dio + retrofit.

**Nila Sphere — Carbon-footprint tracker** · *Sole Developer · 2026*
🍏 [App Store](https://apps.apple.com/us/app/nila-sphere/id6754004164) · 🤖 [Google Play](https://play.google.com/store/apps/details?id=com.nilasphere.fr)
Carbon-footprint app for **carbon neutrality**: measure the CO₂ impact of daily tasks, track weekly emissions and a carbon score, complete **green challenges** to win partner gifts, discover greener consumption alternatives, and share eco achievements on a dedicated social feed — with environmental news and tips.
**Tech:** Flutter · **fl_chart** (impact visualizations) · camerawesome · AppsFlyer · RevenueCat · Lottie.

**Docteur Sirop — Children's health AI companion** · *Sole Developer · 2025 – 2026*
🤖 [Google Play](https://play.google.com/store/apps/details?id=com.doctorsyrup.app) *(Digital Unicorn account)*
AI health companion for **hospitalized children**: helps the child understand their hospital environment and care team through **real-time voice conversations with an AI doctor**, daily mood check-ins and questions, a relaxation *"espace zen"* and interactive stories, plus a reward system that makes the child an active participant in their care — also a communication tool with caregivers.
**Tech:** Flutter · **OpenAI Realtime (openai_core + openai_webrtc)** · speech_to_text + flutter_tts + just_audio (voice) · **flutter_embed_unity** (Unity 3D character) · dio + retrofit · Firebase Auth.

**Arage — Local events discovery** · *Sole Developer · 2024 – 2025*
📦 [apkcombo](https://apkcombo.com/arage/com.arage.app/)
Local-events app that connects you to your community: **discover events on an interactive map**, create and manage your own, follow upcoming regional events, filter and join in a few clicks, with attendee profiles, favourites and subscriptions.
**Tech:** Flutter · Google Maps + static maps · Firestore · auto_route, Provider, get_it · AppsFlyer · RevenueCat.

**Let Share — Student peer-to-peer sharing app** · *Core Contributor · 2026*
📦 [apkcombo](https://apkcombo.com/let-share/com.letshare.app/)
Student/community app to discover **local projects and initiatives** via a geolocated **swipe** feed: create fully-customised projects (title, photos, theme), approve participants manually, and chat in real time (group & private) — with push notifications and report/block moderation.
**Tech:** Flutter · auto_route, Provider, get_it · dio + retrofit · Firebase · Google Maps · **Socket.IO** (chat) · wechat_assets_picker · stylish_bottom_bar · RevenueCat.

**Spaurt — Sports-training app** · *Sole Developer · 2025 – 2026*
🍏 [App Store](https://apps.apple.com/fr/app/spaurt/id6743203018) · 🤖 [Google Play](https://play.google.com/store/apps/details?id=com.spaurt.app)
Hybrid **sports-training** app with personalized coaching built around four pillars (strength, body control, endurance, conditioning): personalized rep- and time-based **workout routines**, a routine library, **1-rep-max & personal-record** tracking, physical tests, goals and statistics, calendar scheduling, session badges and rewards.
**Tech:** Flutter · fl_chart + sleek_circular_slider (stats) · qr_flutter · calendar_date_picker2 · tutorial_coach_mark · in_app_review · just_audio.

### 🧩 Additional client apps & contributions

**Swy'Eat — Restaurant-review social network** · *Lead Developer · 2022 – 2026 · launching on iOS & Android*
A **social network of certified restaurant reviews**: restaurant & chef profiles with menus, geo/photo-authenticated reviews (*avis*), a social feed (posts, comments, follows), **recipe contests**, a leaderboard with points & gifts, **KBIS** business verification for restaurants, and a map.
**Tech:** Flutter · dio + retrofit + pretty_dio_logger · Firebase Auth + Google/Apple/**Facebook** sign-in · Google Maps + static maps + geolocator · rating bar · photo_view · Syncfusion PDF viewer · reorderables · camerawesome · AppsFlyer.

**Kimia — Peer-to-peer travel-deal marketplace** · *Sole Developer · 2024 – 2026*
Marketplace connecting **travellers and requesters**: travellers post trips while others post item/delivery requests and negotiate **deals**, with bookings, in-app payments, a wallet, chat, reviews and map search.
**Tech:** Flutter · **flutter_stripe** · Cloud Firestore · Google Maps + geocoding · image_cropper · App Tracking Transparency · AppsFlyer · dio + retrofit.

**UAVLog — Drone flight logbook** · *Sole Developer · 2024 – 2025*
Drone/UAV flight logbook: **create, start and end missions**, attach mission documents, record flights, check weather and handle payments — with offline storage.
**Tech:** Flutter · Google Maps + location + geocoding · **Hive** (offline DB) · audio_waveforms + just_audio · torch_light · vibration · RevenueCat · dio + retrofit.

**Live-streaming social network** · *Mobile Developer (team) · 2024 – 2025*
Social-community app: **create and join communities** with boards and posts, leaderboards and members, an activities feed, inbox messaging, and **live video streaming** with a built-in player.
**Tech:** Flutter · **GetX + injectable** (clean architecture) · **Agora RTC + RTM + Chat SDK** (live stream & realtime chat) · easy_localization · pro_image_editor · WeChat asset/camera pickers · chewie · Firebase.

**Event — Event-management app** · *Sole Developer · 2022 – 2024*
Event app: **create events and manage participants**, invite members from phone contacts, share event **photo/video galleries**, comment, and browse by category.
**Tech:** Flutter · Firebase **Dynamic Links** · flutter_contacts · flutter_downloader + gal · chewie + video_player · image_editor · extended_image/text.

**Âmes Sœurs — Local dating / matchmaking** · *Contributor · 2024 – 2025*
Local French dating app with verified profiles, video presentations and map-based discovery.
**Tech:** Flutter · **GetX + Stacked** · Google Maps + **cluster manager** + custom markers · calendar_view · **Branch** deep links · RevenueCat · Firebase + Firestore.

**Barberz — Barbershop booking platform (customer + pro)** · *Contributor · 2024 – 2025*
Two-sided barber/salon booking platform: browse **e-services by category**, book & checkout, manage favourites, salon profiles and galleries, maps, messaging, ratings and wallet.
**Tech:** Flutter · **GetX** (get/get_storage) · dio + http cache · Firebase + Firestore + Storage · Google Maps + place picker · carousel · OTP.

**ShapeUp — On-demand hairdresser booking** · *Contributor · 2025 – 2026*
On-demand hairdresser booking (**client + pro**): book stylists with **hair preferences & styles**, multi-step booking & scheduling, **Stripe payments**, **KYC** pro onboarding, availability, earnings and ratings.
**Tech:** Flutter · SignalR (realtime) · Cloud Firestore · Google Maps · flutter_stripe · KYC webview · confetti.

**ard — Mosquito-surveillance / public-health app** · *Sole Developer · 2026*
Community public-health app for mosquito-borne disease prevention: **report mosquito breeding sites and incidents on a map**, set reminders, take surveys, and follow a community forum, news and training calendar.
**Tech:** Flutter · **SignalR + Socket.IO** (realtime) · Google Maps · photo_view · AppsFlyer · dio + retrofit.

**Adress — Visitor / enterprise app** · *Contributor · 2025 – 2026*
Visitor/enterprise app with **enterprise, guest and visitor modes**: explore venues, make bookings/reservations, keep an address book (*carnet*) and notes, chat, and pay in-app — with **QR & ID-card scanning**.
**Tech:** Flutter · mobile_scanner (QR) · flutter_cardidy (card scan) · Firebase Realtime DB · record + just_audio + audio_service · bottom_picker.

**Dear — Couple / relationship app** · *Contributor · 2025*
Relationship app: shared calendar, milestones and photos.
**Tech:** Flutter · table_calendar · phone_form_field + pinput · scroll_datetime_picker · Google Maps · animations + confetti.

**Sentinelle — Safety app** · *Sole Developer · 2024 – 2026*
Safety / surveillance app (early-stage) with a home dashboard, notifications and account flows, built on the in-house Flutter base.
**Tech:** Flutter · camera · Google Maps + geocoding + geolocator · dio + retrofit · Firebase.

### 🧪 Independent / personal projects (pre–Digital Unicorn)

**Medical / clinic management app** · *Independent · 2021 – 2022* · 💻 GitHub `Bow-T/ykhoa_app`
Personal Flutter project — a medical / clinic management app (Vietnamese *"y khoa"*) built on a self-made MVVM base.
**Tech:** Flutter · MVVM · REST.

---

## Education

**Software Engineering** — Duy Tan University, Da Nang, Vietnam · 2015 – 2019

---

<sub>Store links verified via App Store / Google Play; download figures from Google Play. Project features described from each app's source.</sub>