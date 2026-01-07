<h1>📱 Live Notification Android</h1>
<p><em>(Progress-Centric Notifications for Android 16)</em></p>

<p><strong>Live Notification Android</strong> demonstrates the use of the <strong>progress-centric notifications</strong> — a new feature introduced in <strong>Android 16 (API level 36)</strong> — to display live and dynamic updates directly in the notification shade.</p>

<h1>🎬 Demo</h1>
<p align="left">
    <a title="live_notification_android_segment_style">
      <img src="https://github.com/r1n1os/Live-Notification-Android/raw/main/screenshots/live_notification_android_segment_style.gif" height="530" width="250">
    </a>
 <a title="live_notification_android_segment_point_style"> <img src="https://github.com/r1n1os/Live-Notification-Android/raw/main/screenshots/live_notification_android_segment_point_style.gif" height="530" width="250">
    </a>
</p>

<h2>🚀 Features</h2>
<ul>
  <li>✅ Support for <strong>Live Progress-centric Notifications</strong> (Android 16+ only)</li>
  <li>🧪 Includes a <strong>local simulation</strong> to test live updates without a server</li>
  <li>🧩 Clean and minimal implementation using modern Android APIs</li>
</ul>


<h2>📦 Requirements</h2>
<ul>
  <li><strong>Target SDK</strong>: 36 (Android 16 Preview)</li>
</ul>
<p><strong>⚠️ Note:</strong> Live updates only work on Android 16 (API 36) and above. Devices running lower versions will not support this feature.</p>


<h2>⚙️ Configuration Summary</h2>
<pre><code>compileSDK: 36
targetSDK: 36
minSDK: 28
gradle: 8.14.2
agp: 8.5.0
kotlin: 2.1.21
</code></pre>

<h2>🔨 Building APK Files</h2>

<h3>Using GitHub Actions (Recommended)</h3>
<p>The project includes a GitHub Actions workflow that automatically builds APK files on push to main branch or pull requests. The built APK files are available as downloadable artifacts in the Actions tab.</p>

<h3>Building Locally</h3>
<p>To build the APK files locally, ensure you have:</p>
<ul>
  <li>JDK 17 or higher</li>
  <li>Android SDK with API level 36 installed</li>
</ul>

<p><strong>Build debug APK:</strong></p>
<pre><code>./gradlew assembleDebug</code></pre>

<p><strong>Build release APK:</strong></p>
<pre><code>./gradlew assembleRelease</code></pre>

<p>The built APK files will be located in:</p>
<ul>
  <li>Debug: <code>app/build/outputs/apk/debug/app-debug.apk</code></li>
  <li>Release: <code>app/build/outputs/apk/release/app-release-unsigned.apk</code></li>
</ul>

>[!NOTE]
> Medium Article
For a full walkthrough and explanation, check out the accompanying Medium article: <br>
👉 <a href="https://r1n1os.medium.com/level-up-android-notifications-with-live-progress-centric-styles-android-16-605d34781ad1" target="_blank">Level Up Your Android Notifications with Progress-Centric (Live) Notifications in Android 16+</a></li>
>


<h2>📚 References</h2>
<ul>
  <li><a href="https://developer.android.com/about/versions/16/features/progress-centric-notifications" target="_blank">Progress-Centric Notifications – Android 16 Documentation</a></li>
  <li><a href="https://github.com/android/platform-samples/tree/main/samples/user-interface/live-updates" target="_blank">Live Updates – Android Platform Samples (GitHub)</a></li>
  <li><a href="https://github.com/NicosNicolaou16/Live_Update_Notifcation_Android" target="_blank">Live Update Notification – Community Sample by NicosNicolaou16</a></li>
</ul>
