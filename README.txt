Personal AI - Android APK (GitHub দিয়ে অনলাইনে বানানো)

1. github.com-এ বিনামূল্যে অ্যাকাউন্ট খুলুন, তারপর নতুন একটা Repository বানান (নাম: personal-ai)।
2. "uploading an existing file" চাপুন এবং এই ফোল্ডারের সব ফাইল/ফোল্ডার (www, .github, package.json, capacitor.config.json) টেনে ছেড়ে দিন, তারপর Commit করুন।
3. Actions ট্যাবে যান -> "Build Android APK" -> Run workflow। ৫-৮ মিনিট অপেক্ষা করুন।
4. কাজ শেষ হলে ওই রানের নিচে Artifacts থেকে PersonalAI-apk নামিয়ে নিন (zip খুললে app-debug.apk পাবেন)।
5. APK ফোনে পাঠিয়ে ইনস্টল করুন (Unknown sources / এই উৎস থেকে ইনস্টল চালু করতে হতে পারে)।

সার্ভারে CORS চালু থাকতে হবে (Ollama: OLLAMA_ORIGINS=*)।
