# Privacy Policy

_Last updated: 2026-06-12_

This policy explains what data **Merciless Studio** games collect, why, and
what choices you have. It applies to all apps published under the Merciless
Studio developer account on Google Play.

Publisher: **Merciless Studio** — contact: yeminghuang.lakeforest@gmail.com

---

## GeoDaily

### What we collect

- **Game progress.** Your daily puzzle results (guesses, streaks, wins)
  serialised as JSON for cross-device save sync.
- **Anonymous account identifier (Firebase UID).** When you sign in,
  Firebase Authentication issues a random string ID tied to your device
  install, not to your real identity.

We do **not** collect: real name, email address, phone number, location,
device contacts, photos, advertising ID, or purchase history.

### Where it's stored

- Locally on your device
- In **Google Cloud Firestore**, keyed by your Firebase UID

Traffic between the app and Firestore is encrypted with TLS.

### How we use it

Exclusively to sync your game progress across devices. We do not sell,
rent, or share your data with third parties. We do not profile users, show
ads, or run analytics.

## Mind the Gap

### What we collect

We collect only what's needed to save your game and let you resume it on
the same device (or on another device if you sign in with Google).

- **Anonymous account identifier (Firebase UID).** When you first launch the
  app, Firebase Authentication issues a random string ID. This ID is tied
  to your device install, not to your real identity.
- **Google account identifier (optional, Android only).** If you sign in
  with Google, we store the UID Firebase gives us for that account so your
  save can follow you across devices. We do **not** read your email, name,
  profile picture, or Google contacts.
- **Game save state.** Your in-game cash, inventory, day, location, and
  similar gameplay values, serialised as JSON. No personal information
  appears in this payload.

### Where it's stored

- Locally on your device
- In **Google Cloud Firestore**, keyed by your Firebase UID

Traffic between the app and Firestore is encrypted with TLS.

### How we use it

Exclusively to save and load your game. We do not sell, rent, or share your
data with third parties. We do not profile users, show ads, or run
analytics.

### Who has access

- **You**, via the app signed into your UID
- **Google / Firebase**, as the infrastructure provider — their handling is
  governed by [Google's Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice)
- **The developer**, only via Firebase Console for debugging and abuse
  investigation

### Retention

Save data remains in Firestore until you delete it. Deleting your save in
the app removes the cloud copy.

---

## Dungeon Doom Dash

Dungeon Doom Dash does **not** collect, store, or transmit any personal
data. All game state stays entirely on your device. No accounts, no
servers, no network calls during gameplay. No analytics, no advertising, no
tracking of any kind.

---

## Your rights across all games

To delete any cloud data tied to your install, email
**yeminghuang.lakeforest@gmail.com**.

Residents of the EU/UK (GDPR) and California (CCPA) have additional rights
to access, correct, and delete their data. Email the address above and we
will respond within 30 days.

## Children

Our apps are rated for ages 13+. We do not knowingly collect data from
children under 13. If you believe a child has used our apps, contact us and
we will delete any associated data.

## Changes

Material changes to this policy will be published at the URL where you
found this document, with an updated "Last updated" date at the top.
