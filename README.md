This AI tool assists HR teams with leave management tasks. The codebase implements an MCP server that connects to a mock leave database and responds to MCP client queries.

Setup Instructions:

1.Install Claude Desktop
  Download and set up Claude Desktop on your machine.
2.Install uv package manager
  pip install uv

3.Initialize your project
  uv init my-first-mcp-server
4.Add MCP CLI to the project
  uv add "mcp[cli]"
5.Resolve possible type errors
  Some users may encounter typing issues. If so, upgrade typer to the latest version:
  pip install --upgrade typer
6.Implement the leave management server
  Write the server logic in main.py.
7.Install the server into Claude Desktop
  From the project directory: uv run mcp install main.py
8.Restart Claude Desktop
  Close any running Claude process from Task Manager. Restart Claude Desktop.
  Once restarted, the tools from your custom server will appear inside Claude Desktop. 🎉
