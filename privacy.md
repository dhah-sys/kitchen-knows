---
layout: default
description: "What Tum Tum collects, what stays on your iPhone, what our server keeps and for how long, and who else is involved. No account, no ads."
title: Privacy policy
---

# Privacy policy

Effective November 15, 2026. Tum Tum, made by Dhiraj Pandey.

Tum Tum helps you keep track of the food you buy and eat it before it goes bad. We built it to know as little about you as possible. There is no account, no sign-up and no advertising, and we do not sell or share your information for advertising or tracking.

## What stays on your iPhone

Your Kitchen, receipt history, shopping list, meals and recipes, cookbook (including any photos of meals you take), nutrition details, garden, cooking timers and settings are saved on your iPhone. We cannot see them. The one exception: what was read from a receipt or groceries photo (the store, items, prices and date) is also kept on our server for 30 days, so scanning the same photo again is free (see **Our server**). They are part of your iPhone's own backup if you use one. Food you log and your goals in My plate stay on this iPhone too; they are never sent to us or anyone, and Delete all my data removes them. If you say a meal out loud, your iPhone turns your voice into text itself when it can; when it can't, your voice goes to Apple to be turned into text.

You can remove all of it at any time in **Settings > Help & privacy > Delete all my data**. Three things are kept: how many receipts were read in the last 30 days, so the Plus limits work (a count only, with no receipt content), whether you share usage counts, and the random code that signs your copy of the app in to our server.

## Photos read by AI: receipts and groceries

Tum Tum can read a photo of a grocery receipt (one photo, or two for a long receipt), a receipt file (PDF or picture) you open in the app, or a photo of groceries without a receipt. A photo leaves your iPhone only when you scan one; nothing is sent in the background.

When you scan, the photo goes through our server to **Anthropic**, the company that makes the Claude AI model, which reads the store, items, prices and date (for a groceries photo, only the names of the foods it sees). The answer comes back to your iPhone, where you check it before anything is added to your Kitchen.

- A receipt can show the last digits of a card, a member number, a store location or a name. Our server does not keep the photo.
- Anthropic receives the photo only to read it. Under its commercial terms, as we understand them today, it does not use this data to train its models and deletes it within 30 days. It keeps it longer (up to 2 years) only if it is flagged under its usage policy, or if the law requires.
- On your iPhone, Tum Tum hides long numbers it finds on non-purchase lines before saving a receipt to your history.
- If there is no connection when you scan, the photo waits on your iPhone (and nowhere else) until you read it or delete it. It is deleted as soon as it has been read.

## Our server

Our server is hosted by **Supabase**. It passes your photos and your cooking questions to Anthropic and runs recipe searches. To stop abuse and keep costs fair, it keeps:

- a random code for your copy of the app, checked with Apple's App Attest and DeviceCheck, so limits apply per iPhone;
- how many receipts were read, and when, for 400 days, so the Plus limits and its free trial work;
- how many cooking questions went to Anthropic, and when, with their size and cost (never the words), for 400 days, so the Plus limits work;
- a fingerprint (a hash) of each photo, for 30 days. A hash can't be turned back into the photo;
- what was read from each photo (the store, items, prices and date), for 30 days, so scanning the same photo again is free; then it is cleared;
- a scrambled code (a hash) of the network address a request came from, for one hour, to slow down attacks. Never the address itself;
- messages you send with **Send feedback**, and your answers to the app's occasional short questions, with the random code for your copy of the app, until we have dealt with them (at most a year);
- a few usage counts, such as "the app was opened today", "Meals was opened today", "3 foods were checked yesterday" or "a receipt was confirmed (16 foods)", with the time and the random code for your copy of the app, for at most 400 days. They never include food names, prices, photos or anything you typed. Turn them off in **Settings > Help & privacy > Share usage counts**.

It does not keep your name, email, your iPhone's location, the receipt photo, your questions to Tum Tum or his answers, your Kitchen or My plate. Its logs record counts and errors, never receipt content or questions. These clean-ups run every day on their own.

## Food lookups and recipes

- **Nutrition and best-by estimates** are worked out on your iPhone from USDA's public food lists, which are built into the app. Nothing is sent.
- **Barcodes:** a barcode you scan is looked up in Open Food Facts straight from your iPhone. Only the barcode number is sent.
- **Recipes:** the recipe list and your search words go through our server to TheMealDB. Your Kitchen is never sent; recipes are matched with your Kitchen on your iPhone. Recipe pages you open are kept on your iPhone so they work offline.
- **Recipe photos and links:** recipe photos load straight from TheMealDB, and a recipe link you paste is opened from your iPhone. Those sites see your network address, nothing else.

## Ask Tum Tum, Update kitchen, voice and reading aloud

Quick kitchen questions to Ask Tum Tum (what you have, what to eat first, what you spent, how long a food keeps) are answered on your iPhone, with Apple's on-device model on iPhones that have it. Update kitchen works on your iPhone too. These questions and changes are not sent to us.

Cooking questions (a recipe, a swap, how to cook something) can be answered by **Anthropic's** Claude AI with Tum Tum Plus, including its free trial. Quick kitchen questions are answered on your iPhone. A cooking question goes through our server to Anthropic with the food names in your Kitchen (no amounts, prices or receipts) and your last few messages in that chat, so the answer can use what you have. Anthropic receives them only to answer. Under its commercial terms, as we understand them today, it does not use this data to train its models and deletes it within 30 days, keeping it longer only if it is flagged under its usage policy or the law requires. Our server does not keep the question or the answer, only counts (see **Our server**).

If you speak to Tum Tum, Apple's speech recognition turns it into text; Tum Tum asks for the microphone only when you start speaking. Reading a cooking step aloud uses your iPhone's built-in voice.

## Siri, the widget, reminders and cooking timers

- **Siri and Shortcuts** commands are handled by Apple and your iPhone.
- **The widget** shows foods to eat first on your Home Screen. Its copy of the list stays on your iPhone and is cleared by Delete all my data.
- **Food reminders** are scheduled on your iPhone. Turning them on asks iOS for permission. Nothing about them is sent to us.
- **Cooking timers** are alarms set on your iPhone (with your permission, so they ring even on silent and show on the Lock Screen). Nothing about them is sent to us.

## Camera and photos

Tum Tum uses the camera only when you choose to scan a receipt, groceries or a barcode, or take a photo of a meal for your cookbook. Meal photos stay on your iPhone. Choosing a photo from your library gives Tum Tum only that photo.

## Subscriptions

Tum Tum Plus is sold through Apple. Apple handles payment; we never see your card. Our server receives Apple's signed record of your subscription (its transaction number, plan and end date, and which copies of the app use it) to apply the Plus limits. It keeps this while Plus is active and for one year after it ends. Manage or cancel it in **iPhone Settings > your name > Subscriptions**. Deleting your data in Tum Tum does not cancel a subscription.

## Who else is involved

- **Apple**: the App Store, payments, App Attest, Siri, speech recognition and the on-device model.
- **Supabase**: hosts our server.
- **Anthropic**: reads the photos you choose to scan, and answers the cooking questions you ask Tum Tum.
- **TheMealDB**: recipes.
- **Open Food Facts**: barcode lookups.

Each receives only what is described above and must protect it at least as well as this policy does.

## Children

Tum Tum is not meant for children under 13, and we do not knowingly collect information from them.

## Your choices and rights

- Turn off usage counts, reminders or read-aloud in Settings at any time. Photos are read only when you scan one, and cooking questions go to Anthropic only when you ask one with Plus.
- Delete everything on your iPhone with **Delete all my data**.
- To ask for server records to be removed sooner, or for any privacy question, use **Settings > Help & privacy > Send feedback** or email **dhiraj.bayar@gmail.com**.
- Depending on where you live (for example California or the EU), you may have rights to see, correct or delete your information. We will honor those requests.

## Changes

If this policy changes in a way that matters, we will update the date above and tell you in the app.

[Terms of use](terms.html) · [Support](support.html)
