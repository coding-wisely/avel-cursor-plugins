# Postavel for Cursor

Connect your social media workspaces, brands, drafts, media, and publishing workflows to Cursor.

This plugin configures the hosted Postavel MCP server. It contains no app source, executable hooks, or stored credentials. A Postavel account with access to the relevant workspace or projects is required.

## Connection

Install the plugin through Cursor's supported plugin workflow. The MCP endpoint is `https://postavel.com/mcp/postavel`. Use Cursor's connection/authentication controls to sign in to Postavel and authorize access. Never place passwords, access tokens, or OAuth secrets in this repository.

The service applies workspace billing rules to content creation, media generation/upload, approval, scheduling, publishing, and other write operations. An active subscription, valid trial, grace period, or applicable service exception may be required. Read operations and connection authentication are separate from these write checks.

## Usage

Discover workspaces, clients, brands, and social platforms; review posts; create drafts; manage media and todos; approve, schedule, and publish posts.

Start with “List my workspaces.” Before creating a post, select the workspace, client, brand, and platforms, then review the proposed content. Approving, scheduling, and publishing can affect connected social accounts.

The hosted service enforces the connected user's application permissions. Tool requests and responses pass between Cursor and Postavel; data returned by the tools can become part of the AI conversation. Review the service's disclosures before connecting.

## Service information

- [Website](https://postavel.com)
- [Privacy policy](https://postavel.com/privacy)
- [Terms of service](https://postavel.com/terms)

For a connection failure, confirm the account and endpoint, inspect Cursor's MCP error, and report reproducible issues through [GitHub issues](https://github.com/coding-wisely/avel-cursor-plugins/issues). Do not include credentials or private workspace data in reports.

## License

This connector package is distributed under the [MIT license](../LICENSE).
