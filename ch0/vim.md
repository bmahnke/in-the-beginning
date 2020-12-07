Commands:

- Splitting files from the command line
```
  vim -o [file] [file2] # horizontal
  vim -O [file] [file2] # vertical
```
- Split files from within a file
```
  - vi [file]
  - :vsp [file2]
```
- Switch between panels when split: `[CTRL] + w`
- Skip to end of line: `[Shift] + $`
- Find and replace words: `:%s/\~/\*`
```
  - %: global replace in file
  - s: the search
  - \~: the item you're searching for (this is escaped with `\` because of the special charater)
  - \*: the item to replace with (also escaped `\` becaues of special charaters)
```
