# Migration Guide - Proactivity

## v1.0.1 Architecture Update

This update keeps the same home folder, `~/.openclaw/proactivity/`, and preserves existing files.
The new version adds active-state files for recovery and follow-through.

### Before

- `~/.openclaw/proactivity/memory.md`
- `~/.openclaw/proactivity/domains/`
- `~/.openclaw/proactivity/patterns.md`
- `~/.openclaw/proactivity/log.md`

### After

- `~/.openclaw/proactivity/memory.md`
- `~/.openclaw/proactivity/session-state.md`
- `~/.openclaw/proactivity/heartbeat.md`
- `~/.openclaw/proactivity/patterns.md`
- `~/.openclaw/proactivity/log.md`
- `~/.openclaw/proactivity/domains/`
- `~/.openclaw/proactivity/memory/working-buffer.md`

## Safe Migration

1. Create the new files without deleting the old ones:
```bash
mkdir -p ~/.openclaw/proactivity/memory
touch ~/.openclaw/proactivity/session-state.md
touch ~/.openclaw/proactivity/heartbeat.md
touch ~/.openclaw/proactivity/memory/working-buffer.md
```

2. Keep `memory.md`, `patterns.md`, and `log.md` exactly as they are.

3. If old proactive rules live in free-form notes, copy them into the new sections in `memory.md`.

4. Start writing only live task state to session state and working buffer.

5. Do not delete or rename any legacy file unless the user explicitly asks for cleanup later.
