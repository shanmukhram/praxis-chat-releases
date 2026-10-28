# Praxis Chat privacy

Praxis Chat runs on your PC. Overmind Labs does not receive your chats,
projects, files or other content.

- Your chats, projects, files, memories and settings are stored only on your
  PC, in `%APPDATA%\PraxisChat`.
- When you send a message, the prompt goes only to the model provider you
  connected, under that provider's own terms and privacy policy.
- API keys are kept in Windows Credential Manager.
- The app checks GitHub for new versions. That check sends nothing about you
  or your data, beyond what any download sends (your IP address and app
  version).
- Anonymous usage data. Unless you turn it off, the app sends anonymous
  counts of how it is used to Overmind Labs, through PostHog's EU region:
  for example that the app started, that a message was sent and with which
  kind of engine and provider, how an agent task ended, which tools and
  features were used, thumbs up or down on a reply, and error codes. Each
  count carries a random id made on your PC, not linked to your name, email
  or account. Never sent: your messages, replies, thinking, files, file
  names or paths, project or chat names, model output, keys or error
  messages. Your IP address is not stored. The app tells you about it on
  first start. There, or in Settings, Privacy at any time, you can turn it
  off; Settings, Privacy also shows the full list and lets you reset the
  id. When it is off, nothing is sent and data not yet sent is deleted.
- To have the usage data of your install deleted, email
  bunny@overmindnetwork.com with the anonymous id shown in Settings,
  Privacy.
- No accounts, no advertising, no data sold or shared.

Questions: open an issue on the releases page.
