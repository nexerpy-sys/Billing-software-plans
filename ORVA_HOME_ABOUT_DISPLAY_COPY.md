# ORVA — Home & About Us Display Copy

**Purpose:** Copy handoff for Gemini's Android Home and About Us frontend implementation.

**Source authority:** ORVA WPF showcase design constitution and Home/About experience blueprint in `ORVA-main.zip`, plus the current Android collaboration specification (Sections 12–20). This file consolidates display wording; it does not authorize redesigning ORVA's branding or inventing factual claims.

**Language policy:** English and Bengali must have parity. The English and Bengali strings below are grounded in the existing ORVA source. Bengali translations marked **[translation for parity]** translate the blueprint's newly specified Home folder-sheet labels; they were not quoted verbatim from the old WPF fallback.

---

## 1. Home

### H1 — Opening hero

**Top metadata**
- Shop name: `{ShopName}` (dynamic, from the existing shop profile)
- Date: `{DateText}` (dynamic)

**Headline**
- EN: `Built for the pace` / *`behind the counter.`*
- BN: `কাউন্টারের প্রতিদিনের` / *`গতির জন্য তৈরি।`*

**Subtitle**
- EN: `Fast counter billing, careful batch and expiry checks, and local records that stay under your roof.`
- BN: `দ্রুত বিলিং, ব্যাচ ও মেয়াদের সতর্ক হিসাব এবং আপনার কম্পিউটারেই সুরক্ষিত দোকানের রেকর্ড।`

**Actions**
- EN: `Start Billing →` | `+ Add Stock`
- BN: `বিলিং শুরু করুন →` | `+ স্টক যোগ করুন`

**Single-line readiness strip**
- EN: `{ShopName} · {UsableMedicines} medicines ready · {ExpiringSoonCount} expiring within 30 days · Backup: {BackupStatusText}`
- BN: `{ShopName} · {UsableMedicines}টি ওষুধ প্রস্তুত · ৩০ দিনের মধ্যে মেয়াদ শেষ: {ExpiringSoonCount} · ব্যাকআপ: {BackupStatusText}`

Backup status values:
- `Saved` → `সুরক্ষিত`
- `Due today` → `বকেয়া`
- `Not yet backed up` → `এখনো ব্যাকআপ হয়নি`

Only show real values supplied by the existing local Home data. Do not invent counts, status, shop names, or dates. Keep this as one restrained text strip: no KPI cards, progress rings, or technical jargon.

### H2 — Editorial identity statement

**Left statement**
- EN: `Clear bills.` / `Careful stock.`
- BN: `পরিষ্কার বিল।` / `সতর্ক স্টক।`

**Right paragraphs**
- EN paragraph 1: `ORVA is built for independent retail pharmacies that need dependable counter software without clutter or cloud lock-in. Everyday billing, batch tracking, sales returns, and GST records run locally on your counter computer.`
- EN paragraph 2: `Open the navigation menu at any time—or press Ctrl+B—to move straight into billing.`
- BN paragraph 1: `স্বাধীন ফার্মেসির প্রতিদিনের কাজের জন্য জটিলতাহীন ও নির্ভরযোগ্য ডেস্কটপ সফটওয়্যার হিসেবে ORVA তৈরি। বিলিং, ব্যাচ ও মেয়াদ তদারকি, সেলস রিটার্ন এবং GST রেকর্ড—সবকিছুই আপনার দোকানের কম্পিউটারেই চলে।`
- **Android-edition wording review:** The Bengali line above is inherited from the older Windows/WPF copy and explicitly says “desktop software” and “shop computer.” For the Android edition, a platform-neutral adaptation is: `স্বাধীন ফার্মেসির প্রতিদিনের কাজের জন্য জটিলতাহীন ও নির্ভরযোগ্য কাউন্টার সফটওয়্যার হিসেবে ORVA তৈরি। বিলিং, ব্যাচ ও মেয়াদ তদারকি, সেলস রিটার্ন এবং GST রেকর্ড—সবকিছুই স্থানীয়ভাবে পরিচালিত হয়।` Treat this as an adaptation proposal for review, not a verbatim legacy string.
- BN paragraph 2: `যেকোনো সময় উপরের বাম মেনু খুলুন—অথবা Ctrl+B চেপে সরাসরি বিলিংয়ে যান।`

**Three-item strengths index**
- EN: `Local & Always Ready` · `Clean GST Invoices` · `Portable Shop Backups`
- BN: `স্থানীয়ভাবে, সবসময় প্রস্তুত` · `পরিষ্কার GST বিল` · `সহজে বহনযোগ্য দোকানের ব্যাকআপ` **[translation for parity]**

### H3 — Physical folder shelf

**Section heading**
- EN: `Built for the counter.`
- BN: `কাউন্টারের কাজের জন্য।`

**Folder 01 — Quick Billing**
- Tab: `01 · COUNTER` / `০১ · কাউন্টার`
- Title: `Quick Billing` / `দ্রুত বিলিং`
- Action: `Start Billing` / `বিলিং শুরু করুন`
- Existing concise body: `Create bills quickly and print clean customer receipts.` / `দ্রুত বিল তৈরি করুন এবং পরিষ্কার রসিদ প্রিন্ট করুন।`
- Inner sheets (blueprint wording):
  1. `Keyboard & Barcode Ready` / `কিবোর্ড ও বারকোড ব্যবহারের উপযোগী` **[translation for parity]**
  2. `Clean GST & Customer Receipts` / `পরিষ্কার GST বিল ও গ্রাহকের রসিদ` **[translation for parity]**
  3. `Fast Counter Checkout` / `কাউন্টারে দ্রুত বিল সম্পন্ন` **[translation for parity]**

**Folder 02 — Expiry & Stock**
- Tab: `02 · EXPIRY WATCH` / `০২ · মেয়াদ তদারকি`
- Title: `Expiry & Stock` / `মেয়াদ ও স্টক`
- Action: `Open Inventory` / `স্টক দেখুন`
- Existing concise body: `Keeps expired stock out of regular counter sales automatically.` / `মেয়াদোত্তীর্ণ ওষুধ সাধারণ বিক্রি থেকে স্বয়ংক্রিয়ভাবে আলাদা রাখে।`
- Inner sheets (blueprint wording):
  1. `Batch & Expiry Safeguards` / `ব্যাচ ও মেয়াদের সুরক্ষা` **[translation for parity]**
  2. `{ExpiringSoonCount} Expiring ≤ 30 Days` / `৩০ দিনের মধ্যে মেয়াদ শেষ: {ExpiringSoonCount}`
  3. `Earliest-Expiry Stock Priority` / `যে ব্যাচের মেয়াদ আগে, সেটিকে আগে অগ্রাধিকার` **[translation for parity]**

**Folder 03 — About ORVA**
- Tab: `03 · RINDLE WORKS` / `০৩ · RINDLE WORKS`
- Title: `About ORVA` / `ORVA সম্পর্কে`
- Action: `Read About Us` / `আমাদের কথা পড়ুন`
- Existing concise body: `Story, principles, version, and local support details.` / `আমাদের গল্প, মূলনীতি, সংস্করণ ও সহায়তার তথ্য।`
- Inner sheets:
  1. `Rindle Works · Provisional Studio` / `Rindle Works · আপাতত ব্যবহৃত স্টুডিও-নাম` **[translation for parity]**
  2. `ORVA v{AppVersion}` (dynamic version)
  3. `Five Principles & Support` / `পাঁচটি মূলনীতি ও সহায়তা` **[translation for parity]**

### H4 — Footer and closing line

- Closing line EN: `See you at the counter.`
- Closing line BN: `কাউন্টারের প্রতিদিনের কাজে আপনার সাথে।`
- Links: `Start Billing` · `About Us` · `Back to top ↑`
- Dynamic metadata: `RINDLE WORKS · ORVA v{AppVersion}`

---

## 2. About Us

### A1 — Hero

**Metadata**
- Left: `ORVA — ABOUT US` / `ORVA — আমাদের কথা`
- Right: `RINDLE WORKS · V{AppVersion}` (dynamic)

**Headline**
- EN: `Made for the work behind the counter.`
- BN: `কাউন্টারের প্রতিদিনের কাজের জন্য তৈরি।`

**Lead**
- EN: `Clear bills. Careful stock. Your records, kept close.`
- BN: `পরিষ্কার বিল। সতর্ক স্টক ব্যবস্থাপনা। আপনার রেকর্ড, আপনার কাছেই।`

### A2 — Our Story

**Section label:** `OUR STORY` / `আমাদের কথা`

**Paragraph 1**
- EN: `Rindle Works is the working studio name behind ORVA. We are building ORVA around the everyday realities of independent pharmacies: quick billing, careful batch and expiry management, and reliable business records.`
- BN: `ORVA-এর পেছনের নির্মাণ-পরিচয় Rindle Works। স্বাধীন ফার্মেসির প্রতিদিনের বাস্তব প্রয়োজন—দ্রুত বিলিং, ব্যাচ ও মেয়াদের সঠিক হিসাব এবং নির্ভরযোগ্য ব্যবসায়িক রেকর্ড—মাথায় রেখেই ORVA তৈরি হচ্ছে।`

**Paragraph 2**
- EN: `Our aim is simple: make essential shop operations easier to manage, without making the software itself complicated. ORVA keeps everyday work local, practical and under the shop's control.`
- BN: `আমাদের উদ্দেশ্য সহজ: প্রয়োজনীয় দোকানের কাজগুলোকে আরও গুছিয়ে দেওয়া, সফটওয়্যারকে জটিল না করে। ORVA দৈনন্দিন কাজকে স্থানীয়ভাবে পরিচালিত, ব্যবহারিক এবং দোকানের নিজস্ব নিয়ন্ত্রণে রাখতে সাহায্য করে।`

This story is deliberately grounded. Do not add a founding year, founder biography, team-size claim, office address, customer count, testimonial, or unsupported company history.

### A3 — The Principles Behind ORVA

**Section label:** `THE PRINCIPLES BEHIND ORVA` / `ORVA-এর পাঁচটি মূলনীতি`

**01 — Local by Design**
- BN title: `০১ — স্থানীয় ব্যবস্থায়, ইন্টারনেট ছাড়াও`
- EN: `Everyday billing and inventory operations are designed to work without an internet connection.`
- BN: `দৈনন্দিন বিলিং ও স্টকের কাজ ইন্টারনেট সংযোগ ছাড়াই চালিয়ে যাওয়ার জন্য ORVA তৈরি।`

**02 — Accurate to the Paise**
- BN title: `০২ — পয়সা পর্যন্ত নির্ভুল হিসাব`
- EN: `Invoice amounts and GST calculations use integer-paise precision for careful financial handling.`
- BN: `বিলের পরিমাণ ও GST-এর হিসাব পূর্ণ পয়সার এককে করা হয়, যাতে আর্থিক হিসাব নির্ভুল থাকে।`

**03 — Every Batch Matters**
- BN title: `০৩ — প্রতিটি ব্যাচ গুরুত্বপূর্ণ`
- EN: `Batch numbers, expiry dates and earliest-expiry-first stock selection help ensure that unsuitable stock is excluded from ordinary sales.`
- BN: `ব্যাচ নম্বর, মেয়াদ এবং আগে মেয়াদ শেষ হওয়া ব্যাচ আগে বাছাইয়ের মাধ্যমে মেয়াদোত্তীর্ণ বা অনুপযুক্ত স্টক সাধারণ বিক্রি থেকে বাদ রাখা হয়।`
- Wording note: Prefer the plain-language phrase `earliest-expiry-first stock selection`; the blueprint recommends avoiding the unexplained acronym `FEFO`.

**04 — Your Records, Your Control**
- BN title: `০৪ — আপনার রেকর্ড, আপনার নিয়ন্ত্রণে`
- EN: `Shop data is stored locally. The portable .shopbackup file gives the shop owner control over backup, recovery and migration.`
- BN: `দোকানের তথ্য স্থানীয় স্টোরেজে থাকে। .shopbackup ফাইলের মাধ্যমে দোকানের মালিক নিজেই ব্যাকআপ, পুনরুদ্ধার ও অন্য কম্পিউটারে তথ্য স্থানান্তর করতে পারেন।`

**05 — Made for Real Counters**
- BN title: `০৫ — ফার্মেসির বাস্তব কাজের কথা ভেবে`
- EN: `Keyboard-friendly billing, barcode scanning and English–Bengali support are designed around the pace of everyday pharmacy work.`
- BN: `কিবোর্ডের মাধ্যমে দ্রুত বিলিং, বারকোড স্ক্যানিং এবং বাংলা–ইংরেজি ভাষার সুবিধা প্রতিদিনের কাজকে সহজ ও গতিশীল রাখার জন্য তৈরি।`

### A4 — Support & Contact / Product & Ownership

**Support heading**
- EN: `SUPPORT & CONTACT` / `Need assistance?`
- BN: `সহায়তা ও যোগাযোগ` / `সহায়তা প্রয়োজন?`

Contact values must be read from app settings only:
- Phone: show only when a support phone value is configured.
- Email: show only when a support email value is configured.
- Never hardcode fallback phone numbers or email addresses.
- If both are absent, display: `Support contact details are not configured yet. Add them in Settings.`
- BN: `সহায়তার যোগাযোগের তথ্য এখনো সেটিংসে যুক্ত করা হয়নি।`

**Product & ownership**
- Heading: `PRODUCT & OWNERSHIP` / `পণ্য ও পরিচিতি`
- Product: `ORVA — Pharmacy Billing & Inventory` / `ORVA — ফার্মেসি বিলিং ও ইনভেন্টরি`
- Developed by: `Rindle Works` / `নির্মাতা: Rindle Works`
- Studio status EN: `Studio name: Provisional; Indian trademark clearance pending.`
- Studio status BN: `স্টুডিওর নাম: আপাতত ব্যবহৃত; ভারতে ট্রেডমার্ক যাচাই ও অনুমোদন বাকি।`
- Version: `{AppVersion}` (dynamic)
- Build: `{BuildNumber}` (dynamic)
- Optional ownership reassurance EN: `Your shop's business records remain in local storage under your control.`

**Actions**
- `Start Billing →` / `বিলিং শুরু করুন →`
- `Back to Home` / `হোমে ফিরে যান`

### Shared closing

Use the same closing/frieze language as Home:
- `See you at the counter.` / `কাউন্টারের প্রতিদিনের কাজে আপনার সাথে।`
- Dynamic metadata `RINDLE WORKS · ORVA v{AppVersion}`.

---

## 3. Data-driven text and implementation guardrails

1. `{ShopName}`, `{DateText}`, counts, backup status, app version, build number, phone and email are dynamic fields, not literal copy.
2. Do not show internal development labels, fake metrics, unsupported statistics, or invented business history.
3. Do not hardcode support phone/email fallback values. If a value is absent, omit the row; if both are absent, use the approved empty-state sentence.
4. Never hardcode a sample shop name or sample counts in the production UI.
5. Preserve full English/Bengali parity for all visible copy, buttons, folder sheets, labels, empty states and accessibility descriptions.
6. Keep ORVA's existing showcase identity and font direction. saai.pro is an animation-behaviour reference only; do not copy its branding, content, fonts, layout or artwork.
7. Home and About are showcase screens. Do not restyle operational billing/inventory screens as part of this task.
8. Keep the About construction animation as a mandatory part of the About experience, while keeping the final Compose content real, accessible and interactive.
