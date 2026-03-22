# 🛡️ DORAOracle

**DORA Compliance MCP Server** — 15 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-15-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/dora/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "doraoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/dora/mcp/"]
    }
  }
}
```

## Tools (15)

| Tool | Description |
|------|-------------|
| `cve_search` | Search CVEs by keyword, vendor or product. Returns CVSS scores, attack vectors,  |
| `cve_latest` | Latest critical CVEs — daily DORA ICT risk briefing. Filter by severity and bank |
| `kev_list` | CISA Known Exploited Vulnerabilities — actively exploited CVEs with patch deadli |
| `kev_check` | Check if a specific CVE is in CISA KEV (actively exploited in the wild). Returns |
| `cert_advisories` | CERT-Bund security advisories — authoritative DE source for ICT threats. DORA Ar |
| `breach_check` | HaveIBeenPwned breach database — check domain/company breach exposure. DORA Art. |
| `threat_actors` | Feodo Tracker: live C2 botnet servers (Emotet, QakBot, etc.). Actionable IP bloc |
| `incident_timeline` | Generate DORA-compliant ICT incident reporting timeline with exact deadlines. DO |
| `mitre_techniques` | MITRE ATT&CK techniques for DORA TLPT / TIBER-EU penetration testing. Maps to DO |
| `tlpt_scenarios` | TIBER-EU threat scenarios for DORA resilience testing planning. Banking-specific |
| `cloud_status` | Live status of AWS, GCP, Azure cloud providers. DORA Art. 28 third-party ICT ris |
| `provider_risk` | DORA Art. 28 ICT third-party risk assessment: CVE history, news, GLEIF registrat |
| `dora_news` | EBA/DORA regulatory news for banks. Topics: general, eba, incident, third_party, |
| `dora_calendar` | DORA compliance milestones and upcoming deadlines for financial institutions. Al |
| `health_check` | DORAOracle server status and all backend connectivity checks. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

DORAOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/dora/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
