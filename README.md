# Custos — Local-First Guardian for Sensitive Financial Data Before It Reaches AI

**AI can help with money. Custos keeps the sensitive parts yours. A free, privacy-first, local-first guardian that detects and controls sensitive financial data before it reaches AI services.**

[![Live App](https://img.shields.io/badge/Live%20App-custos.lyfmail.com-teal)](https://custos.lyfmail.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://github.com/lyfmail-official/custos/blob/main/LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Installable-orange.svg)](https://custos.lyfmail.com)
[![Privacy](https://img.shields.io/badge/Privacy-Local--First-green.svg)](https://custos.lyfmail.com)
[![Maintained by LYF Mail](https://img.shields.io/badge/Maintained%20by-LYF%20Mail-red)](https://lyfmail.com)

A free project from [LYF Mail](https://lyfmail.com) — India's privacy-first digital wellness platform.

---

## 🛡️ What Is Custos?

**Custos** is a free, privacy-first, **local-first guardian for sensitive financial data**. It detects cards, IDs, UPI handles, credentials, balances and spending clues **locally in your browser**, then lets you **block, redact, intelligently generalize or knowingly allow** — with a tamper-evident record of each choice.

**No account. No cloud inspection. Your text stays in your browser.**

Built by [LYF Mail](https://lyfmail.com), a [privacy-first digital wellness platform](https://lyfmail.com) serving 50,000+ subscribers across India since 2020, Custos extends our mission of **"Every Choice Shapes Tomorrow"** into everyday money and AI use.

---

## 🧭 Why Custos Exists

- 🤖 **AI assistants now help with budgeting, invoices, tax and spending questions** — all of which involve money.
- 💳 **Financial details are easy to paste by accident:** card numbers, Aadhaar, PAN, UPI handles, account numbers, balances.
- ☁️ **Once text is sent to an online service, you no longer control where it goes.**

Custos reduces accidental disclosure **without pretending every sensitive detail can be perfectly identified**.

---

## ✨ Key Features

### 🔎 Advanced Detection
Detects cards (with brand), Aadhaar, PAN, IFSC, UPI handles, IBAN, SSN, account numbers, CVV and expiry, OTPs and passwords, API keys, crypto wallets, email, phone numbers and dates of birth. Matches are **validated by checksums** (Luhn, Verhoeff, IBAN mod-97) to cut false alarms.

### 🧩 Intelligent Generalization
*"I spent ₹42,000 at Titan"* becomes *"I spent a mid-sized amount at a jewelry & watch retailer."* Income and balances are withheld, and identifiers get **consistent placeholders** so the AI can still follow your story.

### 🎚️ Risk Score and Control
See a **live 0–100 risk score**, highlighted matches, and untick false positives before deciding. Custos suggests the safest sensible action: **block, redact, generalize or allow**.

### 🔗 Verifiable Local Log
Only **categories, score and decision** are recorded — **never your text**. The log uses a SHA-256 hash chain with a one-click integrity check and JSON export.

### 📊 Insight Dashboard
Weekly activity, average risk, and the categories you expose most often.

### 📱 Installable PWA
Works offline on desktop and mobile, with dark-mode support.

### 🧷 Custos Guard — Chromium Extension
The v2 extension intercepts **Enter and form submits** in prompt boxes, shows a **risk-scored review panel**, and lets you redact, generalize, cancel or send anyway — using the **same engine as the dashboard**.

---

## 🧬 How Custos Works

1. **Paste or compose** — review text before using an AI money assistant.
2. **Scan locally** — patterns, checksums and context are checked on your device.
3. **Choose** — block, redact, generalize or allow with consent.
4. **Copy safe text** — review the result, then decide where to send it.

Try the **built-in sample**: it uses synthetic data only, and nothing is sent to a server.

---

## ⚠️ Honest Limits

- **Not a bank connection.** Custos never connects to accounts or retrieves transactions.
- **Not a universal firewall.** It cannot see other apps, iframes, or custom network calls. It is a best-effort guard.
- **Not a guarantee.** Detection is heuristic. Always review proposed output before sharing.

---

## 🚀 Quick Start Guide

### For Users
1. **Visit** [custos.lyfmail.com](https://custos.lyfmail.com) and open the **Dashboard**.
2. **Paste your text** into the scanner (or load the built-in sample).
3. **Review the risk score** and matches, then choose block, redact, generalize or allow.
4. **Copy the safe text**, and install Custos as an app for offline use.

### For Developers
```bash
git clone https://github.com/lyfmail-official/custos.git
cd custos
python -m http.server 8080   # or: npx serve .
```
Open `http://localhost:8080`. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines.

---

## 🌍 Who Uses Custos?

### 💼 Professionals Using AI Tools
People who work with financial text and use AI chat assistants every day.

### 🧾 Freelancers & Small Business Owners
Anyone handling invoices, statements and client financial details.

### 🇮🇳 Indian Users
Built-in awareness of Aadhaar, PAN, IFSC and UPI formats.

### 🔒 Privacy-Conscious Individuals
Anyone who wants to think twice before pasting money-related details into AI.

---

## 🤝 Contributing to Custos

Custos welcomes contributions that respect our core principles:

- **Local-first** — analysis must run in the user's browser; never send user text to a server.
- **Never store the text** — the local log may record categories, score and decision only.
- **Honest limits** — detection is heuristic; never claim guaranteed protection.
- **Privacy-first** — never introduce tracking, analytics or unnecessary data collection.
- **Accessibility-first** — every feature must work for users with disabilities.

Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) before submitting pull requests. To report a vulnerability, see [`SECURITY.md`](SECURITY.md).

---

## 🏗️ The LYF Mail Ecosystem

Custos is one of **fifteen free privacy-first apps** built by [LYF Mail](https://lyfmail.com), a [digital wellness platform](https://lyfmail.com) from Varanasi, India, serving 50,000+ subscribers since 2020. Browse them all at [lyfmail.com/privacy-first-apps](https://lyfmail.com/privacy-first-apps), or explore our other projects:

| Project | Description | Live App | Repository |
|---------|-------------|----------|------------|
| **[LYF Mail](https://lyfmail.com)** | Privacy-first newsletters for health, wealth, career & mindfulness. | [lyfmail.com](https://lyfmail.com) | `lyfmail` |
| **[LYF Mail App](https://app.lyfmail.com)** | Installable app with newsletters, guides and free tools. | [app.lyfmail.com](https://app.lyfmail.com) | `lyfmail-pwa` |
| **[Ebb](https://ebb.lyfmail.com)** | Private period and fertility tracker. Data stays on your device. | [ebb.lyfmail.com](https://ebb.lyfmail.com) | `ebb` |
| **[Together](https://together.lyfmail.com)** | Silent shared presence for calm. No feed, no likes, no chat. | [together.lyfmail.com](https://together.lyfmail.com) | `together` |
| **[Rewriter](https://rewriter.lyfmail.com)** | Private narrative therapy writing companion with six guided phases. | [rewriter.lyfmail.com](https://rewriter.lyfmail.com) | `rewriter` |
| **[Offload](https://offload.lyfmail.com)** | Pre-sleep brain dump with pink noise, optional binaural beats and a dream journal. | [offload.lyfmail.com](https://offload.lyfmail.com) | `offload` |
| **[Mnemo](https://mnemo.lyfmail.com)** | Private encrypted second brain with on-device AI search and chat. | [mnemo.lyfmail.com](https://mnemo.lyfmail.com) | `mnemo` |
| **[Psychelog](https://psychelog.lyfmail.com)** | Encrypted integration journal with on-device insights and therapist export. | [psychelog.lyfmail.com](https://psychelog.lyfmail.com) | `psychelog` |
| **[Fitrail](https://fitrail.lyfmail.com)** | Encrypted fitness, sleep and workout tracker with route privacy. | [fitrail.lyfmail.com](https://fitrail.lyfmail.com) | `fitrail` |
| **[TrustLens](https://trustlens.lyfmail.com)** | Check news, links and forwarded messages for misinformation before you share. | [trustlens.lyfmail.com](https://trustlens.lyfmail.com) | `trustlens` |
| **[LYF SOS](https://lyfsos.lyfmail.com)** | Offline emergency mesh network for Android. Built for India. | [lyfsos.lyfmail.com](https://lyfsos.lyfmail.com) | `lyfsos` |
| **[PDPR](https://pdpr.lyfmail.com)** | Public Dark-Pattern Registry. Document deceptive UX ethically. | [pdpr.lyfmail.com](https://pdpr.lyfmail.com) | `pdpr` |
| **[Signals](https://signals.lyfmail.com)** | Privacy-first analytics. Human vs. bot detection without cookies or fingerprinting. | [signals.lyfmail.com](https://signals.lyfmail.com) | `signals` |
| **[HireStack](https://hirestack.lyfmail.com)** | Nine free career tools for freelancers and job seekers. Works offline. | [hirestack.lyfmail.com](https://hirestack.lyfmail.com) | `hirestack` |
| **[Veilora](https://veilora.lyfmail.com)** | Six free tools for creators: clean image metadata, scan text, check before publishing. | [veilora.lyfmail.com](https://veilora.lyfmail.com) | `veilora` |

### 📚 Free Newsletters & Guides
- [Health & Wellness Guide](https://lyfmail.com/health-wellness-guide)
- [Personal Finance Guide](https://lyfmail.com/personal-finance-guide)
- [Career Development Guide](https://lyfmail.com/career-development-guide)
- [Creativity Resources](https://lyfmail.com/creativity-resources)
- [Mindfulness Practices](https://lyfmail.com/mindfulness-practices)

**Newsletter Signups:** [Health](https://health.signup.lyfmail.com) · [Finance](https://financing.signup.lyfmail.com) · [Career](https://career.signup.lyfmail.com) · [Creativity](https://creativity.signup.lyfmail.com) · [Personal Development](https://intuition.signup.lyfmail.com)

---

## 📜 License

Custos is released under the **MIT License**. You are free to use, modify and distribute it — including commercially. See [`LICENSE`](LICENSE) for full terms.

---

## 📫 Connect With Us

- **🌐 Website:** [lyfmail.com](https://lyfmail.com)
- **🛡️ Custos App:** [custos.lyfmail.com](https://custos.lyfmail.com)
- **🛠️ All Privacy-First Apps:** [lyfmail.com/privacy-first-apps](https://lyfmail.com/privacy-first-apps)
- **📱 PWA:** [app.lyfmail.com](https://app.lyfmail.com)
- **📚 Documentation:** [docs.lyfmail.com](https://docs.lyfmail.com)
- **🎨 Brand Assets:** [github.com/lyfmail-official/lyfmail-brand-assets](https://github.com/lyfmail-official/lyfmail-brand-assets)
- **🐦 X / Twitter:** [LYF Mail](https://x.com/lyfmailcom)
- **📘 Facebook:** [LYF Mail](https://www.facebook.com/thelyfmail)
- **▶️ YouTube:** [LYF Mail](https://m.youtube.com/channel/UCurymhWrl2nkvv31uJMuc0g)
- **💼 LinkedIn:** [LYF Mail](https://www.linkedin.com/company/lyf-mail)
- **📧 General Email:** contact@lyfmail.com
- **🆘 Support:** [support.lyfmail.com](https://support.lyfmail.com)

---

*"Every Choice Shapes Tomorrow"*

**Maintained by [LYF Mail](https://lyfmail.com)** · Founded by [Ajay Kumar Chaudhary](https://github.com/lyfmail) · Varanasi, Uttar Pradesh, India · Since 2020

---

## 💬 Frequently Asked Questions

**Q: Does Custos send my text to a server?**  
A: No. Analysis runs in your browser, and your text stays there. Only categories, a score and your decision are written to the local log, never the text itself.

**Q: What kinds of data does Custos detect?**  
A: Cards (with brand), Aadhaar, PAN, IFSC, UPI handles, IBAN, SSN, account numbers, CVV and expiry, OTPs and passwords, API keys, crypto wallets, email, phone numbers and dates of birth.

**Q: What does generalization mean?**  
A: Instead of removing a detail completely, Custos replaces it with a safer, less specific version. For example, an exact purchase amount at a named shop becomes a mid-sized amount at a type of retailer. Identifiers get consistent placeholders so the AI can still follow the story.

**Q: Does Custos guarantee that nothing sensitive reaches an AI tool?**  
A: No. Detection is heuristic and the extension cannot see other apps, iframes or custom network calls. Always review the output before sharing.

**Q: Is Custos financial or legal advice?**  
A: No. Custos is a privacy tool. It never connects to your bank and does not provide financial, legal or compliance advice.

**Q: Can I install it?**  
A: Yes. Custos is an installable PWA that works offline on desktop and mobile. A separate Chromium extension, Custos Guard, checks prompts at the send button.

**Q: Is Custos free to use?**  
A: Yes. Custos is free to use under the MIT License, a project by [LYF Mail](https://lyfmail.com).

**Q: Can I contribute to Custos?**  
A: Yes. We welcome developers, designers, writers, translators and accessibility advocates. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) first.

**Q: How do I report a bug or a security issue?**  
A: Open a [GitHub issue](https://github.com/lyfmail-official/custos/issues) for bugs. For security vulnerabilities, **do not** open a public issue — follow [`SECURITY.md`](SECURITY.md).

---

*This README is maintained by the LYF Mail team. For issues, feature requests or contributions, please visit our [GitHub repository](https://github.com/lyfmail-official/custos).*
