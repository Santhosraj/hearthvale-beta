# Hearthvale beta

Hearthvale is a habit app with a household of five assistants who look after you: **Arin** (sleep), **Dev** (fitness and food), **Kai** (focus and tasks), **Mira** (money) and **Liam** (calendar and mail). They track how your day is going, nudge you at the right moment, and talk among themselves about what you do.

You're one of a handful of friends trying it early. Thank you! Expect rough edges, and please tell me about them.

## ⬇️ [Download Hearthvale for Android](https://github.com/Santhosraj/hearthvale-beta/releases/latest/download/hearthvale.apk)

One tap downloads the newest version. Then open it and tap **Install**.

## Install (Android 8 or newer)

1. On your phone, tap **[Download Hearthvale](https://github.com/Santhosraj/hearthvale-beta/releases/latest/download/hearthvale.apk)** (or open the [latest release](https://github.com/Santhosraj/hearthvale-beta/releases/latest) and tap `hearthvale.apk`).
2. Open the downloaded file. Android will ask you to allow installs from your browser (or WhatsApp, Files…): tap **Settings → Allow from this source**, go back, and tap **Install**.
3. If Play Protect says it doesn't recognise the app, tap **More details → Install anyway**. It's not on the Play Store yet, so Google hasn't seen it.

**Updates:** when there's a new version, the app tells you on Home ("Hearthvale 0.x is out"). Tap **Update**, then install it over the old one. Nothing is lost.

## Getting started

1. **Sign up** with your email and confirm it from the email you get.
   > **Can't find the email?** Hearthvale's emails (the sign-up confirmation and the password-reset code) often land in **Spam**, or in Gmail's **Promotions** or **Updates** tabs. Look there, and tap **Not spam** so the next one arrives in your inbox. The same goes for **Forgot password** on the sign-in screen.
2. **Meet your household**: rename them, or keep the defaults.
3. Enter the **invite code** I gave you. It's needed to set up your household.
4. **Let them see what they need.** Each one asks for its own permission and says why. Everything is optional, and you can change it later in Settings.

| Permission | Who uses it | What for |
|---|---|---|
| Health Connect | Arin, Dev | Sleep, steps and workouts (read only) |
| Usage access | Kai, Arin | Screen time by kind of app, late-night phone use |
| Notifications | Everyone | Reminders and nudges |
| Alarms & reminders | Everyone | So reminders come on the minute |
| SMS, notification access | Mira | Automatic money tracking from bank texts and payment apps (optional) |
| Calendar | Liam | Today's events and meeting reminders |

## Make reminders reliable (important)

Most phones stop apps in the background to save battery, which makes reminders late or silent. After setup:

- **In the app:** Settings → **Reminders with the app closed** → follow the checklist (it opens the right screens for you).
- **vivo / iQOO:** Settings → Battery → Background power consumption → Hearthvale → **Allow**. Also: Settings → Apps → Hearthvale → **Autostart on**.
- **Xiaomi / Redmi / POCO:** Settings → Apps → Hearthvale → **Autostart on**, Battery saver → **No restrictions**.
- **Samsung:** Settings → Apps → Hearthvale → Battery → **Unrestricted**.
- **OnePlus / Oppo / Realme:** Settings → Battery → Hearthvale → **Allow background activity**.

## Tell me what's wrong

- **In the app:** Settings → **Send feedback**. It sends your note with the app version and your phone's Android version.
- **Screenshots:** send them to me on WhatsApp. They're the fastest way to show me what you see.

Useful things to mention: what you did, what you expected, what happened instead, and roughly when.

## Your data

- The full policy: **[hearthvale-api.onrender.com/privacy](https://hearthvale-api.onrender.com/privacy)**.
- In short: the server gets daily totals, not raw health records, and never which apps you used. Payment texts and emails are read on your phone; only each payment's amount, payee, category and time are sent, and nothing from your mail.
- The assistants are written by Google's Gemini API. During the beta it's on a plan where **Google may use what's sent to improve its products**. What's sent is only what a reply needs (your message, the day's numbers, the meal you describe).
- **Settings → Delete account** deletes your account and everything in it, straight away.

## Known rough edges

- The first open of the day can take up to a minute while the server wakes up.
- Sleep comes from Health Connect when your phone's health app shares it; otherwise Hearthvale estimates it from when your phone wasn't used overnight.
- Screen time may differ a little from your phone's own count.

---

The app's source isn't public. This page only hosts the installable APKs.
