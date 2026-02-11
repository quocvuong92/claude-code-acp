# Changelog

## 0.16.1

- Update to @anthropic-ai/claude-agent-sdk@0.2.38
- Fix incorrect paths for session/list
- Fix available commands after loading a session
- Make loading session more permissive for finding events
- Fix overriding user-provided disallowedTools

## 0.16.0

- Update to @anthropic-ai/claude-agent-sdk@0.2.34
- Experimental support for session loading

## 0.15.0

- Update to @anthropic-ai/claude-agent-sdk@0.2.32 (adds support for Opus 4.6 and 1M context Opus)

## 0.14.0

- Update to @anthropic-ai/claude-agent-sdk@0.2.29
- Update to using the recommended `CLAUDE_CONFIG_DIR` environment variable for setting where config files are kept
- Support /context command
- Fix incorrect context type mapping for tool calls
- Fix glob matching for file permissions on Windows
- Support the `IS_SANDBOX` env var for supporting bypass permissions in root mode
- Fix missing notification for entering plan mode
- Experimental unstable support for listing sessions

## 0.13.2

- Update to @anthropic-ai/claude-agent-sdk@0.2.22
- Fix: return content from ACP write tool to help with issues with alternate providers.
- Fix: Enforce minimum 60-second timeout for Bash commands to prevent premature termination with certain model providers (e.g., Kiro/AWS CodeWhisperer)

## 0.13.1

- Update to @anthropic-ai/claude-agent-sdk@0.2.7
- Add TypeScript declaration files for library users
- Fixed error handling in custom ACP focused MCP tools

## 0.13.0

- Update to @anthropic-ai/claude-agent-sdk@0.2.6
- Update to @agentclientprotocol/sdk@0.13.0

## 0.12.0

- Add configurable MCP server support via settings
- Add `/mcp` command for managing MCP servers
- Add support for custom permissions
- Update to @anthropic-ai/claude-agent-sdk@0.2.5
- Update to @agentclientprotocol/sdk@0.12.0

## 0.11.0

- Notify when agent is paused
- Update to @agentclientprotocol/sdk@0.11.0

## 0.10.0

- Add support for `markdownCodeBlock` to exclude code blocks from LLM context
- Update to @agentclientprotocol/sdk@0.10.0

## 0.9.1

- Fix: return correct tool name in tool results
- Update to @anthropic-ai/claude-agent-sdk@0.2.4

## 0.9.0

- Add support for Claude Sonnet 4/2025
- Update to @agentclientprotocol/sdk@0.9.0

## 0.8.0

- Update to @agentclientprotocol/sdk@0.8.0

## 0.7.0

- Update to @agentclientprotocol/sdk@0.7.0

## 0.6.1

- Add support for custom tool use permissions

## 0.6.0

- Update to @agentclientprotocol/sdk@0.6.0
- Improve error messages

## 0.5.0

- Update to @agentclientprotocol/sdk@0.5.0

## 0.4.0

- Add support for complex message content types

## 0.3.0

- Add support for Bash tool

## 0.2.0

- Initial release with basic tools
