# ralang
Relational algebra structurer.
Offers basic table, row and column style query syntax, formatted as functions which output markdown text.
Made in excel using formulas imitating context free grammar and circuits, in a sense.

Usage notes:
- Select preferred syntax sheet.
- Each operation consists of the operator function (from given list) and 1 - 4 paramters, followed by an ID (up to 100).
- Existing operations can be chained (in any order) by plugging in the keyword f_# as a parmater, where # is the other ID.
- Gradual interpretation runs in steps over later columns, finally copying the expanded text back near the input table.
  The main function can be copied over to a markdown / regular notebook of choice.
