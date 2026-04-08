# MechaRams STEM Trivia — Android App

## How to Build the APK

### Requirements
- [Android Studio](https://developer.android.com/studio) (free, ~1 GB download)
- Java 8 or higher (bundled with Android Studio)

---

### Steps

**1. Open the project**
- Launch Android Studio
- Click **File → Open** and select this `MechaRamsTrivia` folder

**2. Let Gradle sync**
- Android Studio will automatically download dependencies (~30 seconds)
- Wait for the "Gradle sync finished" message at the bottom

**3. Build the APK**
- Click **Build → Build Bundle(s) / APK(s) → Build APK(s)**
- Wait ~1–2 minutes

**4. Find your APK**
- Click **"locate"** in the popup that appears, OR
- Navigate to: `app/build/outputs/apk/debug/app-debug.apk`

**5. Install on your Android device**
- Enable **Settings → Developer Options → USB Debugging** on your phone
- Plug in via USB and click **Run ▶** in Android Studio, OR
- Copy the `.apk` file to your phone and open it (enable "Install unknown apps" in settings)

---

### App Details
- **Package ID:** `com.mecharams.trivia`
- **Min Android version:** Android 5.0 (API 21) — works on almost all modern devices
- **Orientation:** Portrait only
- **Fullscreen:** Yes (immersive mode, hides status/nav bar)
- **Offline:** Yes — all trivia content is bundled, no internet needed

---

### Customization
- To update quiz questions, edit: `app/src/main/assets/index.html`
- To change the app name, edit: `app/src/main/res/values/strings.xml`
- To change the icon, replace the `ic_launcher.png` files in the `mipmap-*` folders
