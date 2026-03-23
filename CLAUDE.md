# Outreach Dashboard

## Workflow

Changes are requested via Telegram. After implementing any change:

1. Review the change for correctness and quality
2. Commit it with a clear message (set git user if needed: `git config user.email "agent@podero.ai" && git config user.name "Sales Agent"`)
3. Push to main using the gh CLI: `git push "$(gh repo view --json url -q .url)" main`

Do this automatically — no need to ask for confirmation before committing and pushing.
