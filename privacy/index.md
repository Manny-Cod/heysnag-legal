---
title: Privacy Policy — Snag
canonical_url: https://heysnag.app/privacy
---

# Privacy Policy

**Effective May 5, 2026**

This Privacy Policy describes how Snag Entertainment LLC ("Snag", "we", "us", "our") collects, uses, and shares your personal information when you use the Snag mobile application (the "App"). Snag Entertainment LLC is a Colorado limited liability company. You can reach us at hello@heysnag.app.

## Information We Collect

### Account information
When you create an account, we collect your email address and a password (or, if you sign in with Apple or Google, an authenticated identity token). When you use Sign in with Apple, we receive a stable user identifier, your email address (or Apple's private relay address if you choose Hide My Email), and any name you choose to share. When you use Sign in with Google, we receive a stable user identifier, your email address, and your Google profile display name. Anonymous guest accounts are also supported and don't require an email until you choose to link one.

### Content you create
We store the cases you file: the dispute subject, your written statements, your partner's statements (if invited), category and tone selections, and the AI-generated verdict. We also store related content like daily vibe submissions, saved trips, weekend ratings, streaks, and referral codes. This content is stored on Supabase infrastructure (our backend provider).

Some games (such as saved trips and weekend ratings) let you search for and save place names. When you type a place name, we send your search to OpenStreetMap's Nominatim service to look up matching locations, and we store the place label and coordinates you choose as part of that game's state. We do not access your device's location.

### Usage analytics
We use PostHog to understand how the App is used. We track events such as: filing a case, submitting a statement, inviting a partner, viewing a verdict, and sharing results. Analytics events are tied to your account ID (a UUID) and do not include the text of your cases or statements.

The PostHog SDK also collects device-level technical context, including your IP address, device model, operating system and version, app version, language, and a PostHog-assigned device ID. Under the CCPA/CPRA and similar US state laws, these are considered "unique personal identifiers". We use them to distinguish devices, debug issues, and understand aggregate usage patterns, not to identify you outside the App.

### Crash reports
We use Sentry to capture crash and error reports when the App misbehaves. Sentry receives technical context including device model, operating system and version, IP address, app version, stack traces, your account ID, and a Sentry-assigned device ID to help us diagnose issues. Sentry does not receive the content of your cases.

### Push notifications
If you grant notification permission, we store a device push token so we can send you notifications (e.g. when a partner responds to a case). On iOS, notifications are delivered via Apple Push Notification Service (APNs); on Android, via Firebase Cloud Messaging (FCM). You can revoke notification permission at any time in your device settings.

## Information About Other People

Snag is built around disputes between two or more people, so you'll often write about someone else — a partner, family member, roommate, friend, or coworker (each a "third party"). When you file a case, invite a partner, or describe a third party in your statements, we receive information about that person even if they don't have a Snag account.

By submitting that information, you represent that you have a lawful basis to share it: typically because the third party is a participant in the dispute and the content reflects your own perspective on shared events. You agree not to submit information about a third party that you know to be false, that the third party has explicitly asked you not to share, or that a reasonable person would expect to remain private (medical records, financial account numbers, etc.).

We do not independently verify statements you make about third parties. The AI processes them as your perspective on the dispute. Verdicts are entertainment, not findings of fact about anyone.

A third party who doesn't have a Snag account can ask us what information has been processed about them, request its deletion, or ask to be excluded from future cases. To do so, contact hello@heysnag.app. Because we may not be able to verify the identity of a non-account third party, we may need additional information before acting on a request.

## Sensitive Information

Disputes are personal, and the cases you file may contain information that's considered sensitive under various privacy laws — including details about your sex life, romantic relationships, religion, finances, mental health, ethnicity, or political views. We do not ask for any of this categorically, and we encourage you to share only what's necessary to describe the dispute.

We do not use sensitive personal information to infer characteristics about you, and we do not sell it or share it for cross-context behavioral advertising. We use it only as part of the User Content we process to operate the App.

## How We Use Your Information

We use the information we collect to:

- Operate the App (file cases, generate verdicts, deliver invitations and notifications)
- Authenticate you and protect against fraud or abuse
- Send service messages, like when a verdict is ready or a partner responds
- Improve the App (debug crashes, understand which features are used)
- Comply with legal obligations and enforce our Terms of Service

We do not currently send marketing or promotional emails. The emails you receive from us are service messages (verdict ready, partner responded, account or security notices). If we ever add marketing emails, every such message will include a clear opt-out link.

## How We Use AI

The verdicts in Snag are generated by Anthropic's Claude AI. When you file a case, the text of your case (your statement, your partner's statement if present, category, tone, and judge personality) is sent to Anthropic to generate a verdict. Per Anthropic's commercial API terms, your inputs and outputs are not used to train Anthropic's models. Under those same terms, Anthropic may retain API inputs and outputs for up to 30 days for trust-and-safety monitoring before deletion. Snag does not currently have a separate zero-data-retention agreement with Anthropic. Anthropic processes the text per its own privacy and data handling policies.

## Automated Decision-Making

The AI generates verdicts and similar entertainment content automatically. Verdicts have no legal or otherwise significant effect on you: they don't determine your access to any service, your eligibility, your pricing, or anything outside the App's entertainment loop. We do not use automated decision-making to make decisions about your account status, identity, or rights.

## How We Share Information

We do not sell your personal information. We share data only with:

- Supabase, our backend hosting and database provider
- Anthropic, for AI verdict generation
- PostHog, for analytics
- Sentry, for crash reporting
- Apple Push Notification Service (APNs) and Google Firebase Cloud Messaging (FCM), when delivering push notifications
- Apple and Google, if you choose Sign in with Apple or Sign in with Google
- Successors or acquirers in connection with a corporate transaction (see Business Transfers below)
- Law enforcement or other parties when we believe disclosure is necessary to comply with the law, enforce our Terms, or protect the rights, safety, or property of Snag, our users, or the public

We may also share aggregated or de-identified data that is no longer reasonably linkable to you. When we de-identify data, we maintain reasonable technical safeguards to prevent re-identification, do not attempt to re-identify it, and contractually require any recipient of the data to commit to the same.

## Security

We protect your information with industry-standard measures: data is encrypted in transit (HTTPS/TLS) between the App and our servers, your account is protected by your sign-in method, and access to production systems is limited to authorized personnel. No system is perfectly secure, and we cannot guarantee that information transmitted over the internet or stored electronically will never be subject to unauthorized access.

If we become aware of a security incident affecting your information, we will notify you and any applicable authorities as required by law.

## Data Retention

We retain your account data for as long as your account is active. When you delete your account, your data is removed from our active databases within 30 days. Encrypted backups are retained on a rolling schedule for up to 35 days, after which any residual data is purged.

We may retain a minimal record of deleted accounts (such as a hashed user identifier and the deletion date) to help us detect abuse and respond to legal requests. This record cannot be used to reconstruct your case content.

## Your Privacy Rights

Regardless of where you live, you can:

- Access the personal information associated with your account
- Delete your account and all associated data from Profile → Delete My Account
- Correct inaccurate information by editing your profile or contacting us
- Port a copy of your account data by contacting us
- Opt out of email or push notifications in the App or your device settings
- Decline any future sale or sharing of your personal information for cross-context behavioral advertising — though we do not currently engage in either

To exercise any of these rights, use the in-app deletion flow or email hello@heysnag.app. We will respond within 45 days, with a possible 45-day extension for complex requests, and we will not discriminate against you for exercising your rights.

### How we verify rights requests
To protect your account, we typically verify a rights request by confirming the request comes from the email address tied to your account, or by asking you to confirm a step inside the App. For sensitive requests (such as deletion or data export) we may ask for additional information. Where state law permits (including California's CCPA/CPRA, Colorado's CPA, Connecticut's CTDPA, and similar frameworks), you may submit a privacy request through an authorized agent; we will require written proof of authorization from you and may still need to verify your identity through normal means.

Anonymous guest accounts are not tied to an email address, so we cannot verify out-of-app rights requests for them. To delete a guest account or its data, please use the in-app deletion flow (Profile → Delete My Account) directly from the device where the account was created. If you've since linked a guest account to an email, the verification methods above apply.

### California, Colorado, Connecticut, Virginia, and Texas residents
In addition to the rights above, the laws of your state give you the right to confirm whether we process your personal information, request that we limit the use of your sensitive personal information, and appeal a decision we make on a privacy request. To submit an appeal, reply to our response email and we will review the request again.

We do not "sell" personal information for money, and we do not "share" it for cross-context behavioral advertising as those terms are defined under the CCPA/CPRA (California), CPA (Colorado), CTDPA (Connecticut), VCDPA (Virginia), or TDPSA (Texas).

For Texas residents specifically: we do not sell sensitive personal data, and we do not sell biometric personal data, as those terms are defined under the TDPSA. We do not collect biometric personal data at all.

California right to limit use of sensitive personal information: California residents have the right under the CPRA to limit the use and disclosure of their sensitive personal information ("SPI") to the purposes specified in California Civil Code § 1798.121(a). Because we use SPI only for those permitted purposes — operating the App you've asked us to operate, preventing fraud, ensuring security, and complying with law — we are not required to provide a separate "Limit the Use of My Sensitive Personal Information" mechanism. If our practices change such that this exemption no longer applies, we will provide a way to exercise this right and update this Policy accordingly.

Global Privacy Control: where the App or any associated website operates in a context that supports the Global Privacy Control ("GPC") browser signal, we will treat that signal as a valid request to opt out of the sale and sharing of personal information for cross-context behavioral advertising. We do not currently engage in either, and the App's mobile context does not transmit GPC signals; if we add a website or our practices change, we will honor GPC consistent with applicable law.

## Children and Minors

Snag is intended for users aged 17 and older, consistent with the App's intended audience and Apple App Store age rating. We do not knowingly collect personal information from children under 13. If we learn we have collected such information from a child under 13, we will delete it. If you believe a child under 13 has provided us with personal information, please contact us at hello@heysnag.app.

## Business Transfers

If Snag Entertainment LLC is involved in a merger, acquisition, financing, reorganization, or sale of assets, your information may be transferred as part of that transaction. We will notify you (and where required by law, ask for your consent) before your information becomes subject to a different privacy policy.

## International Users

Snag is currently available only in the United States. Our servers and service providers (including Supabase, Anthropic, PostHog, and Sentry) primarily process information in the United States. If you access the App from outside the US, you understand your information will be transferred to and processed in the US.

## Changes to This Policy

We may update this Privacy Policy from time to time. The "Effective" date at the top reflects the most recent version. Material changes will be communicated in-app or by email.

## Contact

Snag Entertainment LLC

Mailing address: [to be added upon LLC registration with the Colorado Secretary of State; the registered agent address will be used here]

Email: hello@heysnag.app

Use the subject line "Privacy Request" to help us route privacy-related questions.
