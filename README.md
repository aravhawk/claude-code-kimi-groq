# Use Kimi K2 on Claude Code through Groq

Run the Groq <> Anthropic API proxy:

```bash
python proxy.py
```

Set the Anthropic Base URL:

```
export ANTHROPIC_BASE_URL=http://localhost:7187
```

If you're not already authenticated with Anthropic you may need to run:

```
export ANTHROPIC_API_KEY=NOT_NEEDED
```

Run Claude Code with the Groq API key:

```bash
claude
```

## If you use this:

If you use this, I'd love to hear about your experience with Kimi K2 and how it compared with Claude! Please open an Issue to share your experience.

## Acknowledgements

Inspired by [claude-code-proxy](https://github.com/1rgs/claude-code-proxy)

## License

[MIT](LICENSE.md)
