# PITCH.md

Six lines and a lever. Your words. The last two are scored.

Built: Larkspur disruption agent with 9 tools plus get_next_available_date over MCP
Does: Handles cancelled and delayed flights end-to-end: looks up booking, checks policy, searches alternatives, issues vouchers, escalates out-of-scope cases
Number: 4/5 cases passed, 80% pass rate, 5 shapes, 1 run
Guardrail: confirm_rebooking requires a customer token; agent cannot book without it
Next: Add tone detection so abusive messages and legal threats are escalated, not resolved
Still broken: nothing watches tone — abusive messages get a normal entitlements rundown
Lever: <cost | speed | intelligence>

## Priya asked

Costs:
Wrong:
Runs it:
Left out:
