# console-log-remover README

Easily remove the most complex console.log() statements from your code.

## How to use

Cmd + Shift + P -> Console Log Remover
or
Alt + C

## Features

1. Single-line comment console.log(): This is the case when we comment out a console.log(), like so:

```js
console.log("foo");
```

2. Single-line console.log() with single quotes:

   ```js
   console.log("boo");
   ```

3. Single-line console.log() with multiple arguments:

```js
console.log("firstName", firstName);
```

4. Multiline console.log() statement:

```js
   console.log(
   'hello'
   )
```

5. Nested parentheses:

```js
   console.log("user", getUser(), "name", getName());
```

### 0.0.1

Initial release of Console Log Remover

---

### Repository

https://github.com/kurucaner/console-log-remover

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

- Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
- Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
- Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

- [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
- [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
