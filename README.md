# 4D.tmbundle
A TextMate bundle for 4D.

<img src="https://github.com/user-attachments/assets/3506f71e-86af-4d88-8930-3042fb53c763" width=400 height=auto />

|scope&nbsp|Description|
|-|-|
|`source.4dm`|code|
|`comment.block.4d`|[inline or multiline comments](https://developer.4d.com/docs/Concepts/quick-tour#inline-or-multiline-comments-comment) - folds|
|`comment.line.double-slash.4d`|[single line comments](https://developer.4d.com/docs/Concepts/quick-tour#single-line-comments-comment)|
|`constant.numeric.4d`|[number literals](https://developer.4d.com/docs/18/Concepts/number#number-literals) - decimal integer|
|`constant.numeric.decimal.4d`|[number literals](https://developer.4d.com/docs/18/Concepts/number#number-literals) - decimal point is period or comma|
|`constant.numeric.exponential.4d`|[number literals](https://developer.4d.com/docs/18/Concepts/number#number-literals) - scientific notation|
|`constant.numeric.hexadecimal.4d`|[number literals](https://developer.4d.com/docs/18/Concepts/number#number-literals) - hexadecimal integer|
|`constant.other.time.4d`|[time literals](https://developer.4d.com/docs/Concepts/time#time-literals)|
|`constant.other.date.4d`|[date literals](https://developer.4d.com/docs/Concepts/date#date-literals)|
|`constant.language.4d`|[constants](https://developer.4d.com/docs/Concepts/quick-tour#constants)|
|`string.quoted.double.4d`|[string literals](https://developer.4d.com/docs/Concepts/string#string-literals)|
|`variable.parameter.numeric.4d`|[parameters](https://developer.4d.com/docs/18/Concepts/parameters#parameter-indirection)|
|`variable.language.orda.4d`|`ds` `cs` `4D` `this` `form` `null` `super`|
|`variable.other.local.4d`|[local variables](https://developer.4d.com/docs/Concepts/variables#local-variables)|
|`variable.other.interprocess.4d`|[interprocess variables](https://developer.4d.com/docs/Concepts/variables#interprocess-variables)|
|`entity.name.function.classic.4d`|classic language|
|`entity.name.function.classic.deprecated.4d`|classic language with `_O_` prefix|
|`entity.name.function.orda.4d`|object member function|
|`support.variable.classic.4d`|[system variables](https://developer.4d.com/docs/Concepts/variables#system-variables)|
|`support.variable.orda.4d`|object property|
|`support.type.classic.4d`|classic language with `C_` prefix|
|`support.type.orda.4d`|[variable type](https://developer.4d.com/docs/Concepts/variables.html#declaring-variables)|
|`keyword.control.4d`|`try` `catch` `end try` `return` `break` `continue` `case of` `au cas ou` `end case` `fin de cas` `if` `si` `else` `sinon` `end if` `fin de si` `boucle` `fin de boucle` `repeat` `repeter` `until` `jusque` `while` `tant que` `end while` `fin tant que` `pour chaque` `for each` `end for each` `for` `end for` `fin de chaque`|
|`keyword.other.4d`|`class constructor` `class extends` `use` `end use` `utiliser` `fin utiliser` `begin sql` `debut sql` `end sql` `fin sql`|
|`keyword.other.function.4d`|[function](https://developer.4d.com/docs/Concepts/classes#function)|
|`keyword.other.alias.4d`|[alias attributes](https://developer.4d.com/docs/ORDA/ordaClasses#alias-attributes-1)|
|`keyword.other.declare.4d`|[declaring parameters](https://developer.4d.com/docs/Concepts/parameters#declaring-parameters)|
|`keyword.operator.4d`|`+=` `-=` `*=` `/=` `~\|` `&&` `&` `\|\|` `\|` `<<` `<=` `<` `>>` `>=` `>` `:=` `??` `?+` `?-` `+` `=` `*` `/` `=` `#` `^` `%` `?` `:`|
|`storage.type.4d`|`var` `property`|

## remarks

the following symbols are not assigned any scopes:

* unary operator `->`
* argument delimiter `;`
* decimal point `.`
* comma `,`
* parentheses `()` `{}` `[]` `[[]]` 
* object literal
* collection literal

not using `beginCaptures` for token sequences; simply markup tokens without context.
