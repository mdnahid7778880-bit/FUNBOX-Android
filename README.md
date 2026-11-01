# FUNBOX Android Native Project
**Package Name:** `com.funbox.entertainment`  
**Tagline:** *Less Boring, More Laughing! 😂 (কম বোরিং, বেশি হাসাহাসি!)*  
**Architecture:** Kotlin, Jetpack Compose, Material 3, MVVM, Room, Navigation Compose  
**Developer:** Shuvo Nahid (WhatsApp: +8801918732722)

---

## 📱 How to Build a Signed APK with Android Studio (ধাপে ধাপে গাইড)

### Step 1: Open Project in Android Studio
1. Open **Android Studio** (Ladybug, Koala, Hedgehog, or newer).
2. Click **File -> Open...** and select the `android` folder from this project.
3. Wait for **Gradle Sync** to finish downloading dependencies.

### Step 2: Test on Emulator / Physical Device
1. Connect your Android phone with **USB Debugging** enabled (or start an Android Virtual Device emulator).
2. Click the green **Run (▶)** button in the top toolbar to install the debug APK.

### Step 3: Generate Signed APK (রিলিজ APK তৈরি)
1. Android Studio এর মেনু থেকে যান: **Build -> Generate Signed Bundle / APK...**
2. **APK** সিলেক্ট করে **Next** ক্লিক করুন।
3. **Key store path** এ:
   - নতুন হলে **Create new...** ক্লিক করুন।
   - একটি পাসওয়ার্ড এবং কি-স্টোর পাথ দিন (যেমন `funbox-keystore.jks`)।
   - Key Alias দিন (যেমন `funbox_key`) এবং পাসওয়ার্ড নিশ্চিত করুন।
4. **Next** বাটনে ক্লিক করুন।
5. **Destination Folder** সিলেক্ট করুন এবং Build Variants এ **release** নির্বাচন করুন।
6. **V1 (Jar Signature)** এবং **V2 (Full APK Signature)** উভয় চেকবক্সে টিক দিন।
7. **Create / Finish** বাটনে ক্লিক করুন!

কয়েক মুহূর্তের মধ্যে আপনার Signed Release APK তৈরি হয়ে যাবে:
`app/release/app-release.apk`
আপনি এটি যেকোনো অ্যান্ড্রয়েড ফোনে সরাসরি ইনস্টল করে চালাতে ও বন্ধুদের শেয়ার করতে পারবেন!
