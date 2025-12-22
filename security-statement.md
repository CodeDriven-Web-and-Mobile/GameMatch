# Game Match Security & Data Protection Statement

_Last updated: December 14, 2025_

At Game Match, protecting user data and maintaining a secure environment are top priorities. This Security & Data Protection Statement outlines the administrative, technical, and physical safeguards we implement to protect information handled through the Game Match mobile and web application (the "App").

---

## 1. Platform & Infrastructure
- **Cloud Hosting:** The App is built on Google Firebase, leveraging Google Cloud Platform’s infrastructure, redundancy, and physical security controls.
- **Regional Hosting:** Data is stored in Google Cloud regions configured for our Firebase project. We can provide region information on request for compliance reviews.

---

## 2. Authentication & Access Control
- **Firebase Authentication:** All accounts require secure email/password sign-in. Passwords are never stored in plain text; Firebase handles hashing and credential protection.
- **Role-Based Authorization:** Administrative actions (game creation, user management) are restricted to authorized accounts using server-side validation.
- **Session Security:** Firebase issues short-lived tokens that expire automatically and can be revoked on logout or suspicious activity.

---

## 3. Data Encryption
- **In Transit:** All network communication between the App and Firebase services uses TLS 1.2+ encryption.
- **At Rest:** Data stored in Firestore, Cloud Storage, and Authentication services is encrypted at rest by Google Cloud using AES-256 or equivalent standards.

---

## 4. Application Security
- **Secure Development Practices:** Code changes undergo peer review and testing before release. Dependencies are pinned and monitored for security advisories.
- **Input Validation:** Server rules and app logic validate user input to prevent unauthorized access or data corruption.
- **Error Handling:** Sensitive details are stripped from user-facing error messages; technical logs are stored securely for diagnostics.

---

## 5. Operational Security
- **Least Privilege:** Access to Firebase Console, analytics dashboards, and billing is limited to essential personnel with multi-factor authentication enabled.
- **Monitoring:** Firebase Security Rules, audit logs, and usage alerts notify us of anomalous activity.
- **Incident Response:** We maintain a documented incident response plan covering detection, containment, user notification, and remediation.

---

## 6. Data Privacy & Retention
- **Privacy Controls:** Users can request account deletion and data export as described in our [Account & Data Deletion Policy](data-deletion-policy.html).
- **Retention:** Personal data is retained only as long as necessary for service delivery, legal compliance, and fraud prevention.
- **Third-Party Sharing:** We share data only with service providers required to operate the App (e.g., Firebase, payment processors) under strict confidentiality agreements.

---

## 7. Compliance & Certifications
- Game Match itself is not currently certified under standards such as SOC 2 or ISO 27001. However, we rely on Google Cloud Platform and Firebase, which hold numerous industry certifications.
- We are committed to supporting partners who require due diligence documentation and will provide security questionnaires or data flow diagrams upon request.

---

## 8. User Responsibilities
- Use strong, unique passwords and enable device-level security (PIN, biometrics).
- Keep your device’s operating system and the Game Match app up to date.
- Report suspected security issues immediately to **security@gamematch.app** or **nallataifeh@gmail.com**.

---

## 9. Continuous Improvement
We review security practices at least annually and whenever new features launch. Feedback from users and partners helps us prioritize enhancements.

---

## 10. Contact
For security inquiries, penetration test coordination, or compliance documentation, contact:

> Game Match Security Team  
> Email: **security@gamematch.app**

---

Thank you for trusting Game Match. We remain dedicated to safeguarding your data and earning your confidence.
