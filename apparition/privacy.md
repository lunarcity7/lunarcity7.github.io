# Privacy Policy

**Effective date:** June 28, 2026

This privacy policy explains how Apparition ("the app") handles your data.

## Data Collection

Apparition accesses your device's **app usage statistics** (via `android.permission.PACKAGE_USAGE_STATS`) to determine which apps you have launched and at what times. This data is used solely to power the widget's time-of-day prediction feature — showing you apps you're likely to open next.

## Data Storage & Transmission

**Apparition does not collect, transmit, or share any data.** Specifically:

- No network access is requested or used
- No analytics or crash-reporting SDKs are included
- No data is sent to remote servers
- All usage data is processed and stored exclusively on your device using Android's local DataStore
- The app does not collect personally identifiable information (PII), location data, or device identifiers

## Data Usage

The usage statistics (app launch events and timestamps) are used only to:

1. Identify which apps you use at different times of day
2. Show your most frequently used apps as a fallback
3. Display recently installed apps (within the last 3 hours)

## Third-Party Services

Apparition does not integrate any third-party services, SDKs, or analytics frameworks.

## Permission

You can revoke the usage statistics permission at any time via your device settings:

```
Settings → Apps → Apparition → Permissions
```

## Changes to This Policy

If this policy changes, the updated version will be posted here with a new effective date.

## Contact

For questions about this policy, contact the developer at the email address listed on the app's Google Play Store listing.
