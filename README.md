# Blog Link: here


### Steps to Get Started
Here’s how you can start using Chrome Built-in AI:

- **Install Latestst Chrome**: Make sure you have version 128.0.6545.0 or above.
- **Enable Gemini Nano and the Prompt API**:
   - Go to `chrome://flags` and search for "Gemini Nano".
   - Enable the "Gemini Nano" API you want to use. (`Rewriter API for Gemini Nano` must for this blog)
   - Relaunch Chrome after enabling these settings.

---

### Confirming Availability
To ensure the Gemini Nano model is available:
- Open Chrome DevTools.
- Check if the Gemini Nano model is downloaded and ready to use. By running the following code in the Console tab, you can confirm the availability of the model:
```javascript
  (await window.ai.languageModel.capabilities()).available // readily
```
#### Note: If the model is not available, you may need to wait for it to download.

---

### Live Preview:
![chrome-capture-2024-12-8 (1)](https://github.com/user-attachments/assets/d5b07db1-04de-4b51-b898-afc8012856f8)
