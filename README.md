This repository contains two complementary Android applications designed to provide a secure, highly customizable, and controlled browsing environment: **SafeSurf** (a content-filtering browser) and **Safeguard** (a system-level enforcement tool).

---

## 🌐 SafeSurf

SafeSurf is a highly customizable WebView-based browser designed to give users granular control over their web traffic and content exposure.

### Key Features.
* **Multi-Format Support:** Capable of blocking various content types including videos, audio, fonts, text, scripts, and applications, with sub-type granularity.
* **Global & Site-Specific Rules:** * Define global rules to allow or block specific types of content across all websites.
  * Create site-specific rules to override global rules, allowing users to exclude specific file types or whitelist entire websites.
* **Advanced URL Filtering:** Capable of blocking a primary domain (e.g., youtube.com) while allowing access to a specific sub-URL, such as a particular video.
* **Modification Protection:** Any modifications to rules or categories are protected by a user-defined time delay or require real-time approval from a designated sponsor via WhatsApp.

<img src="https://github.com/user-attachments/assets/713ad2a5-0c15-42f9-8d93-af6b2f3f1007" width="300">
<img src="https://github.com/user-attachments/assets/6db0cd7a-0543-4baf-802b-3280f2d00bbf" width="300">
<img src="https://github.com/user-attachments/assets/c9a6bc60-7939-42ba-9613-d7f2042c4331" width="300">
<img src="https://github.com/user-attachments/assets/5178f675-90d0-4701-aa7f-1e6ba3a2af67" width="300">
<img src="https://github.com/user-attachments/assets/2f03ee22-8d34-4555-8203-50c16f8ef2ad" width="300">
<img src="https://github.com/user-attachments/assets/99632798-c4cd-4c14-84ca-1486a1ce6d7f" width="300">
<img src="https://github.com/user-attachments/assets/684ecd36-c827-4ea6-b910-ee4e69d30371" width="300">
<img src="https://github.com/user-attachments/assets/d19cf0a5-d60b-4ad7-b036-b8f076f1b36c" width="300">
<img src="https://github.com/user-attachments/assets/c9499fe9-3867-4a54-a9c9-b09e4fc64ec0" width="300">

---

## 🛡️ Safeguard

Safeguard acts as a companion and enforcement utility for SafeSurf, ensuring that the browsing rules cannot be bypassed or compromised.

### Key Features
* **Internal Browser Blocking:** Blocks access to internal browsers (WebViews) within applications selected by the user, and can suspend apps entirely to prevent access.
* **Browser Enforcement:** Actively blocks all other web browsers on the device to ensure that SafeSurf remains the only gateway to the internet.
* **Active Monitoring:** Continuously monitors for newly installed applications and blocks them immediately to prevent the installation of unauthorized browsers.
* **Advanced System-Level Restrictions:** Includes protections against device modifications:
  * Time and date lock
  * Global VPN lock & App-specific VPN lock
  * Hotspot or USB internet sharing lock
  * Network reset prevention
  * Safe boot lock
  * Factory reset lock
  * FRP (Factory Reset Protection) lock
  * Developer options lock
* **Modification Protection:** Making changes within Safeguard requires waiting out a user-defined time delay or entering a predetermined password.
* **Sponsor Override:** Similar to SafeSurf, actions that require a time delay can be expedited by obtaining immediate approval from a sponsor.
<img src="https://github.com/user-attachments/assets/2116c911-b9b8-4987-90d9-e4391799914d" width="300">
<img src="https://github.com/user-attachments/assets/2f921dc3-8df2-41da-bc77-c512c3262453" width="300">
<img src="https://github.com/user-attachments/assets/68dbe75c-987d-413e-aed8-6fe0d2b073a1" width="300">
<img src="https://github.com/user-attachments/assets/49fa1ea6-c209-49ed-8966-f9d66c8f503e" width="300">

