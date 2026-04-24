# Privacy Policy — Mind the Gap

_Last updated: 2026-04-20_

This policy explains what data **Mind the Gap** (the "App") collects, why,
and what choices you have.

Publisher: **Merciless Studio** — contact: yeminghuang.lakeforest@gmail.com

---

## What we collect

We collect only what's needed to save your game and let you resume it on the
same device (or on another device if you sign in with Google).

- **Anonymous account identifier (Firebase UID).** When you first launch the
  App, Firebase Authentication issues a random string ID. This ID is tied
  to your device install, not to your real identity.
- **Google account identifier (optional, Android only).** If you sign in
  with Google, we store the UID Firebase gives us for that account so your
  save can follow you across devices. We do **not** read your email, name,
  profile picture, or Google contacts.
- **Game save state.** Your in-game cash, inventory, day, location, and
  similar gameplay values, serialised as JSON. No personal information
  appears in this payload.

We do **not** collect: real name, email address, phone number, location,
device contacts, photos, microphone, camera, advertising ID, purchase
history, or any analytics or telemetry.

## Where it's stored

- Locally on your device (browser localStorage or Android app storage)
- In **Google Cloud Firestore**, keyed by your Firebase UID, at a document
  only your authenticated session can read or write

Traffic between the App and Firestore is encrypted with TLS.

## How we use it

Exclusively to save and load your game. We do not sell, rent, or share your
data with third parties. We do not profile users, show ads, or run
analytics.

## Who has access

- **You**, via the App signed into your UID
- **Google / Firebase**, as the infrastructure provider — their handling is
  governed by [Google's Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice)
- **The developer**, only via Firebase Console for debugging and abuse
  investigation

No advertising networks, analytics providers, or other third parties
receive your data.

## Retention

Save data remains in Firestore until you delete it. Deleting your save in
the App (or finishing a run — the App deletes the save automatically at
game-over) removes the cloud copy.

## Your rights

To delete all cloud data tied to your install, email
**yeminghuang.lakeforest@gmail.com** with the Firebase UID shown in the
App's avatar modal, or uninstall the App after finishing a run.

Residents of the EU/UK (GDPR) and California (CCPA) have additional rights
to access, correct, and delete their data. Email the address above and we
will respond within 30 days.

## Children

The App is rated for ages 13+. We do not knowingly collect data from
children under 13. If you believe a child has used the App, contact us and
we will delete any associated data.

## Changes

Material changes to this policy will be published at the URL where you
found this document, with an updated "Last updated" date at the top.
