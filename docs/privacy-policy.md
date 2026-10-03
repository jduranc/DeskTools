# Privacy Policy

**Last Updated:** October 3, 2026

At **DeskTools** (“we,” “our,” or “us”), we believe desktop productivity tools should respect user privacy and operate with complete transparency. 

This Privacy Policy explains how DeskTools handles information when you purchase, download, install, and use our macOS desktop application (the “Application”) distributed via the Apple Mac App Store.

---

### Core Privacy Principles

- **100% Local On-Device Execution:** All features—including floating desktop tags, drag-and-drop file shelves, screen recording, and sleep prevention timers—operate exclusively on your local Mac. No content ever leaves your machine.
- **Zero Tracking & Zero Third-Party Telemetry:** DeskTools contains no tracking SDKs, no behavioral telemetry, no advertising frameworks, and no background analytics services.
- **No Data Monetization:** We do not collect, monetize, sell, trade, or share personal data or usage patterns with third parties or data brokers.
- **One-Time Upfront Purchase:** DeskTools is a paid upfront utility with no subscriptions, in-app purchases, or hidden access tiers. We do not collect or store your billing or credit card information.

---

### 1. Information We Do NOT Collect

DeskTools is engineered from the ground up for strict compliance with Apple’s App Sandbox architecture. We do not access, process, or store:

- **No Screen Recordings or Screenshots:** Screen captures and window recordings captured via Apple's native `ScreenCaptureKit` framework are encoded directly on your device and saved exclusively to the local directory you designate (e.g., `~/Movies` or `~/Desktop`). We do not have remote access to, nor do we inspect, your recordings or images.
- **No File, Document, or Link Inspection:** Items dropped onto floating tag shelves (such as files, apps, folders, or URLs) are referenced locally using native macOS security-scoped bookmarks and file system URLs. DeskTools does not read the contents of your attached documents or track your browsing activity.
- **No Personal Identifiers:** We do not require accounts, logins, emails, or personal identities to use any feature of the Application.
- **No Financial Data:** Payments are handled exclusively by Apple Inc. through the Mac App Store. We do not receive, process, or retain credit card details, billing addresses, or bank accounts.

---

### 2. System Permissions & Local Processing

DeskTools relies on standard, sandboxed macOS system APIs to perform its core utilities:

- **Screen Recording Permission:** Required to capture windows and record screen activity using Apple’s official `ScreenCaptureKit`. macOS will prompt you to explicitly grant this permission under *System Settings > Privacy & Security > Screen Recording*. Recordings are processed purely in local memory and saved directly to your local storage.
- **File System Access:** Access to save destinations (such as your chosen output folder) is secured via standard user-selected dialogs (`NSSavePanel`) and stored locally using Apple’s Security-Scoped Bookmarks. DeskTools cannot access files or directories outside the folders you explicitly select.
- **Display & Power Assertions:** The screen awake utility uses native macOS `IOKit` power assertions (`IOPMAssertionCreateWithName`) to temporarily prevent your monitor from sleeping. This process modifies local system power sleep state only and involves no data collection.

---

### 3. Data Storage & Retention

All user preferences—such as tag titles, positions, color selections, shelf items, and sleep timer presets—are stored entirely locally in your Mac’s sandboxed container directory and local `UserDefaults`. 

DeskTools does not maintain remote servers or databases. If you remove the Application and delete its container data, all stored configuration data is permanently removed from your machine.

---

### 4. Third-Party Services

DeskTools does not integrate third-party analytics, crash-reporting software (such as Firebase), or external tracking dependencies:

- **Apple Inc. (Mac App Store):** The Application is distributed through the Mac App Store. Apple may collect diagnostic and performance reports if you have opted in to share analytics with application developers under macOS *System Settings > Privacy & Security > Analytics & Improvements*. Any such data provided to us by Apple is anonymized and aggregated.

---

### 5. Children's Privacy

DeskTools is a general-purpose desktop utility and does not knowingly collect or solicit personal information from anyone, including children under the age of 13.

---

### 6. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect product enhancements or changes to applicable legal or platform guidelines. Any changes will be posted with an updated “Last Updated” date at the top of this policy.

---

### 7. Contact Us

If you have any questions or feedback regarding this Privacy Policy or our privacy practices, please contact us at:

Jose Duran
📧 [Email](mailto:rays-mouse01@icloud.com)
🇺🇸 Mercer Island, WA, USA
