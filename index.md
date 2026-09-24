# Privacy Policy — Joi AI Discord Bots

**Last updated: 24 September 2026**

This policy covers the Discord applications operated by Joi AI in the
"Joi AI" Discord server. It applies to Healper (support) and Bootler
(moderation and account safety). These bots are not publicly
installable and operate only in that one server.

## What we process

**Healper** reads the plain text of messages posted in our support
channels and support forum threads, so it can answer questions and so
staff can teach it new answers.

**Bootler** reads the plain text of messages, and images and videos
attached to them, across all channels in the server. This is necessary
to detect spam, scams, phishing and compromised accounts, which can
appear in any channel.

Neither bot reads message content in any other server. Neither bot
reads direct messages between members.

## Where it goes

Message text is transmitted to the Anthropic API for processing and the
result is returned to Discord. Anthropic processes this data under its
commercial terms as our service provider.

For Bootler, most messages never reach Anthropic: messages matching our
local spam patterns are handled without any external call, and messages
from bots, staff and trusted members are excluded before analysis.

We do not share message content with advertisers, data brokers, or any
other third party.

## What we keep

We do not store raw message text.

**Healper** stores question-and-answer entries in an internal knowledge
base. These are summaries written by the language model or by staff,
reviewed and explicitly approved by a staff member before being saved.
Each entry records the approving staff member's Discord ID and a link
back to the source message. The asking member's username and Discord ID
are not stored. Entries are kept until staff delete them.

**Bootler** stores spam patterns that a moderator has explicitly taught
it: a hash of the message text, extracted words and web domains,
perceptual hashes of any images or video, and a small thumbnail image.
The Discord ID of the moderator who taught the pattern is recorded; the
Discord ID of the person who posted the spam is not. Patterns are kept
until a moderator deletes them.

Moderation actions are logged to a private moderator-only channel within
the server, including a short excerpt of the offending message. These
logs remain in Discord under normal Discord message retention until
moderators clear them.

Token usage accounting is kept for 30 days and contains no message text.

## Your choices

To request deletion of data relating to you, or to ask what we hold,
contact support@joi.com or open a ticket in the server and tag @joi_ai.

Note that messages you post remain subject to Discord's own privacy
policy and retention independently of this one.

## Changes

We will update this page if our data handling changes, and update the
date above.
