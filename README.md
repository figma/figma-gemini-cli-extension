# figma-gemini-cli-extension

Welcome to Figma's Gemini CLI Extension. Currently this repo contains the config to connect to Figma's Remote MCP Server.


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

Once there you can ask Gemini to implement Figma designs or Makes by sharing links to the files.

### Figma Remote MCP Resources

- https://developers.figma.com/docs/figma-mcp-server/remote-server-installation/
