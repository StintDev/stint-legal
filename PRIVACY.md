# Stint Privacy Policy

_Last updated: 6 August 2026_

Stint is a study-session tracker with a social layer. We collect the minimum
data needed to run it, and nothing else. There are no ads, no analytics SDKs,
and no advertising identifiers.

Most of our users are teenagers. That shapes everything below: defaults are
private, sharing is opt-in, and we do not build profiles of you for anyone
else's benefit.

## What we collect

**Account**
- Your email address, for sign-in and verification.
- A username and display name you choose.
- Whether you are under 18 — a yes/no flag derived at sign-up. We do not store
  your date of birth.

**Your study activity**
- Sessions: subject, category, start time and end time. Durations are computed
  by our servers from those timestamps, not sent by your phone.
- Subjects you create.
- Plans and reflections you write yourself: daily intentions, weekly goals, and
  post-session focus ratings with optional short notes.
- Semester chapters, exam dates and subjects, and break periods you set.

**Social**
- Friendships and friend requests, and invite links you create.
- Groups and squads you create or join, and shared weekly group targets.
- Scheduled study sessions you propose or join.
- Streak-twin pairings you accept.
- Reports and blocks you file.

**On your device only**
Some preferences never leave your phone: your chosen focus scene and
soundscape, sound and haptic settings, which prompts you've dismissed, and
which personal records you've already been shown. These live in the iOS
Keychain and are removed when you delete the app.

## What we never collect

- Precise location. No GPS, ever.
- Your contacts, photos, microphone, or camera. The app requests no such
  permission.
- Analytics or advertising identifiers. No ad networks, no third-party
  trackers, no cross-app tracking.
- Your date of birth.

## Who can see your data

- **Your sessions and stats are visible only to friends whose requests you have
  accepted.** Nothing about you is public. There are no public profiles.
- Someone searching your username sees only your username, display name and
  avatar — nothing else — until you accept them.
- Group and squad members see the hours you contribute to shared targets.
- People you have scheduled a session with can see that you joined it.
- Blocking someone immediately hides everything between you and them, in both
  directions. They are not told.

## Companies that process data for us

**Supabase** hosts our database, authentication and server functions. Your
account and activity are stored there, protected by row-level security rules
that deny access by default.

**Anthropic** processes the AI study coach, which is an optional paid feature.
If you use it, we send your messages in that conversation together with a
summary of your recent sessions, focus ratings, goals and daily intentions, so
the coach can answer usefully. We do not send your email address, your name, or
anything identifying you. We do not store the conversation — we keep only a
timestamp per request, to enforce a daily limit. **If you never open the coach,
nothing is ever sent to Anthropic.**

**Apple** processes subscription payments through the App Store. We never see
or store your payment details.

We do not sell your data, and we do not share it with anyone for advertising.

## Where it lives and how it's protected

Data is stored with Supabase (PostgreSQL). Every table has row-level security
enabled and denies access by default, so a request can only ever read rows that
belong to you or to a friend who has accepted you. All traffic is encrypted in
transit. Your sign-in tokens are stored in the iOS Keychain on your device.

## Your rights

- **Export your data** any time from You → Export my data. This is free and is
  not a paid feature.
- **Delete your account** any time from You → Delete account. Deletion is
  immediate and removes your profile, sessions, plans, reflections, goals,
  friendships, invites, groups, squads, scheduled sessions, streak twins,
  reports and blocks. It cannot be undone. Copies may persist briefly in our
  database provider's routine backups before those rotate out.
- **Ask us anything** about your data using the support contact on our App
  Store listing.

Depending on where you live you may have additional rights over your personal
data. Contact us and we will honour them.

## Children

Stint is not intended for children under 13, and we do not knowingly collect
data from them. If we learn that we have, we delete the account.

Users aged 13 to 17 get our strictest settings with no way to loosen them:
friends-only visibility, no public profile, and no way for a stranger to see
anything about them.

If you are a parent or guardian and want your child's data removed, contact us
using contact@2finellc.com and we will delete the
account.

## Changes

If this policy changes in a way that materially affects you, we will tell you
in the app before the change takes effect.
