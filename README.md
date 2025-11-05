# MCP Server and Client

This project is a hands-on implementation of the Model Context Protocol (MCP), featuring both MCP server and client applications developed in TypeScript.

## Features

- Full MCP protocol implementation with both server and client logic.
- Create, query, and manipulate user data using custom tools and resources.
- Integrated JSON data management and user prompt interactions.
- Inspector UI for real-time resource and tool inspection.

## Screenshots

Below are some key screenshots illustrating how the project works in practice:

  ![mcp.json](example-img-for-refer/mcp-json.jpg)
  Configuration setup for MCP servers and runtime options.
  
  ![MCP-Inspector](example-img-for-refer/mcp-inspector.jpg)
  Graphical interface for inspecting resources, tools, and prompts within the MCP server.
   
  ![Accessing tools](example-img-for-refer/tools.jpg)
  Steps to view and select available automation tools and actions.
  
  ![Prompts](example-img-for-refer/prompt.jpg)
  Demonstration of custom prompts and how they help generate user or test data.
  
  ![Using-Gemini](example-img-for-refer/gemini.jpg)
  Example of integrating Gemini and processing responses within the tool.

1. Clone this repository and install dependencies with:

   ```bash
   git clone <your-repo-url>
   cd mcp-server-and-client
   npm install
   ```

2. Build the TypeScript project:

   ```bash
   npm run build
   ```

3. Start the server and client as shown in the tutorial:

   ```bash
   npm run server:dev
   npm run client:dev
   ```

4. Use the MCP Inspector for advanced interactions and visualization.

## Usage

- Run server/client scripts and interact with the terminal or Inspector UI.
- Follow prompts to create and manage fake user data.
- Explore available MCP tools, resources, and prompts.

## Technologies Used

- TypeScript
- Node.js
- MCP (Model Context Protocol) SDK
- Inquirer.js for CLI prompts
- Zod for validation
