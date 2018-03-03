# Noto 2

Please file any bugs or feature requests [here](https://github.com/noto-app/org/issues). You can also discuss on the forums [here](https://groups.google.com/forum/#!forum/noto-app).

## Changelog
- v2.0.7 (2018-03-02)
  - Fix bug where deleting attachment crashes app
- v2.0.6 (2018-03-02)
  - Fix bug where send via Noto fails to send image attachments
- v2.0.5 (2018-02-28)
  - Add indicator for which email you're sending to
  - Fix bug when images are deleted from a user's device
- v2.0.4 (2018-02-23)
  - Improve Settings page so it doesn't look completely n00b
  - Improve Archive / Outbox / Draft pages to give more information
  - Fix launch screen blacking out
- v2.0.3 (2018-02-18)
  - Dial down haptic from heavy to medium
  - Fix enable notifications bug
  - Treat whitespace-only drafts as empty
  - Improve flash messages when sending
- v2.0.2 (2018-02-16)
  - Fix bug where we can't save draft during onboarding flow
- v2.0.1 (2018-02-15)
  - Improved onboarding flow
- v2.0.0 (2018-02-15)
  - Initial release!

## Release checklist
- Increment version / build as needed for all targets in Xcode
- Write update notification string in ```whats_new```
- Archive and upload to the App Store
- Write changelog notes and update this document
- Commit and tag release on GitHub. Copy changelog notes.
- Copy changelog notes to ```What's New``` in the App Store
