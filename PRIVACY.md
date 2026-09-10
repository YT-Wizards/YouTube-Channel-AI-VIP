# Privacy policy — YouTube Channel AI VIP

_Last updated: 10 September 2026_

YouTube Channel AI VIP is a desktop application that runs entirely on your own computer. It is not a hosted service. There is no account, no server of ours, and nothing you do in the app is sent to us.

## What the app is

A YouTube analytics workspace for channel owners: it shows your channel's performance, tracks competitor channels you choose, analyses video hooks and titles, and generates cover images. You install it from this repository and run it locally.

## What Google data the app accesses, and why

When you connect a YouTube channel with Google sign-in, the app asks for these permissions:

- **YouTube Data API, read-only** (`youtube.readonly`) — to list your channel and its videos.
- **YouTube Analytics API, read-only** (`yt-analytics.readonly`) — to show views, watch time, audience and traffic reports for your own channel.
- **YouTube Analytics monetary data, read-only** (`yt-analytics-monetary.readonly`) — to show estimated revenue for your own channel, if it is monetised.

The app never writes to your channel, never uploads, edits or deletes anything on YouTube, and never reads data from channels you have not connected yourself.

## Where your data is stored

Everything the app collects — channel statistics, video lists, transcripts, generated images and the Google sign-in tokens themselves — is stored in a local database in your home folder (`~/.youtube-channel-ai-vip` on macOS, the equivalent folder on Windows). It stays on your computer. Deleting that folder removes all of it.

## What leaves your computer

Only what you explicitly configure:

- Requests to **Google's YouTube APIs**, using your own Google authorisation, to fetch the data above.
- Requests to the **AI providers you add keys for** (for example Anthropic, OpenAI, Google Gemini, kie.ai, fal.ai), carrying the text or images you ask them to analyse or generate. Each provider's own privacy policy applies to what you send it.
- Optional **Telegram** notifications, if you connect a bot of your own.

The developers of this app do not operate any server that receives your data, do not collect analytics about your use of the app, and have no access to your Google account, your API keys or your database.

## Revoking access

You can disconnect Google inside the app at any time (Integrations → Disconnect), which deletes the stored tokens. You can also revoke the app's access from your Google Account at https://myaccount.google.com/permissions.

## Contact

Questions about this policy: open an issue in this repository.
