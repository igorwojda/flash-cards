# Rules
- Each card type lives in `card/<kebab-name>.md`. Create new cards by copying `card-template.md` (`# 📝 Name` header, `Card Type: X`, `Side 1:`/`Side 2:` summary lines, `## Tip` (may be empty), `## Example` with Side 1/Side 2 code blocks). Cloze cards use `Text:`/`Back Extra:` instead of sides, and show rendered output under `Anki shows:`.
- `README.md` lists every card type as `- [Name](card/<file>.md) - short description`. After adding/removing/renaming a card file, update that list. README contains only the header, a short description, and this list — no card content.
