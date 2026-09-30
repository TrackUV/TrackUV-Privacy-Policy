# TrackUV Privacy Policy

**Last updated:** September 30, 2026

TrackUV is a macOS menu-bar app and widget that shows the current UV index
for your location. This policy explains what data the app touches and what
it does with it.

## 1. Information We Collect

TrackUV does not collect, transmit, sell, or share any personal information
with us or with any third party. There are no user accounts, no analytics,
and no advertising.

The only data the app touches is:

- **Your location** (via macOS Location Services), used to look up the UV
  index for where you are.
- **The most recent UV reading**, cached on your Mac so the menu bar and
  widget have something to show instantly, and so they still work briefly
  offline.
- **One display setting** — whether the optional map background is turned
  on — saved on your Mac.

None of this is ever sent to us — TrackUV has no servers of its own. Your
location is sent only to Apple, as described below.

## 2. How We Use Information

Your location is used only to show you UV information for where you are.
To do that, TrackUV sends it to Apple in up to three ways:

- **Apple Weather (WeatherKit)** — to get the current and forecast UV index
  for your location. This always happens when the app fetches UV data.
- **Apple's place-name lookup (reverse geocoding)** — to turn your
  coordinates into the city name shown at the top of the card, and to get
  that place's time zone so forecast times are shown in local time. This
  always happens when the app fetches UV data.
- **Apple Maps (MapKit)** — only if you turn on the optional map background
  in the card (it is off by default). TrackUV then asks Apple Maps for a
  picture of the street map around your location to show behind the card.
  The picture is kept in memory while the app is running and is not saved.

The cached UV reading is used to display the menu bar icon and the
Notification Centre widget without waiting on a fresh network request every
time.

## 3. Permissions We Request, and Why

| Permission | Why |
|---|---|
| **Location (When In Use)** | Required to determine the UV index at your current location. macOS asks you once, after you click "Allow Location Access" in the TrackUV card. |
| **Network access** | Used only to contact Apple services: Apple Weather for UV data, Apple's place-name lookup for your city name and time zone, Apple Maps for the optional map background, and the small "Powered by Apple Weather" attribution image Apple requires apps to display. |

TrackUV requests no other permissions — no camera, microphone, contacts,
photos, or file access.

## 4. Data Sharing and Third Parties

TrackUV's only data partner is **Apple**, through services built into
macOS: Apple Weather (WeatherKit), Apple's place-name lookup, and — only
when the map background is on — Apple Maps (MapKit). Your location is sent
to Apple solely to get the weather data, place name, time zone, and map
picture described in section 2. Apple's handling of those requests is
governed by Apple's own privacy policy, not this one. TrackUV does not add
any tracking of its own on top of those requests.

TrackUV contains no third-party analytics or advertising software
development kits (SDKs) of any kind.

The app shares the current UV reading — together with the place name and an
approximate location (rounded to about 1 km), not your exact coordinates —
between the main app and the Notification Centre widget, on your device
only, using Apple's standard App Group mechanism. This never leaves your
Mac.

## 5. Data Retention and Deletion

The cached UV reading (including the place name and time zone it was
fetched for) is stored locally using standard macOS app storage and is
automatically replaced each time TrackUV fetches new data. The map picture
is never saved to disk. Deleting TrackUV (and its widget) from your Mac
removes this cached data and the map-background setting along with the
app.

## 6. Children's Privacy

TrackUV does not knowingly collect information from anyone, including
children, because it does not collect information from anyone at all.

## 7. Changes to This Policy

If a future version of TrackUV changes how it handles location — including
sending it to any new service, Apple's or anyone else's — or adds a feature
that communicates with a server we operate, this policy will be updated
before that version ships, and the "Last updated" date above will change.

## 8. Contact Us

Questions about this policy can be sent to: **raghurayachoti@gmail.com**
