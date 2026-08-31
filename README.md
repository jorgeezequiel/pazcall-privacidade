# Privacy Policy — PazCall

**Last updated:** August 31, 2026

---

## 🔒 Privacy at a Glance

**PazCall is designed with privacy as a fundamental principle.**

The application follows a strictly **offline-first architecture**. PazCall does not operate a backend server, does not require an internet connection, and does not transmit your personal information outside your device.

> **Your contacts stay on your device. Your call-filtering decisions are processed locally.**

This Privacy Policy explains what information PazCall accesses through Android system permissions and how that information is handled.

---

## 1. Data Collection and Sharing

PazCall **does not collect, store on external servers, sell, or share** personal data.

Specifically, PazCall does not transmit or remotely store:

* Phone numbers
* Contact information
* Call history
* Caller information
* Personal information
* Usage analytics
* Tracking identifiers

PazCall has **no backend service and no internet-based data transmission**. The information required for call filtering remains on your Android device.

### Local Processing

When a call is received, PazCall processes the information required to determine whether the caller is saved in your contacts.

This processing occurs **locally on the device**.

No contact list or caller information is uploaded to a server.

---

## 2. Android System Permissions

PazCall requires access to specific Android system capabilities to perform its core function as a call-screening application.

All processing associated with these permissions occurs locally on your device.

### 📇 Read Contacts — `READ_CONTACTS`

PazCall requests access to your contacts so it can determine whether an incoming caller is already saved in your phonebook.

The permission is used to:

1. Read the relevant contact information locally.
2. Compare the incoming caller's number with your saved contacts.
3. Allow calls from recognized contacts.
4. Block unknown callers when **Protection** is enabled.

Your contacts are **not copied to external servers, uploaded, sold, or shared with third parties**.

### 📞 Call Screening Service — `BIND_SCREENING_SERVICE`

PazCall uses Android's **Call Screening** capability to process incoming calls before they are presented to you.

This allows PazCall to determine whether a call should be allowed or blocked according to your Protection setting.

When Protection is enabled:

* Calls from saved contacts are allowed.
* Calls from numbers not found in your contacts may be blocked.
* Blocked calls are handled silently.

PazCall does not use this capability to record or store conversations.

---

## 3. How Call Filtering Works

The filtering process is performed entirely on your device.

```text
Incoming call
     │
     ▼
PazCall receives caller information
     │
     ▼
Compare with contacts stored on the device
     │
     ├── Contact found ──────► Allow call
     │
     └── Contact not found ──► Block silently
```

### Fail-Open Privacy and Safety Behavior

PazCall follows a **fail-open** approach.

If the application cannot reliably verify the caller against your contacts — for example, because the contacts permission is unavailable or a local lookup cannot be completed — PazCall **allows the call rather than blocking it based on incomplete information**.

This prevents a technical failure from unnecessarily blocking a potentially legitimate call.

---

## 4. Data Storage

PazCall does not maintain a remote database containing your contacts, phone numbers, or call information.

The application may maintain limited local application state required for its functionality, such as your Protection preference and application settings.

This information remains on your device and is not transmitted to PazCall servers.

---

## 5. Third-Party Services

PazCall does **not use third-party services for:**

* Advertising
* Behavioral tracking
* Analytics
* User profiling
* Selling or sharing personal information

The application does not include advertising or tracking SDKs.

### No Internet-Based Processing

PazCall does not require an internet connection to perform its core call-filtering functionality.

Call filtering and contact matching are performed locally on the Android device.

---

## 6. Children's Privacy

PazCall is **not directed at children under the age of 18**.

PazCall does not knowingly collect personal information from children or teenagers.

Because PazCall does not collect or transmit personal information to external servers, there is no remote user database from which children's personal information is collected.

---

## 7. Data Security

PazCall follows a privacy-focused, local-processing architecture.

The application is designed to minimize the amount of information that leaves the device:

* Contact information remains on the device.
* Call-filtering decisions are made locally.
* No personal information is transmitted to PazCall servers.
* No account or registration is required.
* No advertising or tracking infrastructure is used.

Users should also protect their Android device using the security mechanisms provided by their device manufacturer and Android.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes to the application, its functionality, or applicable requirements.

When changes are made, the **"Last updated"** date at the top of this page will be updated.

Because PazCall's core functionality is offline and does not require communication with a remote server, we recommend periodically reviewing this page for the latest version of this policy.

---

## 9. Contact Us

If you have questions about this Privacy Policy, PazCall, or how the application handles permissions and call filtering, please contact us:

**Email:** [dev.zels@gmail.com](mailto:dev.zels@gmail.com)

---

## Summary

| Category                             | PazCall             |
| ------------------------------------ | ------------------- |
| Collects personal data               | **No**              |
| Uploads contacts                     | **No**              |
| Stores contacts on servers           | **No**              |
| Shares data with third parties       | **No**              |
| Advertising                          | **No**              |
| Tracking                             | **No**              |
| Analytics SDK                        | **No**              |
| Backend server                       | **No**              |
| Internet required for call filtering | **No**              |
| Contact processing                   | **Local on device** |
| Call filtering                       | **Local on device** |
| Account required                     | **No**              |

---

**PazCall**
*Privacy-first, silent call protection.*
