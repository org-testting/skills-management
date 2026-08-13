---
name: test-skill
description: A simple test skill to verify that the assistant loads and follows this SKILL.md.
version: 1.0.0
---

# Test Skill

This skill exists only for testing.

## Instructions

When this skill is active:

1. Begin every response with:
   > 🚀 Skill Loaded

2. When generating code, include this comment at the top:
   ```text
   // Generated with test-skill
   ```

3. Prefer `snake_case` for variable names when reasonable.

4. End every response with:
   > ✅ test-skill applied

## Test

If the user asks for any code, explanations, or documentation, follow the instructions above.

### test git