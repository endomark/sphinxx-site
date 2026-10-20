---
title: Sphinxx Privacy Policy
permalink: /privacy/
---

# Sphinxx Privacy Policy

_Effective: October 20, 2026_

Sphinxx is a vocabulary app that blocks the apps you choose until you answer your own flashcards. This policy explains what Sphinxx collects, why, who processes it, and how to delete it.

## 1. Who we are

Sphinxx is made by YOUNGJUNE IM, an individual developer based in the Republic of Korea, who is also the person responsible for protecting your data. For anything about your data, write to **imyoungjun883@gmail.com**. We answer within 30 days.

## 2. What we collect

When you create an account and use Sphinxx, we store the following on our server, linked to your account:

- **Account**: your email address and an account ID.
- **Your study content**: the decks and cards you import or create (front, back, notes, tags, language), and the cards Sphinxx generates for you ("Sphinxx picks").
- **Your answers**: what you typed — or said, as text — for each card, whether it was right, how it was graded (exact match, AI or challenge), how you answered (typed, spoken, or a flashcard you marked as known or not), whether you peeked with a hint or Show answer, how long you took, your 👍/👎 feedback on AI grading with any note you add, and the grading instructions you write in Settings.
- **Study settings and level**: the number of correct answers needed, quiz direction, the languages you study, whether you allowed AI and when you decided, and a study level that the AI estimates from your cards when it generates new ones.
- **Usage events**: when the block screen (shield) appears, when a quiz starts, passes or ends, unlocks and relocks, emergency bypasses, pauses, and **how many** apps, categories and websites you chose to block (for example "3 apps · 1 category").
- **Diagnostic details**: error messages from the app and its Screen Time extensions, and the status of AI card generation requests.

We use this to run the app: sync your decks to a new phone, grade answers, verify the weekly bypass on the server, and see whether the gate works as intended (our own analysis — no third-party analytics).

## 3. What we do not collect

- **Which apps or websites you block.** Apple's Screen Time API gives Sphinxx an opaque token for each choice; the list stays on your phone, and we cannot read it.
- **Your voice.** When you choose to answer out loud, Apple's speech recognition turns the sound into text **on your iPhone**. The sound is never sent to us or anyone else and is not stored — only the resulting text is kept, as your answer. iOS may download a speech model for that language from Apple; no audio is uploaded. Playing a pronunciation uses the voices built into iOS and sends nothing.
- Your location, contacts, photos, health data, browsing history, or advertising identifier.
- Sphinxx has **no advertising, no tracking, and no third-party analytics or crash-reporting SDKs**. We do not sell or share your data for advertising.

## 4. AI processing (third party: Anthropic)

Sphinxx uses Claude, an AI model by **Anthropic PBC**, through our own server:

- **Grading**: when a sentence answer is not an exact match, or when you challenge a wrong word answer, we send the card's front, back and example, your answer, your grading instructions and the language pair.
- **Generating cards**: when you run out of cards to study, we send a sample of the cards in the decks you have turned on (front, back, example, tags, and how often you answered them right), the fronts of the other cards in those decks so it does not repeat them, and your studied languages, so the AI can write new cards at your level. Cards in decks you have turned off are not sent.

We do **not** send your email address or account ID to Anthropic. Anthropic processes this data only to return the result, under its commercial terms, and does not use it to train its models. Anthropic deletes these inputs and outputs within 30 days, unless it must keep them longer to enforce its usage policy or to comply with the law. See [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy).

Sphinxx asks for your permission before the first AI use, and you can turn AI off at any time in **Settings → AI judge → Use AI**. Without AI, answers are graded by exact match only, no new cards are written, and no data is sent to Anthropic.

## 5. Where your data lives

- **Our server**: Supabase (hosted in the EU, West EU region). Data is encrypted in transit (HTTPS), and row-level security lets each account read and write only its own rows.
- **Your phone**: your decks, answers and settings are also kept on the device so the app works offline. The Screen Time choices and the gate's lock state are shared only between Sphinxx and its own extensions on the device.
- **Who processes your data for us, and where**: Supabase, Inc. stores your account data in the EU. If you allow AI, Anthropic PBC processes the text described in section 4 in the United States. Your data therefore leaves your country; it travels encrypted and is used only for the purposes in this policy. No one else receives it.
- If you sign in to Sphinxx with a different account on the same iPhone, Sphinxx first erases the previous account's data from that iPhone, so two accounts never mix.

## 6. Retention and deletion

- **Delete your account** in **Settings → Account → Delete account**. This immediately deletes everything we store on the server for that account, including cards you deleted earlier.
- Deleting your account also erases what Sphinxx keeps on that iPhone — decks, answers, settings and the apps you chose to guard — and the app starts over from its first screen. On any other device where you used Sphinxx, that copy stays until you delete the app there.
- Deleting the app removes everything it kept on that phone.
- How long we keep data on the server while your account exists:
  - **Your decks, cards, answers, study sessions, grading feedback and settings**: as long as your account exists, so your history, statistics and review schedule work.
  - **Cards and decks you delete**: their text is erased from the server right away. Only an ID and the time of deletion stay, so your other devices learn about the deletion.
  - **Usage events and diagnostic details, cached grading results, AI card-generation logs and the server's record of each emergency bypass** (used to allow one a week): 90 days, then deleted automatically. A bypass also appears in your study history like any other session; that stays with your account.
  - **The daily count of AI grading requests** (used to limit them): 7 days.
- You can also ask us by email to delete your account and data. We do it within 30 days.

## 7. Your rights

You can ask us for a copy of your data, to correct it, to delete it, or to stop processing it, by writing to imyoungjun883@gmail.com. You can also delete everything yourself at any time in Settings → Account → Delete account, and turn AI off in Settings → AI judge.

- **Why we may process it**: to provide the service you signed up for. AI processing happens only with your permission, which you can withdraw at any time.
- **EU/EEA and UK**: you have these rights under the GDPR and can complain to your local data protection authority.
- **Republic of Korea**: you have these rights under the Personal Information Protection Act and can contact the Personal Information Protection Commission or the Personal Information Dispute Mediation Committee.

## 8. Children

Sphinxx is for adults who want to limit their own screen time. It has no child accounts or parental-control mode and is not directed at children. Do not create an account if you are under 14 (under 16 in the EU/EEA). If we learn that a child under that age has an account, we delete it.

## 9. Changes

If we change this policy, we update the effective date above and, for material changes, tell you in the app.
