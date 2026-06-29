# ARSE-AI-exporter
ARES (AI Response Save Extension) is a powerful, privacy-focused browser extension that ensures you never lose a valuable AI conversation. Compatible with over 50 platforms including ChatGPT, Claude, Kimi, and DeepSeek, it automatically scrolls and captures full chat histories, saving them directly to your device as PDF, TXT, or JSON files

# ARES AI Exporter

## About

**ARES (AI Response Save Extension)** is a powerful and easy-to-use browser extension that allows you to seamlessly export your conversations from over 50+ AI chat platforms into clean TXT, JSON, or PDF formats.

Whether you're using ChatGPT, Claude, DeepSeek, Kimi, GLM, Qwen, or others, ARES ensures your valuable chats and AI insights are securely saved to your local device with a single click.

## Features

- 📥 **Export to Multiple Formats:** Save your AI conversations as `.txt`, `.json`, or `.pdf`.
- 🌐 **Wide Compatibility:** Works with top AI platforms including:
  - ChatGPT (`chatgpt.com`, `openai.com`)
  - Claude (`claude.ai`)
  - DeepSeek (`deepseek.com`)
  - Kimi (`kimi.moonshot.cn`, `kimi.ai`, `kimi.com`)
  - Qwen / Tongyi (`qwenlm.ai`, `qwen.ai`, `tongyi.aliyun.com`)
  - ChatGLM (`chatglm.cn`)
  - Perplexity (`perplexity.ai`)
  - Gemini (`gemini.google.com`)
  - Poe (`poe.com`)
  - Copilot (`copilot.microsoft.com`)
  - Pi (`pi.ai`)
  - Hugging Face (`huggingface.co`)
  - Chat Z (`chat.z.ai`)
  - And many more!
- ⌨️ **Keyboard Shortcuts:** Press `Ctrl + X` to quickly export the current chat as a PDF.
- 📜 **Auto-Scrolling:** Automatically scrolls through the chat before exporting to capture all lazy-loaded messages.
- 🕵️ **Privacy Focused:** All data is processed locally on your device. No data is sent to external servers.

## Installation Instructions
###YOUTUBE VIDEO LINK FOR INSTALLATION 
https://youtu.be/3hJUzPrKLmE

Currently, the extension can be installed by loading it as an unpacked extension in Chrome, Edge, or Brave.

1. Download the `ares-ai-exporter.zip` file (or generate it via the app).
2. **Right-click the ZIP file** and select "Extract All..." to unzip it into a regular folder.
3. Open your browser and go to the Extensions page:
   - Chrome/Brave: `chrome://extensions/`
   - Edge: `edge://extensions/`
4. Enable **Developer mode** in the top right corner.
5. Click the **Load unpacked** button.
6. Select the **extracted folder** (not the zip file).
7. The ARES AI Exporter is now installed! Visit any supported AI chat website, and a floating "Export" button will appear in the bottom right corner.

## Usage

1. Open a conversation on any supported AI chat platform.
2. Look for the floating **📥 Export** button in the bottom right corner of the screen.
3. Click the button to reveal export options.
4. Choose your preferred format: **TXT**, **JSON**, or **PDF**.
5. Wait a moment for the extension to capture the full chat (it will auto-scroll if necessary), and the file will download automatically.

## How it works

The extension injects a lightweight content script (`content.js`) into supported AI chat domains. It uses generic and platform-specific DOM selectors to identify user prompts and AI responses, formats them appropriately, and utilizes `jsPDF` for PDF generation directly in the browser.

## Contributing

Contributions are welcome! Feel free to open issues for bug reports or feature requests, or submit pull requests with improvements.

### Adding Support for New Platforms

To add a new platform, simply add its domain to the `aiDomains` array in the main application logic, and ensure the generic selectors correctly capture its chat elements.

## License

This project is licensed under the MIT License.
