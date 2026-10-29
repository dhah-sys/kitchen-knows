---
title: Privacy policy
---

# Privacy policy

Effective October 28, 2026. Kitchen Knows, made by Dhiraj Pandey.

Kitchen Knows helps you keep track of the food you buy and eat it before it goes bad. We built it to know as little about you as possible. There is no account, no sign-up and no advertising, and we do not sell or share your information for advertising or tracking.

## What stays on your iPhone

Your Kitchen, receipt history, shopping list, meals and recipes, cookbook (including any photos of meals you take), nutrition details, garden, cooking timers and settings are saved only on your iPhone. We cannot see them. They are part of your iPhone's own backup if you use one.

You can remove all of it at any time in **Settings > Help & privacy > Delete all my data**. Two things are kept: how many free receipts you have used, so the free trial can't be restarted (a count only, with no receipt content), and whether you share usage counts.

## Photos read by AI: receipts and groceries

Kitchen Knows can read a photo of a grocery receipt (one photo, or two for a long receipt), a receipt file (PDF or picture) you open in the app, or a photo of groceries without a receipt. Before the first photo ever leaves your iPhone, Kitchen Knows asks your permission. After that, a photo is sent only when you scan one. **Delete all my data** also takes back your permission, and the app asks again before the next scan.

With your permission, the photo goes through our server to **Anthropic**, the company that makes the Claude AI model, which reads the store, items, prices and date (for a groceries photo, only the names of the foods it sees). The answer comes back to your iPhone, where you check it before anything is added to your Kitchen.

- A receipt can show the last digits of a card, a member number, a store location or a name. Our server does not keep the photo.
- Anthropic receives the photo only to read it. Under its commercial terms, as we understand them today, it does not use this data to train its models and deletes it within 30 days. It keeps it longer (up to 2 years) only if it is flagged under its usage policy, or if the law requires.
- On your iPhone, Kitchen Knows hides long numbers it finds on non-purchase lines before saving a receipt to your history.
- If there is no connection when you scan, the photo waits on your iPhone (and nowhere else) until you read it or delete it. It is deleted as soon as it has been read.

## Our server

Our server is hosted by **Supabase**. It passes your photo to Anthropic and runs recipe searches. To stop abuse and keep costs fair, it keeps:

- a random code for your copy of the app, checked with Apple's App Attest and DeviceCheck, so free trials and limits apply per iPhone;
- how many receipts were read and confirmed, and when, with a fingerprint (a hash) of each photo. A hash can't be turned back into the photo;
- what was read from each photo, for 30 days, so scanning the same photo again is free; then it is cleared;
- a scrambled code (a hash) of the network address a request came from, for one hour, to slow down attacks. Never the address itself;
- messages you send with **Send feedback**, until we have dealt with them (at most a year);
- a few usage counts, such as "the app was opened today", "Meals was opened today", "3 foods were checked yesterday" or "a receipt was confirmed (16 foods)", with the time and the random code for your copy of the app, for at most 400 days. They never include food names, prices, photos or anything you typed. Turn them off in **Settings > Help & privacy > Share usage counts**.

It does not keep your name, email, location, the receipt photo or your Kitchen. Its logs record counts and errors, never receipt content.

## Food lookups and recipes

- **Nutrition and best-by estimates** are worked out on your iPhone from USDA's public food lists, which are built into the app. Nothing is sent.
- **Barcodes:** a barcode you scan is looked up in Open Food Facts straight from your iPhone. Only the barcode number is sent.
- **Recipes:** the recipe list and your search words go through our server to TheMealDB. Your Kitchen is never sent; recipes are matched with your Kitchen on your iPhone. Recipe pages you open are kept on your iPhone so they work offline.

## Ask Tum Tum, Update kitchen, voice and reading aloud

Ask Tum Tum and Update kitchen work on your iPhone, with Apple's on-device model on iPhones that have it. Your questions and changes are not sent to us. If you speak to Kitchen Knows, Apple's speech recognition turns it into text; Kitchen Knows asks for the microphone only when you start speaking. Reading a cooking step aloud uses your iPhone's built-in voice.

## Siri, the widget, reminders and cooking timers

- **Siri and Shortcuts** commands are handled by Apple and your iPhone.
- **The widget** shows foods to eat first on your Home Screen. Its copy of the list stays on your iPhone and is cleared by Delete all my data.
- **Food reminders** are scheduled on your iPhone. Turning them on asks iOS for permission. Nothing about them is sent to us.
- **Cooking timers** are alarms set on your iPhone (with your permission, so they ring even on silent and show on the Lock Screen). Nothing about them is sent to us.

## Camera and photos

Kitchen Knows uses the camera only when you choose to scan a receipt, groceries or a barcode, or take a photo of a meal for your cookbook. Meal photos stay on your iPhone. Choosing a photo from your library gives Kitchen Knows only that photo.

## Subscriptions

Kitchen Knows Plus is sold through Apple. Apple handles payment; we never see your card. Our server receives Apple's signed record of your subscription to apply the Plus limits. Manage or cancel it in **iPhone Settings > your name > Subscriptions**. Deleting your data in Kitchen Knows does not cancel a subscription.

## Who else is involved

- **Apple**: the App Store, payments, App Attest, Siri, speech recognition and the on-device model.
- **Supabase**: hosts our server.
- **Anthropic**: reads the photos you choose to scan.
- **TheMealDB**: recipes.
- **Open Food Facts**: barcode lookups.

Each receives only what is described above.

## Children

Kitchen Knows is not meant for children under 13, and we do not knowingly collect information from them.

## Your choices and rights

- Turn off usage counts, reminders or read-aloud in Settings at any time. Photos are read only when you scan one.
- Delete everything on your iPhone with **Delete all my data**.
- To ask for server records to be removed sooner, or for any privacy question, use **Settings > Help & privacy > Send feedback** or email **dhiraj.bayar@gmail.com**.
- Depending on where you live (for example California or the EU), you may have rights to see, correct or delete your information. We will honor those requests.

## Changes

If this policy changes in a way that matters, we will update the date above and tell you in the app.

[Terms of use](terms.html) · [Support](support.html)
