# Privacy Policy

Last Updated: 2026-05-02

## 1. Introduction

Popcornie is a mobile application for spoiler-safe TV show discovery, watch-progress tracking, and AI-assisted Q&A. This Privacy Policy explains what information we collect, how we use it, which service providers are involved, and what choices you have.

If you do not agree with this Privacy Policy, do not use Popcornie.

## 2. Information We Collect

### 2.1 Information you provide directly

We may collect:

- Email address
- Password, when you choose email/password sign-up
- Full name, when provided directly or returned by Apple Sign In / Google Sign In
- Preferred AI response language
- TV shows you add to your library
- Watch progress such as season and episode
- Questions you ask in the app
- Chat history connected to your questions and AI answers
- Support messages you choose to send to us by email

### 2.2 Information collected through app functionality

To operate the service, we also process:

- User account identifiers created through Supabase Auth
- RevenueCat customer and entitlement identifiers used for purchases
- Purchase and subscription status
- Popcorn balance and popcorn transaction history
- Show search requests sent through our backend and TMDB-powered search flow

### 2.3 Information we do not knowingly collect as part of the current app

Based on the current shipped app and repository state, Popcornie does not knowingly use:

- Cross-app tracking for advertising
- Ad network SDKs
- Location data
- Contacts
- Photos
- Camera
- Microphone
- Health data

## 3. How We Use Information

We use information to:

- Create and secure user accounts
- Sign users in with email/password, Apple, or Google
- Store and sync show library and watch progress
- Generate spoiler-safe AI answers
- Maintain popcorn balances, purchases, and premium access
- Process restore purchases and subscription sync
- Personalize app experiences or recommendations if recommendation features are included in the active release
- Respond to support requests you send us
- Detect abuse, fraud, and security issues
- Comply with legal obligations

## 4. Service Providers and Third Parties

Popcornie relies on third-party services to function.

| Provider | Purpose |
| --- | --- |
| Supabase | Authentication, database, backend functions |
| RevenueCat | Subscription and in-app purchase management |
| Apple | Apple Sign In and App Store purchase processing |
| Google | Google Sign In and AI model infrastructure |
| TMDB | TV show metadata, posters, and related content |

### 4.1 What may be shared

Depending on the action you take in the app, limited data may be shared with these providers, such as:

- Authentication tokens or account identity data for sign-in
- Purchase and entitlement state for billing
- Show search requests and show identifiers for TV metadata lookup
- Question text and context needed to generate AI responses

We do not sell your personal information.

We do not use your data for cross-app advertising tracking.

## 5. App Privacy Disclosure Summary

The current app behavior supports the following App Store privacy disclosures:

- Tracking: No
- Contact Info: Yes
- User Content: Yes
- Identifiers: Yes
- Purchases: Yes
- Search History: Yes, using a conservative disclosure because show search text is sent from the app into the backend/TMDB search flow

If the app later adds analytics, crash reporting, ads, or new SDKs, these disclosures may need to change.

## 6. Data Retention

We keep data for as long as it is needed to provide the service and operate your account.

Current app behavior:

- Account data, show library, watch progress, and questions stay associated with your account while it is active.
- If you request account deletion in the app, your account enters a 30-day recovery window before permanent deletion is executed.
- Apple, Google, RevenueCat, and other service providers may retain their own store, fraud, tax, or operational records according to their own policies.

We avoid making broader retention promises than the current system guarantees.

## 7. Account Deletion and Your Rights

You can request account deletion inside the app:

- Profile -> Danger Zone -> Delete Account

Current deletion flow:

- You confirm deletion in the app
- Your account is scheduled for deletion
- You are signed out immediately
- You have a 30-day recovery period to sign back in and cancel the deletion request
- After that window, deletion is intended to become permanent

You may also contact us to request help with access, correction, or deletion questions.

## 8. International Transfers

Popcornie uses cloud services and third-party providers that may process information in countries other than your own, including the United States.

By using Popcornie, you understand that your information may be processed through those providers in order to deliver the service.

## 9. Children's Privacy

Popcornie is not intended for children under 13.

If you believe a child under 13 has provided personal information through the app, contact us and we will review the request.

## 10. Security

We use reasonable technical and organizational measures to help protect the service, including:

- TLS/HTTPS for data in transit
- Auth and session handling through Supabase
- Access controls and server-side authorization checks
- Purchase validation and entitlement sync through RevenueCat-backed flows

No internet service can guarantee absolute security.

## 11. Changes to This Policy

We may update this Privacy Policy from time to time.

When we do, we will update the "Last Updated" date on this page. If a change is material, we may also communicate it through the app or other appropriate channels.

## 12. Contact

If you have privacy questions, contact:

- Developer: Arda Nogay
- Email: `ardanogay@hotmail.com`
