---
title: Sphinxx Privacy Policy
permalink: /privacy/
---

# Sphinxx Privacy Policy

_Effective: October 24, 2026_

Sphinxx is a vocabulary app that blocks the apps you choose until you answer your own flashcards. This policy explains what Sphinxx collects, why, who processes it, and how to delete it.

## 1. Who we are

Sphinxx is made by YOUNGJUNE IM, an individual developer based in the Republic of Korea, who is also the person responsible for protecting your data. For anything about your data, write to **imyoungjun883@gmail.com**. We answer within 30 days.

## 2. What we collect

When you create an account and use Sphinxx, we store the following on our server, linked to your account:

- **Account**: your email address and an account ID.
- **Your study content**: the decks and cards you import or create (front, back, notes, tags, language), and the cards Sphinxx generates for you ("Sphinxx picks").
- **Photo captures**: when you add cards from photos or PDF pages, the result of each capture — its title, a short summary of the lesson, grammar points, the words, phrases and sentences found with their importance and meanings, which ones you picked, the deck they went to and the number of pages. The photos themselves are not stored on our server (see sections 3 and 4).
- **Your answers**: what you typed — or said, as text — for each card, whether it was right, how it was graded (exact match, AI or challenge), how you answered (typed, spoken, or a flashcard you marked as known or not), whether you peeked with a hint or Show answer, how long you took, your 👍/👎 feedback on AI grading with any note you add, and the grading instructions you write in Settings.
- **Study settings and level**: the number of correct answers needed, quiz direction, the languages you study, your native language, learning goal and study style (words, a mix, or sentences), whether you allowed AI and photo capture and when you decided, and a study level that the AI estimates from your cards when it generates new ones. Your native language, learning goal and study style are saved in your profile and included in AI grading and card-generation requests if you allow AI.
- **Memory aids and pictures**: when you ask for a memory aid for a card, the explanation written for it — its core image and meanings, origin and word family, a sound link in your language, easily confused words, words it goes with, example sentences and a suggestion for a picture. Also the pictures Sphinxx draws for your cards and the photos you choose to add to a card. They are kept with the card so they appear on your other devices.
- **Recordings**: for each lecture or conversation you record — its type, length, the topic you give, which voice you picked as yours, your answers to follow-up questions, and its title and status. While a recording is processed, our server keeps its transcript (who said what, and when) and the review written from it (summary, useful expressions, your mistakes, moments you got stuck, suggested words and sentences); the review, including the full transcript and any translation improved using its context, is also kept on your iPhone. Short clips of other speakers that you add to cards are stored with the card. If you turn on live translation while recording, the translated sentences and reply suggestions are kept only on your iPhone; our server keeps a log of each reply suggestion request (when, which model, how long it took, how many tokens — never the text) for 90 days.
- **Notification token**: an Apple push notification token for this iPhone, so our server can tell you when a recording review is ready.
- **Purchases and subscriptions**: the product you bought, subscription status and expiry date, whether it is a trial, and the original transaction ID that identifies the subscription. We receive this information from Apple and store it on our server to verify and restore your access. We do not receive your payment-card details.
- **Feature usage and store notifications**: records and monthly totals of requests to features with usage limits, and a record of each subscription notification received from Apple (its ID, type, date and the transaction it concerns — not its contents), to apply those limits and keep subscription access up to date.
- **Usage events**: when the block screen (shield) appears, when a quiz starts, passes or ends, unlocks and relocks, emergency bypasses, pauses, and **how many** apps, categories and websites you chose to block (for example "3 apps · 1 category").
- **Diagnostic details**: error messages from the app and its Screen Time extensions, the status of AI card generation requests, for each photo capture request, the AI model used, token counts, timing and status — not the photos or their text — and, for each memory-aid or drawing request, which kind of request it was and when — not its text or picture.

We use this to run the app: sync your decks to a new phone, grade answers, turn your photos into cards, write memory aids and draw pictures for your cards, turn your recordings into reviews, personalize study content, verify subscriptions and usage limits, verify the weekly bypass on the server, and see whether the gate works as intended (our own analysis — no third-party analytics).

## 3. What we do not collect

- **Which apps or websites you block.** Apple's Screen Time API gives Sphinxx an opaque token for each choice; the list stays on your phone, and we cannot read it.
- **Your voice when you answer out loud.** When you choose to answer out loud, Apple's speech recognition turns the sound into text **on your iPhone**. The sound is never sent to us or anyone else and is not stored — only the resulting text is kept, as your answer. iOS may download a speech model for that language from Apple; no audio is uploaded. Playing a pronunciation uses the voices built into iOS and sends nothing. Recordings you start yourself (lectures, conversations) are different — see the next item and section 4.
- **The audio of your recordings, after transcription.** The audio is uploaded only to be turned into text. It is deleted from our server and from Soniox right after transcription, and at the latest within 24 hours. The full recording stays on your iPhone.
- **The photos you capture.** When you add cards from photos or PDF pages, your iPhone reads the text on them, and the pages are sent, reduced in size, through our server to Anthropic for analysis (section 4). Our server does not store the photos — only the result described in section 2. Sphinxx sees only the photos you take or pick, not the rest of your photo library.
- **Photos you add to a card** are made smaller (at most 1024 pixels on the longer side) and stripped of their location and other metadata on your iPhone before they are stored privately in your account (sections 2 and 5). They are not sent to any AI.
- Your location, contacts, health data, browsing history, or advertising identifier.
- Sphinxx has **no advertising, no tracking, and no third-party analytics or crash-reporting SDKs**. We do not sell or share your data for advertising.

## 4. AI processing (third parties: Anthropic, OpenAI and Soniox)

Sphinxx uses Claude, an AI model by **Anthropic PBC**, through our own server:

- **Grading**: when a sentence answer is not an exact match, or when you challenge a wrong word answer, we send the card's front, back and example, your answer, your grading instructions and the language pair.
- **Generating cards**: when you run out of cards to study, we send a sample of the cards in the decks you have turned on (front, back, example, tags, and how often you answered them right), the fronts of the other cards in those decks so it does not repeat them, and your studied languages, so the AI can write new cards at your level. Cards in decks you have turned off are not sent.
- **Memory aids**: when you ask for a memory aid, we send the card's front, back and example, its language, your native language and your study style, so the AI can explain the word in your language.
- **Recording review**: when you record a lecture or conversation, we send the transcript (with who spoke when), the topic and the answers you give, your native language and your study style, so the AI can pick out useful expressions, your mistakes and the moments you got stuck. When you open a completed review, we also use the full transcript and this context to improve its translation and provide meanings for suggested phrases. These translations are kept with the review (30 days on our server, and on your iPhone until you delete its data).
- **Reply suggestions**: while translation is on, when a question is followed by a pause or you tap **Help me reply**, recent caption sentences and their translations, your native language and the target language are sent to suggest short replies. Only text is sent to Anthropic, never audio. Live caption translation itself uses Soniox as described below.
- **Photo capture**: when you add cards from photos or PDF pages, we send the pages (reduced to at most 1600 pixels on the longer side) and the text your iPhone read from them, with your native language, the languages you study and your study style, so the AI can find the lesson, rank its words by importance and write their meanings. We keep only the result described in section 2, not the photos.

Grading and card-generation requests also include your profile's native language, learning goal and study style to tailor the language and learning content to you.

We do **not** send your email address or account ID to Anthropic. Anthropic processes this data only to return the result, under its commercial terms, and does not use it to train its models. Anthropic deletes these inputs and outputs within 30 days, unless it must keep them longer to enforce its usage policy or to comply with the law. See [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy).

Sphinxx asks for your permission before the first AI use, and you can turn AI off at any time in **Settings → AI judge → Use AI**. Without AI, answers are graded by exact match only, no new cards are written, and no answers or cards are sent to Anthropic.

Photo capture asks for its own permission the first time you use it, and you can turn it off at any time in **Settings → AI & data → Photo capture**. Without that permission, no photos are sent. Memory aids ask for their own permission in the same way (**Settings → AI & data → Memory aids**); without it, no cards are sent for memory aids.

**Drawing pictures (third party: OpenAI).** When you ask Sphinxx to draw a picture for a card, we send a short description of the picture — written by the memory aid, not your own text — through our server to **OpenAI, L.L.C.**, which returns the image. We store the picture privately in your account (section 5). We do not send your email address or account ID to OpenAI. OpenAI does not use this data to train its models and may keep it for up to 30 days to monitor abuse. See [OpenAI's Privacy Policy](https://openai.com/policies/privacy-policy/). Drawing asks for its own permission the first time, and you can turn it off at any time in **Settings → AI & data → Drawn pictures**. Your own photos are never sent to OpenAI or any other AI.

**Transcribing and translating recordings (third party: Soniox).** To transcribe a recording and translate live captions when translation is on, its audio goes to **Soniox, Inc.** in the United States — streamed while you record if live captions are on, or uploaded through our server when you finish. Soniox processes it only to return the transcript and, when enabled, live translations, and we delete the audio and the transcript from Soniox right after we receive the text. We do not send your email address or account ID to Soniox. Recordings ask for their own permissions the first time (**Settings → AI & data → Transcription** and **Recording review**); without them, recordings aren't transcribed or reviewed. Answers you say out loud are never sent to Soniox.

## 5. Where your data lives

- **Our server**: Supabase (hosted in the EU, West EU region). Data is encrypted in transit (HTTPS), and row-level security lets each account read and write only its own rows. Pictures Sphinxx draws and photos you add to cards are kept in Supabase Storage in the same region, in a private folder that only your account can read.
- **Your phone**: your decks, answers and settings are also kept on the device so the app works offline. The photos and PDF pages you capture are kept only on that iPhone and are left out of iCloud backups. The Screen Time choices and the gate's lock state are shared only between Sphinxx and its own extensions on the device.
- **Apple and subscriptions**: Apple processes App Store payments under its own [Privacy Policy](https://www.apple.com/legal/privacy/). Apple sends us purchase and subscription status, product, expiry date, trial status and original transaction ID. We store these on our Supabase server and use Apple's transaction verification and subscription notifications to keep access current. Your Sphinxx account ID is used as an app account token to link the purchase to your account; Apple receives this token during purchase. We do not send Apple your cards or answers for subscription verification.
- **Who processes your data for us, and where**: Supabase, Inc. stores your account data in the EU. If you allow AI, photo capture or memory aids, Anthropic PBC processes the text and page photos described in section 4 in the United States. If you allow drawn pictures, OpenAI, L.L.C. processes the picture descriptions described in section 4 in the United States. If you allow transcription, Soniox, Inc. processes the audio of your recordings in the United States. Apple delivers notifications through its push notification service. Apple handles purchases and subscriptions under its own privacy policy. Your data may therefore leave your country; it travels encrypted and is used for the purposes described here.
- If you sign in to Sphinxx with a different account on the same iPhone, Sphinxx first erases the previous account's data from that iPhone, so two accounts never mix.

## 6. Retention and deletion

- **Delete your account** in **Settings → Account → Delete account**. This immediately deletes everything we store on the server for that account, including cards you deleted earlier, the pictures, photos and audio clips stored with your cards, recording audio that is still waiting to be transcribed, and the copies at Soniox.
- Deleting your Sphinxx account does not cancel your Apple subscription or delete records held by Apple under its own policy. To stop future billing, cancel in your App Store account settings → Subscriptions.
- Deleting your account also erases what Sphinxx keeps on that iPhone — decks, answers, settings, captured photos, recordings, card pictures and the apps you chose to guard — and the app starts over from its first screen. On any other device where you used Sphinxx, that copy stays until you delete the app there.
- Deleting the app removes everything it kept on that phone.
- You can also ask us by email to delete your account and data. We do it within 30 days.

How long we keep data on our server while your account exists:

| Data | Retention |
|---|---|
| Decks, cards, answers, study sessions, grading feedback and profile settings (including native language, learning goal and study style) | As long as your account exists, so your history, statistics and review schedule work. |
| Photo capture results (title, lesson summary, grammar points, words and meanings). The photos themselves are not stored. | As long as your account exists, so you can open a capture again. |
| Cards, decks and photo captures you delete | Text is erased right away. Only an ID and deletion time stay so other devices learn about the deletion. |
| Memory aids, drawn pictures, photos and audio clips you add to cards | As long as your account exists. When you delete a card, its memory aid is erased right away and its pictures and clips are deleted from our storage. |
| Recording transcripts and reviews on our server | 30 days after the recording has been processed. The review stays on your iPhone. |
| Recording audio we upload (on our server and at Soniox) | Deleted right after transcription, and at the latest within 24 hours. |
| Reply suggestion request log (time, model, duration, token counts — no text) | 90 days. The translated sentences themselves stay on your iPhone. |
| Notification token | Deleted when you sign out or delete your account, or after 180 days without use. |
| Memory-aid and drawing request logs (kind of request and time — no text or pictures) | 90 days. |
| Gate usage events and diagnostic details, cached grading results, AI card-generation logs and emergency bypass records | 90 days, then deleted automatically. A bypass in your study history stays with your account like any other session. |
| Daily counts of AI grading requests | 7 days. |
| Photo capture request logs (AI model, token counts, timing and status — no photos or text) | 90 days. |
| Subscription records | As long as your account exists, to verify and restore access. |
| Individual feature-usage records (`usage_events`) | 90 days. |
| Monthly feature-usage totals (`usage_monthly`) | 400 days. |
| Records of App Store subscription notifications (ID, type, date, transaction; no contents) (`store_notifications`) | 90 days. |

## 7. Your rights

You can ask us for a copy of your data, to correct it, to delete it, or to stop processing it, by writing to imyoungjun883@gmail.com. You can also delete everything yourself at any time in Settings → Account → Delete account, and turn AI off in Settings → AI judge.

- **Why we may process it**: to provide the service you signed up for. AI processing happens only with your permission, which you can withdraw at any time.
- **EU/EEA and UK**: you have these rights under the GDPR and can complain to your local data protection authority.
- **Republic of Korea**: you have these rights under the Personal Information Protection Act and can contact the Personal Information Protection Commission or the Personal Information Dispute Mediation Committee.

## 8. Children

Sphinxx is for adults who want to limit their own screen time. It has no child accounts or parental-control mode and is not directed at children. Do not create an account if you are under 14 (under 16 in the EU/EEA). If we learn that a child under that age has an account, we delete it.

## 9. Changes

If we change this policy, we update the effective date above and, for material changes, tell you in the app.
