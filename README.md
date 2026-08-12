# RK Family A/C Android App

এই project-টি Android 7.0+ এর জন্য তৈরি। এটি আপনার
`https://rk-family-accounting.ai.studio/` অ্যাপটি WebView-এর মধ্যে চালায়।

## APK বানানো
Android Studio-তে project folder খুলে:
Build > Build App Bundle(s) / APK(s) > Build APK(s)

Debug APK তৈরি হবে:
`app/build/outputs/apk/debug/app-debug.apk`

এই debug APK signed এবং test/install করার জন্য ব্যবহারযোগ্য।

## GitHub Actions
Project-টি GitHub-এ push করে Actions থেকে "Build APK" চালালে APK artifact হিসেবে পাওয়া যাবে।
