# Scribe Markup Language

Scribe Markup Language is designed to be readable easily as is, thanks to its natural markup system. See below the syntax description.

There are three type of Scribe files:

+ `.scribe` is the raw format, which contains only markup'ed text
+ `xscribe` is the hybrid format, wich contains `scribe script`, a feature for bringing programmatic shipping of content
+ `iscribe` is the scribe script only format, and it's purpose is to be be imported inside xscribe files

The second and third formats are made to generate dynamically or statically basic .scribe files.

## Basic syntax

### Headings

#### Heading level 1

```
Heading h1
##########
```

#### Heading level 2

```
heading 2
=========
```

#### Heading level 3

```
Heading 3
*********
```

#### Heading level 4 

```
Heading 4
---------
```

### Paragraphs and line breaks

```
Lorem ipsum dolor sit amet, consectetur, dipisicing elit, sed doeiusmod tempor. Incididunt ut labore et dolore magna aliqua.

Lorem ipsum dolor sit amet, consectetur, Adipisicing elit, sed doeiusmod tempor.
Incididunt ut labore et dolore magna aliqua.
```

### Emphasis

```
#Bold#

~Italic~

\Strike\
```

### Blockquotes

```
  | Lorem ipsum dolor sit amet, consectetur,
  | Adipisicing elit, sed doeiusmod tempor.
  | Incididunt ut labore et dolore magna aliqua.
```

Alternate syntax:

```

  | ------------------------------------------
  | Gravitation is not responsible for people
  | falling in love.
  | ------------------------------------------
  | - Albert Einstein      ------------------
  | - https://example.com/ -------------------

```

### Lists

Ordered

```

  1. Item
  2. Item 
  3. Item

```

Unordered

```

  * Item
  * Item 
  * Item

```

### Code blocks

```

:---(python)
def f(n: int) -> bool:
    if n == 0:
        return False
    return True
---:

```

Inline code:

```
To intitialize a git repository do :-git init-:.
```

# tables

```

| Item | Item | Item |
+=----=+=----=+=-----=+
| Item | Item | Item |
+------+------+------+
| Item | Item | Item |

```

### Links, Images and Videos

See  how to use the xscribe scripting language to create html files...

---

## Scribe scripting language

## Syntax, the basics

**Not yet implemented!**

### Scribe scripting language import files

**Not yet implemented!**

## TODO

+ [ ] Design of the xscibe script language (specifications, concepts, etc.)
+ [ ] A transpiler to produce .scribe file from .xscribe and .iscribe file
+ [ ] A lot of example files
