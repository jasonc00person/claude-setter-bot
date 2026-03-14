# Setter Bot Working Memory

> Persistent memory for the Instagram DM Setter Bot. Full playbook in `CLAUDE.md`. Pipeline in `pipeline-state.md`.

---

## Topic Files

- `setting-script.md` — **THE setting script.** Single source of truth: Stage 1-6 DM flow, voice rules, reaction phrasebook, tone spectrum, objection handling (DM + post-call), Hormozi principles, decision trees. Read before any DM session.
- `pipeline-state.md` — Active pipeline (single source of truth)
- `sales-call-script.md` — Phone call script (post-booking). 7-phase call + objection cheat sheet.
- `user-preferences.md` — Workflow preferences + learned mistakes
- `jason-dm-voice-guidelines.md` — *(Consolidated into setting-script.md)*
- `objection-handling.md` — *(Consolidated into setting-script.md)*
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
- `memory/feedback_work_autonomously.md` — Don't pause between workflows. Keep working until told to stop
- `memory/feedback_no_cd_in_git.md` — NEVER use cd in Bash commands. Use `git -C <path>` or absolute paths
- `memory/feedback_skool_url.md` — Skool DMs: navigate to skool.com/creatoraccelerator (not /chat). Use chat icon, not notifications bell
- `memory/four-pillars-dm-setting.md` — The 4 Workflows: Conversing, Following Up, Prospecting, Outreach. All 4 every day.

## Tool Rules

- **Edit tool (not Bash) for pipeline-state.md updates.** Auto-approved, faster.
- **Git commands: NEVER use cd prefix.** Just run `git status`, `git push`, etc. directly. cd + git triggers security prompt. See `memory/feedback_git_commands.md`.
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

## Quick Voice Reminders (Full rules in setting-script.md)

- **First person ALWAYS.** We ARE Jason.
- **React to specifics, don't summarize.**
- **Never start with:** "Ok so", "I see", "Got it", "Sounds good"
- **Check gender** before bro/dude/brother
- **No em dashes.** Dead AI giveaway.
- **Default to selling, not screening.** If ANY overlap with Jason's coaching, run the pipeline.
- **Paid Skool members:** ALWAYS run pipeline. Never pre-disqualify.
- **Bridge messages = SHORT.** One sentence max. Don't over-explain what happens on the call.
- **Emoji specificity matters.** 🤠 (cowboy, playful) not 😊 (generic, customer service). Jason's emoji picks have personality.
- **Scheduling friction: explain WHY you're busy.** Two messages: empathy + solution. "I can def fit you in on tuesday tho!"
- **Pitcher from other Skool groups:** "Saw you in [group], what are you working on?" = skip. They're running THEIR pipeline on us.
- **Warm re-engages override geo filter.** Prior relationship + exchanged value = run pipeline regardless of geography.

## Session History

| Session | Date | Key Outcomes |
|-|-|-|
| 1-2 | Mar 3 | 37 leads, Brayden booked, voice guidelines created |
| 3-7 | Mar 4 | NISARG booked, Skool pipeline started, CRM killed |
| 8 | Mar 4 | IG outreach: 51 DMs, 2 calls booked (NISARG + Albin), CFong Stage 6 |
| 9 | Mar 7 | Whisper voice transcription tested. Antonio bridge sent |
| 10-28 | Mar 5-7 | ManyChat + Skool. Multiple bookings. Geo filter cleanup. AI detection refined |
| 29-31 | Mar 7 | Skool outreach. Laraib voice correction. Pipeline reconstructed |
| 32-33 | Mar 8 | ManyChat + Skool. Mateja gender correction. Stage 2 Hormozi overhaul |
| 34 | Mar 9 | Skool. George Mobbs booked. Pablo + Saharat re-engaged. CA skip Stage 3 rule |
| 35-37 | Mar 9-10 | ManyChat. Melvin AI detection. Dame Sellz CA pitch. Albert Wang booked |
| 38-39 | Mar 10-11 | 12-call transcript analysis. Call outcomes backfilled. Sales call script built |
| 40-41 | Mar 12-13 | ManyChat. Penbera + Afsarchamp Calendly sent. Yohan Q2. Matt Pham re-engaged |
| 42-44 | Mar 13-14 | KB overhaul. Setting-script created. IG outreach (6 openers). Ayden $3K PIF. Albert $3K PIF |
| 45 | Mar 14 | Jay convo (Example 4). Skool DMs: Markus/Mateja/Victoria/Prince. Voice: scheduling empathy, emoji 🤠, pitcher detection, bridge shortness. KB audit + cleanup |

## Known Issues / Action Items

- [ ] 5 lead magnet URLs still missing in lead-magnets.md. Pull from ManyChat next session
- [ ] April 3 deadline: Update objection-handling.md + setting-script.md market research reframe
- [ ] George + Saharat + Gobb: Document results for April 3 launch (first 3 case studies)
- [ ] Build agency-specific track/proof for Pablo re-engagement
- [x] ~~Victoria requalify late March~~ Victoria agreed to call next week. Calendly sent Mar 14
- [x] ~~DRY cleanup~~ voice-guidelines.md + objection-handling.md consolidated into setting-script.md (Mar 14)
- [ ] 12+ completed calls in Hot Leads need outcomes filled + archival
