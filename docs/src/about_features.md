- Open source, [AGPL License](/LICENSE).
- Self hostable, easy to deploy.
  - Comes with [Docker](#docker), [Ansible](#ansible), [Kubernetes](#kubernetes).
- Clean, mobile-friendly interface.
  - Live-updating Comment threads.
  - Full vote scores `(+/-)` like old reddit.
  - Themes, including light, dark, and solarized.
  - Emojis with autocomplete support. Start typing `:`
  - User tagging using `@`, Community tagging using `#`.
  - Notifications, on comment replies and when you're tagged.
  - i18n / internationalization support.
  - RSS / Atom feeds for `All`, `Subscribed`, `Inbox`, `User`, and `Community`.
- Cross-posting support.
  - A *similar post search* when creating new posts. Great for question / answer communities.
- Moderation abilities.
  - Public Moderation Logs.
  - Both site admins, and community moderators, who can appoint other moderators.
  - Can lock, remove, and restore posts and comments.
  - Can ban and unban users from communities and the site.
  - Can transfer site and communities to others.
- Can fully erase your data, replacing all posts and comments.
- NSFW post / community support.
- High performance.
  - Server is written in rust.
  - Front end is `~80kB` gzipped.
  - Supports arm64 / Raspberry Pi.