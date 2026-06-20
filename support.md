# Support — Wink Music

**Developer:** Daniel Singh

---

## What is Wink Music?

Wink Music is a sheet music reader for iPhone and iPad. You import your PDFs or photos of sheet music, place your device on a stand, and turn pages by winking. No tapping required once a piece is open. Your hands stay on your instrument.

Wink Music runs entirely on your device. There is no account to create, no internet connection required, and nothing is ever uploaded anywhere.

---

## System requirements

- iPhone or iPad running iOS 18.6 or later
- A TrueDepth front camera for wink detection (iPhone X or later, or an iPad Pro with Face ID)

If your device does not have a TrueDepth camera, Wink Music still works as a full-featured sheet music reader. Wink detection will not be available, but on-screen arrows and swipe gestures work on any supported device.

---

## Getting started

**Import a piece.** Tap the plus button on the library screen. You can import a PDF from the Files app, pick an image from Photos, or photograph a physical page with your camera. Wink Music copies the file onto your device and asks you for a title.

**Open it.** Tap any piece in your library to open it in the viewer. The page fills the screen. A small page indicator shows your position.

**Wink to turn the page.** Place your device on a stand roughly an arm's length away. Wink your right eye to go forward. Wink your left eye to go back. A natural blink with both eyes together is ignored and will not trigger a page turn.

You will feel a light haptic tap and see a brief directional flash at the screen edge each time a wink is detected.

---

## Wink controls

- **Right eye wink** (right eye closes, left stays open): advance to the next page
- **Left eye wink** (left eye closes, right stays open): go back to the previous page
- **Normal blink** (both eyes close together): ignored, no page turn fires
- **On-screen arrows**: always available for manual navigation; tap anywhere in the viewer to reveal them
- **Swipe**: swipe left or right across the page as an alternative touch gesture
- **Wink toggle**: reveal the in-viewer controls and tap the toggle to disable wink detection instantly, without closing your piece

At the first page, a back wink does nothing (you will feel a subtle bump). At the last page of a piece in a setlist, a forward wink opens the next piece automatically.

---

## Calibration

Calibration teaches Wink Music how your eyes move. It is worth running if winks are not registering reliably, if detection feels slow, or if you wear glasses or contact lenses.

Open Settings and tap Calibrate. A small camera preview shows your face in real time. Follow the prompts: wink your right eye when asked, then your left. Wink Music watches your open and closed values live and suggests thresholds that fit you specifically.

You can also reach calibration from inside the viewer using the calibrate shortcut in the controls, without closing your piece.

---

## Sensitivity

**Responsive** uses lower thresholds and shorter hold times. Winks fire quickly, which suits practice sessions, but may produce occasional accidental turns.

**Balanced** is the default. It works well for most people and most situations.

**Deliberate** uses higher thresholds and a longer hold time. It is designed for live performance, where an accidental page turn would be disruptive. Deliberate mode also supports double-wink confirmation, which requires two quick winks of the same eye to fire a single turn.

**Custom** lets you set each detection value manually with sliders. Use it after calibration if no preset feels quite right.

---

## Setlists

A setlist is an ordered collection of pieces. You might create one for a recital, a practice session, or a gig.

Tap the Setlists tab and the plus button to create one. Give it a name, then add pieces from your library. Pieces can belong to more than one setlist.

When you open a setlist in performance mode, winking through the last page of one piece automatically opens the first page of the next. You can work through an entire programme without touching the screen. Reorder pieces within a setlist by dragging them.

---

## Troubleshooting

**Face not detected**

A small indicator appears when Wink Music cannot see your face. Common causes:

- Your face is outside the camera's field of view. Adjust the stand angle so the front camera points toward your face.
- The room is too dark. ARKit needs some light on your face to track it. Try adding a light source near the stand.
- Something is partially covering the front camera, such as a case or a finger.

Wink Music resumes detection automatically once your face is visible again.

**Eyes feel reversed**

If winking your right eye goes back instead of forward, open Settings and toggle "Eyes feel reversed." This flips the mapping immediately without requiring recalibration.

**Winks are not registering**

First check that the face-detected indicator is showing. Then try running a fresh calibration or switching to a more responsive sensitivity preset. If you wear glasses or contact lenses, calibrate with them in place. Make sure wink detection is toggled on inside the viewer.

If you are using Deliberate mode with double-wink confirmation, remember that two quick winks of the same eye are required to fire a single page turn.

**Camera permission was denied**

Go to the Settings app on your device, scroll down to Wink Music, and turn Camera on. Without camera permission, wink detection cannot run. The rest of the app, including the library, import, and manual navigation, continues to work normally.

**Accidental page turns**

Switch to the Balanced or Deliberate sensitivity preset. You can also enable double-wink confirmation in Settings for an extra layer of protection. The cooldown period built into detection prevents rapid double-fires after any turn.

---

## Privacy

Wink Music reads two numeric values per eye per frame from ARKit. That is the full extent of camera data it uses. No images or audio are recorded. Nothing leaves your device.

Your sheet music files are stored in the app's private sandbox on your device. Deleting Wink Music removes everything permanently. There is no server, no account, and nothing stored remotely.

For full details, read the [Privacy Policy](./privacy-policy.md).

---

## Use at your own risk

Wink Music is provided as-is. Wink detection depends on your device's camera hardware, Apple's ARKit framework, ambient lighting, face position, and other factors outside the developer's control. Daniel Singh makes no guarantee that detection will work reliably in every situation.

For important performances, verify that detection is working before you begin. On-screen arrows and swipe are always available as a backup, regardless of whether wink detection is active.

---

## Contact

For support questions or bug reports, contact Daniel Singh through the Wink Music listing on the App Store. Please include your device model and iOS version so the issue can be looked into.

---

*Wink Music is developed independently by Daniel Singh.*
