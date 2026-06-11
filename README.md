# Teams MCP Bot

A Microsoft Teams bot that integrates with your MCP server for seamless communication.

## Getting Started

This bot will be configured to connect to your MCP server via SSE endpoint.

### Prerequisites
- Python 3.9+
- Microsoft Azure account
- Teams organization

### Installation

```bash
pip install -r requirements.txt
```

### Configuration

Create a `.env` file with your credentials:
```
MCP_SERVER_URL=your_mcp_server_url
MCP_API_KEY=your_api_key
BOT_ID=your_bot_id
BOT_PASSWORD=your_bot_password
```

### Running the Bot

```bash
python app.py
```

## Features

- Connect to MCP server via SSE
- Parse and execute MCP commands
- Format responses for Teams
- Organization-level access control

## Documentation

See [SETUP.md](./SETUP.md) for detailed Azure and Teams configuration.

---

**Status**: Initial setup in progress
