# ReplyZero

ReplyZero is a Chrome extension for YouTube creators that turns unanswered comments into a focused inbox.

Instead of opening videos one by one and trying to remember which viewers still need a response, ReplyZero scans the authenticated creator's channel, identifies comment threads that have not received a reply from that channel, and surfaces them in one place.

🌐 **Website:** https://replyzero.eu/

## What ReplyZero does

- Connects to a YouTube creator account through Google OAuth
- Detects the authenticated YouTube channel
- Scans comment threads and replies
- Surfaces comments the channel has not replied to yet
- Lets creators open the original comment on YouTube
- Lets creators mark comments as handled
- Persists handled-comment state between sessions
- Sorts the inbox by newest, oldest, or most liked
- Restores the YouTube session when Google authorization is still available
- Supports Free and Pro access

## Pricing

### Free - €0

- Up to 20 unlocked unanswered comments
- Inbox and handled views
- Open comments directly on YouTube
- Sorting by newest, oldest, or likes

### Pro - €5.99/month

- Unlimited unanswered comments
- Everything included in Free
- Subscription status handled through ExtensionPay and Stripe

## Privacy

ReplyZero uses Google OAuth and the YouTube Data API to provide its core inbox functionality.

The current application behavior does **not** post, edit, moderate, or delete YouTube comments, videos, ratings, captions, or other YouTube content.

ReplyZero does not sell YouTube user data or use it for advertising.

Full privacy policy:

https://replyzero.eu/privacy-policy.html

## Payments

ReplyZero subscriptions are handled through ExtensionPay and Stripe.

ReplyZero does not receive or store full payment-card details.

## Website repository

This repository hosts the public ReplyZero website, privacy policy, domain configuration, and Google site-verification file.

It is **not intended to expose private credentials or secrets**.

OAuth secrets, passwords, Stripe secrets, test-account credentials, and other sensitive values should never be committed here.
