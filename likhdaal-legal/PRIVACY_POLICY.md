# Privacy Policy — LikhDaal

**Effective date:** 9 September 2026  
**App name:** LikhDaal  
**Developer:** Bhaskar  
**Contact:** support.likhdaal@gmail.com

---

## 1. Introduction

LikhDaal (“we”, “our”, “the app”) is a personal expense and income tracker. This Privacy Policy explains what information the app handles, how it is used, and your choices.

By using LikhDaal, you agree to this Privacy Policy. If you do not agree, please do not use the app.

---

## 2. Summary

- **Your financial entries are stored on your device** by default. If you turn on **Cloud sync** in Settings → Security & backup, we upload about the **last 6 months** of dated transactions (and related app data such as categories, budgets, notes, and preferences) to **Supabase** so you can continue on another device. Older dated cloud rows are removed automatically; older history stays on the device unless you create an offline backup.
- Phone **OTP** uses **Supabase Auth** to verify your mobile number for account login across devices. OTP SMS may be delivered by Supabase and its SMS providers.
- Basic **profile fields** (name, optional email, phone) may be stored with your Supabase Auth user and, when Cloud sync is on, with your synced preferences.
- **MPIN** (hashed) and **profile photo** stay on this device — they are **not** uploaded by Cloud sync.
- Offline backups you create are **ledger-focused** (they do not need to include your MPIN or phone identity) and are the right way to archive data older than the sync window.
- We do **not** sell your personal information.
- You can **delete your account** from Settings. That removes local app data on the device and, when a cloud account exists, associated cloud sync data for that account.
- Turning **Cloud sync off** stops new uploads; existing cloud copies for your account are retained until you delete the account or request deletion.
- **SMS & email capture** is not available yet (shown as coming later in Settings). We do not read your SMS or email in the current version.

---

## 3. Information we handle

### 3.1 Information you provide

| Data | Purpose | Stored where |
|------|---------|--------------|
| Mobile phone number | Create account, log in, and phone OTP | On your device; also with Supabase Auth when OTP is used |
| First and last name | Profile display; reopen on new device after OTP | On your device; also in Supabase Auth user metadata when cloud account exists |
| Email (optional) | Profile; reopen on new device after OTP | On your device; also in Supabase Auth user metadata when saved to cloud |
| MPIN (4-digit PIN) | Secure access on **this** device | Stored as a **one-way hash** on device — not plain text; **not** included in Cloud sync or offline backups |
| Profile photo (optional) | Avatar | On your device only (not Cloud synced in the current version) |
| Income & expense entries | Core app functionality | On your device; last ~6 months also on Supabase when Cloud sync is on |
| Categories, budgets, notes, preferences | Organize and personalize the app | On your device; also on Supabase when Cloud sync is on |
| Recurring payment settings | Auto-entries & reminders | On your device; also on Supabase when Cloud sync is on |

### 3.2 Information collected automatically

| Data | Purpose |
|------|---------|
| App preferences | Language, currency, theme, font, text size, month start, Home toggles; when Cloud sync is on also app-lock enabled and gentle-reminders toggle |
| Session identifier | Keep you signed in on the device |

We do **not** use third-party advertising analytics in the current version unless stated in an app update.

---

## 4. Device permissions

LikhDaal may request:

| Permission | Why |
|------------|-----|
| **Notifications** | Optional reminders for recurring payments |
| **Camera** | Optional — take profile photo |
| **Photo library** | Optional — choose profile photo |

You can deny optional permissions; core tracking still works.

---

## 5. How we use information

We use your information only to:

- Operate the app (record, display, and report your finances)
- Secure access with MPIN
- Verify your phone number with OTP when you create or restore a cloud-linked account
- Sync about the last 6 months when you enable Cloud sync
- Send **local** reminders you enable
- Export reports or offline backups that **you** initiate

We do **not** use your data for advertising or sell it to third parties.

---

## 6. Data storage and security

- Primary storage is a **local database on your phone**.
- MPIN is stored as a **hashed** value, not readable text.
- Cloud sync (when enabled) stores in-window data with **Supabase** under their security practices and our configuration.
- **Uninstalling the app** or using **Delete account** removes app data from that device (subject to OS behavior). Delete account also removes associated cloud sync data for that account when a cloud account exists.
- No method of storage is 100% secure; protect your device with a screen lock and keep offline backup passphrases safe.

---

## 7. Data sharing / processors

We **do not sell** your personal or financial entries.

When you use phone OTP or enable Cloud sync, data is processed by **Supabase** (and, for OTP SMS, Supabase’s SMS providers) as needed to provide those features. Their use is subject to their terms and this Privacy Policy.

Information may also be disclosed if:

- Required by law or valid legal process
- Necessary to protect rights, safety, or prevent fraud

If we expand cloud sync (for example a longer history window or profile photo cloud storage) or add SMS/email import, we will update this policy before or when those features launch.

---

## 8. Data retention

- On-device data remains until you edit or delete entries, delete your account, or uninstall the app.
- Cloud-dated entries outside the ~6-month window are pruned automatically when Cloud sync runs; local history is **not** deleted by sync.
- After **Delete account**, we delete your user profile, transactions, categories, recurring settings, and profile photo from the app database on that device and associated cloud sync data for that account when applicable.

---

## 9. Your rights and choices

You can:

- **Access** your data within the app
- **Update** profile and entries
- Turn **Cloud sync** on or off in Security & backup
- **Delete account** (Settings → Delete account)
- **Change** notification and reminder settings
- **Export** reports where the app provides export
- **Create / restore an offline backup** (encrypted with your passphrase; **ledger data** under your control on the files you save — backups do not need to include MPIN or phone identity). If you forget the passphrase, that backup cannot be recovered.

For users in India and other regions with privacy laws, you may contact us to ask questions about your data.

---

## 10. Children

LikhDaal is **not directed at children under 13** (or under 18 for financial use). We do not knowingly collect data from children. Contact us if you believe a child has provided information.

---

## 11. International users

The app is designed primarily for users in **India** (INR default, Hindi/English). On-device data is processed where you use the app. Cloud sync and Auth may process data in regions used by Supabase for those services.

---

## 12. Changes to this policy

We may update this Privacy Policy. We will change the **Effective date** at the top. Continued use after updates means you accept the revised policy. Material changes may be noted in the app or store listing.

---

## 13. Contact us

**Bhaskar**  
Email: **support.likhdaal@gmail.com**

Questions about privacy or data deletion: **support.likhdaal@gmail.com**

---

*LikhDaal — Apna hisab, aaram se.*
