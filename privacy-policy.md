# LOMO Route Studio Privacy Policy

Last updated: 2026-05-24

LOMO Route Studio is a local-first iPhone app that turns selected photos into short route-story videos. This policy describes what the app accesses on your device and the limited network calls it makes.

## What the app accesses

- Selected photos from your photo library
- Metadata contained in those selected photos, including timestamp and GPS location when available
- Generated video files created on your device
- Records of in-app purchases (handled by Apple)

## How the app uses that data

- To sort selected photos by time
- To group photos into places or moments
- To request a human-readable place name from Apple's reverse geocoding service using the photo's GPS coordinates
- To generate route previews and route-story videos
- To save exported videos back to your photo library when you choose to save them
- To unlock LOMO Pro features (watermark removal, additional globe skins) after a successful in-app purchase

## Network use

LOMO Route Studio renders videos entirely on your device, but it does make a small number of network calls in the following cases:

- **Reverse geocoding** — when you build a new route, the app sends the GPS coordinates extracted from your selected photos to Apple's reverse geocoding service to obtain readable place names (for example, "Paris, France"). No user identifier is attached to these requests. They are governed by Apple's privacy policy.
- **In-app purchases** — purchasing or restoring LOMO Pro communicates with Apple's StoreKit and App Store services. The app receives only an entitlement flag in response. Apple handles all payment information.
- **Sharing** — when you tap "Share" on a rendered video, iOS opens its standard Share Sheet and you choose the destination app. LOMO Route Studio itself does not upload your video; the destination app you select handles delivery.
- **Project page link** — tapping the project page link in Settings opens an external browser. The app does not transmit your data to that page.

## What the app does not do

- No account creation, no sign-in
- No upload of your photos or videos
- No backend server for user data
- No analytics, advertising, or tracking SDKs
- No social posting on your behalf
- No sale of personal data

## Data retention

LOMO Route Studio does not store your photos, videos, or coordinates on any server. Reverse-geocoding requests sent to Apple are not retained by LOMO Route Studio. Selected photos, generated outputs, and your LOMO Pro entitlement are stored locally on your device.

## Third-party software

The app uses third-party software components for photo access (`photo_manager`), video encoding and playback (`video_player`, AVFoundation), reverse geocoding (`geocoding`), in-app purchases (`in_app_purchase`), iOS Share Sheet integration (`share_plus`), external link handling (`url_launcher`), local settings storage (`shared_preferences`), and the Flutter runtime. These components run locally on your device.

## Contact

For support or privacy questions, use the GitHub Issues page:

https://github.com/jikoolomo/lomo-apps-lomoroutestudio/issues
