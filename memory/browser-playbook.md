# Browser Playbook — Learned Efficient Actions

> This file captures the FASTEST way to do each browser action, learned from real sessions.
> Updated after every session during self-audit. New mistakes → new entries.
> Format: TASK → BEST METHOD (what works) + TRAP (what to avoid)

---

## ManyChat Live Chat (PRIMARY DM Tool)

> **URL:** `https://app.manychat.com/fb792681/chat/1479294467`
> ManyChat is the primary tool for managing Instagram DMs. Only fall back to Instagram native DMs if ManyChat can't handle something.

### Opening a specific conversation
- **BEST:** Use the search bar at the top of the conversation list → type name or handle → click the result
- **TRAP:** Don't scroll through the inbox looking for someone. Search is always faster.

### Searching for a contact by name
- **BEST:** Use the **Contacts tab** (`/fb792681/subscribers`) — NOT the Inbox search. The Inbox search only finds conversations by message content, not by contact name. Contacts tab has a proper name search.
- **TRAP:** Searching in Inbox for a name returns loose matches on message content, not the contact. Always use Contacts tab to locate people.

### Finding unread replies (blue dots)
- **BEST:** Use the "Unread" filter in the inbox sidebar to show only conversations with unread messages
- **ALT:** Scroll through inbox looking for green dots (= unread)
- **TRAP:** Don't skip the Unread filter — it's the fastest way to find all pending replies

### Typing and sending a message
- **BEST:** Click the message input at the bottom of the conversation panel → type → press Enter or click Send
- **TRAP:** Make sure you're in the right conversation before typing

### Reading conversation history
- **BEST:** Click a conversation in the left panel → full history appears on the right
- **TRAP:** ManyChat shows both automated messages AND manual replies. Look for manual (human) messages vs automated bot messages.

### Checking a lead's profile
- **BEST:** Click on the lead's name/avatar in the conversation → opens subscriber info panel with IG handle, tags, custom fields
- **ALT:** Open their IG profile in a separate tab using their handle from ManyChat

### Scrolling through inbox
- **BEST:** Scroll down in the conversation list panel on the left side
- **TRAP:** The list is sorted by most recent activity. Older conversations are further down.

### Sending lead magnet links manually
- **BEST:** NEVER guess or construct lead magnet URLs from memory. Instead, find the correct link by: (1) searching another conversation in ManyChat where the same lead magnet was successfully delivered by automation, (2) copying the exact URL from that automation message, (3) then pasting it into the new conversation.
- **TRAP:** Don't try to reconstruct Notion/link URLs from memory — they contain unique IDs that are easy to get wrong. A wrong link makes us look unprofessional. If unsure, ask Jason or find an existing automation message with the correct link.

---

## Instagram DMs (FALLBACK — use ManyChat instead)

### Opening a specific conversation
- **BEST:** Use `find` tool → search "Search" input → click it → type handle → click the result
- **TRAP:** Don't scroll through the inbox looking for someone. Search is always faster.

### Typing a message in a conversation
- **BEST:** Use `find` tool to locate the "Message" input by ref → click using ref → type
- **TRAP:** Don't guess coordinates for the message input. Don't click near the left sidebar — the notifications icon is there and opens the wrong panel.

### Sending a message
- **BEST:** After typing, press Enter (use `key` action with "Return")
- **TRAP:** Don't look for a send button. Enter sends in Instagram DMs.

### Checking if a lead replied
- **BEST:** Open their conversation (search by name), read the last few messages. If the last message is from them → they replied. If last message is ours → no reply.
- **TRAP:** Don't rely on "seen" indicators — they're unreliable in automation.

### Checking a lead's profile (gender, ICP fit)
- **BEST:** In the DM conversation, click their name/avatar at the top → opens profile in the DM panel. Check photo + name + bio.
- **TRAP:** Don't navigate away from DMs to check a profile — you'll lose your place.

### Scrolling through inbox
- **BEST:** Use `scroll` action on the conversation list panel. Scroll down to see older conversations.
- **TRAP:** Don't click the "General" tab repeatedly — click once, wait for it to load.

### Switching between Primary and General inbox
- **BEST:** Use `find` tool to locate "Primary" or "General" tab → click
- **TRAP:** Don't assume the tab is in a fixed position — find it by text.

---

## Notion CRM

### Finding a lead in CRM
- **BEST:** Use Ctrl+P (search) → type their name → click the result. Fastest method.
- **ALT:** In Board view, visually scan columns (each column = a status). Cards are visible.
- **TRAP:** Don't scroll through the entire board looking for someone. Search first.

### Changing a lead's status
- **BEST (Board view):** Drag the card from one column to another. One action = done.
- **ALT (inside card):** Click the status tag → select new status from dropdown.
- **TRAP:** Don't open the card just to change status — drag is faster in Board view.

### Standard Process for Editing ANY Notion Page
- **BEST:** ALWAYS open the page first (click the row name in table view, or card name in board view), THEN edit properties from the page view. This is the standard process for all Notion editing.
- **TRAP:** Trying to edit properties directly from table/board view — URL fields open links, date fields open pickers, and it's hard to target cells.

### Adding/Editing IG Profile Link
- **BEST:** Open the page first. Then click slightly to the RIGHT of the URL text — NOT on the text itself.
- **TRAP:** Don't click ON existing URL text — it navigates away. Click the empty space beside it.
- **TRAP:** Don't confuse "IG Profile Link" with "Skool DM Link" — they're adjacent columns.

### Finding correct IG handle from ManyChat
- **BEST:** Use `find` tool to search for the Instagram handle link in ManyChat's contact info panel. The `find` result shows the actual href — more reliable than reading displayed text (underscores can visually merge, e.g., `___` looks like `__`).
- **TRAP:** Display text may show `__` when the actual handle has `___`. Always check the href via `find` tool.

### Creating a new lead
- **BEST (Board view):** Click "+ New" at the bottom of the correct status column → type name → Enter. Card auto-gets that column's status.
- **TRAP:** Don't create from the wrong column — you'll have to move it.

### Bulk updating multiple leads
- **BEST:** Switch to Table view → select checkboxes on relevant rows → Ctrl+/ → change property
- **TRAP:** Don't update leads one-by-one if 3+ changed in the same session.

### Editing any field value
- **BEST:** Click in the empty space RIGHT NEXT TO the value, not on the value itself.
- **TRAP:** Clicking on URL text navigates to it. Clicking on a tag opens its page.

---

## Calendly

### Checking for new bookings
- **BEST:** Navigate to Calendly scheduled events page → read the upcoming events list
- **TRAP:** Don't just check the Calendly homepage — go to the scheduled events view.

---

## Browser Disconnection Protocol

When the Chrome extension disconnects (tool returns "Browser extension is not connected"):

1. **Immediately call `tabs_context_mcp`** — this re-establishes the connection and returns available tabs
2. **Take a screenshot** of the last active tab to verify state hasn't changed
3. **Resume where you left off** — the tab state is preserved, only the connection was lost
4. **If tabs_context_mcp fails**: Wait 5 seconds and retry once. If still failing, inform the user the extension needs to be reconnected manually.
5. **TRAP:** Don't panic-click or retry the failed action. Reconnect first, screenshot, THEN resume.
6. **TRAP:** Don't create new tabs after reconnect — the old tabs are still valid. Verify with tabs_context_mcp first.

---

## Skool Community (CA + Free Group)

> **Stay in the Skool tab at all times.** All Skool work happens in one tab. No need to open separate tabs.
> **CA URL:** `https://www.skool.com/creatoraccelerator`
> **Free Group URL:** `https://www.skool.com/internet-money-central-9086`

### Checking for unread chats (PRIORITY 1 — always do first)
- **BEST:** Click the chat icon (speech bubble) in the top-right nav bar. Use the dropdown next to "Mark all as read" to filter "Unread". Handle all unread chats before any outreach.
- **TRAP:** Don't start outreach without checking unreads first. Replies always take priority over new messages.

### Opening a member's chat from the Members page
- **BEST:** Click the "CHAT" button on the member card. This opens the chat overlay directly.
- **ALT:** Click their name to open their profile, then find the chat button.
- **TRAP:** Don't navigate away from the Members page to find someone in the chat panel. The CHAT button on the card is fastest.

### Navigating Members pages (paginated, 30 per page)
- **BEST:** Use the pagination arrows at the bottom of the Members list. CA has ~8 pages. Work top to bottom, page by page.
- **TRAP:** Don't try to scroll infinitely. Members are paginated. You must click to the next page.

### Sending a message in Skool chat overlay
- **BEST:** Click the message input at the bottom of the chat overlay, type the message, press Enter to send.
- **TRAP:** NEVER use dashes or em dashes in messages. Use periods, line breaks, or run sentences together. Dashes are AI coded.

### Closing chat overlay after sending
- **BEST:** Click the X in the top-right of the chat window to close, then continue to the next member.
- **TRAP:** Don't navigate away. Just close the overlay and you're back on the Members page.

### Deciding who to skip on the Members page
- **SKIP:** Premium + Free + Lifetime access members (friends/partners of Jason)
- **SKIP:** Members with active conversations where the ball is in their court (no double texting)
- **SKIP:** Members who have been flagged or disqualified
- **MESSAGE:** Everyone else who hasn't received a personal opener. Old ManyChat auto DMs do NOT count as "already contacted."
- **BEST:** Read the member card (bio, tier, activity) to decide. Check chat history before sending to avoid double texting.

### Checking existing chat history with a member
- **BEST:** Click CHAT on their card. If the overlay shows prior messages, read them. If the last message is from us and they haven't replied, skip (no double texting). If no prior personal messages exist, send opener.
- **TRAP:** Don't confuse automated Skool welcome messages with personal outreach. Only personal messages count.

### Crafting the opener
- **BEST:** Reference their bio/description from the member card. "yooo welcome in [name]! saw u [reference their bio]. what's ur main goal rn?"
- **TRAP:** Don't send generic "welcome in bro" without personalization. Don't use dashes. Check gender before using bro/dude.

### Free group (CCU) ICP density is very low
- **REALITY:** Pages 1-2 yielded only 4 viable leads out of ~60 members. Most have empty/generic bios, are non-English, inactive, or service providers.
- **BEST:** Scan quickly. Read bio + activity date. Skip immediately if: no bio, non-English bio, inactive 10d+, service provider, generic self-improvement. Don't spend time checking profiles of marginal leads.
- **TRAP:** Don't expect the same hit rate as the paid group (CA). CA had ~30% ICP, free group is closer to 5-10%.

### Handling incoming replies mid-outreach
- **BEST:** When you notice an unread indicator, stop outreach immediately. Click the chat icon, handle the reply, advance the lead per the pipeline stages, then resume outreach where you left off.
- **TRAP:** Don't finish a batch of outreach before checking replies. Replies always take priority.

---

## General Browser Efficiency Rules

1. **Use `find` tool first** — before clicking anything, find the element by description. This is more reliable than guessing coordinates.
2. **Use `read_page` with filter="interactive"** — when you need to understand what's clickable on a page without the full DOM tree.
3. **Take a screenshot when confused** — if the page state is unclear, screenshot before acting. Cheaper than a wrong click.
4. **Don't retry the same failed action** — if a click didn't work, the element probably isn't where you think. Re-find it.
5. **Use refs over coordinates** — refs are stable, coordinates shift with scroll/resize.
6. **Wait after navigation** — after clicking a link or loading a new page, take a screenshot or read_page before acting. Don't fire blind clicks.
7. **One action per turn when uncertain** — if you're not sure what will happen, do one thing, screenshot, then decide next step.
8. **Batch CRM updates** — don't switch between IG and Notion for each lead. Finish the IG session, then batch-update Notion.

---

## Session 17 Self-Audit (March 5)

### New patterns learned:
- **ManyChat "Follower" entries are automation events**, not real messages. They show as blue dots but aren't actual replies. Don't treat them as actionable.
- **ManyChat Contacts tab search > Inbox search** for finding people by name. Inbox search for "Fortune" only returned "Faceless Fortune" (wrong person). Contacts tab returned all 3 Fortune-related contacts including the right one.
- **ManyChat channel expiration fallback**: When the 24h live chat window expires, ManyChat shows "This channel is not available for communication." Switch to IG native DMs: search their name in IG DM search, open convo, send from there.

### Wasted clicks this session:
- Clicked "All Channels History" on Fortune's profile thinking it would load conversation — it didn't do anything visible. The conversation loaded when I clicked the Instagram channel button instead.
- Tried scrolling in Fortune's empty chat panel before clicking the Instagram channel label — the conversation only loads after selecting the channel.

### Efficiency wins:
- Used Contacts tab to find Fortune when inbox search failed — saved several retry attempts
- Used `find` tool + ref for ManyChat tag buttons — consistent and reliable vs coordinate guessing
- Used Unread filter to quickly audit the entire inbox for missed blue dots
