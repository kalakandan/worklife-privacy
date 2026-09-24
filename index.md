# Privacy Policy — Work & Life

**Last updated: 24 September 2026**
**Policy version: 1**

<!-- Policy version MUST match AdConsentPrefs.POLICY_VERSION in the app. The app compares the two:
     bump both together on a MATERIAL change (new data, new recipient, new purpose) and every user
     is re-asked to agree. Do NOT bump for typos or rewording — re-prompting for cosmetic edits
     trains people to tap through without reading, which destroys the consent you were documenting.
     2026-09-24: rewritten to match the shipped app exactly (checked against the manifest and code);
     no new data, recipient or purpose, so the version stays 1. -->

Work & Life ("the app") is a planner for shift and irregular-schedule workers. This policy explains,
in plain language, exactly what the app does with your information. It describes the app **as it is
today**. If that ever changes, this policy changes first, and for any material change you will be
asked to agree again inside the app before it continues.

## 1. Who makes the app, and what they can see

Work & Life is made and published by **Kalakandan**. There is no server and no cloud storage:
everything you enter stays on your phone and is never sent to the developer, who has no way to see
it.

The one thing that leaves your phone is the limited device data Google uses to show the ad banner
(section 4). Because the app includes that banner, its publisher is the responsible party for that
data under privacy law, and the person to contact about it.

Contact: **imkalakandan@gmail.com**

## 2. Short version

- Everything you enter stays **on your phone**. There are no accounts, no logins, no server and no
  cloud storage of ours. We cannot see your data, because we never receive it.
- The **only** reason the app uses the internet is to show one banner advertisement, served by
  **Google AdMob**.
- To show that ad, Google collects limited device data, described in full in section 4.
- The app asks you before any of that happens (section 8).
- The app contains **no** analytics, crash-reporting or tracking software. The only third-party
  software in it is Google's ad software.

## 3. What you enter, and where it lives

Everything you enter — your shift pattern, schedule changes, leave, notes, habits, tasks, spending,
pay settings, reminders and sleep preferences — is stored **only in the app's private storage on
your own phone**.

- The database holding it is **encrypted**, with the key kept in your phone's own secure key store.
- A small amount of app state sits alongside it without that extra layer, protected by Android's app
  sandbox instead: the answers you give during setup before you finish it, the details of an alarm
  you have snoozed, your app-lock and ad-consent choices, and a few housekeeping flags (for example,
  which "What's new" note you have already seen).
- The app keeps its own **local safety copy** of the database in its private folder, encrypted, so a
  failed update cannot wipe your data. It never leaves the phone.
- The app writes a small **local diagnostics log** (at most about 200 KB) when something goes wrong
  inside it. It records only the type of error, where in the app's code it happened, and the app
  version — never anything you typed, and no amounts, names or dates. It stays on the phone unless
  you choose to share it (section 12).

None of this is ever uploaded, because there is nowhere to upload it to. The app's backup rules
exclude all of it from Android's cloud backup and device-to-device transfer, so it does not travel
with your Google account either.

**If your phone's secure key store is unavailable** when the app starts (rare, usually after a system
fault), the app keeps working with reduced protection — the database may run unencrypted, or its key
may be kept without the key store's protection — and it tells you so in Settings → About. It
re-secures itself automatically once the key store recovers. Even then, nothing leaves the phone.

## 4. Information collected automatically (advertising only)

The app shows one banner ad, using **Google AdMob**. To select and measure that ad, Google's ad
software collects and processes:

- your device's **advertising ID** (a resettable identifier used for advertising);
- your **IP address**, from which an **approximate (city-level) location** can be inferred;
- basic **device information** (model, operating system version, language, screen size);
- **ad-interaction data** (that an ad was shown, viewed or tapped);
- **diagnostics about the ad software itself** (for example, that an ad failed to load).

This is collected by **Google as a third party**, under Google's own policies. It is **never
combined** with anything you enter in the app — that data never leaves your phone.

Google AdMob is the **only** third party that receives anything from this app. There is no mediation
network, no ad exchange and no other third-party software.

To be precise about "analytics": the app contains **no analytics or crash-reporting software of
ours** — no Firebase, no Google Analytics, no Crashlytics, nothing that reports your use of the app
to us. We receive no reports at all. Google's own ad software does perform its own measurement of
the advertising data listed above, for the purposes in section 5.

Google's policies:
- How Google uses information from sites and apps that use its services: https://policies.google.com/technologies/partner-sites
- Google Privacy Policy: https://policies.google.com/privacy

## 5. Why it is collected, and the legal basis

The data in section 4 is collected **only for the advertising that keeps the app free**, and only by
Google. Google uses it to:

- **select and display** the banner advertisement;
- **measure** advertising performance (whether an ad was shown, seen or tapped);
- **detect fraud and invalid traffic** (for example, fake or automated ad taps).

These are the same purposes declared in this app's **Data safety** section on Google Play; the two
are meant to be read together. The data is used for **no other purpose**, is **not used by us**, and
is never used to build a profile of you for anything other than the ad above.

Where the GDPR applies, the legal basis is your **consent**, obtained before any ad request is made.
Elsewhere, we rely on the choices you make in the prompts described in section 8.

## 6. International transfers

Google processes advertising data on servers outside your country, including in the **United
States**, under Google's own safeguards (such as EU Standard Contractual Clauses and the EU–US Data
Privacy Framework), as described in Google's privacy policy linked above.

## 7. How long it is kept

**We keep nothing** — there is no server and we receive no data, so we have no retention period to
state. What you enter lives on your phone until you delete it or uninstall the app; uninstalling
removes all of it. Advertising data described in section 4 is kept by **Google** under Google's own
retention policies.

## 8. Your choices

- **Before any ad loads**, on first launch, the app shows you a disclosure and asks you to agree.
  Nothing is requested from Google — not even the check for whether a consent form is needed — until
  you do. If you do not agree, the app closes; there is no version of the app without the ad.
- **Consent forms.** Where the law requires it (the EEA and the UK), Google's own consent form is
  shown after that, and a row **Settings → About → Ad privacy choices** lets you change your answer
  at any time. Outside those regions the form and the row do not appear, because no consent form
  applies there.
- **Withdrawing consent** does not remove the banner; the ads you see may become non-personalised or
  limited instead.
- **Resetting your advertising ID.** You can reset or delete your advertising ID at any time in your
  phone's settings (Settings → Google → Ads, or Settings → Privacy → Ads, depending on the phone).
- **If this policy materially changes**, the app will ask you to read and agree again. An earlier
  agreement is **not** carried over: it covers the disclosure that was on screen at the time, and
  nothing else.

## 9. US state privacy rights (California and others)

**We do not receive money in exchange for your personal information.** We would rather be accurate
than reassuring, though: because the app passes an advertising ID to Google for advertising, that
activity **may count as a "sale" or as "sharing" for cross-context behavioural advertising** under the
California Consumer Privacy Act (as amended by the CPRA) and similar laws in other US states.

You can opt out by resetting or deleting your advertising ID in your phone's settings and, where
Google's ad privacy form is offered to you, through **Settings → About → Ad privacy choices**. We do
not treat you differently for exercising this right. We do not knowingly process sensitive personal
information for advertising.

## 10. Your rights

Depending on where you live, you may have the right to **access**, **correct**, **delete**, **object
to** or **restrict** the processing of your personal data, to **data portability**, and to
**withdraw consent** at any time.

Because there is no server and we hold no data about you, the practical position is:

- **Data you entered:** already entirely under your control. Export it to a file from
  Settings → Backup & export, or uninstall the app to remove it from your phone.
- **Advertising data:** held by **Google**, not by us. Exercise those rights with Google directly at
  https://myadcenter.google.com and https://myaccount.google.com/privacy.
- **Anything else:** email **imkalakandan@gmail.com**.

If you are in the EEA, the UK or Switzerland, you also have the right to lodge a complaint with your
national data protection supervisory authority.

## 11. Permissions the app uses, and why

- **Internet:** used **only** to load the Google AdMob banner, and Google's consent form where it
  applies. Google's ad software also declares the standard **advertising ID** permission, for the
  same purpose.
- **Alarms and reminders** — exact alarms, notifications, full-screen alarm, run at start-up, ignore
  battery optimisations, vibrate, keep the phone awake, foreground service: to ring your wake-up and
  "leave for your shift" alarms and reminders at the right time, show a ringing alarm over the lock
  screen, keep it ringing reliably, and restore your alarms after a restart. All of it works on your
  phone alone.

The app holds **no** microphone, camera, location, contacts, calendar, phone or storage permission.
In particular:

- **Voice input (optional):** when you tap a microphone button, your phone's **own speech-to-text
  service** does the listening and hands the app the words. The app never records, stores or sends
  audio. Depending on your phone, that system service may process your speech online, under its
  maker's policy.
- **Calendar:** the app does not read or write your phone's calendar. (Versions before 3.5 could
  mirror shifts into a calendar named "Work & Life"; if one is still on your phone from that time, it
  is yours to delete in your Calendar app.)
- **Files:** when you save a backup, or open one to restore, Android's file picker opens and you
  choose the file. The app cannot see any other file.

## 12. Sharing, and what others can see

The app never sends what you enter anywhere by itself. When **you** choose to share something,
Android's own share sheet opens and you pick where it goes:

- your roster as plain text, or your free evenings, to a colleague or your family;
- an "I'm home" or "my ETA" message to someone you choose — it contains the text and time only, as the
  app has no access to your location;
- a backup file, saved to a place you pick;
- the diagnostics log described in section 3, if you decide to send it to us or to anyone else.

On the phone itself, your shifts may be visible where you have put them: on the lock screen when an
alarm rings or a reminder shows, and on the home-screen widget, which shows shift colours and the
number of notes on a day — never a note's text.

Links in the app (this policy, the pattern-building guide, the Play Store listing, "Write to me")
open your browser, the Play Store or your mail app, and from there those apps' own policies apply.
Our website is a plain static site with no analytics and no cookies of ours.

## 13. Children

The app is a general-purpose planner and is **not directed at children**. We do not knowingly collect
personal information from children; aside from the advertising data in section 4, the app collects
no personal information at all. If you believe a child has provided personal information, contact us
and we will act.

## 14. Security

Your data is held in the app's private storage, encrypted as described in section 3, with the key in
your phone's own secure key store, and excluded from cloud backup and device transfer. An optional
**app lock** in Settings uses your phone's own screen lock or fingerprint/face unlock; the app never
sees or stores biometric data — Android only tells it whether the unlock succeeded. Because nothing
is sent to us or held by us, there is no server of ours that can be breached.

## 15. Changes to this policy

If this policy changes, the updated version is posted at this address with a new "last updated"
date. A **material** change — new data collected, a new recipient, a new purpose — also gets a new
policy version and requires your agreement again inside the app before it continues.

## 16. Contact

Questions, requests or complaints about this policy: **imkalakandan@gmail.com**
