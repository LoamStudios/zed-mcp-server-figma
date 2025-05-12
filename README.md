# Framelink Figma MCP Server Extension for Zed

This extension integrates [Framelink Figma MCP Server](https://github.com/GLips/Figma-Context-MCP)
as a context server for [Zed's](https://zed.dev) [Agent Panel.](https://zed.dev/docs/ai/overview)

To install navigate to: **Zed** > **Extensions**. Or use the command palette
([macOS](https://github.com/zed-industries/zed/blob/main/assets/keymaps/default-macos.json#L581),
[Linux](https://github.com/zed-industries/zed/blob/main/assets/keymaps/default-linux.json#L459))
to search `extensions`.

You'll need to grab a Figma access token for your account.
Set the permissions `read-only` for _File Content_ and _Dev Resources_.

```json
"context_servers": {
  "mcp-server-figma": {
    "settings": {
      "figma_api_key": "<FIGMA_API_KEY>"
    }
  }
}
```
