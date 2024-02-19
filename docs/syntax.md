# Literals

## Integers

Ya know, just your regular ol' numbers:

```
0 42 1000 -12
```

## Floating Point Numbers

```
0.0 4.7 3.5e8
```

## Strings

```
"A bunch of characters"
'Can use single or double quotes'
"""
Triple quotes can include newlines
and unquoted 'single' and "double"
quote characters.
"""
```

## Lists

Lists are heterogeneous sequences of atoms.

```
[ 0 1 2 3 4 ]
```

## Tuples

Tuples are immutable heterogeneous sequences of atoms.

```
| 1 2 |
```

## Quotes, or Syntax

I guess it does something to put literal words on the stack instead of immediately interpreting them

```
{ dup * }
```

## Records

Like structs, I guess?

```
<Point 0 0> {x:} {y:} bi


```

How do you define a record?

```

```

## Maps, Soups, or Whatever

```

"a" 5 (map insert)
```

## Messages

```
(start.)
graphics { |5 6| # }
graphics .set
```

# Examples

1. Squares

```
[1 2 3 4] {dup *} map
# [1 4 9 16]

: map { swap }
```
