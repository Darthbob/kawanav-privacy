# KawaNav privacy policy

Last updated: 25 October 2026

KawaNav is a free, open-source app. It has no account, no ads, no analytics and no crash
reporting, and it sends nothing about you to the developers. Questions about privacy:
[kumuluskomata@gmail.com](mailto:kumuluskomata@gmail.com).

## What the app uses, and where it stays

| Data | What it is for | Leaves the phone? |
|---|---|---|
| Location (GPS), also in the background | Curves and speed camera warnings on the dash, ride recording, where the bike was parked | The rides' tracks and the parking spot go into Android's backup (see below); otherwise only as listed under "Network requests" |
| Google Maps' navigation notification | The turn arrow and distance for the dash | No. Its text (the next maneuver, often with a street name) is written to the app log |
| Calls and messages (notifications of other apps) | The call or mail icon on the dash | No. Only the app and the kind of notification are looked at, never its sender or text; the bike gets only "there is one", nothing is stored |
| The bike's data (odometer, fuel, temperatures, live values, VIN, settings) | Shown in the app and kept with the rides | Only in Android's backup (see below) |
| Rides, refuels, battery readings, maintenance log, settings | Your riding log and diary | Only in Android's own backup and phone-to-phone transfer (end-to-end encrypted; without a screen lock the cloud backup is off), or when you export or share a ride yourself |
| Bluetooth | The link to the bike; the headset icon while your intercom is connected. The bike is told the phone's model name, as Kawasaki's own app does | No |
| App log | A technical log for finding faults: what the app did and when, with the Google Maps directions text, the Bluetooth names and addresses of the bike and the headset, and speeds at curve warnings. At most about 4 MB; the oldest lines are dropped | No. It stays in the app's private storage, is not backed up, and the app has no way to send it |

## Network requests

The app connects to these servers only for the purposes below. They see your IP address, as with
any web request, and handle it under their own privacy policies.

- **Geofabrik** (download.geofabrik.de): the list of offline map regions, the regions you download,
  and whether a downloaded region has newer data (when you open "Offline maps").
- **OpenStreetMap** (tile.openstreetmap.org): map tiles under a ride's track when you open it. The
  server sees which area the tiles show.
- **Google Maps**: only when you tap "Walk to the bike", which opens Google Maps with the parking spot.
- **GitHub** (api.github.com, raw.githubusercontent.com): the version downloaded from GitHub checks
  there for updates. The version from Google Play does not.

Spoken warnings use the phone's text-to-speech engine, under that engine's own privacy policy.

## Deleting your data

Everything KawaNav keeps is on your phone. Clear the app's storage or uninstall it to delete it all;
a ride can also be deleted on its own in the app.

## Children

KawaNav is meant for adult motorcycle riders and is not directed at children.

## Changes

Changes to this policy are made in this file; its history on GitHub shows every earlier version.
