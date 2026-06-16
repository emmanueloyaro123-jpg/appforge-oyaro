# AppForge by OYARO - Frequently Asked Questions

## Installation & Setup

### Q: Where do I download AppForge?
**A:** Download from the [Releases page](https://github.com/emmanueloyaro123-jpg/appforge-oyaro/releases)

### Q: Is it safe to install APK from unknown sources?
**A:** Yes, if you trust the source. AppForge is open-source, so you can inspect the code.

### Q: Do I need Android 12+?
**A:** No, AppForge works on Android 11 and above.

### Q: How much storage do I need?
**A:** Minimum 500MB free space for app generation.

---

## Creating Apps

### Q: Do I need to know how to code?
**A:** No! You can describe what you want in plain English and AI will generate the code.

### Q: How long does it take to build an app?
**A:** 2-5 minutes depending on device performance and code complexity.

### Q: Can I create games?
**A:** Yes! You can use HTML5 Canvas and JavaScript to create games.

### Q: Are there templates?
**A:** Yes, AppForge includes 60+ demo apps you can use as templates.

### Q: Can I edit the generated code?
**A:** Absolutely! Use the built-in code editor to customize.

---

## AI Code Generation

### Q: Do I need internet to use AppForge?
**A:** You need internet only for AI code generation. Everything else works offline.

### Q: Which AI providers are supported?
**A:** 
- Anthropic Claude
- OpenAI GPT-4
- Google Gemini
- OpenRouter
- Local LLMs

### Q: Do I need an API key?
**A:** Yes, for AI code generation. Get free credits from providers.

### Q: Is my API key safe?
**A:** API keys are stored locally on your device only.

---

## App Features

### Q: What can I access with native bridges?
**A:** Camera, GPS, sensors, contacts, calendar, SMS, phone calls, files, audio, notifications, and more (37+ features).

### Q: How do I use the camera in my app?
**A:** Use:
```javascript
window.iappyx.camera.takePicture().then(photo => {
    // Use photo
});
