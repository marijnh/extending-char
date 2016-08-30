# Extending-char

Tiny library for determining whether a character (in fact, an UTF-8
16-bit value) is an extending character, i.e. doesn't start a new
glyph. The second half of surrogate pairs counts as an extending
character as far as this library is concerned.

License: MIT

## Interface

**`isExtendingChar`**`(ch: string) → bool`

Check whether the given character is an extending char.

**`isExtendingCharAt`**`(string: string, pos: number) → bool`

Check whether the character at the given position in the string is an
extending char.

