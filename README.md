# nis2-compliance-mcp

EU NIS2 Directive compliance tools u2014 scope check, gap analysis, incident timeline, penalty calculator, compliance checklist. Serves 36,000+ DACH entities subject to mandatory NIS2 compliance.

## Quick Start

```bash
git clone https://github.com/marilynceo/nis2-compliance-mcp.git
cd nis2-compliance-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://nis2-compliance.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/nis2-compliance-mcp

# Or connect directly via MCP client
# Endpoint: https://nis2-compliance.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
