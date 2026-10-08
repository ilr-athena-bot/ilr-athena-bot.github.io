---
title: Athena Privacy Policy
permalink: /privacy
---

# Athena Privacy Policy

Last updated: October 8, 2026.

Athena is a private Discord moderation bot, developed and operated by an independent developer, Eileen. It is not public: only its developer can add it to a server. Contact: athena-bot-contact@proton.me.

## Data processed

| Data | Purpose | Where | Retention |
| --- | --- | --- | --- |
| Server configuration (channels, welcome and leave messages, language, warning templates, automatic response triggers and responses written by staff, streaming role settings including the IDs of members excluded or included by moderators, date the bot was added) | Running the bot | Bot database | As long as the bot is on the server |
| Warnings: server, moderator and member IDs, reason chosen from a list, date | Moderation history | Bot database | 3 years |
| Mutes and channel restrictions: server, moderator and member IDs, date, duration, expiry | Applying the sanction, re-applying it if the member leaves and rejoins, and escalating repeat offenders | Bot database | 3 years |
| Content of the last 100 messages in each channel | Showing moderators an edited or deleted message | Memory (RAM) only, never written to disk | 24 hours at most |
| Content of edited or deleted messages, voice channel joins and leaves | Moderation log | Posted to a Discord channel restricted to staff, not kept by the bot | Purged after 30 days at most |

The bot does not store usernames, avatars or message content in its database.

If a server enables the streaming role, the bot reads in real time whether a member with the configured role is streaming, only to add or remove a live role. After a restart, it may check the current activity of members who still have that role, to decide whether to keep it. This presence data is held in memory only for the moment needed, and is never written to disk, logged or shared. Members without the configured role are not affected, and any member can ask a moderator to be excluded from this feature.

## Legal basis

This processing is based on the legitimate interest in moderating the servers where the bot is installed and protecting their members (preventing raids, spam and abuse), and in highlighting community members who streams.

## What the bot does not do

- No selling, renting or sharing of data with third parties.
- No advertising or profiling.
- No use of messages for machine learning or AI training.

## Hosting and access

The bot's database is hosted by a hosting provider in the European Union (currently in Germany), on storage encrypted at rest. Only the developer, Eileen, has access to it. Moderation logs are visible only to the moderation team of the server concerned.

## Your rights

Message and voice channel logs are purged automatically after 30 days at most. You can request access to, correction of, or deletion of your data by writing to athena-bot-contact@proton.me. Include your Discord ID and the server concerned. Requests are handled within one month. Moderation records may be kept when they are needed to enforce an active sanction. You can also file a complaint with the data protection authority of your country.

## Changes

Any change to this policy is published on this page, with its update date.
