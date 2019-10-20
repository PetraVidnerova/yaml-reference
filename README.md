# yaml-reference


For any character, look up what it means in [YAML](http://yaml.org/).

Compiled from the [reference card](http://www.yaml.org/refcard.html).

## Table of Contents:
[ <a href="#space">space</a>] &nbsp;
[ <a href="#bang">!</a> ] &nbsp;
[ <a href="#quot">"</a> ] &nbsp;
[ <a href="#hash">\#</a> ] &nbsp;
[ <a href="#dollar">$</a> ] &nbsp;
[ <a href="#percent">%</a> ] &nbsp;
[ <a href="#amp">&amp;</a> ] &nbsp;
[ <a href="#apos">'</a> ] &nbsp;
[ <a href="#lparen">(</a> ] &nbsp;
[ <a href="#rparen">)</a> ] &nbsp;
[ <a href="#asterisk">*</a> ] &nbsp;
[ <a href="#plus">+</a> ] &nbsp;
[ <a href="#comma">,</a> ] &nbsp;
[ <a href="#dash">-</a> ] &nbsp;
[ <a href="#dot">.</a> ] &nbsp;
[ <a href="#slash">/</a> ] &nbsp;
[ <a href="#digit">0123456789</a> ] &nbsp;
[ <a href="#colon">:</a> ] &nbsp;
[ <a href="#semicolon">;</a> ] &nbsp;
[ <a href="#lt">&lt;</a> ] &nbsp;
[ <a href="#equal">=</a> ] &nbsp;
[ <a href="#gt">&gt;</a> ] &nbsp;
[ <a href="#question">?</a> ] &nbsp;
[ <a href="#at">@</a> ] &nbsp;
[ <a href="#uppercase">ABCDEFGHIJKLMNOPQRSTUVWXYZ</a> ] &nbsp;
[ <a href="#lbracket">[</a> ] &nbsp;
[ <a href="#backslash">\\</a> ] &nbsp;
[ <a href="#rbracket">]</a> ] &nbsp;
[ <a href="#caret">^</a> ] &nbsp;
[ <a href="#underscore">_</a> ] &nbsp;
[ <a href="#backquote">`</a> ] &nbsp;
[ <a href="#lowercase">abcdefghijklmnopqrstuvwxyz</a> ] &nbsp;
[ <a href="#lbrace">{</a> ] &nbsp;
[ <a href="#pipe">|</a> ] &nbsp;
[ <a href="#rbrace">}</a> ] &nbsp;
[ <a href="#tilde">~</a> ] &nbsp;

## Characters' roles 

### :arrow_right: space

(details unknown)

### :arrow_right: <a name="bang">!</a>

tag

### :arrow_right: <a name="quot">"</a>

string, with escapes

### :arrow_right: <a name="hash">\#</a> #

comment

### :arrow_right: <a name="dollar">$</a>

nothing special?

### :arrow_right: <a name="percent">%</a>

directive

### :arrow_right: <a name="amp">&amp;</a>

anchor

### :arrow_right: <a name="apos">'</a>

string, without escapes

### :arrow_right: <a name="lparen">(</a>

nothing special?

### :arrow_right: <a name="rparen">)</a>

nothing special?

### :arrow_right: <a name="asterisk">*</a>

alias (anchor dereference?)

### :arrow_right: <a name="plus">+</a>

Keep chomp modifier ('|+' or '>+').

See [|](#pipe) and [&gt;](#gt)

### :arrow_right: <a name="comma">,</a>

', ' : Separate in-line branch entries.

### :arrow_right: <a name="dash">-</a>

'- ' : Nested series entry indicator.

'-'  : Strip chomp modifier ('|-' or '>-').

See [|](#pipe) and [&gt;](#gt)

'---': Document header.

### :arrow_right: <a name="dot">.</a>

'...': Document terminator.

numbers: decimal

### :arrow_right: <a name="slash">/</a>

nothing special?

### :arrow_right: <a name="digit">0123456789</a>

1-9  : Explicit indentation modifier ('|1' or '>2').

See [|](#pipe) and [&gt;](#gt)

### :arrow_right: <a name="colon">:</a>

': ' : Value indicator.

### :arrow_right: <a name="semicolon">;</a>

nothing special?

### :arrow_right: <a name="lt">&lt;</a>

'<<' : Merge keys from another mapping.

### :arrow_right: <a name="equal">=</a>

'='  : Default "value" mapping key.

### :arrow_right: <a name="gt">&gt;</a>

'>'  : Folded scalar indicator.

### :arrow_right: <a name="question">?</a>

'? ' : Key indicator.

### :arrow_right: <a name="at">@</a>

reserved for future use (as of ver 1.1?)

### :arrow_right: <a name="uppercase">ABCDEFGHIJKLMNOPQRSTUVWXYZ</a>

lots of fun words...

### :arrow_right: <a name="lbracket">[</a>

'[]' : Surround in-line series branch.

### :arrow_right: <a name="backslash">\\</a>

escapes in "double quoted" strings

### :arrow_right: <a name="rbracket">]</a>

'[]' : Surround in-line series branch.

### :arrow_right: <a name="caret">^</a>

nothing special?

### :arrow_right: <a name="underscore">_</a>

1_230.15 Fixed float

"\_": NBSP

### :arrow_right: <a name="backquote">`</a>

reserved for future use (as of ver 1.1?)

### :arrow_right: <a name="lowercase">abcdefghijklmnopqrstuvwxyz</a>

see ABCDEFGHIJKLMNOPQRSTUVWXYZ

### :arrow_right: <a name="lbrace">{</a>

'{}' : Surround in-line keyed branch.

### :arrow_right: <a name="pipe">|</a>

'|'  : Block scalar indicator.

- Strip leading indentation.
- Keep final line break but clip any trailing empty lines.
- Remaining newlines and whitespace are preserved.

'|-' : strip final line break and trailing empty lines

### :arrow_right: <a name="rbrace">}</a>

'{}' : Surround in-line keyed branch.

### :arrow_right: <a name="tilde">~</a>

~, null : Null (no value).
