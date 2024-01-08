# scripture-language-support README

Scripture language support for translation with the Codex app. Supports `.bible`, `.scripture`, and `.codex` file extensions.

Scripture language is intended to be cross-linguistic, and it is meant to interface with translation-related language servers and extensions in the Codex app.

## Features

- Key words include USFM scripture abbreviations (e.g., `MAT`, `GEN`, `PSA`, etc.)
- Line comments begin with `+` (e.g., `+ This is a comment`)
- Block comments begin with `[` and end with `]`. For example, `[ This is a comment ]`, or

```
[
This is a block comment
]
```

## Notes

This is just a POC. We will be adding more features in the future.
