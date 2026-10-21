<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stratosmedia-eu/.github/main/profile/stratos-color-dark.svg">
    <img src="https://raw.githubusercontent.com/stratosmedia-eu/.github/main/profile/stratos-color-light.svg" alt="Stratos" width="420">
  </picture>
</p>

<p align="center"><b>Your media world.</b></p>

Stratos is a **self-hosted media server and a family of players** for six kinds of media in one place:
films and TV, music, audiobooks, podcasts, ebooks and comics. It is built as a modern alternative to
Jellyfin and Plex that keeps what people like about them and fixes what annoys them.

Your library stays on your own hardware. **No ads, no tracking, no third-party analytics.** The server
contacts only the outside services its admin switches on.

<p align="center">
  <img src="https://raw.githubusercontent.com/stratosmedia-eu/.github/main/profile/mockup-tv-film-detail.webp" alt="Mockup of a film page in the Stratos TV player, Cinema skin" width="760">
  <br><sub><i>Design mockup of the default "Cinema" skin on a TV, not a screenshot of the finished app. Titles, people and artwork are made up.</i></sub>
</p>

## What we are building

| Part | What it is |
|------|-----------|
| **Stratos Media Server** | Headless server: scanning, metadata, transcoding, streaming, accounts and profiles, a documented REST API. .NET, SQLite or PostgreSQL. Also speaks enough of the Jellyfin API that existing Jellyfin apps can use it. |
| **Stratos Media Player** | The player for Android TV and Google TV, Fire TV, phones, tablets and desktop. |
| **Stratos TV for Samsung and LG** | A lightweight player for Samsung Tizen and LG webOS TVs. |
| **Stratos Server Manager** | The admin app for setup, libraries and accounts, which also plays your media like the player. On desktop, Android, Android TV and in the browser. |
| **Stratos Media Relay Server** | An optional, federated relay that helps apps reach a home server from outside, without carrying the media itself. Anyone can run one. |

## Repositories

- **Stratos**: the server, the apps and the plan, in one repository. It is private while the
  foundations are built and **opens to everyone at the pre-release**.
- **stratos-media-engine**: Stratos Media Engine, the media processing library behind the server
  (LGPL-2.1-or-later). Also private for now.

## Where we are

1. **Foundations: done.** Server identity, accounts, the database layer and the plugin host.
2. **Home use: in progress.** Scanning, metadata, playback and progress, first with existing Jellyfin
   apps, then with our own players on Android TV and Samsung TVs.
3. **Household:** profiles, resume and Continue Watching everywhere, NAS installs, a desktop player, and
   an API preview for client developers.
4. **Pre-release, repository opens:** hardware transcoding, music, network-share libraries, LG webOS
   and remote access.
5. **Version 1:** films, TV and music done well, Watch Together, and a store for plugins and skins.
   Audiobooks, podcasts, ebooks and comics follow after it.

## Open source

The server is **AGPL-3.0**, the apps **GPL-3.0**, and the SDK and plugin interfaces **MIT**, so anyone
can build on them. Contributions will be welcome once the repository opens, from people and from their
AI assistants alike, through pull requests with a DCO sign-off.

---

*"Stratos" and the Stratos logo are names of this project; please do not use them for other products.*
