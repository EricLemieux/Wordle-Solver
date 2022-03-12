# Wordle Solver

Generate hints for wordle using grep and dictionary file.

## Usage

* This likley only works with gnu grep, as that's the only version I tested it on.

Assuming that we have already put a couple guesses into the game, and now we are stuck.
From our previous guesses we know that the letters 'wtyoadfjkzcv' are all available.
We also learned that the letters 'ato' are in the word, and that the word must start with 'a'.

```
wordle-solver 'wtyoadfjkzcv' 'ato' 'a....'
```

Will out put 'afoot'

For more information you can use `--help`

```
wordle-solver --help
```

