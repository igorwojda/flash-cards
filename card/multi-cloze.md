# 📝 Multi Cloze

Sentence with two or more related parts hidden.
Each `cN` number generates a separate card. Gaps with the same number are hidden together.

## Structure

Card Type: Cloze

Side 1: Sentence with multiple gaps (`{{c1::...}}`, `{{c2::...}}`)
Side 2: Full sentence (optional `Extra` explanation)

## Tip

Use for paired or contrasting parts (immediate/ultimate, knowledge/skill)

## Example

Side 1:  

```
With bad habits, the {{c1::immediate}} outcome feels good, but the {{c2::ultimate}} outcome feels bad
```

Anki generates 2 cards:

- Card 1: `With bad habits, the [...] outcome feels good, but the ultimate outcome feels bad`
- Card 2: `With bad habits, the immediate outcome feels good, but the [...] outcome feels bad`

Side 2:  

```
With bad habits, the immediate outcome feels good, but the ultimate outcome feels bad
```
