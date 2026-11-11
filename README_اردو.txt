شاپ رینٹ مینجمنٹ — Android Studio پروجیکٹ

یہ ایک Android WebView ایپ پروجیکٹ ہے جس میں آپ کا موجودہ HTML پروگرام شامل ہے۔

APK بنانے کا طریقہ:
1) کمپیوٹر میں Android Studio انسٹال کریں۔
2) Android Studio میں اس فولڈر ShopRentAndroid کو Open کریں۔
3) Gradle Sync مکمل ہونے دیں۔
4) Build > Build Bundle(s) / APK(s) > Build APK(s) منتخب کریں۔
5) APK عموماً app/build/outputs/apk/debug/app-debug.apk میں ملے گی۔

اہم:
- پہلی بار Android Studio کو Gradle اور Android SDK ڈاؤن لوڈ کرنے کے لیے انٹرنیٹ درکار ہوگا۔
- ایپ کا ریکارڈ اسی موبائل کے اندر WebView storage میں محفوظ رہتا ہے۔
- فون تبدیل کرنے یا ایپ کا ڈیٹا صاف کرنے سے پہلے بیک اپ ضرور بنائیں۔
- Tailwind CSS اور Google Fonts اصل HTML کے مطابق انٹرنیٹ سے لوڈ ہوتے ہیں؛ ان کے بغیر ڈیزائن محدود ہو سکتا ہے، اگرچہ بنیادی جاوااسکرپٹ کام کرتا ہے۔
