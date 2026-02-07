# Safe Portfolio Guide

Use this checklist to avoid legal, ethical, or reputation issues when sharing your GitHub.

## 1) Be explicit about authorship

- Mark what you built vs what came from coursework/upstream.
- Keep attribution visible in `README.md` and `ATTRIBUTION.md`.

## 2) Do not leak private data

- Never commit passwords, API keys, access tokens, or personal IDs.
- Keep `.env` files local only.
- Run a quick secret scan before pushing.

## 3) Keep claims accurate

- Avoid saying "I built everything here" if repo contains external content.
- Say: "Built the ACA app and integrated it with course materials."

## 4) Recruiter-safe narrative

Use this one-liner:
"This repo combines my original Flask learning platform with clearly attributed deep-learning course materials used as learning context."

## 5) Pre-push checklist

- [ ] `git status` is clean
- [ ] README reflects mixed ownership accurately
- [ ] Attribution file is present
- [ ] No secrets in staged files
- [ ] Commit message is specific and truthful
