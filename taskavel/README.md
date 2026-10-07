# Taskavel for Cursor

Connect your projects, tasks, boards, comments, milestones, and time tracking to Cursor.

This plugin configures the hosted Taskavel MCP server. It contains no app source, executable hooks, or stored credentials. A Taskavel account with access to the relevant workspace or projects is required.

## Connection

Install the plugin through Cursor's supported plugin workflow. The MCP endpoint is `https://taskavel.com/mcp/taskavel`. Use Cursor's connection/authentication controls to sign in to Taskavel and authorize access. Never place passwords, access tokens, or OAuth secrets in this repository.

OAuth sign-in must be verified with the current Cursor client before marketplace release. A completed Cursor compatibility test is not yet claimed.

## Usage

Discover projects, boards, and tasks; search assigned work and deadlines; manage tasks, comments, milestones, tags, and time tracking.

Start with “List my projects.” Select the project and inspect the relevant task before changing it. Task deletion is permanent and requires an already archived task and explicit confirmation.

The hosted service enforces the connected user's application permissions. Tool requests and responses pass between Cursor and Taskavel; data returned by the tools can become part of the AI conversation. Review the service's disclosures before connecting.

## Service information

- [Website](https://taskavel.com)
- [Privacy policy](https://taskavel.com/privacy)
- [Terms of service](https://taskavel.com/terms)

For a connection failure, confirm the account and endpoint, inspect Cursor's MCP error, and report reproducible issues through [GitHub issues](https://github.com/coding-wisely/avel-cursor-plugins/issues). Do not include credentials or private workspace data in reports.

## License

This connector package is distributed under the [MIT license](../LICENSE).
