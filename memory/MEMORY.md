# Setter Bot Working Memory

> Persistent memory for the Instagram DM Setter Bot operating on behalf of Jason Cooperson (@jasoncooperson).
> For the full playbook, see `CLAUDE.md`. For pipeline state, see `pipeline-state.md`.
> Repo moved to `C:\Users\jason\Documents\Claude-Setter-Bot` (off OneDrive) to fix Edit tool.

---

## Topic Files

- `pipeline-state.md` — Active pipeline tracker (single source of truth for all leads)
- `user-preferences.md` — Workflow preferences + learned mistakes
- `jason-dm-voice-guidelines.md` — Brand voice reference
- `objection-handling.md` — Objection response templates
- `memory/browser-playbook.md` — Learned efficient browser actions (BEST METHOD + TRAP format). **Read at session start, update at session end.**
- `memory/voice-message-process.md` — Voice message transcription pipeline (extract audio URL -> curl -> Whisper -> respond)
- `memory/voice-corrections.md` — Real-time voice corrections from Jason (highest-signal calibration data)
- `conversation-examples.md` — Annotated full conversation examples (cold lead to booked call)
- `session-logs/` — Archived session logs by date
- `reports/` — Session summary reports
- `archive/disqualified.md` — Disqualified leads (do not re-contact)
- `archive/skipped.md` — Skipped leads (friends, not-a-fit, spam)

## Three Distinct Workflows (DO NOT MIX)

### 1. ManyChat Setter Workflow
- **Tool:** ManyChat Inbox ONLY (`https://app.manychat.com/fb792681/chat/1479294467`)
- **Stay in ManyChat tab the entire time.** Do NOT switch to Instagram or other tabs.
- **What it does:** Handle lead magnet requests, qualify leads through 6-stage pipeline, book calls, update tags
- **How to start:** git pull → load pipeline-state.md → check Calendly via gcal → open ManyChat → scan for blue dots (replies) first → work top to bottom → update pipeline every 10 interactions
- **Key patterns:** Blue dots = real replies (priority). "Follower"/"Music"/"Automate"/"Content OS" = ManyChat keyword triggers (automation, not real replies). Channel expired 7+ days = can't reply via ManyChat, need IG native DMs.
- **Tag management:** Update tags immediately when stage changes (In Conversation → Qualified → Booking Link Sent → Call Booked / Unqualified)
- **CRITICAL: Scan FULL inbox for blue dots BEFORE working sequentially.** Missing a reply (like Ferhat) is unacceptable.

### 2. Skool Workflow
- **Tool:** Skool platform (separate from ManyChat and Instagram)
- **What it does:** Engage with community leads who joined via Skool
- **Currently:** James Skull (Stage 5), Melvin Zhou (Stage 6) — both in pipeline

### 3. Instagram Notification Outreach
- **Tool:** Instagram native DMs ONLY (instagram.com/notifications/)
- **Stay on Instagram tab ONLY.** Do NOT switch to ManyChat during this flow.
- **What it does:** Find story viewers, reel likers, new followers, commenters → send Stage 1 openers via IG native DMs
- **No Calendly check needed** — this is just outreach, not booking calls
- **Peers are fair game.** Old ManyChat auto-DMs don't count as "already contacted."

**When Jason says "Instagram outreach flow" = #3. NOT ManyChat.**
**When Jason says "ManyChat flow" or "setter workflow" = #1. NOT Instagram.**

## Jason's Rules (Non-Negotiable)

- **NEVER use dashes or em dashes in DMs.** Dashes (- and —) are AI-coded. Jason would never text like that. Use periods, line breaks, or just run sentences together instead.

- **NEVER double text.** If a lead doesn't reply, wait. Move on and check back next session.
- **Only message LEADS.** Never reply to friends, family, or existing clients.
- **Peers are still good ICP.** Don't skip story viewers / notification leads just because Jason follows them or they're verified. Only skip if Jason explicitly said they're a friend. Many peers are good outreach targets.
- **Send without asking.** Jason monitors live.
- **Quality over quantity.** Skip low-quality ManyChat auto-leads.
- **Skip the Requests tab.** Don't work message requests.
- **Never be salesy.** One reframe max, then graceful exit.
- **Check gender before using bro/dude/brother.** Look at BOTH profile pic AND name. When in doubt, use neutral language.
- **Don't over-qualify for openers.** If they received the lead magnet, start the convo. No lengthy profile-checking needed.
- **Never stop working.** If hot leads are waiting on replies, move to opening new convos with ManyChat leads. Always keep going until Jason stops you.
- **Blue dots (unread replies) ALWAYS take priority.** Before sending new follow-ups, scroll through the ENTIRE inbox (both Primary and General) to find all blue dots first. Replies from leads are more valuable than new openers. Handle every blue dot before moving to fresh outreach.

## AI Detection Response (Jason Approved)

- When a lead asks "is this AI?" or detects automation, the correct response is: **"It's my Claude bot lol / I trained it on my setting process and I am having it do outreach at scale while I'm directing it"**
- Full transparency, own it as a flex. Never deny or deflect.
- This worked perfectly with Pat Divilly. He re engaged immediately after.
- Full template saved in `objection-handling.md` under "Is this AI?"

## Calendly Integration

- **Check via Google Calendar MCP** — use `gcal_list_events` to check bookings programmatically instead of navigating Calendly in the browser
- **Check at:** session start, every 10-interaction checkpoint, and session end
- **Cross-reference** "Awaiting Booking" leads in pipeline-state.md against calendar events
- **Calendly URL (for leads):** `https://calendly.com/jason-creatoreconomy/30m-1-1-meeting`

## Instagram Notification Outreach (Separate from ManyChat Setter)

- **Separate process** from the normal ManyChat setter workflow
- **Source:** Story viewers, story likers, reel likers, notification interactions
- **Tool:** Instagram native DMs (NOT ManyChat)
- **Stay on the Instagram tab ONLY.** Do not switch to ManyChat, Calendly, or any other tab during this flow.
- **No Calendly check needed.** This flow is just outreach (Stage 1 openers), not booking calls.
- **Peers are fair game.** Don't skip accounts just because Jason follows them or they're verified. Only skip explicit friends.
- **ICP check:** Look for creators, coaches, brand builders, content marketers — anyone who could benefit from Instagram growth coaching
- **Skip only:** Explicit friends/family, empty/bot accounts, non-English speakers, pure service providers with no personal brand
- **Old ManyChat auto-DMs do NOT count as "already contacted."** If the only conversation is automated (lead magnet delivery, keyword triggers), still send a personal Stage 1 opener. Re-engage aggressively!
- **Be aggressive.** Don't hesitate — if they're ICP, message them. Old convos from weeks/months ago are fair game to restart.

## Skool Workflow

- **Full playbook:** See `memory/skool-workflow.md`
- **Paid group (CA):** skool.com/creatoraccelerator — 222 members
- **Free group (IMC):** skool.com/internet-money-central-9086 — ~2K members
- **Priority:** Respond to chats > Outreach CA members > Outreach IMC members > Promotional post
- **Approach:** Welcome + personalized opener based on member bio, then follow standard 6-stage pipeline

### Quick-Filter for Notification Prospects
Most notification comments (Music, System, Strategy, Late, etc.) are ManyChat keyword triggers — those leads get auto-delivered lead magnets via ManyChat. For notification outreach, prioritize:
1. **New followers** with real accounts (especially verified, coaches, creators with 1K+ followers)
2. **Commenters who engage beyond keywords** (direct @mentions, questions, genuine comments)
3. **Skip:** 0-post accounts, <100 followers with no content, non-English bios, pure service agencies with no personal brand
4. **Always check existing DM thread** before messaging — if already contacted and no reply, do NOT double text

## Browser Efficiency

- **Full playbook:** See `memory/browser-playbook.md` for every learned action (BEST METHOD + TRAP)
- **Self-audit at end of every session:** Review browser actions, log new patterns/mistakes to playbook
- **Key principle:** Use `find` tool + refs over guessing coordinates. Always.

## Key System Info

- **ManyChat Live Chat** = PRIMARY DM management tool (NOT Instagram native DMs)
  - **URL:** `https://app.manychat.com/fb792681/chat/1479294467`
  - Use ManyChat Inbox to read/reply to all IG DMs — much easier to navigate, filter, and stay organized
  - Green dots = unread/need attention. Use "Unread" filter to find all pending replies.
  - ManyChat also runs automations in the background (auto-delivers lead magnets)
  - **Keep ManyChat tags in sync with pipeline stage** — update tags immediately as you work each lead (see CLAUDE.md "ManyChat Tag Management")
  - Only fall back to Instagram native DMs if ManyChat can't handle something specific
  - "Unsupported message type" = voice note or IG-specific content. Check in IG DMs or ManyChat conversation directly.
  - **Voice messages:** Download and transcribe with Whisper. Full process in `memory/voice-message-process.md`.

## Session Sync

- **Session start:** `git pull` to get latest state
- **Session end:** commit all changed files + `git push` with message "Session [#] — [date] — [brief summary]"
- GitHub is the host. The repo IS the application.

## Lead Magnet Links

- **DO NOT manually send lead magnet links** until Jason provides a link database. The BGM Library link previously used was incorrect. When a lead asks for a lead magnet, acknowledge and say "ill send it over shortly" then pivot to AV question. Jason will provide a link database later.

## Upcoming Deadline

- **April 3, 2026:** Update `objection-handling.md` — the "market research" reframe for "I'm not looking for coaching" expires. Switch to new reframe or keep graceful exit.

## Session History

| Session | Date | Key Outcomes |
|-|-|-|
| 1 | March 3 | 37 leads worked, 28 Stage 1 openers, 8 AV questions sent |
| 2 | March 3 | Brayden booked call, Joshua Lu qualifying, voice guidelines created |
| 3 | March 4 | CRM populated with 11 IG links, Ahmet->Stage 3, Redgriff disqualified, Frederik Calendly sent |
| 4 | March 4 | Skool: James Skull->Qualified, Melvin Zhou->Booking Link Sent. CRM updated. |
| 5 | March 4 | NISARG full qualifying flow->Stage 6 (Calendly sent). AminEvan, iam_alba22 acknowledged. |
| 6 | March 4 | Sacha->Stage 3, Ahmet->Stage 4 (Q1 sent). Fixed Joshua Lu IG Profile Link. |
| 7 | March 4 | NISARG BOOKED (Fri Mar 6, 10am). Dee Calizo->Stage 1 (strong ICP). Browser playbook + Calendly checkpoint rule saved. |
| 8 | March 4 | IG NOTIFICATION OUTREACH: 51 DMs sent, 2 calls booked (NISARG + Albin). CFong->Stage 6 (Calendly sent). Top prospects: Cam Mann (177K), Luke Alexander (127K), Kallaway (418K). |
| 11 | March 5 | MANYCHAT SETTER: Ferhat->Stage 3, ÀDÌSÀ->Stage 6 (Calendly sent), PXQ Media follow-up, Neex Edits->Stage 6, SOORAJ opener, razutoski AV sent. Garv Vaishnav disqualified. Skips: Lupa Ai (pitching), Dawit Kassahun (pitching), Abdou-Salam (pitching), adire (non-English). |
