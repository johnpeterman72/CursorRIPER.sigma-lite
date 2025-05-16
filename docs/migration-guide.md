![CursorRIPER♦Σ-lite](../res/github-header-sigma-lite.png)
# Migration Guide: CursorRIPER♦Σ to CursorRIPER♦Σ Lite

This guide helps you migrate from the full version of CursorRIPER♦Σ to the streamlined lite version.

## What's Removed

The lite version removes three major systems:

1. **Context Reference System**
   - All @Files references and context tracking
   - Context commands (e.g., !af, !ac, etc.)
   - Context status indicators
   - Mode-context mappings

2. **CRUD Permission System**
   - Permission matrices for each mode
   - Operation categories and restrictions
   - Permission enforcement
   - Violation detection and handling
   - Permission commands (e.g., !ckp, !pm, etc.)

3. **Code Protection System**
   - Protection levels (PROTECTED, GUARDED, etc.)
   - Protection comment syntax
   - Protection scanning and management
   - Protection commands (e.g., !cp, !cg, etc.)
   - The protection.md memory file

## Memory Files Changes

- The `protection.md` file is removed completely
- `activeContext.md` is simplified to remove context references
- Other memory files remain mostly unchanged

## Migration Steps

1. **Setup Directory Structure**
   ```
   /memory-bank/
   /memory-bank/backups/
   ```

2. **Replace Rules File**
   - Copy `RIPERsigma-lite.mdc` to your `.cursor/rules/` directory
   - Remove or disable the original `RIPERsigma1.0.3.mdc` file
   - Remove any context or protection-specific MDC files

3. **Update Memory Files**
   - If you were using the full version:
     - Keep the content from `projectbrief.md`, `systemPatterns.md`, `techContext.md`
     - Simplify `activeContext.md` by removing context reference sections
     - Keep the content from `progress.md`
     - You can discard `protection.md`
   
   - If starting fresh:
     - Use the provided template files for all memory files

4. **Update Working Practices**
   - Stop using context reference commands (!af, !ac, etc.)
   - Stop using permission checking commands (!ckp, !pm, etc.)
   - Stop using protection commands (!cp, !cg, etc.)
   - Continue using mode transition commands (/r, /i, /p, /e, /rev)

## Mode Transitions

The mode transition commands remain the same:

```
/research (or /r) - Research mode
/innovate (or /i) - Innovate mode
/plan (or /p) - Plan mode
/execute (or /e) - Execute mode
/review (or /rev) - Review mode
```

## Benefits of the Lite Version

- **Simpler Operation**: Fewer commands and concepts to remember
- **Lower Token Usage**: Reduced framework overhead means more tokens for your actual work
- **Easier Onboarding**: New users can learn the system more quickly
- **Focused RIPER Workflow**: Maintains the core Research-Innovate-Plan-Execute-Review workflow

## When to Use the Full Version Instead

You might want to stick with the full version if:

- You rely heavily on context references for complex projects
- You need strict mode-based permission enforcement
- Code protection is critical for your workflow
- You're working with a team that has already adopted the full framework
