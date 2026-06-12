# Privacy Policy — Redd's Database

**Last updated: June 12, 2026**

This Privacy Policy describes how the Redd's Database Discord bot ("the Bot", "we", "our") collects, uses, and stores user data.

## What the Bot Does

Redd's Database is a Discord bot for an Animal Crossing: New Horizons fan community. It functions as a searchable item reference database with a personal basket feature: users search for items by name, save them to a personal list, and the bot returns a formatted reference string they can use elsewhere.

## Data We Collect

The Bot collects only the minimum data needed to function:

| Data | Purpose | Storage |
|---|---|---|
| Your Discord User ID | To associate your basket with you | Local JSON file on the bot host |
| Item names and reference codes you add to your basket | To remember your basket between sessions | Local JSON file (`user_baskets.json`) |
| Active private-thread IDs | To restore private browsing sessions after bot restarts | Local JSON file (`active_carts.json`) |
| Saved packs (NookPacks) you create | To let you reload pre-built item lists | Local JSON file (`nookpacks.json`) |
| The text of `!`-prefixed commands you send | To process your commands (e.g. `!find lily record player`) | Read in memory only — not stored |

## What We Do Not Collect

- We do not store the raw text of any message
- We do not collect Direct Messages
- We do not track your presence, status, or activity
- We do not collect personal information such as email, real name, or location
- We do not use any data for advertising, profiling, analytics, or machine learning / AI training
- We do not share, sell, or transfer your data to any third party

## How Long We Keep Data

- **Baskets**: kept until you clear them with `!clearorder` or until the bot operator wipes data
- **NookPacks**: kept until you delete them with `!mypack delete`
- **Active threads**: removed automatically after 3 hours of inactivity

## How to Delete Your Data

You can remove your data at any time:

- Run `!clearorder` to empty your basket
- Run `!mypack delete <name>` to delete a saved pack
- Contact a community staff member or the bot operator to request full removal of all your stored data

## Data Security

The Bot's data files are stored on a private, access-controlled server hosted by a third-party hosting provider. Access to the server is restricted to the bot operator only. The JSON files contain only Discord User IDs and the item names and reference codes users have added to their baskets — no personal information, no message content, no credentials, and no sensitive data of any kind.

## Privileged Intents

The Bot requests the **Message Content** privileged intent because all its commands use a `!` prefix (e.g. `!find`, `!order`, `!basket`). The Bot only processes messages starting with `!` in designated channels and ignores all other message content. The Bot does **not** request or use Guild Members or Guild Presences intents.

## Children's Privacy

The Bot operates within a Discord server. Use of Discord requires users to be 13 or older (or older where required by local law). The Bot is not directed at children under 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be announced in the community's Discord server.

## Contact

For questions about this Privacy Policy or to request full data removal:
- In-server: contact a community staff member in the community's Discord server
- Or use the in-bot commands `!clearorder` (clear basket) and `!mypack delete <name>` (delete a saved pack)
