# 🛡️ Protect yourself against repo confusion on GitHub

> Millions of malicious forks are flooding GitHub, stealing credentials & crypto.  
> *More by Dan Goodin [@Ars Technica](https://arstechnica.com/security/2024/02/github-besieged-by-millions-of-malicious-repositories-in-ongoing-attack)*

Check out the longread on [freeCodeCamp](https://www.freecodecamp.org/news/protect-github-repos-from-malicious-clones/)!

## Table of Contents

- [🛡️ Protect yourself against repo confusion on GitHub](#️-protect-yourself-against-repo-confusion-on-github)
  - [Table of Contents](#table-of-contents)
  - [What is a repository confusion attack?](#what-is-a-repository-confusion-attack)
  - [⚠ Basic mitigation strategies](#-basic-mitigation-strategies)
    - [Verify contributor profiles](#verify-contributor-profiles)
    - [Search for clones](#search-for-clones)
    - [Examine commit patterns](#examine-commit-patterns)
    - [Inspect commit history \& contents](#inspect-commit-history--contents)
    - [Compare file changes](#compare-file-changes)
  - [💊 Action time](#-action-time)
  - [Conclusion \& further reading](#conclusion--further-reading)

---

## What is a repository confusion attack?

A malicious actor:

1. Forks or clones a legit repo.
2. Injects obfuscated malware (password/crypto stealers).
3. Pushes & floods GitHub with look-alike clones impersonating legit ones.

## ⚠ Basic mitigation strategies

**Always verify any repository before cloning or installing.**

### Verify contributor profiles

- Watch for brand new or empty profiles with a single, hyperactive repo.
- In fake repos, the real contributor shows up below the impostor in the contributors list.

### Search for clones

- GitHub search by repo name → sort by *“recently updated.”*
- Malicious forks often sit at the top due to automated commits.

### Examine commit patterns

- Look for unusual volume/timing: clockwork or hyperactive commits.
- Human-driven projects tend to have irregular, story-driven commit graphs.

### Inspect commit history & contents

- Check if only first/last commits are visible —hiding the commit history is **suspicious**.
- Review diffs: automated loops (e.g., AI-generated README churn) signal bots.

### Compare file changes

1. Archive-or-official README: structured, clear guidance, useful.
2. Suspect README: emoji-spam, low-value AI fluff, repeating malicious download links.

## 💊 Action time

1. Gather evidence (screenshots, links, diffs).  
2. Notify original maintainers.  
3. Report the malicious clone to GitHub.  

## Conclusion & further reading

- Repo-confusion relies on mass-automation: quantity > quality.  
- As AI tools will perform better, distinguishing human vs. bot-made forks will get harder.

- See also:
  - AI poisoning & model security: [Ars Technica](https://arstechnica.com/information-technology/2024/01/ai-poisoning-could-turn-open-models-into-destructive-sleeper-agents-says-anthropic/)

**Stay informed. Stay secure.**
