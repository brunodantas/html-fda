## HTML FDA

Implementation of finite deterministic automata using pure HTML. States are HTML pages and transitions are hyperlinks. This is actually written in Markdown and converted/hosted by GitHub Pages. The only functionality used are pages and hyperlinks.

The following FDA are defined over the alphabet {0, 1}, including the empty string symbol ε to denote end of word for convenience.

- [∅](empty/s1.md) (empty language)
- [ε](empty_string/s1.md) (empty string)
- [0*](zstar/s1.md)
- [0\*1\*](zstarostar/s1.md)
- [(0+1)](zpo/s1.md)
- [(1\*) (0 (1\*) 0 (1\*))\*](even/s1.md) (even number of 0)
