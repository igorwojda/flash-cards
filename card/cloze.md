# 📝 Cloze

Sentence with a single key part hidden.
Recall the hidden part from the rest of the sentence.

## Structure

Card Type: Cloze

Text: Sentence with one gap (`{{c1::...}}`)
Back Extra: Optional explanation

## Tip

Hide only the key word or phrase, not the whole sentence.
Hint can be added to cloze card `{{c1::Hidden Text::Hint}}`.

## Example

Text:  

```
Larger vocabulary size means {{c1::fewer}} tokens
```

Anki shows:

- Front: `Larger vocabulary size means [...] tokens`
- Back: `Larger vocabulary size means fewer tokens`

## Example With Hint

Text:  

```
Larger vocabulary size means {{c1::fewer::amount}} tokens
```

Anki shows:

- Front: `Larger vocabulary size means [amount] tokens`
- Back: `Larger vocabulary size means fewer tokens`
