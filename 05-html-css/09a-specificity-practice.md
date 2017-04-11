## Specificity Examples: Test Yourself

It’s easier to calculate the specificity using the first method. Let’s find out, how it actually is done.

| Question | Selector     | Specificity
| :------------- | :------------- | :------------- |
<<<<<<< HEAD
| 1      | * { }  | 0 |
| 2      | li.cool { }  |  11   |
| 3      | li { }  | 1   |
| 4      | li:first-line { }  |  1  |
| 5      | ul li { }  |  2  |
| 6      | ul ol+li { } |  3  |
| 7      | h1 + *[rel=up] { } | 11  |
| 8      | ul ol li.red { } |  13  |
| 9      | li.red.level { } |  21  |
| 10     | style=”” |  1000  |
| 11     | p { } | 1  |
| 12     | div p { } |  2  |
| 13     | .ada { } |  10  |
| 14     | div p.ada { } | 12   |
| 15     | #grace { } | 100   |
| 16     | body #grace.ada p { } |  112  |
=======
| 1      | `* { }`  |    |
| 2      | `li.cool { } ` |    |
| 3      | `li { }`  |    |
| 4      | `li::first-line { }`  |    |
| 5      | `ul li { }`  |    |
| 6      | `ul ol+li { }` |    |
| 7      | `h1 + *[rel=up] { }` |    |
| 8      | `ul ol li.red { }` |    |
| 9      | `li.red.level { }` |    |
| 10     | `style=””` |    |
| 11     | `p { }` |    |
| 12     | `div p { }` |    |
| 13     | `.ada { }` |    |
| 14     | `div p.ada { }` |    |
| 15     | `#grace { }` |    |
| 16     | `body #grace.ada p { }` |    |
>>>>>>> ada/master
