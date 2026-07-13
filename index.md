# Bloom Privacy Policy

**Effective date: July 13, 2026**

Bloom is a mental-wellness app for teens. This policy explains, in plain language, what data the app handles, where that data lives, and how to delete it.

The short version: **everything you put into Bloom stays on your device. We don't collect it, we can't see it, and we never send it anywhere.**

---

## What data the app stores

Bloom stores the following **only on your device**:

- **Mood check-ins** — the emoji you pick and any note you write
- **Journal entries** and comments you add to them, whether typed or spoken
- **Affirmations** you save, favorite, or accept from suggestions
- **Goals** and their progress
- **Trusted contacts** — names, relationships, phone numbers, email addresses, and notes you enter or pick from your contacts
- **Saved resources** and your star ratings on exercises and suggestions, which the app uses on-device to personalize future recommendations
- **Topics detected in your notes** (like "stress" or "sleep") so the app can spot patterns and suggest resources
- **Your settings** — age group, school, theme, reminder times, and similar preferences

None of this is uploaded, synced, backed up by us, or shared with anyone. We have no servers, no accounts, and no way to access anything you write.

## What we collect

**Nothing.** Bloom has no sign-up, no account, and no analytics. We do not collect, receive, or store any information about you or your use of the app — not your name, not your entries, not even anonymous usage statistics.

## Analytics and crash reporting

**We use none.** Bloom contains no analytics or crash-reporting services — no Firebase, no Sentry, no Crashlytics, no Mixpanel, nothing similar. The app makes no network requests of its own.

## How the app processes your data — all on your device

Bloom does some smart things with what you write, and all of it happens locally using Apple's on-device frameworks:

- **Understanding your notes** — keyword matching, sentence meaning (embeddings), and sentiment analysis run entirely on your device to suggest relevant resources.
- **Crisis detection** — if what you write suggests you may be in crisis, Bloom shows crisis resources. This runs entirely on your device using a fixed, deterministic set of word and phrase rules — the same input always produces the same result, and no learning or profiling is involved. For journal entries it is optional and off by default (Settings → "Analyze journal entries for crisis detection"); for mood check-in notes it is always on, because your safety comes first. Bloom is not therapy or counseling, and detection results never leave your phone.
- **Voice transcription** — when you use voice journaling, your speech is transcribed **on your device** by iOS. Your voice audio is never sent to any server, including Apple's. On the rare device that can't transcribe locally, voice journaling is simply unavailable — we never fall back to a server.
- **Face ID / Touch ID lock** — handled entirely by iOS. Bloom only learns "unlocked or not"; it never sees or stores biometric data.

## Permissions we ask for

Bloom only requests a permission at the moment a feature needs it, and every feature still works without granting it (aside from the feature itself). iOS controls these, and you can change them anytime in iOS Settings.

- **Microphone** — to record your voice for voice journaling.
- **Speech recognition** — to transcribe that voice into text, on your device.
- **Face ID / Touch ID** — to optionally lock the app.
- **Notifications** — to send the reminders described below.
- **Contacts** — only if you choose to pick a trusted contact from your address book. Bloom uses Apple's contact picker, so it never reads your contacts; iOS simply hands back the one person you select.

## When you leave the app

A few features hand you off to things outside Bloom, always at your explicit request:

- **External websites** — resource links open those organizations' websites. Like any website, they can see your IP address and use their own cookies. Their privacy policies apply to what happens there.
- **Calling, texting, and emailing** — tapping a call/text/email button for a crisis line or trusted contact opens your phone, Messages, or mail app. Bloom just passes the number or address along.
- **Sharing a resource** — the share button sends the resource's name and contact info through the iOS share sheet to whatever app you choose.

## Notifications

Reminders (affirmations, daily check-in nudges, and next-day check-ins after a hard day) are scheduled locally on your device. Note that notification text — including affirmation wording — can appear on your lock screen; you can control this in iOS Settings → Notifications.

## Children's privacy

Bloom is designed for teens, and some users may be under 13. Because Bloom collects **no personal information from anyone** — child or adult — no personal data from children is ever gathered, stored by us, or shared. Everything stays on the device the app is installed on.

## Deleting your data

You're always one step from a full wipe:

- **Delete everything**: Settings → **Clear All Data**. This erases every check-in, journal entry, affirmation, goal, trusted contact, saved resource, and setting, and cancels scheduled reminders. It cannot be undone.
- **Delete individual items**: swipe or long-press to remove single journal entries, goals, affirmations, contacts, or saved resources.
- **Delete the app**: removing Bloom from your device also removes all of its data.

Because we never receive your data, there is nothing for us to delete on any server — and nothing we could hand over to anyone else.

## Security

Your data is protected by your device's built-in encryption. You can additionally require Face ID / Touch ID to open Bloom (offered on first journal use, or in Settings → Privacy).

## Changes to this policy

If Bloom's data practices ever change — for example, if a future feature needs a network connection — we will update this policy, change the effective date above, and explain the change in plain language before it applies to you.

## Contact

Questions about privacy? Email us at **bloom.app.inquiries@gmail.com**.
