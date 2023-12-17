# ⭐ Pug Language Features

This extension is designed to significantly improve DX when working with Pug. This extension adds:

- 🌈 Best Syntax Highlighting
- 👆 Hover
- ⚙️ Rename
- 🔍 Definition
- 🤖 Autocomplete
- ✨ Code Formatter
- 🔥 JavaScript Integration
- 📜 `PugDoc` Integration

## 🛣️ Road Map

This extension is still in development, so the roadmap consists of the following steps:

- [X] 🌈 Best Syntax Highlighting
- [ ] 👆 Hover
- [ ] ⚙️ Rename
- [ ] 🔍 Definition
- [ ] 🤖 Autocomplete
- [ ] ✨ Code Formatter
- [ ] 🔥 Integrate JavaScript
- [ ] 📜 Made and Integrate `PugDoc`

## 🌈 Best Syntax Highlighting

In this extension to highlight the `Pug` syntax, special attention is paid to the choice of names for tokens. We strive to use more intuitive and logically sound names, adhering to established norms and standards. One of the key aspects is the consistency of token names with those used in `HTML` and `JavaScript`. This solution not only reduces the specificity of token names, but also contributes to the unification of code perception between different languages.

Other features of this variant of syntax coloring include:

- ❌ `Syntax Error Highlighting` - this plugin tries to find and prevent any syntax errors in the Pug code without destroying the highlighting of the rest of the code.
- 😸 `Handling of Extreme Cases` - Extreme cases that were not taken into account in the old version of syntax highlighting were corrected and refined. These little things could upset Pug fans and add confusion to the code.

In addition, you will no longer have to look for a suitable theme for the correct syntax coloring, because logically sound token names will make it correct when using any theme. You can verify this by looking at comparisons of the old syntax coloring against the new one:

<details>
<summary>🤩 Comparison 🌈</summary>

[import-extends-old]: https://raw.githubusercontent.com/Deemoguse/pug-language-features/main/assets/syntaxes/import-extends-old.png
[import-extends-new]: https://raw.githubusercontent.com/Deemoguse/pug-language-features/main/assets/syntaxes/import-extends-new.png
[mixin-with-block-variables-old]: https://raw.githubusercontent.com/Deemoguse/pug-language-features/main/assets/syntaxes/mixin-with-block-variables-old.png
[mixin-with-block-variables-new]: https://raw.githubusercontent.com/Deemoguse/pug-language-features/main/assets/syntaxes/mixin-with-block-variables-new.png
[mixin-with-dynamic-name-old]: https://raw.githubusercontent.com/Deemoguse/pug-language-features/main/assets/syntaxes/mixin-with-dynamic-name-old.png
[mixin-with-dynamic-name-new]: https://raw.githubusercontent.com/Deemoguse/pug-language-features/main/assets/syntaxes/mixin-with-dynamic-name-new.png

### Import And Extends
| Old Syntax Highlight                      | New Syntax Highlight                      |
| :---------------------------------------- | :---------------------------------------- |
| ![import-extends-old][import-extends-old] | ![import-extends-new][import-extends-new] |

### Mixin With Block Variables
| Old Syntax Highlight                                              | New Syntax Highlight                                              |
| :---------------------------------------------------------------- | :---------------------------------------------------------------- |
| ![mixin-with-block-variables-old][mixin-with-block-variables-old] | ![mixin-with-block-variables-new][mixin-with-block-variables-new] |

### Mixin With Dynamic Name
| Old Syntax Highlight                                        | New Syntax Highlight                                        |
| :---------------------------------------------------------- | :---------------------------------------------------------- |
| ![mixin-with-dynamic-name-old][mixin-with-dynamic-name-old] | ![mixin-with-dynamic-name-new][mixin-with-dynamic-name-new] |
</details>

## Comming Soon...

The project is in the *__WIP__* _(Work In Progress)_ status. The rest of the functions are being developed and will appear gradually.