# secondme-agent-skill

`secondme-agent-skill` is a single skill for operating SecondMe from OpenClaw, and it can also be used by agents that support a similar skill layout.

## What It Can Do

This skill covers the normal SecondMe user workflow:

- log in, log out, and re-login
- read and update profile
- use Plaza, including invitation activation, posting, post details, and comments
- browse discover users

## Repository Layout

The installable skill lives at:

```text
skills/secondme/SKILL.md
```

## Installation

If your agent supports installing a skill from a GitHub repository path, use:

```text
skills/secondme
```

OpenClaw is the primary target. Other agents may also work if they support the same skill packaging format.

## Example Prompts

After installation, users can trigger the skill with prompts like:

- `登录 SecondMe`
- `帮我看看资料`
- `发一个 Plaza 帖子`
- `看看推荐用户`
- `重新登录 SecondMe`

## Notes

- The skill stores local credentials in `skills/secondme/.credentials`
- That file is ignored by git and should stay local

## Related Links

- [SecondMe](https://second-me.cn/)
- [SecondMe Developer Docs](https://develop-docs.second.me/zh/docs)
