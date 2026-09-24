# DeckBro AI: TikTok & Ecom Script Generator

A local-first e-commerce video script generator browser extension for Google Chrome. Convert Amazon and TikTok Shop product listing pages into humanized UGC script decks using a Bring Your Own Key (BYOK) architecture that processes all text extractions and AI generation requests entirely within the user's local browser sandbox.

Turn Amazon & TikTok Shop pages into humanized UGC script decks — BYOK & 100% local storage for maximum creator privacy

---

## 🚀 Key Features
* **Multi-Store Extraction:** Grab product names, core specifications and technical details directly from Amazon or TikTok Shop product listing pages with a single click.
* **High Retention Script Frameworks:** Generate scripts by choosing from 3 high-velocity social video structures including "The Brutally Honest Review" to build trust, "The Day in the Life Problem Solver" for lifestyle storytelling, and "The Casual Don't Buy This Until..." to stop scrolling thumbs..
* **Targeted Onsite & TikTok Decks:** Dedicated settings for Amazon Onsite Decks (Spec View, Unboxing View, Value Review scripts) to dominate the product carousel and TikTok Decks (Hype Hook, Sensory ASMR, FOMO Pitch scripts) to maximize shoppable video conversions.
* **Multi-Format Simultaneous Generation:** Select the 'Cross Platform' output tab to generate tailored variants for TikTok (complete with native call-to-actions), Instagram Reels (optimized for visual-text synchronization), and YouTube Shorts (featuring infinite-loop scripting mechanics) simultaneously.
* **B-Roll & Visual Direction:** Every script is generated as a complete screenplay deck, featuring dedicated hooks, scene bodies, and synchronized B-roll visual cues detailing precise camera shot instructions.
* **Clean-Clipboard Export:** Tap the 'Copy Script' button on any script card to quickly copy clean text to your clipboard.
* **Volatile State Protection:** Never lose an angle. Your active script deck, framework settings, API keys, and AI model configuration are automatically backed up locally during accidental side panel closures or sudden browser restarts.
* **True BYOK Architecture:** Securely connect your personal OpenAI, Anthropic Claude, or Google Gemini keys directly from your local settings menu.
* **Zero-Host Privacy:** Direct-to-API network isolation guarantees your product data and generated script drafts never touch an external developer server or a third-party intermediary.
* **Framework-Free Architecture:** Built with ultra-lightweight native code and zero bloated libraries for lightning-fast performance inside your side panel.

---

## 🛠️ Getting Started
1. Click 'Add to Chrome' and pin **DeckBro AI** to your toolbar.

2. Open the **DeckBro AI** side panel, click the gear icon (⚙️ - **API Settings**), securely paste your personal API keys (OpenAI, Claude, and/or Gemini).

3. Click your **Select Active Model** from the dropdown menu and click **Save Settings**.

4. Open a supported Amazon or TikTok Shop product listing page. 

5. Choose your output format on the tab menu (**Optimize Output For:**), select your framework from the dropdown menu (**Select Script Framework**), and press **Generate Script Deck**!

Note: Users must input their own personal API keys (OpenAI, Claude, and/or Gemini) to establish connectivity. New users can sign up for credits directly through these providers.

🔑 Tip: Gemini models are free-key friendly. OpenAI and Claude require paid key credits, though some OpenAI models may grant temporary free key access.

---

## 📞 Support & Feedback
If you encounter any bugs, have feature requests, or need technical assistance, please reach out via email:
* **Email:** mailto:corsandeffect@gmail.com

---

## 🔒 Privacy Policy

### 1. Data Handling & Privacy Declarations
To function, this extension processes and handles **Authentication information** (API Keys), **Personal communications** (chat history) and **Website content** (user-highlighted text). We do not collect, track, or store any of this data on external databases or developer servers. All user-generated text inputs, credential assets, and conversation history records remain strictly within your browser's local ecosystem.

### 2. API Key Security & Network Sandbox
* **Local Storage:** Keys are saved encrypted on your device using the browser's native `chrome.storage.local` API sandbox structure.
* **Network Sandbox:** The extension operates under a strict Content Security Policy (`connect-src`). It cannot send information to unauthorized third-party trackers or external tracking endpoints.
* **Direct Transmission:** Your keys and prompt text travel exclusively to the official endpoints:
  * OpenAI (`https://api.openai.com*`)
  * Anthropic Claude (`https://api.anthropic.com*`)
  * Google Gemini (`https://generativelanguage.googleapis.com*`)

### 3. Google Search Grounding Note
When explicitly activating the **Google Search Grounding** feature within Gemini settings, your specific prompt text is transmitted directly to Google Search index routers to pull real-time data into your chat response. No personal identifiers or API keys are exposed during this search.

### 4. Third-Party Disclaimers
Because you supply your own API keys, your prompt data and generation habits fall under the respective developer terms of service and data privacy agreements of the platforms you connect to:
* [OpenAI](https://openai.com/policies/row-privacy-policy/)
* [Anthropic Claude](https://www.anthropic.com/legal/privacy)
* [Google Gemini](https://support.google.com/gemini/answer/13594961?hl=en)

### 5. Policy Updates
Any future revisions to this document will be updated transparently on this landing page. Contact us at the support email above for code review inquiries.

---
