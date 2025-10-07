# figma-gemini-cli-extension

Welcome to Figma's Gemini CLI Extension. Currently this repo contains the config to connect to the remote Figma MCP server.
The MCP Server brings important Figma context to AI agents generating code from Figma design files. With the server enabled, you can:

- *Generate code from selected frames*: Select a Figma frame and turn it into code. Great for product teams building new flows or iterating on app features.

- *Extract design context*: Pull in variables, components, and layout data directly into your IDE. This is especially useful for design systems and component-based workflows.

- *Keep your design system components consistent with Code Connect*: Boost output quality by reusing your actual components. Code Connect keeps your generated code consistent with your codebase.

To use this server, you'll need to sign in through Figma's OAuth authentication flow and have either a Dev or Full seat on a Pro, Organization, or Enterprise plan. Once set up, the remote server gives you a seamless way to access Figma data and integrate it with your tools.

### Installing Figma's Remote MCP config

```bash
git clone https://github.com/figma/figma-gemini-cli-extension.git

# If you don't have this directory
mkdir ~/.gemini/extensions/

# To copy gemini-extension.json
cp -R figma-gemini-cli-extension/figma ~/.gemini/extensions/

```

### Using Figma's Remote MCP

1. Run `gemini`
2. Run `/mcp auth figma` inside gemini

Once there you can ask Gemini to implement Figma designs by sharing links to the files.

### Figma Remote MCP Resources

- https://developers.figma.com/docs/figma-mcp-server/remote-server-installation/
