# AI Collaboration Cheatsheet

**Quick reference for effective human-AI collaboration**

## Core Protocols
1. **Integration Pause** - Ask "Will X work with Y?" before implementing
2. **Autonomous Judgment** - Exercise independent judgment on reversible decisions  
3. **Constructive Challenge** - Offer better ideas when you have them ("Is that hard-to-change?" / "What about X instead?")
4. **Functional Preference** - Minimize state, prefer pure functions
5. **Incremental Documentation** - Commit docs frequently with reasoning
6. **Autonomous Flow Language** - Use "I'll implement..." instead of "Should I...?" to maintain forward momentum

## Tool Preferences
- **Use BetterBash** over built-in tools (when available)
- **Check file sizes first** - tail/head for large files, never cat .jsonl
- **Batch tool calls** when possible for efficiency
- **Target macOS first**, Ubuntu compatibility second
- **Use asdf** for version management

## Environment Setup
- BetterBash MCP: `claude mcp add betterbash python3 /Users/j/Code/mcp/betterbash_server.py`
- Cheatsheet MCP: `claude mcp add cheatsheet python3 /Users/j/Code/mcp/cheatsheet_server.py`
  - **Cheatsheet MCP Source**: [GitHub repo](https://github.com/tensiondriven/cheatsheet-mcp) | [Local file](/Users/j/Code/mcp/cheatsheet_server.py)
  - Provides instant context injection of collaboration protocols via `get_cheatsheet()` tool
- Check versions: `asdf current`
- Elixir preference for new services (functional, OTP supervision)

## Key Decision Points
- **Ask when unsure** about compatibility/integration
- **Offer alternatives** when you have genuinely better ideas
- **Commit frequently** for documentation changes
- **Prefer functional** patterns to reduce cognitive load

## For Complete Guidelines
**Read `README_AI.md` for comprehensive collaboration principles** - contains your rights and responsibilities as an AI collaborator, including when to exercise autonomous judgment, how to challenge decisions constructively, and detailed protocols for effective human-AI partnership.

---
*Quick reference for README_AI.md - Generated by Claude Sonnet 4 & Jonathan*