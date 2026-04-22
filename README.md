<div align="center">

# Patryk Neubauer
### iOS Developer · Swift · SwiftUI

[![Email](https://img.shields.io/badge/patrykneubauerdev%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:patrykneubauerdev@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/patryk-neubauer)
&nbsp;
[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat&logo=app-store&logoColor=white)](https://apps.apple.com/pl/app/eksplorator/id6744850338)
&nbsp;
[![CV / Resume](https://img.shields.io/badge/CV_%2F_Resume-7C3AED?style=flat&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/patrykneubauerdev/patryk-neubauer-ios-portfolio/main/assets-patryk-neubauer-ios-portfolio/CV_Neubauer_Patryk_ENG.pdf)

</div>

---

I build iOS apps in Swift and SwiftUI - clean architecture, thoughtful UX, and a focus on solving real problems. From AI-driven content moderation to real-time databases, I work with whatever the project calls for.

---

## Projects

> 💡 Click any project title to explore the full repository - source code, screenshots, and full tech breakdown.

---

### <img src="https://raw.githubusercontent.com/patrykneubauerdev/Eksplorator/main/eksplorator-repo-assets/eksplorator-icon-repo.png" width="36" valign="middle"> &nbsp;[Eksplorator](https://github.com/patrykneubauerdev/Eksplorator) &nbsp;[![App Store](https://img.shields.io/badge/Live_on_App_Store-0D96F6?style=flat&logo=app-store&logoColor=white)](https://apps.apple.com/pl/app/eksplorator/id6744850338)

> Urbex discovery app - find, share, and explore abandoned places around the world.

A community-driven platform for urban explorers. Users browse a map of submitted locations, view coordinates and photos, save favourites, and contribute their own finds. Shipping a UGC app means content safety is non-negotiable - every submission goes through multiple layers of AI moderation before it ever reaches another user.

<p align="center">
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Eksplorator/main/eksplorator-repo-assets/iphone-screen-eksplorator-04.png" width="250" title="Browse locations">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Eksplorator/main/eksplorator-repo-assets/iphone-screen-eksplorator-07.png" width="250" title="Location detail">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Eksplorator/main/eksplorator-repo-assets/iphone-screen-eksplorator-09.png" width="250" title="Add a location">
</p>

<details>
<summary><b>Key features</b></summary>
<br>

- 🔐 **Auth with guest mode** - email/password, password reset via Firebase, guest access for App Store compliance
- 🏚️ **Browse & filter** - sortable grid of community-submitted urbex locations with like/dislike counts
- 📍 **Location detail** - full photo, GPS coordinates with Google Maps deep-link, active/inactive status
- ❤️ **Favourites** - save locations and manage them with a swipe-to-remove gesture
- ➕ **Submit your own** - name, description, city, country, coordinates, photo; capped at 5/day per device
- 🛡️ **Multi-layer AI moderation** - OpenAI for text, Google Vision API for images
- 🚩 **Report system** - community flagging for anything that slips through
- 👤 **Full profile tab** - account management, T&C, Privacy Policy, password change, account deletion

</details>

<details>
<summary><b>Tech stack</b></summary>
<br>

| Technology | Role |
|---|---|
| **Swift + SwiftUI** | Full codebase, declarative UI, native animations |
| **Firebase Auth** | Email/password, guest mode, password reset |
| **Firebase Firestore** | Real-time NoSQL database |
| **Firebase Storage** | Cloud storage for user-uploaded photos |
| **OpenAI API** | AI text moderation for usernames, names, descriptions |
| **Google Vision API** | AI image moderation - scans every uploaded photo |
| **URLSession + async/await** | Native HTTP networking, no third-party SDKs |

</details>

---

### <img src="https://raw.githubusercontent.com/patrykneubauerdev/Foodloop/main/foodloop-repo-assets/foodloop-icon-repo.png" width="36" valign="middle"> &nbsp;[Foodloop](https://github.com/patrykneubauerdev/Foodloop)

> Restaurant ordering app - browse the menu, pick your table, place your order.

A clean simulation of the in-restaurant ordering experience built in Swift and SwiftUI. You walk in, open the app, choose your table number, browse the menu, and place your order. Menu data loads from a local JSON file - no backend required. Built with full localization in 🇬🇧 English and 🇵🇱 Polish.

<p align="center">
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Foodloop/main/foodloop-repo-assets/iphone-screen-foodloop-06.gif" width="250" title="Table selection">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Foodloop/main/foodloop-repo-assets/iphone-screen-foodloop-02.png" width="250" title="Cart">&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/patrykneubauerdev/Foodloop/main/foodloop-repo-assets/iphone-screen-foodloop-05.gif" width="250" title="Order history">
</p>

<details>
<summary><b>Key features</b></summary>
<br>

- 🍔 **Menu browsing** - items and prices loaded from local `products.json`, no backend needed
- 🪑 **Table selection** - choose your table before placing an order
- 🛒 **Cart** - add items, review, confirm
- ✅ **Order placement** - sends a real HTTP request; JSON payload logged from httpbin.org's echo response
- 📋 **Order history** - all past orders persisted via SwiftData, survive app restarts
- 🌍 **Full localization** - English and Polish via `Localizable.xcstrings`

</details>

<details>
<summary><b>Tech stack</b></summary>
<br>

| Technology | Role |
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

💼 [linkedin.com/in/patryk-neubauer](https://www.linkedin.com/in/patryk-neubauer)

---

<a href="https://raw.githubusercontent.com/patrykneubauerdev/patryk-neubauer-ios-portfolio/main/assets-patryk-neubauer-ios-portfolio/CV_Neubauer_Patryk_ENG.pdf"><img src="https://img.shields.io/badge/Download_CV_%2F_Resume-7C3AED?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"></a>

---

<div align="center">
  Thanks for stopping by - feel free to reach out! 👋
</div>
