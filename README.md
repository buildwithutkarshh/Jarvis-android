JARVIS Android app - setup guide (Hinglish)
Ye app aapke Jarvis web page ko phone pe full screen kholta hai aur "Jarvis" bolte hi Live baat shuru kar deta hai.
A. Picovoice AccessKey (free)
console.picovoice.ai kholo, free account banao.
AccessKey copy karke rakh lo (baad me app me paste karni hai).
B. APK banao (phone se bhi ho jata hai)
GitHub pe naya repo banao, naam: jarvis-android (Public ya Private, dono chalega).
Repo me Add file > Upload files dabao aur jarvis-android.zip chuno. Zip ko extract mat karna. Commit karo.
Add file > Create new file dabao. Naam ki jagah likho: .github/workflows/build.yml (slash likhte hi folder ban jata hai).
Diya hua build.yml ka poora text paste karo. Commit new file dabao.
Actions tab kholo. "Build Jarvis APK" chalta dikhega (3-6 minute). Hara tick aane tak ruko.
Repo ke home page pe Releases (right side) kholo. Latest build ke neeche app-debug.apk download karo.
C. Install
Downloads se app-debug.apk kholo. "Install unknown apps" poochhe to Chrome/Files ke liye allow karo.
Install dabao. Play Protect warning aaye to "Install anyway".
Purani build ke upar naya install karna ho to seedha install ho jata hai (signature same rehta hai). Error aaye to pehle purana Jarvis uninstall karo.
D. Pehli baar setup (Jarvis app kholo, setup screen aayegi)
Jarvis page address: https://buildwithutkarshh.github.io/JARVIS/ (ya apna link)
Picovoice AccessKey paste karo.
Teeno buttons dabao: microphone/camera/notifications Allow, display over other apps ON, battery do not restrict.
Save and start listening dabao. Notification dikhegi: Listening for "Jarvis".
Open Jarvis dabao. Page me ek baar: key AAPKI_GEMINI_KEY likho (ye app ka alag browser hai).
Ab screen band karke ya kisi aur app me "Jarvis" bolo.
E. Vivo (Funtouch OS) ke liye zaroori
Settings > Apps > Special app access > Autostart > Jarvis ON
Settings > Battery > Background power consumption management > Jarvis > Don't restrict
Recent apps screen me Jarvis ke card ko lock karo
App permissions: Display on lock screen aur Background pop-ups allow karo
F. Dikkat aaye to
Actions me laal X: us run pe tap karo > "Build debug APK" step pe tap karo > error ka screenshot bhejo.
"Wake word error ..." notification: AccessKey galat ya internet nahi. Setup me dobara paste karo.
"Jarvis" bolne par kuch nahi hota: (1) notification dikh rahi hai? (2) Vivo settings (E) kiye? (3) "display over other apps" ON hai?
Page me mic blocked: Setup me microphone Allow karo, app dobara kholo.
Phone restart ke baad app ek baar khud kholo aur "Save and start listening" dobara dabao (Android 14 ka rule).
Android app me browser wali speech recognition nahi hoti; Live mode chalta hai.
Ye app sirf aapke apne phone ke liye hai (debug build), Play Store ke liye nahi.
