# 📝 Multi Cloze

Sentence with two or more related parts hidden.
Each `cN` number generates a separate card. Gaps with the same number are hidden together.

## Structure

Card Type: Cloze

Text: Sentence with multiple gaps (`{{c1::...}}`, `{{c2::...}}`)
Back Extra: Optional explanation

## Tip

Use for paired or contrasting parts (immediate/ultimate, knowledge/skill)

## Example

Text:  

```
With bad habits, the {{c1::immediate}} outcome feels good, but the {{c2::ultimate}} outcome feels bad
```

Anki generates 2 cards:

- Card 1 front: `With bad habits, the [...] outcome feels good, but the ultimate outcome feels bad`
- Card 2 front: `With bad habits, the immediate outcome feels good, but the [...] outcome feels bad`
- Back (both): `With bad habits, the immediate outcome feels good, but the ultimate outcome feels bad`

## Example With Shared Gap Number

Text:  

```
{{c1::Passive}} learning creates {{c2::knowledge}}
{{c1::Active}} learning creates {{c2::skill}}
```

Anki generates 2 cards:

- Card 1 front: `[...] learning creates knowledge / [...] learning creates skill`
- Card 2 front: `Passive learning creates [...] / Active learning creates [...]`
- Back (both): `Passive learning creates knowledge / Active learning creates skill`
