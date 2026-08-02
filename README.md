# Vayyar Imaging

Vayyar Imaging is an Israeli sensor company whose 4D imaging radar-on-chip technology senses, monitors, and images people and objects without cameras — powering Vayyar Care touchless fall detection, automotive in-cabin monitoring, smart buildings, robotics, and the consumer Walabot DIY in-wall imager. Its developer surface centers on the Walabot SDK documentation (api.walabot.com) and the Walabot storefront's agent-commerce endpoints (llms.txt, UCP profile, and a hosted MCP endpoint on walabot.com).

Backed by: battery-ventures

## Artifacts

- `apis.yml` — APIs.json profile for the company
- `well-known/` — probed `/.well-known/` surface: OIDC discovery, OAuth authorization-server metadata, and UCP merchant profile from walabot.com (saved verbatim)
- `llms/` — walabot.com `/llms.txt` agent instructions (saved verbatim)
- `mcp/` — the live UCP MCP endpoint at walabot.com/api/ucp/mcp
- `authentication/`, `scopes/` — customer-account OAuth 2.0 / OIDC profile from discovery documents
- `conformance/` — standards conformance grounded in fetched documents
- `packages/` — registry sweep result (no first-party packages published)
- `security/` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC posture
