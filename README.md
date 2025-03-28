

### Compile & Execute

View the compiled Javascript side by side or Direct execute it.

> The [compiler](https://github.com/LingDong-/wenyan-lang/tree/master/build) is shipped with this extension, no installation required.

![](https://github.com/antfu/wenyan-lang-vscode/raw/master/screenshots/demo-execute.png)


### Punctuations Replacement

Punctuations will be automatically replaced to fit the language.

![](https://github.com/antfu/wenyan-lang-vscode/raw/master/screenshots/demo-punctuations.gif)

*You will get the result immediately, the delay is added for demostraction purpose*


### Snippets

You can write Wenyan quickly by using snippets:

![](https://github.com/antfu/wenyan-lang-vscode/raw/master/screenshots/demo-snippets.gif)

Here are some common snippets. For full list, check out [this file](https://github.com/antfu/wenyan-lang-vscode/blob/master/snippets/static.json).

| Triggers | Snippet |
| --- | --- |
| `if` | `若⋯者。⋯也。` |
| `else` | `若非。⋯也。` |
| `for` | `為是⋯遍。⋯云云。` |
| `break` | `乃止。` |
| `while` | `恆為是。⋯云云。` |
| `function` | `吾有一術。名之曰「⋯」。是術曰。` |
| `int` | `吾有一數。曰⋯。名之曰「⋯」。` |
| `str` | `吾有一言。曰「「⋯」」。名之曰「⋯」。` |
| `bool` | `吾有一爻。曰陰。名之曰「⋯」。` |
| `array` | `吾有一列。名之曰「⋯」。` |
| `object` | `吾有一物。名之曰「⋯」。` |

### [Wenyanizer](https://github.com/zxch3n/wenyanizer) by [@zxch3n](https://github.com/zxch3n)

From `v0.10.0`, we shipped support for compiling Javascript back to Wenyan. Thanks for @zxch3n's great work!

![](https://user-images.githubusercontent.com/11247099/71503497-64e05500-28b0-11ea-978a-782a9181f44d.png)


### Configurations

| Fields | Default | Note |
| --- | --- | --- |
| `wenyan-lang.executablePath` | built-in | Filepath to executable `wenyan.js` |
| `wenyan-lang.targetLanguage` | `javascript` | Target language that compiles to. Can be `javascript`, `python` or `ruby` |
| `wenyan-lang.runOnSave` | true | Execute the code on save |
| `wenyan-lang.romanizeMethod` | null | Romanize identifiers. The method can be `pinyin`, `baxter` or `unicode` |

## ToDo

- [x] Syntax Highlight
- [x] Snippets
- [x] Dynamic Snippets
- [x] Execute
- [x] Compile
- [x] Compile to Python
- [x] Rendering
- [ ] Code Completion
- [ ] Language Server

## License

[MIT License] © 2019-2020
