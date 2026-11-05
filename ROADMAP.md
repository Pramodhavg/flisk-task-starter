## Vision
Flisk should be the quickest way to get any existing app running on your own machine with one command, whether you are on Mac, Linux or Windows, and whether you run it yourself or let your AI agent do it, while staying local only.

## Next 6 months
| Item | Who it is for | Impact | Confidence | Ease | ICE | Number to watch |
|------|---------------|--------|------------|------|-----|-----------------|
| Warn about WSL2 early, in `flisk import` and `flisk doctor` | First-time users on Windows | 8 | 8 | 8 | 512 | Windows users who hit the WSL2 error at `flisk up` (should drop to near 0) |
| One-command WSL2 setup (Ubuntu, Node and Tilt inside WSL2) | First-time users on Windows | 9 | 8 | 4 | 288 | % of Windows users who reach "Flisk is up" on day one |
| An AI agent imports and fixes a Compose app on its own via MCP | Teams using AI coding agents (Claude Code, Cursor) | 8 | 7 | 5 | 280 | % of agent-run imports that reach "Flisk is up" with no human fix |

## Not now
Native Windows containers without WSL2. The roadmap already commits to WSL2, a separate Windows path would take months to build and test for a two-person team, and the early warning plus one-command setup fix the same pain much sooner.