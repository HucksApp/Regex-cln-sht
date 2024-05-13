# Regular Expression clean sheet🔎

## Character sequences   🅰️ 🅱️

### Description 
specify an actual character or set of characters in the sequence

char symbol     |     char symbol meaning and usage
----------------|---------------------------------------------
range -> `[]`   | all  characters between the iteratable start and stop  `[<char1> - <charN>]` eg [a-c] -> a, b, c
dot -> `.`      | any (*one*) character including symbols a-z 0-9 A-Z & . ' " etc
group -> `()`   | grouped characters between () are affected by same sequence specifier
digit -> `\d`   | any (*one*) digit
word -> `\w`    | any (*one*) character (character useable in words)
space -> `\s`   | any (*one*) white space character
tab -> `\t`     | tab (*one*) character
nor -> `^`      | exact beginning of string or ***NOT***
dollar -> `$`   | exact end of the string


## Sequence Quantifier   🧮

### Description 
specify the quantity of character of the sequence

char symbol                  |     char symbol meaning and usage
-----------------------------|-----------------------------------------
range -> `{}`                | specify character quntity between start and stop , exact stop, or start and infinity as follows `{<start>, <stop>}`, `{<stop>}`, `{start, }` 
? ->  `?`                    | character sequence quantity between 0 and 1 (none or 1)
asteric -> `*`               | character sequence quantity between 0 and infinity (none or more)
plus -> `+`                  | character sequence quantity between 1 and infinity (1 or more)

