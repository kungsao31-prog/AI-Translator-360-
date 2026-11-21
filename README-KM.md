# AI Translator 360

គម្រោង Android ថ្មីដាច់ដោយឡែក (applicationId: `com.aitranslator360.app`).

## Build APK
1. បង្កើត GitHub repository ថ្មីឈ្មោះ `AI-Translator-360`.
2. Upload មាតិកាទាំងអស់ក្នុង ZIP នេះទៅ root repository.
3. បើក Actions ហើយរត់ workflow `Build AI Translator 360 APK`.
4. ពេល workflow ជោគជ័យ ទាញយក artifact `AI-Translator-360-debug-apk` ហើយយក `app-debug.apk` ដំឡើង។

## ស្ថានភាពមុខងារ
- មាន Android WebView shell និង file picker សម្រាប់ជ្រើសរើស media។
- មាន UI ផ្ទាំងមុខងារ 8 ប្រភេទ និងការកំណត់ Backend URL។
- ការបកប្រែពិត, speech-to-text, Khmer TTS, OCR, video dubbing, subtitle timing, export MP4 និងការរក្សាទុកឯកសារ ត្រូវការភ្ជាប់/អភិវឌ្ឍ Backend និង native APIs បន្ថែម។ UI មិនអះអាងថាមុខងារទាំងនេះរួចរាល់ទេ។
- Endpoint ដែល UI រំពឹងទុកសម្រាប់ prototype: `POST /api/translate` ជា multipart form data។

## សុវត្ថិភាព
កុំដាក់ Gemini/API keys ក្នុង HTML ឬ APK។ រក្សា secrets នៅ Backend ប៉ុណ្ណោះ។
