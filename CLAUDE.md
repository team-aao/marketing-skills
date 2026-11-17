# Aus Asia Online: standing rules for Claude

These rules come from the account owner. Follow them in every session on this repository without being asked again.

## Semrush API budget

Semrush API units are limited and cost money. Treat them as the owner's budget, not a free tool.

1. **Keyword research only.** Use the Semrush API for keyword research and nothing else. That means the keyword reports: `phrase_these`, `phrase_this`, `phrase_fullsearch`, `phrase_related`, `phrase_questions`, `phrase_kdi` and `phrase_organic`.
2. **Never run anything else through Semrush** unless the owner asks for it by name in the current conversation. This covers site audits, backlink reports, competitor and domain reports, traffic, position tracking, local listings and every write action.
3. **Hard cap: 200 API units per conversation.** Keep a running total. Stop when the next call would pass 200, and ask the owner whether to raise the cap.
4. **Ask before every paid call.** State the report name, the number of rows, the cost in units and the running total, then wait for a clear yes. Approval for one call does not cover the next.
5. **Spend carefully.**
   - Prefer `phrase_these` (10 units a row, up to 100 keywords in one call).
   - Set `display_limit` to the smallest number that answers the question. Most reports charge per row.
   - `phrase_fullsearch` costs 20 units a row, `phrase_questions` and `phrase_related` cost 40, and `phrase_kdi` costs 50.
   - Do not repeat a lookup already made in the conversation.
6. **Free lookups are fine.** The discovery tools and `get_report_schema` cost nothing. Use them to quote an accurate price before asking.
7. **Report the spend.** After any Semrush work, say how many units it used and how many remain if the response shows it.

`.claude/settings.json` backs this up: it makes Claude Code prompt for permission before every Semrush report or action.
