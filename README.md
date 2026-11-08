# DB Agent

Open-source AI tools for people who work with databases.

## Text-to-SQL: [db-agent](https://github.com/db-agent/db-agent)

Ask a question in plain English and get a SQL answer you can check. Schema-aware, with a SELECT-only safety layer,
per-answer token and warehouse cost, an MCP gateway for Claude Desktop, VS Code and Claude Code, and deployment
patterns for Databricks Apps, Postgres/MySQL and AWS.

- Presented at the AAAI-25 Workshop on Open-Source AI for Mainstream Use.
- [Live app](https://db-agent-pg42.onrender.com/) · [Webinar series](https://becloudready.com/webinar/db-agent?utm_source=github&utm_medium=referral&utm_content=org-profile)

## DBA toolkit: the `db-agent` command line (in private testing)

Read-only checks for the people who run databases, one command group per engine:

```
db-agent sqlserver ...     inventory a SQL Server and its SSRS reports before an upgrade or a move to Power BI
db-agent databricks health runtimes, legacy dependencies, DBU spend and spend waste in a workspace
```

PostgreSQL and MySQL are planned, not built. Not released yet; the repository is private until testing finishes.

## Links

[becloudready.com/tools/db-agent](https://becloudready.com/tools/db-agent)
