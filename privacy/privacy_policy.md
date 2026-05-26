# Privacy Policy — ScoreCut Studio

**Last updated: 2026-05-26**

## Summary

ScoreCut Studio is a music-notation capture and cleanup app. Your imported media, captured frames, edited pages, exported PDFs, audio files, and project files stay on your device or in folders you choose.

ScoreCut Studio uses optional account, subscription, desktop-pairing, and cloud shared-configuration services. These services collect the limited data needed to sign in, manage subscriptions, unlock paid features across your devices, and, only if you enable it, upload shared video-configuration JSON that can help other users process the same video.

ScoreCut Studio does not use advertising, third-party ad SDKs, or cross-app tracking.

## Who we are

ScoreCut Studio is developed by Locke Huang, an individual based in New Zealand.

Contact: **scorecutstudio@gmail.com**

## What we collect

### Media and project content

The following stays on your device or in folders you explicitly choose:

- Sheet music images, video files, and audio files you import or capture
- OCR-extracted text from your sheet music
- Project files, edit history, and preferences
- Captured frames, exported pages, and saved PDFs

ScoreCut Studio does not upload your source videos, source images, audio files, exported PDFs, captured frame images, or page images to ScoreCut servers as part of normal processing.

### Account and subscription data

If you sign in, subscribe, restore purchases, pair a desktop, or manage your account, ScoreCut Studio may process:

- Your sign-in identifier, such as email address, Sign in with Apple identifier, Google sign-in identifier, and Firebase user ID
- Subscription status, product identifier, renewal or expiry state, and related purchase-event metadata from RevenueCat and Apple
- Desktop-pairing metadata, such as a generated install ID, operating system, hostname, pairing time, last-seen time, and revocation status
- Account-deletion requests and related operational logs

This data is used for app functionality: authentication, subscription entitlement, purchase restore, desktop unlock, fraud and abuse prevention, support, and account deletion.

### Optional shared video configurations

If you enable **Share configs to the cloud**, ScoreCut Studio may upload shared video-configuration JSON to Firebase/Google Cloud. This feature is optional. Local shared-config import/export can still work without cloud sharing.

Shared configuration JSON may include:

- A source-video fingerprint and basic video metadata, such as filename, duration, file size, format, resolution, and frame rate
- Capture and extraction settings, such as crop regions, highlight-removal settings, capture intervals, and layout settings
- Review decisions, such as frame timestamps, kept or removed zones, barline positions, OCR bar-number values, OCR bounding boxes, and page settings
- Submission metadata, endorsement counts, flag/report records, rate-limit counters, moderation metadata, and the Firebase user ID that submitted or interacted with the config

Shared configuration JSON is intended to contain replay metadata only. It is not intended to include raw video, raw score images, raw audio, exported PDFs, absolute source-file paths, cache directories, or project names.

Cloud shared configurations may be visible to other signed-in users who open a matching video, and may be used to rank, recommend, moderate, or remove shared configs.

## Permissions

ScoreCut Studio requests the following permissions, used solely for the features described:

- **Camera** — to capture sheet-music pages and to scan desktop-pairing QR codes. Camera frames are processed on-device only.
- **Photo Library** — to let you import sheet-music images and select QR-code images you have saved. Read-only; we do not write back to your photo library.
- **Files** — to let you choose where to save exported pages and to import files you select. We only access files you explicitly pick.
- **Microphone** — *not used.* The audio features in ScoreCut Studio process audio extracted from video files you provide; the microphone is never recorded.

## Where data is stored

Local app data is stored in storage your operating system manages for the app, either inside the app's private container or in folders you explicitly choose using the file picker.

If you enable iCloud Drive sync in ScoreCut Studio, exported output files may be saved to your iCloud Drive app container and handled under Apple's iCloud terms and privacy policy.

Account, subscription, desktop-pairing, and optional shared-configuration data is stored using Firebase and Google Cloud services. Subscription events are processed through RevenueCat. Apple processes App Store purchases and Sign in with Apple under Apple's privacy policy. Google processes Google sign-in under Google's privacy policy.

## Third-party services

ScoreCut Studio uses:

- **Firebase / Google Cloud** — authentication, Firestore, Cloud Functions, Cloud Storage, and desktop-pairing support
- **RevenueCat** — subscription receipt and entitlement processing
- **Apple App Store / StoreKit / Sign in with Apple** — purchases, restore purchases, and Apple sign-in
- **Google Sign-In** — optional Google account sign-in

These services are used for app functionality. ScoreCut Studio does not use third-party advertising or tracking services.

## Children's privacy

ScoreCut Studio does not knowingly collect personal information from children under 13. The app is suitable for general audiences and does not contain advertising or tracking.

## Account deletion and data requests

You can delete your account from inside the app. Account deletion removes your Firebase account data used by ScoreCut Studio, including subscription-entitlement documents, desktop-pairing records, and desktop-trial records. Deleting your ScoreCut account does not automatically cancel an App Store subscription; you must cancel subscriptions through Apple.

Shared configurations that you contributed to the cloud corpus may not be automatically removed by in-app account deletion because they may already have been used, endorsed, reported, or forked by other users. To request removal of shared configurations you submitted, email **scorecutstudio@gmail.com**. We may delete, tombstone, or anonymize shared-configuration records as needed for moderation, abuse prevention, legal compliance, and operational integrity.

## Changes to this policy

If this policy is updated, the "Last updated" date at the top will change. For material changes, the in-app and App Store listings will reference the updated policy.

## Your rights

If you have questions about this policy or want to request access, correction, export, or deletion of data associated with your account, email **scorecutstudio@gmail.com**. Local app data on your device can be removed by deleting the app or by deleting files you created in folders you chose.

## Jurisdiction

This policy is governed by the laws of New Zealand. The app is distributed through the Apple App Store; for store-specific policies (purchase records, payment processing), see Apple's Privacy Policy.
