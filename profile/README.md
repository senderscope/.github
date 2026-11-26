<p align="center"><img src="https://raw.githubusercontent.com/senderscope/.github/main/profile/logo.png" width="96" alt="Senderscope logo"></p>

# Reverse email lookup by Senderscope

Reverse email lookup, email finder and email verifier for B2B. Give Senderscope a work email and see who owns it: name, job title, seniority, company and LinkedIn. Give it a name and a company domain and it finds the work email. Email verification tells you whether an address is deliverable before you write to it.

## Connect with AI assistants

Our [MCP server](https://github.com/senderscope/mcp-server) connects Senderscope to compatible AI clients, with browser sign-in and explicit permission.

get_account reads your plan and credits. lookup_email returns the professional profile and deliverability behind a work email; find_email finds a work email from a name and company domain or a LinkedIn URL; verify_email checks deliverability, accept-all, SPF and DMARC. Each uses one credit only when it returns a result. list_lookups and get_lookup read your history for free.

## Links

- [Senderscope website](https://senderscope.app)
- [MCP source and setup](https://github.com/senderscope/mcp-server)
- [Desktop downloads](https://github.com/senderscope/mcp-server/releases)
- [Agent skill](https://github.com/senderscope/agent-skill) — install with `npx skills add senderscope/agent-skill`
