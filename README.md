
# @auroradigital/prettier-config



Prettier, but with opinionated changes.



## Changed rules

| Rule   |   Old  |   New   |   Why                 |
|--------|--------|---------|-----------------------|
| [semi](https://prettier.io/docs/en/options.html#semicolons) | `true` | `false` | Semicolons are unnecessary in JavaScript and are noisy. |
| [singleQuote](https://prettier.io/docs/en/options.html#quotes) | `false` | `true` | Single quotes are more popular in JavaScript than double quotes and are less noisy.
| [trailingComma](https://prettier.io/docs/en/options.html#trailing-commas)    |  `false`   | `all`  | Trailing commas allow for quicker additions.

This rules of this prettier config is designed to play nice with our shareable ESLint config: [eslint-config-aurora](https://github.com/AuroraDigital/eslint-config-aurora).
