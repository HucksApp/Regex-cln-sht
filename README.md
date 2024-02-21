# Regex-clean-sheet🔎

## Character sequences 

### Description 🅰️ 🅱️
specify an actual character or set of characters in the sequence

char symbol     |     Description and usage
----------------|---------------------------
range -> `[]`   | all characters between the iteratable start and stop  `[<char1> - <charN>]`
dot -> `.`      | any character including non Alphanumeric
group -> `()`   | grouped characters between () are affected by same sequence specifier
digit -> `\d`   | all digit
word -> `\w`    | all character (character useable in words)
space -> `\s`   | white space character
tab -> `\t`     | tab character
nor -> `^`      | exact beginning of string
dollar -> `$`   | exact end of the string


## Sequence Quantifier 

### Description 🧮
specify the quantity of character of the sequence

char symbol          |     Description and usage
---------------------|---------------------------
range -> `{}`        | specify character quntity between start and stop , exact stop, or start and infinity as follows -> `{<start>, <stop>}`,  -> `{<stop>}`, -> `{start, }` 
? ->  `?`            | any character quantity between 0 and 1 (0 or 1)
asteric -> `*`       | any character quantity between 0 and infinity (0 or more)
plus -> `+`          | any character quantity between 1 and infinity (1 or more)

