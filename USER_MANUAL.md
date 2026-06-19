# Allergy Scheduler — User Manual

> **Medical Disclaimer**: Allergy Scheduler is a **tracking tool only**. It does not provide medical advice, diagnosis, or treatment. Always consult your physician regarding your treatment plan.

---

# Authentication

## Sign in

Open the app and sign in with your **Email & Password** or **Google Sign-In**.

If you don't have an account yet, tap **Register**:
- Enter a valid email address and a password (minimum 6 characters).
- Confirm the password by typing it a second time.
- Tap the **eye** icon on any password field to show or hide the characters.

The app validates your input automatically and shows specific error messages if something is wrong (e.g. email already in use, weak password).

## Sign out

Tap the **Profile** icon (top-right corner) → **Sign Out**.

---

# Usage

## Patient Settings

A **Patient** is the person whose allergy treatment you are tracking. You can create a patient profile (becoming the owner/admin) or join one managed by someone else.

**Create a patient**
1. Profile menu → **Patient Settings** → **Add** → **Create Patient**.
2. Fill in the name, date of birth, timezone, and allergen details.
3. Tap **Save**.

**Join an existing patient**
1. Ask the patient's admin for their **Patient ID** (20-character code).
2. Profile menu → **Patient Settings** → **Add** → **Join Patient**.
3. Enter the Patient ID and tap **Join**. The admin receives a notification and can accept or decline.

**Manage members (admin only)**
- **Invite**: Tap **+** in the Members section, enter the user's registered email, and tap **Invite**.
- **Accept / Decline requests**: Pending join requests appear at the top of the Patient Settings page.
- **Share Patient ID**: Tap the **Copy** icon next to the Patient ID to copy it to your clipboard.
- **Remove or promote**: Use the **⋯** menu on any member row to remove them or change their role.

**Leave a patient**
Non-admin members can leave a patient group at any time via the **Leave** option on the Patient Settings page.

**Delete a patient (admin only)**
Use the **Delete** option on the Patient Settings page. This is permanent and removes all data for that patient.

> A small **"Syncing…"** indicator at the bottom of the screen means the app is updating your data in the background — this is normal.

## Protocols page

A **Protocol** defines the treatment plan: the allergen blend and the rules that govern how doses are tracked. Only the patient admin can create, edit, or delete protocols.

- **Add**: Tap **+**, give the protocol a name, then add allergen substances to build the **Blend**.
- **Edit / Delete**: Swipe a protocol card left or right, or use the **⋯** menu.
- **Blend**: Add **Base** and **Allergen** substances that make up the mixture.
- **Rules (Premium)**: Customise dose intervals, countdown notification timings (Relax / Go Play / Ready), and which warnings are shown. By default the app uses standard values — override them to match your doctor's specific plan.
- **Filter / Search**: Use the search bar and filter controls at the top of the page.

## Doses Page

The **Doses** tab is where you log every dose administered.

- **Add a dose**: Tap **+**. Select the protocol, enter the dosage amount, set the date and time, then choose the health, medication, and reaction status.
  - **Smart suggestions**: The dosage field shows your last used amount at the top, followed by up to five values from your recent history. You can also type a custom value.
- **Edit / Delete**: Swipe a dose card left or right, or use the **⋯** menu.
- **Filter**: Filter by date range, dosage amount, health / medication / reaction status, or free-text search.
- **Validations**: The app warns you if a dose is set in the future or if the time since the last dose is shorter than the protocol's minimum interval. You can still save the dose if you choose to proceed.

**Special dose statuses**

| Status | What it means |
| :--- | :--- |
| **Day Off** | A planned break. No other doses can be added that day. |
| **Seriously Ill** | Patient is too unwell for the full protocol. Other doses can still be added the same day; time-interval checks are skipped. |

## Home page

The **Home** page shows the current treatment status at a glance.

- **Countdown timer**: Displays how long until the next dose is due, based on the last dose and the active protocol's intervals.
- **Patient selector**: Switch between patients using the selector at the top of the page.
- **Info & Warnings (Plus / Premium)**: Contextual alerts based on the patient's current status — for example, a reminder when an antihistamine is active, when antibiotics are being used, or when the previous day had too few doses.

## Dosage Groups page

The **Dosage Groups** tab summarises your dose history grouped by dosage amount, so you can quickly see how often each amount has been used.

- **Filter**: Combine date ranges, dosage amounts, and status filters to narrow down the view.
- **Export to PDF (Premium)**: Tap the export button to generate a printable report. The report can be previewed in-app, then saved to your device, shared, or printed.

## Statistics page

The **Statistics** tab (Premium) provides a detailed overview of the full treatment history.

- **Key metrics**: Total doses, mean doses per day, and highest single-day dose count.
- **Health breakdown**: A pie chart showing the distribution of health statuses (Healthy, Slightly Ill, Seriously Ill, Day Off).
- **Medication & Reaction counts**: Summaries for each medication and reaction status recorded.
- **Monthly bar chart**: Dose count per month, filterable by year.
- **Filter**: Use the dropdowns at the top to view all-time, yearly, or monthly data.

---

# Personal Settings

## Profile Settings page

Access via the **Profile** icon (top-right corner).

- View and edit your **display name** and **email address**.
- View your unique **User ID**.
- Tap **Manage Subscription** to open the Subscriptions page.

## User Settings page

Access via the **Profile menu → User Settings** (Premium).

- **Date & Time Format**: Choose how dates and times are displayed across the app and in PDF exports.
- **Theme**: Switch between Light and Dark mode.
- **Theme Color**: Pick a custom accent color for the app.
- **Language**: Choose from 13 supported languages — English, Greek, Spanish, French, German, Italian, Portuguese, Portuguese (BR), Arabic, Chinese (Simplified), Japanese, Hindi, Turkish.
- **Notification Devices**: View and remove devices that are registered to receive push notifications.
- **App Guide**: Toggle the step-by-step welcome guide on or off. When enabled, the guide appears automatically on first login. You can replay it at any time from the **Info & Contact** page.

## Doctor Settings page

Access via **Patient Settings → Doctor** section (admin only).

Save your doctor's contact details for quick access from within the app:
- **Phone** — tap to dial directly.
- **Email** and **Address**.

Only the patient admin can add, edit, or delete doctor entries. Use the **⋯** menu or swipe to manage them.

> This information is stored solely for your convenience and is not shared with any third party.

## Info & Contact page

Access via the **Profile menu → Info & Contact**.

- **User Guide** — Opens the built-in step-by-step guide to the core app workflow.
- **User Manual** — Opens this document.
- **Medical Disclaimer** — Review the full disclaimer.
- **Privacy Policy** — Review how your data is handled.
- App version and support contact details.

## Delete user

Permanently delete your account from **Profile Settings → Delete Account**.

This removes:
- Your personal settings and preferences.
- Any patient profiles where you are the **sole member / admin**.

> If you are the admin of a patient that has other members, you must either **transfer admin rights** to another member or **remove all other members** before your account can be fully deleted.

---

# Subscriptions

## Subscription plans/tiers

Allergy Scheduler offers three tiers:

| Feature | Free | Plus | Premium |
| :--- | :---: | :---: | :---: |
| Basic dose tracking | ✅ | ✅ | ✅ |
| Info & Warnings | 🔒 | ✅ | ✅ |
| Dosage Groups | 🔒 | ✅ | ✅ |
| Usage Statistics | 🔒 | 🔒 | ✅ |
| User Settings (theme, language…) | 🔒 | 🔒 | ✅ |
| Protocol Rules | 🔒 | 🔒 | ✅ |
| PDF Export | 🔒 | 🔒 | ✅ |

**Free trial**: New users who have never subscribed receive a **1-month free Premium trial** automatically — no action required.

## Subscriptions page

Access via the **Profile menu → Manage Subscription** or by tapping any locked feature.

- View your current plan and renewal status.
- Upgrade to **Plus** or **Premium** (monthly or yearly billing).
- Eligible packages show a **free trial badge** and a "Then €X/mo" subtitle.
- Manage or cancel your subscription through the store (Google Play / App Store / Web Billing).

---

# Troubleshooting

**App shows "Version Mismatch" and won't open**
The app enforces version synchronisation with the cloud to prevent data corruption. Tap **Open Google Play** (or visit the App Store / hard-refresh your browser) to update to the latest version.

**Data looks out of sync or "ghost" records appear in Dosage Groups**
Patient admins can trigger a full data rebuild: go to **Patient Settings → Rebuild All Tables**. This reconstructs all summaries from your raw dose history.

**Countdown timer or notifications seem wrong**
Verify that the correct **Protocol** is linked to the latest dose, and check that the protocol's **Rules** match your doctor's prescribed intervals.

**"Interval too short" warning when adding a dose**
The app enforces the minimum dose interval defined in the active protocol. You can still save the dose by confirming the override when prompted.

**Push notifications not arriving**
Go to **User Settings → Notification Devices** and confirm your device is listed. Also check that the app has notification permission in your device's system settings.
