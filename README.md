# OpenExtract AI: downloads

The built files of OpenExtract AI, the add-on that lets an AI app (Claude, ChatGPT) answer questions
about the iPhone backups on your computer. OpenExtract installs it for you from its Ask AI screen;
you don't need to download anything from here yourself.

- **The files are in [Releases](../../releases).** Each release has the add-on for Apple-silicon Macs
  (`mac-arm64`) and 64-bit Windows (`win-x64`) as Claude desktop extensions (`.mcpb`), and
  `index.json`, which lists them with their sizes and SHA-256 checksums. OpenExtract checks both
  before it installs anything.
- **This repository holds no source code.** OpenExtract AI is not open source. It reads backups
  through the engine of [OpenExtract](https://github.com/charleswest775/openextract), which is free
  and open source (MIT) and stays that way. The open-source licences of everything the add-on
  includes are in `THIRD-PARTY-NOTICES.txt` inside it.
- **It only reads.** It never changes a backup, and it sends nothing anywhere itself. What your AI
  app reads through it goes to that AI's company, as anything you paste into a chat does.

Made by Charles West · [openextract.app](https://www.openextract.app)
