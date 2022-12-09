## Master the ls

### Instructions

Put in a file `master-the-ls`, the command line that will:

- list the files and directories of the current directory.
- Ignore the hidden files, the "." and the "..".
- Separates the results with commas.
- Order them by ascending order of access time (the newest first).
- Have the directories ends with a `/`.

### Hints

Here are some Commands that can help you:

- `tr`. Translate characters: run replacements based on single characters and character sets.

  - Replace all occurrences of a character in a file, and print the result:
    `tr {{find_character}} {{replace_character}} < {{filename}}`

- `ls`. List directory contents.
- `sed`. Edit text in a scriptable manner.

> You have to use Man or Google to know more about commands flags, in order to solve this exercise!
> Google and Man will be your friends!

### References

- [tr](https://www.gnu.org/software/coreutils/tr).
- [ls](https://www.gnu.org/software/coreutils/ls).
- [sed](https://www.gnu.org/software/sed/manual/sed.html).