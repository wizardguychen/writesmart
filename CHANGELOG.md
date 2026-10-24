# What's new

[中文](CHANGELOG.zh-CN.md) · [Back to the overview](README.md) · [Start a story →](https://writesmart.top)

Every WriteAnytime update, newest first. Updates only add: they never change the books, notes and credits you already have.

This page covers writing, accounts and payments; the full record, privacy policy updates included, is in the [release notes on the site](https://writesmart.top/changelog).

## 2026-10-24

### On phones: a “Me” tab, four tabs at the bottom, and settings as a list <sub>v0.1.43</sub>

- On phones, Home, Ideas and Library have four tabs at the bottom: Home, Ideas, Library and Me. The top bar sits flat at the top with just the mark and the name.
- “Me” holds what the avatar menu held: credits and getting more, membership, settings, feedback, inviting friends, language and look, signing out, and the release notes. Signed out, it is where you sign in or sign up and change language and look.
- Settings on a phone start as a list (account, writing defaults, membership, credits…); each opens as a page of its own, and “‹ Settings” or back returns to the list. Credits, invites and the release notes start with “‹ Me”.
- Menus and panels slide away when they close instead of vanishing; buttons and rows answer when pressed; a new page, or another tab in a book, fades in.
- The email fields on sign-in and sign-up no longer capitalise the first letter or autocorrect.
- The credits and invite pages no longer get widened by their background glow on phones, which made the whole page shrink.

### Writing on a phone: tools on top of the keyboard, saved state and words always in view <sub>v0.1.42</sub>

- On a phone the formatting tools no longer take the top of the page: once you tap into the text and the keyboard comes up, a strip of tools sits on top of it (undo, bold, italic, highlight, scene break, AI continue, hide keyboard), the bottom tabs step aside, and the caret never hides behind the strip.
- The writing page’s top bar shows “Chapter N Title”, with the draft, whether it is saved and its words underneath; tap the chapter’s name for the chapter list.
- The draft bar above the text (text / plan, which draft, final) stays at the top as you scroll and is solid, so the text never shows through; words and today’s time sit at the end of the text instead of floating over it.
- Writing reference, checks, text settings, find and replace, typeset and version history are in the draft bar’s “⋯” and rise from the bottom on a phone; version history fills the screen there, the list first, then one version.
- On a phone, Enter in the assistant’s box starts a new line; the send button sends.
- On touch screens the small icon buttons in the assistant’s header, the conversation list and the find bar are 44 pixels too, and an empty chapter’s “AI draft” and “Plan it first” are easier to tap.

### On phones, back closes menus before going up a level, and menus rise from the bottom <sub>v0.1.41</sub>

- On phones and tablets, back (Android’s back key, the iPhone edge swipe, the browser’s back) first closes an open menu or panel, then goes up a level: an open note back to its folder, a chapter being read back to the contents. Only on one of the book’s own tabs does it leave the book.
- Menus and dialogs on phones rise from the bottom, with taller rows and larger text; tap outside, tap ×, drag down or press back to close. Search, import and the trash take the whole screen; on tablets they sit in the middle. The account menu works the same way.
- The book’s top bar keeps only back, the book’s title, search and “⋯”. Quick note, switching books, import, export, the trash and the credits balance are in “⋯”; with a chapter or note open, the top bar shows its name.
- In a book on a phone, the “Assistant” tab opens the assistant over the page you are on; back puts it away.
- On the planning board on a phone, “Keep this book” no longer half covers the “Ideas” tab: the top bar starts with “‹ Ideas” instead.
- On computers, after opening a folder, a note or a chapter to read, the browser’s back goes up a level.

### Link previews, and easier to find in search <sub>v0.1.40</sub>

- Page titles and descriptions now say what the site does (AI novel writing: one sentence to your first chapter), and each public page has its own title, so search engines find it more easily.
- Links to the site shared on X, Reddit, Discord, WeChat and the like show a title, a description and a picture.

### Easier to tap and read on phones, and ready for the home screen <sub>v0.1.38</sub>

- On phones and touch screens, buttons, icons, menus, list rows and the top tabs are at least 44 pixels tall, so a finger lands where it means to; so are “Sign up” and “Forgot password” on the sign-in page.
- No text on a phone is smaller than 12 pixels any more; notes and assistant replies are 16 pixels, chapter text 18 (unless you picked a size in the text settings).
- Tapping a text box on an iPhone no longer zooms the whole page in.
- Light grey details such as word counts, times and note counts are a little darker and easier to read, on computers too; in the dark theme, blue buttons are deeper so their white text stands out.
- You can “Add to Home Screen”: from the icon it opens in its own window, and the browser bar takes the light or dark theme’s colour.

### Phones get the “update the story bible” offer after a final draft <sub>v0.1.37</sub>

- On a phone, tapping “Make final” now brings up the assistant with the offer to bring the story bible up to date with the chapter: one tap updates it, lists what was added and changed, and can be undone in one go. Before, the offer only showed in the assistant beside the writing page on a computer; on a phone you had to ask the assistant in words.
- In an empty conversation (the Assistant tab, or a new conversation) the offer now sits above the welcome; before, it was below it, out of sight on phones and computers alike. In a conversation with messages, the assistant scrolls down to it.

### Settings no longer lose notes or cut them short <sub>v0.1.36</sub>

- When settings are built for a new book, brought up to date from chapters, organized from an import or from the whole book’s memory, the model sometimes made a small slip writing them — a stray quote, or two notes run together on one line — and notes went missing, sometimes all of them; now every note comes through.
- A note whose text had a real line break in it used to be saved with its first line only; now the whole note is saved.

### Planning cards survive small format slips <sub>v0.1.35</sub>

- Each planning step gives you three cards. When the model made a small slip writing them — a stray quote, or two cards run together on one line — you sometimes got one or two, or none at all; now every card comes through.
- A card with a line break in the middle used to keep only the text before the break and lose the rest; now the whole card is read.

### Assistant: next steps in your language, big changes no longer get stuck <sub>v0.1.34</sub>

- Ask in English and the next-step buttons under the reply are in English too; before, they sometimes came back in Chinese. Other languages follow your latest message the same way.
- When a change touches many notes, the assistant makes it in rounds of a few notes, and each round shows up as it lands. Before, asking for too many changes at once could run past the model’s reply limit: nothing was changed and the reply sat on “Working…”.
- If a reply still stops before it finishes, it says how many changes were not made and offers “Continue”, instead of spinning forever.
- On the writing page, when the toolbar wraps onto two rows, the Checks panel no longer opens over the chapter list, so “Continuity check” can be clicked.

### Planning stays in your idea’s language <sub>v0.1.33</sub>

- An idea written in English now gets every later step — world, characters, opening and the rest — in English; before, a step sometimes came back in Portuguese, Spanish or Chinese. Ideas in Spanish, French and other languages still get their own language.
- The book’s language is decided once when you start planning and goes with the book when you keep it, so chapter plans, drafts and notes follow it too. Rewording the idea decides it again.

## 2026-10-23

### Membership through Creem only <sub>v0.1.32</sub>

- The membership renews every month, so it is now paid through Creem only: its checkout takes cards, Apple Pay, Google Pay or Alipay. Packs can still be bought with Alipay directly (in yuan).
- The ways to pay now show the Visa, Mastercard, Apple Pay, Google Pay and Alipay marks.

### Membership <sub>v0.1.31</sub>

- New: membership. $9.90 a month brings 10,000 credits each month that never expire, plus 200 more every day, saved up to 600. By card it renews monthly and can be stopped or restarted any time in Settings → Membership; with Alipay you buy 30 days at a time and nothing renews.
- Credits are spent in this order: a member’s daily credits, the monthly free ones, gifts, and bought credits last.
- The site tells you when a membership is about to end, a renewal failed, or it has ended; when credits run short it says what arrives tomorrow.
- The terms, the refund policy and the privacy policy now cover the membership.

### Card prices are before tax <sub>v0.1.30</sub>

- When you pay by card, Apple Pay or Google Pay, pack prices are before tax: where tax applies, Creem adds it at checkout and shows the total before you pay. The pricing page and the terms say so. Alipay payments are unchanged.

### Getting ready for card payments <sub>v0.1.28</sub>

- Preparation for paying by card, Apple Pay and Google Pay (handled by Creem): a partial refund takes back credits in proportion to what you actually paid, tax included, and no more.

### Free tries can pause, and Google sign-in is simpler <sub>v0.1.26</sub>

- Trying without an account can be paused when needed; while paused, the home page and the board ask you to sign up or sign in first.
- Settings → Sign-in and security no longer links or unlinks a Google account: signing in with Google is enough, and an account with the same verified email is still linked by itself.

### Plan an idea before signing in <sub>v0.1.25</sub>

- Write one sentence on the home page and the planning board opens without an account: look through directions, characters, world and more, and choose. Writing chapter one or keeping the book asks you to sign in or sign up, and the board comes with you.
- A board tried without an account is kept in that browser for 7 days; free tries are limited each day.
- The privacy policy says so.

### Chinese or English, by your browser’s language <sub>v0.1.24</sub>

- On a first visit the site shows Chinese to browsers set to Chinese and English to everyone else; once you switch the language yourself, your choice stays.

### Link a Google account in Settings <sub>v0.1.21</sub>

- Settings → Sign-in and security can link a Google account — any one, even with a different email — so it signs in to this account; it can be unlinked again.
- Signing in with Google does not ask for the two-step code: your Google account’s own security stands in for it. Email and password sign-in still asks for it.
- Privacy policy: server access logs (time, IP address, page, browser) are kept for at most 14 days, for the site’s security and visit counts.

### Sign in with Google <sub>v0.1.20</sub>

- The sign-in and sign-up pages offer “Continue with Google”: the first time makes your account; an account already made with the same email is linked instead of a second one being made.
- Only your name, email and account id come from Google — not your picture — and nothing is ever done in your Google account. Settings → Sign-in and security shows how you can sign in.
- Invite friends is open to everyone.

### Fuller settings, new note layout, invite friends (preview) <sub>v0.1.19</sub>

- After importing chapters or notes, one click has the assistant organize the settings; a book with chapters but almost no settings gets the offer on its overview and in the assistant.
- Organizing covers more: people (background, abilities, relationships), organizations and their ranks, rules and systems, places, items, the outline and foreshadowing, each in its own note with the chapters it comes from.
- Notes have a new layout: every block lines up on one left edge; timelines by chapter are small annotations, with the latest five first when they are long; names in relationships open their notes.
- Invite friends: avatar menu → Invite friends, with your link, a ready message and a QR code; a friend’s first top-up comes with 10% extra and you get 20% of the credits they buy (a preview at first).
- A release notes page on the site.

### Writing page and assistant polish <sub>v0.1.17</sub>

- No more gap under a chapter title; the word count sits at the foot of the page; an empty chapter’s AI options sit right under its first line.
- On phones the assistant closes with one tap, opens on the latest message, and its box is a one-line chat field; copy and regenerate stay visible.

### Steadier ideas and plans <sub>v0.1.16</sub>

- Ideas in Spanish, French and other languages get their planning cards in that language.
- Chapter plans keep beat one’s opening line; a paragraph is never written twice.
- Fonts come with the site, so pages open faster.

### Alipay for everyone <sub>v0.1.15</sub>

- Every account can buy credit packs with Alipay; prices still show in dollars and Alipay charges yuan at the rate shown.

### Back from Alipay, fixed <sub>v0.1.14</sub>

- After paying you come back to the site and see the credits arrive.

## 2026-10-22

### A new credits page <sub>v0.1.10–v0.1.13</sub>

- Packs are cards you pick, with how much they let you write; one pay panel; on phones the pay bar stays at the bottom.
- The next few releases fixed details on phones.

### Pay with Alipay <sub>v0.1.8–v0.1.9</sub>

- Besides cards, Alipay can be used to pay (first checked in a test environment).

### Faster book page, sign-in records <sub>v0.1.7</sub>

- The book page opens faster on slow connections.
- Each sign-in’s time and network address are kept for 90 days (to spot mass sign-ups); see the privacy policy.

### Credit rules and terms <sub>v0.1.1–v0.1.6</sub>

- The site’s daily free budget counts free credits only; when it runs out, new free AI work waits for the next day, and bought credits are never stopped.
- The credits page shows every pack and its price before buying opens.
- The terms say who runs the service and rule out sexually explicit content; the refund policy explains bonus credits.

### Launch <sub>v0.1.0</sub>

- WriteAnytime opens at writesmart.top: ideas, plans, writing, notes and the assistant.
