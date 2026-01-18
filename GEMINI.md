# Ralph Loop - Autonomous Development Loop

Ralph Loop enables iterative, self-referential development where you work on a task repeatedly until completion. Your work persists between iterations.

## State Management

Ralph Loop state is managed via the `ralph-state-server` MCP tools. The state directory defaults to `.ralph-state/` but can be customized via the `RALPH_STATE_DIR` environment variable.

**DO NOT** attempt to read or write the state files directly unless instructed otherwise. Always use the provided MCP tools to interact with the loop state.

## Commands

- `/ralph:start-loop <task>` - Initialize and start a new development loop.
- `/ralph:status` - Check the current progress and status of the loop.
- `/ralph:pause` - Pause the current loop.
- `/ralph:resume` - Resume a paused loop.
- `/ralph:complete` - Mark the loop as successfully completed.
- `/ralph:cancel` - Stop and cancel the current loop.
- `/ralph:history` - View the iteration history.
- `/ralph:checkpoint <name>` - Create a named checkpoint of the current state.
- `/ralph:restore <name>` - Restore the state from a named checkpoint.
- `/ralph:reset` - Clear all Ralph Loop state and data.
- `/ralph:help` - Show detailed help and usage instructions.

## Workflow

1. **Start**: Use `/ralph:start-loop "Your task description"` to begin.
2. **Iterate**: The loop will proceed in steps. After each meaningful change or sub-task completion, call the `ralph_increment_iteration` tool (or follow the command's specific instructions).
3. **Complete**: When the goal is met, call `ralph_complete_loop` and output `<done>COMPLETE</done>`.

## Important Rules

1. **Use Tools**: Always use MCP tools (e.g., `ralph_get_state`, `ralph_increment_iteration`) to manage state.
2. **Persistence**: Your files and environment changes persist between iterations.
3. **Checkpoints**: Use `ralph_create_checkpoint` before making risky or large-scale changes.
4. **Context**: If you lose track of what to do next, use `/ralph:status` or `ralph_get_state` to orient yourself.