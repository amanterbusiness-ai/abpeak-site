---
layout: default
title: Privacy
lang: en
---
# Privacy policy

Draft – replaced by the reviewed version before launch.

## Controller

- Name: Giuseppe Tringale
- Address: Sperberweg 2c, 31224 Peine, Germany
- Email: support@abpeak.app

## What stays on your device

The app stores your profile, your scans with photos and results, and your workouts on your device, protected by iOS file encryption (File Protection). They are part of your device backup, for example in your own iCloud. This includes your training answers (goal, experience, equipment, time choice) and your test results (plank time, dead-bug answer); they are stored only on your device (and are part of your backup) and are not transmitted to our servers. If you connect Apple Health, the app reads your weight there and saves your workouts; this is optional.

## Camera coach (optional)

The camera coach is off by default and starts only when you switch it on yourself and camera access is allowed. Apple Vision detects body points live on your device to count repetitions and give posture hints. The camera frames are held only in memory to compute the grid. Nothing is saved or uploaded, not even to our servers.

## Scan analysis

For the analysis, the app crops your face off on the device and sends only the image of your torso to a Supabase function in Frankfurt. From there it goes to Google Gemini via Vertex AI in the EU; the photo is not stored. The server keeps the analysis result of your own scan for up to 24 hours so that uploading the same photo again returns the same answer without charging the scan again (replay protection). Once the 24 hours are over, the server deletes it automatically. The legal basis is your explicit consent under Art. 9(2)(a) GDPR, which you can withdraw anytime in Settings.

## Anonymous sign-in and scan quota

At first launch the app signs you in without a name or email, using a random user ID. The server counts your scans for this ID so that the scan quota is kept (Art. 6(1)(b) GDPR, performance of a contract). Without a subscription 1 scan in total is included; with Pro it is 1 scan per day (by UTC calendar day).

## Guest scan

With Pro and guest-scan credit (purchased or gifted through a friend code) you can run a scan for another person. This processes that other person's photo and answers. The person confirms on your device that they are at least 16 years old and gives the explicit consent under Art. 9(2)(a) GDPR themselves. The analysis works like your own scan (Supabase function in Frankfurt, Google Gemini via Vertex AI in the EU). Neither your device nor the server stores the guest's photo, answers or result, and guest results are never kept for replay. For each consumed guest scan the server stores only a counter row with your user ID and a timestamp (Art. 6(1)(b) GDPR, performance of a contract with you). Each guest attempt also counts toward your own daily attempts. The controller named above is also responsible for the guest's data. The guest can decline or stop before the photo is sent and can contact support@abpeak.app.

## Friend code

With a friend code we pseudonymously link two anonymous app accounts (user ID of the referrer and the referred person, timestamps, granted guest scans) to give out the reward (Art. 6(1)(b) GDPR, performance of a contract). This includes your friend code (6 characters), which we store with your user ID even if nobody redeems it, and the time of the reward. This data is deleted when the anonymous account is deleted. “Delete all data” in the app removes the data on your device and immediately deletes the scan results held on the server. Scan counters, guest-scan and friend-code data and the anonymous server account stay. You can request deletion of the server data by email to support@abpeak.app.

## Purchases

You buy and pay for subscriptions through Apple. RevenueCat manages your subscription status and receives your random user ID for this. Apple's standard terms (EULA) apply. Purchased guest scans do not expire and are not transferable. Refunds go through Apple's process.

## Usage statistics

We use TelemetryDeck to count how the app is used, without personal data and without tracking.

## Retention

The data on your device stays until you remove it with “Delete all data” or delete the app. The server does not store the photo of a scan; it keeps the result of your own scan for up to 24 hours and then deletes it automatically (see Scan analysis). “Delete all data” deletes it on the server immediately if the device is online at that moment. The user ID and the scan counter are kept as long as you use AbPeak; on request via support@abpeak.app we delete them. Guest-scan counter rows, granted credits and friend-code data are kept until the anonymous account is deleted (deletion on request via support@abpeak.app).

## This website

The website abpeak.app is served via GitHub Pages (GitHub, Inc., 88 Colin P. Kelly Jr. Street, San Francisco, CA 94107, USA). When you open it, GitHub processes technically necessary data, in particular your IP address, date and time and browser details, to deliver the page and protect it against abuse. The legal basis is our legitimate interest in a secure and stable service (Art. 6(1)(f) GDPR). Data may be transferred to the USA. Details: [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). The website sets no cookies, uses no tracking and loads no third-party content.

## Your rights

Under the GDPR you have these rights:

- Access to your data (Art. 15 GDPR)
- Rectification of inaccurate data (Art. 16 GDPR)
- Erasure (Art. 17 GDPR)
- Restriction of processing (Art. 18 GDPR)
- Data portability (Art. 20 GDPR)
- Objection to processing (Art. 21 GDPR)
- Withdrawal of a consent with effect for the future (Art. 7(3) GDPR), including the explicit consent to the processing of health data under Art. 9(2)(a) GDPR. You withdraw it in Settings; processing carried out until then stays lawful.
- Lodging a complaint with a data protection supervisory authority (Art. 77 GDPR)

You delete the data on your device and the scan results held on the server yourself with “Delete all data” in Settings. If the device is offline at that moment, the app still deletes everything on the device and tells you that deleting on the server did not work; the server then deletes the result by itself after 24 hours at the latest, or you write to support@abpeak.app. For all other rights, write to support@abpeak.app.
