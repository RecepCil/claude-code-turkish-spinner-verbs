# Claude Code Turkish Spinner Verbs

A set of Turkish, developer-humor spinner verbs for [Claude Code](https://claude.com/claude-code).
They replace the default "Thinking…" style words shown while Claude works.

## Usage

Copy the `spinnerVerbs` block from [`spinner-verbs.json`](./spinner-verbs.json) into your
`~/.claude/settings.json` (all projects) or `.claude/settings.json` (one project):

```json
{
  "spinnerVerbs": {
    "mode": "replace",
    "verbs": ["..."]
  }
}
```

Use `"mode": "append"` instead to keep the default verbs and add these.

## Contributing

Open a PR adding a verb to `spinner-verbs.json`. Keep each one a short Turkish phrase that reads after "Claude …".
