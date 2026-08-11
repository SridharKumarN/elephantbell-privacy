# Privacy Policy — ElephantBell

_Last updated: 2026-08-12_

ElephantBell has no ads, no accounts, and no servers of its own. Two features use the internet,
both optional: the map shown when picking a location, and the AI Reminder feature, which sends
only what you choose to share to Google's Gemini AI.

## The short version

This app has no analytics, no advertising SDKs, and no account sign-in — there's no server of
ours for it to send your reminders, location, or app-usage data to, ever. Two things do use the
internet: the map shown when picking a location (see below, optional, on by default), and the
optional AI Reminder feature (Scan/Voice/Text), which only sends data to Google's Gemini AI when
you actively use it — see below for exactly what that involves.

## AI Reminder (only if you use Scan/Voice/Text)

AI Reminder lets you create a reminder from a photo (like a poster, bill, or prescription
label), a spoken phrase, or pasted text — Gemini (Google's AI model) reads it and extracts a
title, date, and time for you to review before saving. This only happens when you actively
choose to scan, speak, or paste something; it never runs in the background. What's sent: the
photo you took or picked (or the transcribed/pasted text), plus today's date, sent to Google via
Firebase AI Logic — Google's App Check service verifies the request genuinely comes from this
app, without this app embedding any reusable API key. That content is used only to extract the
reminder and isn't stored by this app afterward; Gemini's own data handling for this request is
governed by Google's API terms, not this app's. You always see the extracted result on a review
screen and can edit or discard it before anything is saved. If you never use AI Reminder, none
of this applies to you.

## Your reminders

Titles, categories, due times, and repeat schedules you enter are stored only in a local
database on your device. Deleting a reminder deletes it immediately; uninstalling the app
deletes everything.

## Location (only if you add a Location-based reminder)

If you create a location-based reminder, the app stores the coordinates and radius you choose,
and uses Android's Geofencing API to detect when you enter that area. "Allow all the time" is
requested because the reminder must be able to fire even when the app is closed. Location data
is used only for this on-device matching and is never uploaded or shared by this app. One
technical note: searching for a place by name uses Android's built-in address lookup, which
resolves the text you type via a system geocoding service — this happens regardless of the map
setting below, and is the one place typed search text leaves the device, via Android itself
rather than this app. If you don't have any location-based reminders saved, none of this is
active — there's no geofence to monitor, so the permission simply isn't being used.

## Map picker (on by default)

When adding a location-based reminder, a real Google Map is shown so you can tap to fine-tune
the exact spot — this loads map imagery from Google over the internet, used purely to display
the map. The app does not send Google your reminders, your other saved locations, or anything
else about you. Settings has a "Show map when picking a location" toggle if you'd rather turn
this off — while it's off, the app makes no network requests at all, and location search still
works via the offline text search described above.

## App usage (only for App-based reminders)

If you use App-based reminders, the app checks — in real time, on your device only — which app
is currently in the foreground, using Android's Usage Access permission. This is used solely to
detect when you open an app you're monitoring (e.g. Instagram, WhatsApp) so a reminder can fire.
This information is not logged, stored, or sent anywhere.

## Notifications

Notification permission is used only to show you the reminders you create — nothing else.

## Data sharing

We do not share, sell, or transmit any of your data to any third party. The app has no backend
of its own to send anything to. Its network use is: fetching map imagery from Google for the
location picker (which can be turned off in Settings, and that request carries map tile
coordinates, not your data), and — only when you actively use the optional AI Reminder feature —
sending the photo/text you provide to Google's Gemini AI to extract a reminder, as described
above. Neither of these shares your reminders, saved locations, or app-usage data; both are
purely functional and only happen when you use that specific feature.

## Children's privacy

This app is not directed at children under 13 and does not knowingly collect data from anyone,
regardless of age.

## Changes to this policy

If this policy changes, the updated version will be posted here and reflected in the in-app
Privacy Policy screen (Settings → Privacy Policy).

## Contact

Questions about this policy? Email elephantbell.app@gmail.com.
