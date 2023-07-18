# cbasten_eloquent_javascript_notes
Notes for https://eloquentjavascript.net/

## Chapter 1
- Uses number instead of int
- String interpolation is called template literals

- There is only one value in JavaScript that is not equal to itself, and that is NaN (“not a number”)
- NaN is meant to denote the result of a nonsensical computation

- When an operator is applied to the “wrong” type of value, JavaScript will quietly convert that value to the type it needs, using a set of rules that often aren’t what you want or expect. This is called type coercion

## Chapter 2
- In some cases, JavaScript allows you to omit the semicolon at the end of a statement. In other cases, it has to be there, or the next line will be treated as part of the same statement. The rules for when it can be safely omitted are somewhat complex and error-prone.
- var is similar to let but is rarely used due to some rare properties
- The word const stands for constant. It defines a constant binding, which points at the same value for as long as it lives.
- Applying the ! operator will convert a value to Boolean type before negating it, and all strings except "" convert to true. 