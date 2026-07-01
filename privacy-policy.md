# Privacy Policy for Wink Music

**Effective date:** June 19, 2026
**Developer:** Daniel Singh (individual developer)

---

## What this policy is

This policy explains what Wink Music (referred to inside the app as "Wink") does and does not do with your data. The short version: Wink Music runs entirely on your device, never connects to the internet, and Daniel Singh never receives any information about you or your use of the app.

By downloading or using Wink Music, you agree to this policy. If you do not agree, please do not use the app.

---

## Face Data and TrueDepth API

Wink uses Apple's ARKit ARFaceTrackingConfiguration on the front-facing TrueDepth camera to detect eye winks.

**What is collected.** For each camera frame, Wink reads two numeric blend-shape values from ARKit: one representing how closed the left eye is and one representing how closed the right eye is. Each value is a floating-point number between 0.0 and 1.0. No image of your face, no video, no audio, and no depth map is retained.

**Why it is collected.** These two values are used only to determine when you have winked one eye. A wink triggers a page turn in your sheet music. The values are processed frame by frame and are discarded immediately after the current frame is evaluated. Nothing is stored to disk.

**How it is stored.** The values live only in memory during a single frame of face tracking, then are overwritten by the next frame. Nothing is written to a file, database, log, or cache. Nothing is retained after the app closes or the piece is dismissed.

**Where it is sent.** Nowhere. Wink does not use the internet at all. Face data is never transmitted off the device. It is not shared with the developer, with Apple, or with any third party.

**When face tracking is active.** Only while a piece of sheet music is open in the viewer, and only if you have granted camera permission. Face tracking pauses immediately when you close a piece, background the app, or turn off wink detection in the viewer menu. You can revoke camera permission at any time in iOS Settings, and Wink continues to work with manual arrows and swipe gestures.

**No third parties.** Wink contains no analytics, no third-party SDKs, no ads, no crash reporting, no cloud sync, and no account system. There is no channel by which face data could reach a third party.

---

## What data Wink Music accesses on your device

Wink Music accesses your device's front camera to detect winks. While a piece of sheet music is open, Apple's ARKit framework reads two numeric values per frame per eye, representing how closed each eye is. That is the only camera-derived data the app reads.

Wink Music also accesses any PDF or image files you choose to import. It copies those files into its own private storage folder on your device. It does not access anything else on your device.

---

## What data leaves your device

Nothing. Wink Music has no network capability. It makes no outbound connections of any kind. No data is uploaded, transmitted, shared, or sold to any party, at any time, for any purpose. Daniel Singh never receives any information from your use of the app.

---

## How the camera is used

The front camera is active only while a piece of sheet music is open in the viewer and wink detection is enabled. It pauses automatically when you background the app, lock your screen, close the piece, or toggle wink detection off.

Wink Music uses Apple's ARKit framework, which processes the camera feed entirely on your device. No image, video, frame, or audio is captured, recorded, stored, or transmitted. The only output Wink Music reads from ARKit is a pair of numbers per frame representing eye closure.

---

## What is stored locally

Wink Music stores the following on your device only:

- Sheet music files (PDFs and images) you import, copied into the app's private sandbox
- Cover thumbnails generated from the first page of each piece
- Your preferences and settings, including sensitivity presets, calibration values, and sort order, stored in iOS UserDefaults

None of this is accessible to Daniel Singh or any third party. It lives on your device and nowhere else.

---

## Third-party services

Wink Music uses none. There are no analytics tools, no crash reporters, no advertising networks, no third-party SDKs, no social sign-in, and no cloud sync. The only frameworks Wink Music uses are Apple's own system frameworks (ARKit, PDFKit, SwiftUI, SwiftData), which are governed by Apple's own privacy policies. Daniel Singh has no control over Apple's frameworks and is not responsible for how Apple's systems operate.

---

## Children's privacy

Wink Music does not collect personal data from any user, regardless of age. It is suitable for all ages. Because no data is collected or transmitted, Wink Music has nothing to disclose under laws that require it, including COPPA (United States) and general data-protection laws such as PIPEDA (Canada) and GDPR (European Union).

---

## Your rights and how to remove your data

Because all data is stored locally on your device, you are in full control of it at all times. To remove everything Wink Music has stored, delete the app from your device. Deleting Wink Music permanently removes all imported sheet music, thumbnails, preferences, and calibration data. Nothing remains on any server because nothing was ever sent to one.

You can revoke camera permission at any time in iOS Settings under Wink Music. The app continues to work as a manual sheet music reader with on-screen arrows and swipe gestures when wink detection is disabled.

Because Wink Music collects no personal data, requests for access, correction, portability, or erasure of personal data will result in the same answer: there is nothing to access, correct, port, or erase. You may still write with any such request, and the response will confirm this.

---

## Intellectual property

Wink Music, including its name, icon, interface, and underlying code, is the sole property of Daniel Singh. Downloading the app grants you a personal, non-transferable, non-exclusive licence to use it on your device in accordance with Apple's standard App Store terms. You may not copy, reverse-engineer, modify, or distribute the app or any part of it.

---

## Disclaimer of warranties

Wink Music is provided "as is" and "as available," without warranty of any kind. Daniel Singh makes no representation or guarantee, express or implied, that the app will meet your requirements, operate without interruption, or produce accurate wink detection under all conditions.

Wink detection depends on Apple's ARKit framework and your device's front camera. Accuracy varies with lighting, face angle, eyewear, and other factors outside Daniel Singh's control. You use wink detection at your own risk, particularly during live performances.

To the fullest extent permitted by applicable law, Daniel Singh disclaims all implied warranties, including implied warranties of merchantability, fitness for a particular purpose, and non-infringement.

---

## Limitation of liability

To the fullest extent permitted by applicable law, Daniel Singh is not liable for any damages of any kind arising from your use of or inability to use Wink Music. This includes, without limitation, missed page turns, accidental page turns, disruption to a musical performance, loss of data, or any other direct, indirect, incidental, special, consequential, or punitive damages.

In no event shall Daniel Singh's total liability for any claim arising from Wink Music exceed the amount you paid to download it. Because Wink Music is offered free of charge, that amount is zero dollars.

Some jurisdictions do not permit the exclusion or limitation of certain warranties or damages. In those jurisdictions, Daniel Singh's liability is limited to the minimum extent permitted by law.

---

## Indemnification

You agree to indemnify and hold harmless Daniel Singh from any claims, losses, damages, costs, and expenses (including reasonable legal fees) arising from your use or misuse of Wink Music, your violation of this policy, or your violation of any applicable law or third-party right.

---

## Governing law and jurisdiction

This policy and any dispute arising from your use of Wink Music are governed by the laws of the Province of Ontario and the federal laws of Canada applicable in Ontario, without regard to conflict-of-law rules. You agree that any legal action relating to Wink Music will be brought exclusively in the courts of Ontario, Canada, and you consent to the personal jurisdiction of those courts.

---

## Entire agreement

This policy, together with Apple's App Store terms, is the entire agreement between you and Daniel Singh regarding Wink Music. It supersedes any prior representations, discussions, or understandings, written or oral.

---

## Contact

For privacy-related questions, contact Daniel Singh at ltriomino@gmail.com.

---

## Changes to this policy

If this policy changes, the updated version will be posted at the same public URL with a new effective date at the top. Your continued use of Wink Music after a change is posted constitutes acceptance of the revised policy. If you do not agree with a change, delete the app.

Because Wink Music collects no personal data, changes to this policy are likely to be minor clarifications. Any significant change will be noted clearly near the top of the updated document.

---

*Last updated: June 19, 2026*
