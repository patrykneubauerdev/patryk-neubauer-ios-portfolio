<div align="center">

# Patryk Neubauer
### iOS Developer · Swift · Firebase · AI Integration

[![Email](https://img.shields.io/badge/patrykneubauerdev%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:patrykneubauerdev@gmail.com)
&nbsp;
[![Swift](https://img.shields.io/badge/Swift-F54A2A?style=flat&logo=swift&logoColor=white)](#)
&nbsp;
[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat&logo=app-store&logoColor=white)](https://apps.apple.com/pl/app/eksplorator/id6744850338)

</div>

---

I build native iOS apps entirely in Swift — no shortcuts, no bridges. My focus is on clean architecture, thoughtful UX, and solving real problems like content moderation and user trust in UGC apps.

---

## Projects

---

### [Eksplorator](https://github.com/patrykneubauerdev/Eksplorator) &nbsp;[![App Store](https://img.shields.io/badge/Live_on_App_Store-0D96F6?style=flat&logo=app-store&logoColor=white)](https://apps.apple.com/pl/app/eksplorator/id6744850338)

> Urbex discovery app — find, share, and explore abandoned places around the world.

A community-driven platform for urban explorers. Users browse a map of submitted locations, view coordinates and photos, save favourites, and contribute their own finds. Shipping a UGC app means content safety is non-negotiable — every submission goes through multiple layers of AI moderation before it ever reaches another user.

<p align="center">
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Eksplorator/main/eksplorator-repo-assets/iphone-screen-eksplorator-04.png" width="220" title="Browse locations">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Eksplorator/main/eksplorator-repo-assets/iphone-screen-eksplorator-05.png" width="220" title="Location detail">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Eksplorator/main/eksplorator-repo-assets/iphone-screen-eksplorator-08.png" width="220" title="Add a location">
</p>

<details>
<summary><b>Key features</b></summary>
<br>

- 🔐 **Auth with guest mode** — email/password, password reset via Firebase, guest access for App Store compliance
- 🏚️ **Browse & filter** — sortable grid of community-submitted urbex locations with like/dislike counts
- 📍 **Location detail** — full photo, GPS coordinates with Google Maps deep-link, active/inactive status
- ❤️ **Favourites** — save locations with swipe-to-remove gesture
- ➕ **Submit your own** — name, description, city, country, coordinates, photo; capped at 5/day per device
- 🛡️ **Multi-layer AI moderation** — OpenAI for text, Google Vision API for images
- 🚩 **Report system** — community flagging for anything that slips through
- 👤 **Full profile tab** — account management, T&C, Privacy Policy, password change, account deletion

</details>

<details>
<summary><b>Tech stack</b></summary>
<br>

| | |
|---|---|
| **Swift + SwiftUI** | Full codebase, declarative UI, native animations |
| **Firebase Auth** | Email/password, guest mode, password reset |
| **Firebase Firestore** | Real-time NoSQL database |
| **Firebase Storage** | Cloud storage for user-uploaded photos |
| **OpenAI API** | AI text moderation for usernames, names, descriptions |
| **Google Vision API** | AI image moderation — scans every uploaded photo |
| **URLSession + async/await** | Native HTTP networking, no third-party SDKs |

</details>

---

### [Foodloop](https://github.com/patrykneubauerdev/Foodloop)

> Restaurant ordering app — browse the menu, pick your table, place your order.

A clean simulation of the in-restaurant ordering experience, built entirely in Swift with zero external dependencies. You walk in, open the app, choose your table number, browse the menu, and place your order. Menu data loads from a local JSON file — no backend required. Built with full localization in 🇬🇧 English and 🇵🇱 Polish.

<p align="center">
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Foodloop/main/foodloop-repo-assets/iphone-screen-foodloop-01.png" width="220" title="Table selection">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Foodloop/main/foodloop-repo-assets/iphone-screen-foodloop-02.png" width="220" title="Cart">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Foodloop/main/foodloop-repo-assets/iphone-screen-foodloop-04.png" width="220" title="Order history">
</p>

<details>
<summary><b>Key features</b></summary>
<br>

- 🍔 **Menu browsing** — items and prices loaded from local `products.json`, no backend needed
- 🪑 **Table selection** — choose your table before placing an order
- 🛒 **Cart** — add items, review, confirm
- ✅ **Order placement** — sends a real HTTP request; JSON payload logged from httpbin.org's echo response
- 📋 **Order history** — all past orders persisted via SwiftData, survive app restarts
- 🌍 **Full localization** — English and Polish via `Localizable.xcstrings`

</details>

<details>
<summary><b>Tech stack</b></summary>
<br>

| | |
|---|---|
| **Swift + SwiftUI** | Full codebase, smooth native animations |
| **SwiftData** | On-device order history persistence |
| **URLSession + async/await** | Native HTTP networking |
| **httpbin.org** | Echo API stand-in for a real kitchen endpoint |
| **MVVM** | Clean separation of views, view models, models |
| **Localizable.xcstrings** | 🇬🇧 English & 🇵🇱 Polish |

</details>

---

## Contact

✉️ [patrykneubauerdev@gmail.com](mailto:patrykneubauerdev@gmail.com)

---

<div align="center">
  <sub>Built with Swift. No shortcuts.</sub>
</div>
