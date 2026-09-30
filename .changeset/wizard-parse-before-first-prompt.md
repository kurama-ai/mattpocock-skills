---
"mattpocock-skills": patch
---

wizard: run the authored stages inside one function, called on the template's last line, so bash parses the whole script before the first prompt. Bash reads a script incrementally and a wizard waits at prompts for minutes; when the file changed during a run (the agent fixing a hint, say) the running shell resumed at a stale byte offset and died with a spurious syntax error.
