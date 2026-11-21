# Coding Wisely plugins for Cursor

Hosted MCP connections for [Postavel](postavel/README.md) and [Taskavel](taskavel/README.md). These plugins let Cursor work with your existing social media and project management accounts.

## Packages

- **Postavel**: workspaces, clients, brands, content drafts, media, and publishing workflows.
- **Taskavel**: projects, boards, tasks, comments, milestones, and time tracking.

The repository uses Cursor's [multi-plugin format](https://cursor.com/docs/reference/plugins), with `.cursor-plugin/marketplace.json` at the root and a separate manifest and MCP configuration in each product directory. Install the desired plugin using Cursor's supported plugin workflow and connect the relevant account. Read the product README for authentication and service requirements.

Marketplace listing is subject to Cursor review.

## Contents and data

These packages contain connection configuration, documentation, and logos. They use the hosted HTTPS MCP services and include no executable hooks or application server code. User credentials are never stored in this repository. Tool requests and responses are exchanged between Cursor and the connected service; returned account data may become part of the AI conversation. Existing account permissions and service plan limits apply.

[Postavel privacy](https://postavel.com/privacy) · [Postavel terms](https://postavel.com/terms) · [Taskavel privacy](https://taskavel.com/privacy) · [Taskavel terms](https://taskavel.com/terms)

## Support

Report reproducible connector issues in [GitHub issues](https://github.com/coding-wisely/avel-cursor-plugins/issues), excluding tokens, private workspace data, or other credentials.

## License

[MIT](LICENSE), copyright 2026 Coding Wisely. The hosted application services are governed by their own terms.
