# Ming Privacy Policy

**Last updated: April 14, 2026**

Ming ("we", "our", or "the app") is a mobile app that provides symbolic chart readings based on your birth details. We take privacy seriously. This policy explains what we collect, why, who we share it with, and how you can control your data.

---

## 1. Who we are

Ming is developed and operated by the Ming app team. If you have privacy questions, contact us at **support@ming-app.com**.

---

## 2. Data we collect

When you use Ming, we collect the following data, all linked to your account:

| Data | Purpose |
|------|---------|
| **Name** | To personalize your profile and readings |
| **Email address** | Account login, account recovery, service notifications |
| **User ID** (assigned by our system) | To associate your readings and purchases with your account |
| **Birth details** (date, time, gender, calendar type) | Core input for chart calculation — Ming cannot function without it |
| **Purchase history** (subscription/one-time purchase status, transaction IDs) | To unlock paid features and honor refunds |
| **Device identifier** (Apple IDFV) | Used by our subscription provider (RevenueCat) to link purchases to the correct account |

We do **not** collect:
- Location data
- Contacts, photos, or health data
- Browsing history outside the app
- Advertising identifiers
- Crash logs or performance telemetry (we currently do not operate analytics or crash reporting SDKs)

We do **not** track you across other apps or websites. We do not share your data with advertising networks.

---

## 3. Why we collect it

- **App functionality** — login, chart calculation, saved contacts, subscription unlocking
- **Service delivery** — generating your readings via large language models, saving your history so you can read it again
- **Customer support** — responding to questions tied to your account
- **Legal compliance** — tax records for purchases, fraud prevention

We do **not** use your data for:
- Advertising or marketing by third parties
- Profile-building across other apps
- Sale to data brokers

---

## 4. Third-party processors

To operate Ming, we use the following service providers. Each only receives the minimum data they need to perform their function:

| Provider | Role | Data shared |
|----------|------|-------------|
| **Apple** (Sign in with Apple, In-App Purchase) | Authentication and payment processing | Name, email (as provided by Apple), purchase receipts |
| **RevenueCat** | Subscription and entitlement management | User ID, device identifier, purchase history |
| **Hostinger** | Hosts our API server and Postgres database | All account and chart data above, encrypted in transit, at rest on Hostinger infrastructure |
| **LLM providers** (DeepSeek, and optionally OpenAI, Anthropic, or Google) | Generating narrative readings | Only the chart summary derived from your birth data — never your name, email, or any direct identifier |

All third-party processors are bound by their own privacy policies and data-processing agreements.

---

## 5. How long we keep it

- **Account data** (name, email, birth details, user ID): kept for as long as your account is active
- **Purchase history**: retained as long as required by Apple and tax authorities (typically 7 years)
- **Chart readings and saved contacts**: kept until you delete them or delete your account
- **Logs**: rotated and deleted within 30 days
- **Anti-abuse identifier after account deletion**: when you delete your account, we retain a one-way cryptographic hash of your Apple identifier, plus two flags indicating whether the free-tier chart or birth-change allowance was used. This contains no birth data, no name, and no email, and cannot be reversed to identify you. Its sole purpose is to prevent repeat use of the free allowance by deleting and re-creating accounts. Legal basis: legitimate interest in fraud prevention (GDPR Art. 6(1)(f), Recital 47). You may request removal of this record by emailing support@ming-app.com.

---

## 6. Your rights

You have the right to:

- **Access** the data we hold about you — request a copy at support@ming-app.com
- **Correct** inaccurate data — via the app settings, or by contacting us
- **Delete** your account and all associated data — in-app: **Settings → Delete Account**, or email support@ming-app.com and we will process within 30 days
- **Withdraw consent** — stop using the app and request deletion
- **Object** to specific processing — contact us
- **Export** your data in a portable format — request at support@ming-app.com

Residents of California, the EU/UK, or other jurisdictions with equivalent rights under CCPA, GDPR, or similar frameworks can exercise these same rights without discrimination.

---

## 7. Data security

- All traffic between the app and our servers is encrypted in transit (TLS 1.2+)
- Account passwords (when applicable) are hashed; we never store them in plaintext
- Access to our backend is restricted to authorized operators and audit-logged
- We do not knowingly transmit birth details or account data in plaintext to any party not listed above

No method of internet transmission is 100% secure; we continuously harden our systems but cannot guarantee absolute security.

---

## 8. Children

Ming is not directed at children under 13 (or under 16 in the EU/UK). We do not knowingly collect data from children. If you believe a child has provided us with personal data, contact support@ming-app.com and we will delete it.

---

## 9. International transfers

Your data may be processed in the United States or other countries where our service providers operate. Where required by law, we use standard contractual clauses or equivalent safeguards.

---

## 10. Changes to this policy

When we make material changes to this policy, we will update the "Last updated" date at the top and, where appropriate, notify you in-app or by email. Continued use of the app after a change indicates acceptance of the revised policy.

---

## 11. Contact

For any privacy question, data request, or complaint:

**Email:** support@ming-app.com

If you are in the EU/UK and are not satisfied with our response, you have the right to lodge a complaint with your local data protection authority.

---

*Ming provides symbolic readings for entertainment and self-reflection only. Content is not a substitute for medical, psychological, legal, or financial advice.*
