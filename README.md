# PriviPaste

<div align="center">
  <img src="https://raw.githubusercontent.com/StackMindset/PriviPaste/main/icon.png" alt="PriviPaste Logo" width="128">
  
  ### Local PII Redactor for Safer AI Pair Programming
  
</div>

## About

**PriviPaste** is a privacy first VS Code extension that redacts Personally Identifiable Information (PII) locally on your machine. It ensures your sensitive data (names, emails, API keys, etc.) is fully sanitized **before** you share it with AI coding assistants, external chat bots, or web interfaces.

PriviPaste operates entirely offline using open source models, guaranteeing zero data leakage.

**[Download PriviPaste on the VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=stackmindset.privipaste)**

## Our Privacy Guarantee

We understand that you are trusting us with your most sensitive codebase data. **PriviPaste is built with a strict "Local First" philosophy:**

1. **100% Local Processing:** All AI redaction happens locally inside your VS Code instance using the Transformers.js engine.
2. **No Data Collection:** We do not track, collect, or monitor the text you highlight, your clipboard contents, or your code.
3. **No External APIs:** We never send your code to external servers (not even to OpenAI, Anthropic, or our own servers). Once the AI model is downloaded from Hugging Face during your first run, the extension can operate entirely without an internet connection.
4. **No Telemetry:** We explicitly disable telemetry tracking within the extension.

Your data is yours. PriviPaste's only job is to sanitize it *before* it leaves your machine.

## How to Use

PriviPaste is designed to be completely frictionless.

1. **Copy** any text or code snippet containing sensitive data.
2. **Place your cursor** wherever you want to paste the text (e.g., your code editor, VS Code Copilot Chat, or an AI Assistant input box).
3. **Press `Alt+P`** (or `Cmd+Alt+P` on Mac).
4. The extension will automatically redact the PII and **instantly paste** the safe version right where your cursor is!

## FAQ

**Q: Does my code leave my machine?**  
A: No! All redaction is processed 100% locally on your own hardware.

**Q: Why does it need to download a model?**  
A: To keep the initial extension size small, the AI engine downloads the necessary language model directly from Hugging Face on your very first run. After that, it operates entirely offline.

## Bug Reports & Feature Requests

This repository is the central hub for tracking issues, bugs, and feature requests for PriviPaste. 

*(Note: The core extension code is closed source and maintained privately by StackMindset. This repository serves exclusively as a public issue tracker and documentation hub.)*

### How to get help:
* **Found a bug?** [Open an Issue](https://github.com/StackMindset/PriviPaste/issues/new?labels=bug&title=%5BBug%5D+Brief+description) and provide as much detail as possible (VS Code version, OS, and steps to reproduce).
* **Have a feature idea?** [Request a Feature](https://github.com/StackMindset/PriviPaste/issues/new?labels=enhancement&title=%5BFeature%5D+Brief+description)   we would love to hear how we can make PriviPaste better for your workflow!
* **Chrome Extension Support:** If you are reporting an issue for the upcoming Chrome extension, please include `[Chrome]` in your issue title.

## Links & Resources

* **Website & Tutorials:** [StackMindset.com/privipaste](https://stackmindset.com)
* **VS Code Extension:** [View on Marketplace](https://marketplace.visualstudio.com/items?itemName=stackmindset.privipaste)

---

<div align="center">
  <i>Built with privacy in mind by <a href="https://stackmindset.com">StackMindset</a>.</i>
</div>
