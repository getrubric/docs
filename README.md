# Rubric docs

Documentation for Rubric — runtime governance for AI agents. Built with [Mintlify](https://mintlify.com).

Live at: https://docs.rubric-app.com

## Local preview

```bash
npm i -g mint
mint dev
```

Opens at `http://localhost:3000`.

## Structure

```
.
├── docs.json                  # Mintlify config (nav, theme, logo)
├── index.mdx                  # Landing page
├── guides/
│   ├── quickstart.mdx
│   └── installation.mdx
├── concepts/                  # Architecture, identities, policies, evaluation, traces, dlp
├── adapters/                  # MCP, Claude Agent, LangChain
├── dashboard/                 # Per-page documentation
├── sdk-python/                # Python SDK reference
└── logo/                      # Light + dark wordmark SVGs
```

## Contributing

Edit any `.mdx` file, run `mint dev` to preview, push to `main`. Mintlify's GitHub app auto-deploys.

## License

MIT — see `LICENSE`.
