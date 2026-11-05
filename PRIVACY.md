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
- Developer tools (from version 0.2.2). When an agent task needs a
  missing tool such as Node.js, Python or Git, the app installs it with
  winget, or downloads it from the tool's official site (for example
  nodejs.org, go.dev or Microsoft's .NET download site) and checks it
  against the published checksum. These downloads send nothing about you or
  your data, beyond what any download sends.
- Programs you add (from version 0.3.0). Hooks and MCP servers that you,
  or a project folder you trust, set up run on your PC as their own
  programs. Praxis Chat gives them only the step they handle; what they
  send elsewhere is up to them, so add only ones you trust. A project's
  MCP server asks you before its first start.
- Web pages (from version 0.4.0). While "Web search and page reading" is
  on in Settings (it is on by default), the agent can read public web pages
  and watch public WebSocket feeds from your PC, as a browser would: the
  site sees your IP address and the address asked for. Local and private
  addresses are refused. With the switch off, nothing is fetched.
- A second opinion (from version 0.4.0). If you turn on "Second opinion
  from another model" in Settings, Model routing (it is off by default), a
  routed change may be checked by another model you connected, possibly at
  another provider. That provider then receives the request, the change and
  the test output.
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
