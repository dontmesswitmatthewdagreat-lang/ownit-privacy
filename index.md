# OwnIt Privacy Policy

**Last updated**: May 27, 2026

---

## Who we are

OwnIt is operated by **Matthew Chase** ("we", "us", "our"). If you have any questions about this policy or your data, email us at **privacy@ownitapp.net**.

This policy explains what data the OwnIt mobile app collects, how we use it, where it lives, and what control you have over it.

---

## What data we collect

When you use OwnIt, we collect:

**Account information**
- Your email address (used to log in and recover your account)
- A profile name, if you provide one
- Authentication tokens that keep you signed in

**Product data you enter**
- Product names, brands, model numbers, serial numbers
- Purchase price, date, and retailer
- Warranty expiry dates
- Free-form notes you write
- Photos of products and receipts

**AI-related data**
- Text you send to Sortie (our AI assistant) for chat, voice transcription, or research
- Computed product research results (specs, known issues, recalls)
- Conversation history with Sortie within the app

**Device information**
- Operating system version (passively received by our backend with each request, used for diagnostics)
- App version (passively received with each request)
- Push notification token (only if you grant notification permission)

**What we do NOT collect**
- Your location
- Your contacts, calendar, or other apps' data
- Web browsing history outside the app
- Advertising identifiers (the app has no ads and no ad SDKs)
- Behavioral analytics for ad targeting

---

## How we use your data

We use your data only to make the app work for you:
- Show you your products, warranties, photos, and notes
- Power Sortie's AI features (chat, scanning, research, recommendations)
- Send you warranty reminders and proactive insights you've opted into
- Keep you signed in across app sessions
- Diagnose bugs and improve the app

We do **not** sell your data, share it with advertisers, or use it to train any third party's AI models.

---

## Where your data is stored

Your account and product data is stored in **Supabase**, a managed Postgres database and backend service. Supabase's servers are located in the United States (East region). Each user's data is access-controlled via Row Level Security so only you can read and modify your own records.

Photos you upload are stored in Supabase Storage with the same per-user access control (path-prefixed by your user ID).

---

## Third-party AI services

When you use Sortie's AI features, your input is sent to AI providers for processing:

- **Groq** ([groq.com](https://groq.com)) — handles chat, vision (receipt + label scanning), voice transcription, and synthesis of research findings. Inputs are sent to Groq's servers to generate responses and are not retained for training, per Groq's API terms.
- **Tavily** ([tavily.com](https://tavily.com)) — performs the web search used for product research (specs, known issues, recall information).

Your data is sent to these providers only when you actively use a feature that requires them (e.g. scanning a product, opening Sortie chat, running deep research). Routine app browsing does not send anything to AI services.

These providers operate under their own privacy policies:
- Groq Privacy Policy: https://groq.com/privacy-policy/
- Tavily Privacy Policy: https://tavily.com/privacy

---

## Notifications

If you grant notification permission, OwnIt may send you:
- Warranty expiry reminders (based on dates you've entered)
- Sortie insight notifications (e.g. when a recall is found on a product you own)
- A weekly digest summarizing what's worth your attention

You can turn these off at any time in your device's Settings → Notifications → OwnIt.

---

## Your rights

You can:
- **Access** all the data we have on you — it's already in the app (Products, Settings, Sortie chat history)
- **Edit or delete** any individual product, photo, or note from within the app
- **Delete your entire account** — Settings → Account → Delete Account. This removes your account, all products, all photos, and all AI conversation history from our servers. The deletion is permanent and immediate.
- **Export your data** — email us at privacy@ownitapp.net and we'll provide a JSON export of your account within 30 days

---

## Data retention

- Your data is retained for as long as your account is active.
- If you delete your account, all your data is removed immediately.
- If your account is inactive for 24 months, we may notify you by email and delete it shortly after if you don't respond.

---

## Children

OwnIt is not intended for use by children under 13. We do not knowingly collect data from anyone under 13. If you believe a child has provided us with personal information, please contact privacy@ownitapp.net and we will delete it.

---

## Security

We use industry-standard security practices:
- All connections to the app and our backend use HTTPS / TLS encryption
- Authentication credentials are stored in your device's secure enclave (iOS Keychain)
- AI provider API keys are stored on our servers, never embedded in the app, so they can't be extracted from your device

No internet-connected system is 100% secure. If we discover a breach that affects your data, we will notify you within 72 hours and explain what happened and what we're doing about it.

---

## Changes to this policy

We may update this policy when we add new features or change how we handle data. If we make material changes, we'll notify you via in-app banner or push notification at least 7 days before the change takes effect. The "Last updated" date at the top of this page always reflects the current version.

---

## Contact

Privacy questions, data requests, account issues — email us at:

**privacy@ownitapp.net**

We aim to respond within 5 business days.
