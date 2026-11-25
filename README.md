# Lore — Unified Communications (Dialer, SMS, Contacts, RCS)

Lore is an offline-first, privacy-focused Android communications hub unifying phone dialer, SMS/MMS messaging, contact management, and RCS messaging into a single clean app. Built with Kotlin, Jetpack Compose, and Material 3, Lore is designed to replace default carrier bloatware with a fast, ad-free, telemetry-free experience.

---

## 📞 Key Features & Subsystem Breakdown

### 📱 Phone Dialer & Call Manager (`dialer`)
- **Current**: In-call UI, speed dial, call log history, T9 contact searching, DTMF tone dialpad, and dual-SIM SIM selection.
- **Planned / Roadmap**: Local spam call blocker, call recording engine, visual voicemail, and custom ringtone per contact group.

### 💬 SMS & MMS Messaging (`sms`)
- **Current**: Full SMS/MMS thread view, media attachments (images, audio, video), group messaging, and conversation search.
- **Planned / Roadmap**: Scheduled messages, automatic OTP code copying with auto-delete option, message pinning, and archiver.

### 👤 Contact Manager & Address Book (`contacts`)
- **Current**: Contacts list, multi-account sync (Device, SIM, Google, DAVx5), contact details editor, and group tagging.
- **Planned / Roadmap**: Duplicate contact merger, vCard import/export, and smart contact interaction history.

---

## 🏗️ Architecture & Technology Stack

- **Platform**: Android 13+ (minSdk 33, targetSdk 37).
- **UI & Layout**: Kotlin, Jetpack Compose, Material 3, Android Telecom / Telephony APIs.
- **Database**: Room local database.
- **Licensing**: AGPL-3.0.

---

## 🛠️ Building & Running

```bash
./gradlew assembleDebug
./gradlew installDebug
```

---

## 📜 License

Lore is released under the **GNU Affero General Public License v3.0** (AGPL-3.0). See [`LICENSE`](LICENSE) for details.
