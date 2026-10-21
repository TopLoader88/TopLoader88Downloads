# TopLoader88 Downloads

Public, one-tap downloads and browser apps for TopLoader88.
The default branch contains this download page, not the development projects.
The teleprompter's full project remains private; its built browser files are
published separately on the `gh-pages` branch.

**[Open the clean app download page](https://toploader88.github.io/TopLoader88Downloads/)**.

## PodWatch - live whale & orca tracking

Track orcas and whales in near-real time from boat traffic + hydrophones, with
predicted locations and viewing guidance.

**Android**
[Download the APK](https://github.com/TopLoader88/TopLoader88Downloads/releases/download/podwatch/PodWatch.apk)
Open the file on your phone, allow "Install unknown apps" if prompted, then install.

**Windows PC**
[Download for Windows (.zip)](https://github.com/TopLoader88/TopLoader88Downloads/releases/download/podwatch/PodWatch-Windows.zip)
Unzip anywhere, then run **PodWatch.exe**. (Windows SmartScreen may warn on a new
unsigned app - click "More info" then "Run anyway".)

## Local Teleprompter - offline voice-following scripts

Automatically follows your spoken script, with timed and manual scrolling,
microphone selection, document imports, and optional word highlighting.
The runtime and English speech model are bundled for offline use.
The separate display has its own Mirror and Fullscreen buttons. Appearance
settings stay on the control page: dark/light/high-contrast themes, line spacing,
column width and reduced-motion scrolling. The control page stays unmirrored.
Click/tap words in the preview, phone reading view or fullscreen display to change
position. Following continues if already running. Back to start resets and pauses.
Automatic place recovery also follows skipped lines and restarts, using phrase
context around duplicate lines and common retake/start-over hints. With recovery
on, voice mode keeps listening at the end until Pause; phones still pause when
locked/backgrounded. Ambiguous duplicate lines need a little more spoken context.

**iPhone, Android and Mac browser**
[Open the installable browser app](https://toploader88.github.io/TopLoader88Downloads/teleprompter/).
On iPhone, use Safari > Share > Add to Home Screen. On Android, use Chrome's Install
app / Add to Home Screen. On Mac, open it directly in Safari/Chrome/Edge; installation
is optional (Safari File > Add to Dock).

Open the installed app and choose **Save for offline use** (about 53 MB), then
**Check offline engine** in Settings. Keep the phone app visible while reading.
Browser storage may be cleared by the OS or by clearing site data; reconnect and
save again if needed. Safari/iOS 17+ or current Chrome/Edge is recommended.

**Android APK (experimental)**
[Download the offline Android app (.apk)](https://github.com/TopLoader88/TopLoader88Downloads/releases/download/teleprompter-v1.1.0/LocalTeleprompter-1.1.0-Android.apk).
**Experimental:** offline installation and model loading are checked, but native
speech following, full interaction checks and real-phone microphone accuracy are not fully verified.
The browser version above has passed offline reference-speech tests.
The test-signed APK includes the English model and can run offline after a fresh
installation, without a browser model-download step. Android's normal "Install
unknown apps" consent may be needed. Requires Android 7 or newer and an up-to-date
Android System WebView (109+). There is no App Store/iPhone IPA download;
iPhone uses the Home Screen browser app above.

**Windows PC**
[Download the Windows x64 app (.exe)](https://github.com/TopLoader88/TopLoader88Downloads/releases/download/teleprompter-v1.1.0/LocalTeleprompter-1.1.0-Windows-x64.exe)
Run the EXE. No Node installation or terminal window is needed.

**Mac**
[Download for Apple Silicon (.dmg)](https://github.com/TopLoader88/TopLoader88Downloads/releases/download/teleprompter-v1.1.0/LocalTeleprompter-1.1.0-Mac-arm64.dmg)
or [Download for Intel (.dmg)](https://github.com/TopLoader88/TopLoader88Downloads/releases/download/teleprompter-v1.1.0/LocalTeleprompter-1.1.0-Mac-x64.dmg).
Open the DMG, drag **Local Teleprompter** to **Applications**, then open it.

Desktop downloads are not developer-signed or notarized; the Android APK uses a
dedicated test-signing key, not Google Play production signing. Application files are packaged
inside the app, not supplied as loose JavaScript or a source checkout.
Quit the previous desktop version and any older teleprompter server using port 8090
before opening a new download.
[All teleprompter app downloads](https://github.com/TopLoader88/TopLoader88Downloads/releases/tag/teleprompter-v1.1.0).

---

_More apps will be published here._