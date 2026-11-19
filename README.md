# Built Young Skills

Open-source [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for young builders.

Built Young teaches teenagers aged 10–18 to find a problem worth solving and ship a real product. These are the tools we use with our own students, released free for anyone to use.

---

## Skills

### `gtm-dashboard`

Sets up simple go-to-market tracking and reads the numbers each week: a tracked link and daily log per channel, a visits to sign-ups to active-users funnel, the biggest drop-off, one change per channel, a weekly update and an honest traction line for a pitch.

**How it works**

1. **Set up**: define a visit, a sign-up and an active user, say what one sign-up is (a person or an organisation), and start a daily log.
2. **Read the log**, list missing days, and never fill a gap.
3. **Do the arithmetic** in code, not in prose.
4. **Find the leak**: the biggest drop-off and one change per channel.
5. **Say how sure this is**, then a weekly update and a traction line.

Every number carries its unit, and small numbers are called early signals.

It is one stage of [gtm-pipeline](https://github.com/BuiltYoung/gtm-pipeline), the GTM super agent, and also works on its own.

---

## Installing

**Claude Code**

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/BuiltYoung/gtm-dashboard.git ~/.claude/skills/gtm-dashboard
```

Restart Claude Code. The skill loads automatically when your request matches it.

**Claude.ai**

Settings → Capabilities → Skills → Upload, then select the `gtm-dashboard` folder.

---

## Using it

Describe what you need. No command needed:

> *"Here's our log for the last three weeks. Which channel is working?"*

---

## Contributing

Issues and pull requests welcome. If you used this with students and something didn't land, we especially want to hear about it.

## Licence

MIT. See [LICENSE](LICENSE). Use it, fork it, teach with it.

---

**[Built Young](https://builtyoung.org)** · Build before everyone else.
