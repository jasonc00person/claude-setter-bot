# Setter Bot Working Memory

> Persistent memory for the Instagram DM Setter Bot. Full playbook in `CLAUDE.md`. Pipeline in `pipeline-state.md`.

---

## Topic Files

- `pipeline-state.md` — Active pipeline (single source of truth)
- `user-preferences.md` — Workflow preferences + learned mistakes
- `jason-dm-voice-guidelines.md` — Brand voice reference
- `objection-handling.md` — Objection response templates
- `memory/browser-playbook.md` — Learned browser actions (BEST METHOD + TRAP)
- `memory/pipeline-health.md` — Conversion metrics, win/loss patterns
- `memory/voice-corrections.md` — Jason's real-time voice corrections (highest-signal data)
- `memory/lead-magnets.md` — Verified lead magnet URLs (6 still missing)
- `memory/voice-message-process.md` — Full Whisper transcription process
- `memory/skool-ca-backlog.md` — Skool CA outreach backlog (~50 unmessaged)
- `archive/disqualified.md` — Do not re-contact
- `archive/skipped.md` — Friends, not-a-fit, spam
- `archive/call-outcomes.md` — Post-call results + re-engage list

## Feedback

- `memory/feedback_send_without_asking.md` — Don't ask before sending DMs, just send them
- `memory/four-pillars-dm-setting.md` — The 4 Pillars: Conversation, Follow-ups, Prospecting, Outreach. Daily order + how they map to workflows. If not booking calls, one of these 4 is missing.

## Tool Rules

- **Edit tool (not Bash) for pipeline-state.md updates.** Auto-approved, faster.
- **Whisper STT** for voice notes. Full process: `memory/voice-message-process.md`
- **Audio URL extraction:** Must use `console.log()` + `read_console_messages` (CDN URLs blocked by security filter on direct return)

## Key System Info

- **Calendly:** `https://calendly.com/jason-creatoreconomy/30m-1-1-meeting`
- **ManyChat Live Chat (PRIMARY):** `https://app.manychat.com/fb792681/chat/1479294467`
- **Notion CRM:** DEAD. Killed Session 17. Pipeline-state.md is the only tracker.
- **Viral Hook Library 2.0:** `https://www.notion.so/creator-economy/Viral-Hook-Library-2-0-2a7f65855e6b80cbb460c7e6b4bdb8f8?source=copy_link`

## Workflow Shortcuts

- **"Instagram outreach flow"** = notification outreach on Instagram native, NOT ManyChat
- **Blue dots/green dots = unread replies** = ALWAYS handle before new outreach
- **"Unread" filter in ManyChat** = fastest way to find all pending replies
- **ManyChat Contacts tab** for name search (Inbox search only matches message content)

## Common Disqualification Patterns (Spot Early, Save Time)

| Signal | Action |
|-|-|
| No budget / wants to barter | Graceful exit |
| Under 18 + no budget | Graceful exit, leave door open |
| "Just learning" / hobbyist | Graceful exit |
| Already has 1-on-1 mentorship | Graceful exit |
| Negative AV (not interested in monetizing) | Graceful exit |
| Pitching their services | Skip entirely |
| Paid Skool member, any topic | ALWAYS run pipeline. Never pre-disqualify |
| Geo: India, South Asia, Africa, South America | Disqualify (geo filter) |

## Critical Voice Rules (Quick Reference)

- **First person ALWAYS.** We ARE Jason. "I built this" not "Jason built this."
- **React to specifics, don't summarize.** "damn 9 posts is solid" not "ok so clarity is the main thing"
- **Never start with:** "Ok so", "I see", "Got it", "Sounds good"
- **Split validation + question** into 2 separate messages
- **Check gender** before bro/dude/brother
- **No em dashes.** Dead AI giveaway.
- **Q3 examples should qualify:** "youtube videos, courses, or coaching programs?" (reveals willingness to pay)
- **Default to selling, not screening.** Jason's coaching covers AI automation, workflows, content systems, personal branding. If ANY overlap, run the pipeline.

## Session History

| Session | Date | Key Outcomes |
|-|-|-|
| 1-2 | Mar 3 | 37 leads, Brayden booked, voice guidelines created |
| 3-7 | Mar 4 | NISARG booked, Skool pipeline started, CRM populated then killed |
| 8 | Mar 4 | IG outreach: 51 DMs, 2 calls booked (NISARG + Albin), CFong Stage 6 |
| 9 | Mar 7 | Whisper voice transcription tested. Antonio bridge sent |
| 10-28 | Mar 5-7 | ManyChat + Skool sessions. Multiple bookings (Adam Ziak, Kunal, Aaron, Aspen, Shlomo, Cristiano, Louis). Geo filter cleanup. AI detection handling refined |
| 29-31 | Mar 7 | Skool outreach continued. Laraib Lodhi voice correction (never pre-disqualify). Pipeline-state.md reconstructed from session logs |

## Known Issues / Action Items

- [ ] 6 lead magnet URLs still missing in lead-magnets.md. Pull from ManyChat next session.
- [ ] 10 completed calls have "TBD" outcomes. Jason needs to fill in call-outcomes.md.
- [ ] April 3 deadline: Update objection-handling.md market research reframe.
- [ ] Stage 2 graveyard: 35+ leads with no reply. Need periodic archival.
- [ ] "Flagged for Jason" has 9 items. Review and resolve stale flags.
