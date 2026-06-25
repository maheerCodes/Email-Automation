# Security Policy

## 🛡️ Our Commitment to Security
At **Sadia AI**, we take the security of your data and automation workflows very seriously. Since this project interacts with sensitive platforms like **Gmail** and **Google Sheets** via **OAuth 2.0**, we are committed to maintaining a secure environment for all users.

## ✅ Supported Versions
Only the latest stable version of Sadia AI is supported for security updates. Please ensure you are always using the most recent `.json` workflow from the [Releases](https://github.com/maheerCodes/Email-Automation/releases) page.

| Version | Supported          |
| ------- | ------------------ |
| v1.x    | :white_check_mark: |
| < v1.0  | :x:                |

## 🚨 Reporting a Vulnerability
**Please do not report security vulnerabilities through public GitHub issues.** 

If you discover a potential security flaw (e.g., credential leakage logic, prompt injection risks, or OAuth handling issues), please report it privately.

You can report vulnerabilities by:
1. **Email:** Send a detailed report to **maheer.codes@gmail.com**.
2. **GitHub Private Reporting:** Use the "Report a vulnerability" button under the **Security** tab of this repository.

We will acknowledge your report within **48 hours** and provide a timeline for a fix.

## 🔒 Safe Usage Best Practices
To keep your Sadia AI setup secure, please follow these guidelines:

1. **Credentials:** Never hardcode your `Client Secret` or `API Keys` inside the JavaScript nodes. Always use n8n's built-in **Credentials** system.
2. **Environment Variables:** If self-hosting n8n, ensure your `.env` file is properly secured and not publicly accessible.
3. **Workflow Export:** Before sharing your exported `.json` file with others, ensure it does not contain any sensitive session keys or personal data.
4. **API Limits:** Monitor your Google AI Studio usage to prevent unauthorized token consumption.

---
**Thank you for helping us keep Sadia AI secure for everyone!** ❤️
