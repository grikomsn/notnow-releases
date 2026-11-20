# NotNow releases

Downloads for [NotNow](https://notnow.nibras.co), a macOS menu bar app that keeps notification banners from landing under your cursor.

- **Downloads:** each version is a [release](https://github.com/grikomsn/notnow-releases/releases) with a notarised `NotNow-<version>.zip`.
- **Updates:** NotNow checks for them through [Sparkle](https://sparkle-project.org), using the feed at <https://notnow.nibras.co/appcast.xml>, which links to the zips here. Every update is signed, and NotNow installs only updates that carry a valid signature.

The app's source isn't public, and NotNow is proprietary software. Using it is covered by its [terms](https://notnow.nibras.co/terms/).

Releases here are made by NotNow's `scripts/publish.sh`, which also adds them to the feed. Don't delete or rename a release's zip: the feed, and any copy of NotNow that hasn't updated yet, points at it.
