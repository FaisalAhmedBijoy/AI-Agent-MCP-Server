# AI-Agent-MCP-Server
AI Agent MCP Server
 
## Run Project

- Initialize MCP Server
```bash
uv init first-mcp-server
```
- Go to the `first-mcp-server`
```bash
cd first-mcp-server
```
- Run this `LeaveManager` MCP server

```bash
uv run mcp install main.py
```

- Enable developer mode in Clade desktop
- Configure `Claude Desktop` with the `LeaveManager` 

## Ask Question in Claude 
```txt
Question: How many leave days are available for employee E001?
Answer: Employee E001 has 18 leave days remaining.
```

```txt
Question: For the same person i wanted to know about which date he was took leave?
Answer: 
Employee E001 took leave on the following dates:
December 25, 2024
January 1, 2025
```

```txt
Question: I want to apply for 21 February 2026 for employee E002 holiday?
Answer: Leave has been successfully applied for employee E002 on February 21, 2026. They now have 19 leave days remaining.
```

```txt
Question: What are the remaing leave of all empoyee?
Question: 
Based on the available employee records, here are the remaining leave days:

Employee E001: 18 leave days remaining
Employee E002: 19 leave days remaining

These are the employees currently in the system. If there are other employee IDs you'd like me to check, please let me know!
```