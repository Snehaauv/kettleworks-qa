# Kettleworks – QA findings

Issues found while testing https://interview-qa-task.vercel.app/ as a customer and as a shop owner.

**40 tickets** – 31 bugs, 9 enhancements

| Severity | Bugs |
|---|---|
| Critical | 5 |
| High | 10 |
| Medium | 13 |
| Low | 3 |

Each ticket has steps to reproduce, expected and actual results, and screenshots.
Labels: `bug` / `enhancement`, `severity: …`, `area: …` (cart, checkout, catalogue, account, admin, security, accessibility, content).

## Start with these
- #1 Cart ignores quantity – charges for one unit
- #2 GST added on top of GST-inclusive prices
- #10 /admin open to anyone, even signed out
- #12 Reviews run HTML/JavaScript (stored XSS)
- #23 Orders visible to other users and after sign-out

## Tested on
Microsoft Edge on Windows, and a mobile phone browser.
