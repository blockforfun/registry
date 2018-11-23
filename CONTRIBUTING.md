So you want to help us get rid of call and messaging spam? Awesome!

## Format

Every entry is stored in a `.txt` file with two required lines:

```
COMMA,OR, SPACE SEPARATED FLAGS
Description
```

### Flags

There are two flags:

* `WARN`
* `BLOCK`

### Naming

The target number is evaluated by concatenating the name of parent directories and the file name

```
46/8/358486.txt => 468358486
555/123456.txt => 555123456
```
