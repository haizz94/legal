# Privacy Policy for WinFocus

**Last updated:** August 17, 2026

Thank you for choosing **WinFocus**. We are committed to protecting your privacy. This Privacy Policy explains how WinFocus handles user information.

---

## 1. Overview (Privacy by Design)
WinFocus is an offline desktop utility designed to dim inactive background windows and highlight your active foreground window. 

**WinFocus does not collect, store, transmit, or sell any personal data, usage statistics, analytics, or tracking information.**

---

## 2. Information We Handle
* **No Personal Data:** WinFocus does not ask for your name, email address, IP address, or any other identifying information.
* **No Telemetry / Analytics:** WinFocus contains no telemetry, analytics SDKs, advertising trackers, or tracking cookies.
* **Local Settings Only:** All user preferences (such as dimming intensity, tint color, autostart toggle, and activation state) are stored locally on your device in your user directory (`%AppData%\WinFocus\settings.json`). This data never leaves your computer.
* **Window Detection & Win32 APIs:** WinFocus interacts with native Windows APIs (`GetForegroundWindow`, `SetWinEventHook`) solely in memory on your local machine to determine the coordinates of the active window for rendering the dimming overlay. No window titles, keystrokes, contents, or application names are ever recorded or transmitted.

---

## 3. Microsoft Store Licensing & In-App Purchases
When you purchase WinFocus or download the 7-day trial through the Microsoft Store:
* The transaction is processed directly and securely by Microsoft Corporation according to the [Microsoft Privacy Statement](https://privacy.microsoft.com/).
* WinFocus only receives a local binary status (licensed / trial / expired) via the official Windows Store APIs (`Windows.Services.Store`). We never have access to your payment details, credit card numbers, or billing address.

---

## 4. Internet Connectivity
WinFocus operates 100% offline. The application does not require or establish an internet connection, except when Microsoft Store APIs communicate with Microsoft's servers to verify license status or process updates.

---

## 5. Third-Party Services
WinFocus does not integrate with any third-party tracking, advertising, or cloud services.

---

## 6. Children’s Privacy
WinFocus does not collect any data from anyone, including children under the age of 13.

---

## 7. Contact Information
If you have any questions, feedback, or concerns regarding this Privacy Policy, please reach out via GitHub Issues or contact:

* **Website / Repository:** [GitHub Repository](https://github.com/)
* **Email:** support@example.com

---
*This privacy policy applies to all releases of WinFocus distributed via the Microsoft Store, GitHub, and official channels.*
