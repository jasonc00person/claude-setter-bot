# Skool DM Setting Workflow

> For the full Skool workflow definition, priority order, and pipeline stages, see `CLAUDE.md`.
> This file covers Skool-specific **navigation and UI patterns** only.

## Navigation

- **Chat panel:** Click chat icon (speech bubble) in top-right nav bar
- **Filter chats:** Dropdown next to "Mark all as read" — toggle between "All" and "Unread"
- **Members page:** Members tab in nav, or `/creatoraccelerator/-/members`
- **Member chat:** Click "CHAT" button on member card, or click their name to open chat overlay
- **Close chat overlay:** Click X in top-right of chat window

## Member Info Available

Each member card shows:
- Bio/description
- Active status (e.g., "Active 4h ago")
- Join date
- Membership tier ($67/mo, $75/mo, or Free)
- Renewal timeline
- Join source (YouTube, email invite, direct)
- Location (city)

## Skool-Specific Notes

- Pipeline-state.md is the only tracker. Platform = "Skool"
- **Chat URLs:** Can't reliably extract. Search by name to find conversations.
- **Handle column:** Use Skool @username or "--" if not relevant
- **Spam risk warnings:** Often false positives for international members. Ignore unless clearly a bot.
- **CCU free group ICP density is very low** -- Pages 1-2 yielded only ~4 viable leads out of ~60. Most have empty bios, are non-English, or inactive. Expect ~5-10% hit rate vs ~30% in CA.
