# sonarcube

## SonarQube MCP Server

This devcontainer includes a [SonarQube MCP server](https://docs.sonarsource.com/sonarqube-mcp-server/) that connects Ona to your SonarQube Cloud account.

### Required environment variables

Set these before starting the environment:

| Variable | Description |
|----------|-------------|
| `SONARQUBE_TOKEN` | Your SonarQube Cloud [user token](https://sonarcloud.io/account/security) |
| `SONARQUBE_ORG` | Your SonarQube Cloud [organization key](https://sonarcloud.io/account/organizations) |

Configure them as Ona secrets or environment variables so they're available inside the devcontainer. The MCP server will not start without both values set.