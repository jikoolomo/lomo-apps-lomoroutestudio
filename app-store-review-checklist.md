# LOMO Route Studio App Store Review Checklist

## Build

- Confirm `flutter analyze` passes.
- Confirm `flutter test` passes.
- Confirm `flutter build ipa --release` succeeds.
- Upload the `.ipa` from `build/ios/ipa/lomo_route_studio.ipa`.

## App Store Connect

- App name: `LOMO Route Studio`
- Subtitle: short and user-facing, not technical
- Description: explain local-first route-story video creation from selected photos
- Keywords: route video, travel story, photo route, GPS photos, vertical video
- Support URL: `https://jikoolomo.github.io/lomo-apps-lomoroutestudio/support.html`
- Privacy Policy URL: `https://jikoolomo.github.io/lomo-apps-lomoroutestudio/privacy.html`
- App category: likely `Photo & Video`
- Age rating: complete questionnaire honestly
- Review notes: explain that the app reads selected photos locally, uses EXIF time and GPS metadata, renders on-device, and saves to Photos

## App Privacy

- Verify whether the app sends any data off device. Current product intent is local-only.
- Complete App Privacy answers to match actual runtime behavior.
- Re-check privacy manifest behavior after dependency updates.

## Screenshots

- iPhone screenshots for the current supported device classes
- Show:
  - Home
  - Import Photos
  - Route Review
  - Story Preview
  - Creating Your Story
  - Result / Save to Photos

## Final Manual Pass

- Test photo import on a real iPhone
- Test save to Photos on a real iPhone
- Confirm no premium UI is visible
- Confirm the app does not mention unfinished features
- Confirm launch screen and app icon are branded
- Confirm no placeholder text, sample data, or debug UI remains

## Known Non-Code Work Still Needed

- Fill App Store Connect metadata
- Add final App Store screenshots
