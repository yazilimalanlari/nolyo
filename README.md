<div align="center">

# nolyo

### A permanent home for your work with AI

**Chat is fleeting. Your work shouldn't be.**

Connect Claude — or any MCP client — and the markdown you create together
lands somewhere you own: clean documents you can edit, organize, and export.
No more good ideas buried in a 40-message thread.

[Website](https://nolyo.net) · [Docs](https://docs.nolyo.net) · [Pricing](https://nolyo.net/pricing) · [Get started — free](https://app.nolyo.net/signup)

</div>

---

## What is nolyo?

nolyo is a hosted, multi-user **MCP server** that gives your AI a real workspace
instead of a disposable chat. You connect over a single endpoint, and everything
you and your AI write together becomes plain markdown documents you fully own —
editable in the UI, readable by your AI next session, and exportable any time.

It works with **Claude Code, Claude Desktop, and any MCP-compatible client** over
Streamable HTTP, with either a Bearer key or OAuth.

## Why it's different

- **One MCP endpoint** — plug in over Streamable HTTP. Bearer key or OAuth, both work.
- **Markdown, not black boxes** — every document is plain markdown you can read, edit, and own. Headings, lists, checkboxes — rendered cleanly, yours to change.
- **Round-trip with your AI** — Claude writes a document, you refine it in the editor, and it reads its own work back next session. Living docs, not throwaway output.

## Use it as

- **A permanent home** for everything you make with AI — the same documents from any device, any client.
- **An editable draft space** — polish in the UI, and your AI picks the work back up where you left it.
- **One-click export** — markdown files or a full-workspace ZIP. Your work leaves whenever you want.
- **A shared workspace** — you, your AI, and your team touch the same living documents.

## 30-second setup

1. [Sign up](https://app.nolyo.net/signup) and create an API key.
2. Add the server to your client:

   ```bash
   claude mcp add --transport http nolyo https://app.nolyo.net/mcp \
     --header "Authorization: Bearer nly_…"
   ```

3. Ask Claude: *"save this as a note in nolyo."* Done.

Full setup and OAuth instructions: **[docs.nolyo.net](https://docs.nolyo.net)**

## Links

| | |
|---|---|
| Website | https://nolyo.net |
| Documentation | https://docs.nolyo.net |
| Connect Claude | https://app.nolyo.net/app/connect |
| Pricing | https://nolyo.net/pricing |
| MCP endpoint | `https://app.nolyo.net/mcp` |
| About MCP | https://modelcontextprotocol.io |

---

<div align="center">

© nolyo

</div>
