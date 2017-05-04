# motes-md

Markdown parser for Motes.in.

## Usage

```javascript
const md = require('motes-md')({
  hashtag: '/tags/', // default prefix for hashtag url
  mention: '/users/' // default prefix for mention url
});

console.log(md('# Markdown'));

// you can pass an object to get the some values from the parsing
const env = {};
const html = md('# Markdown', env);
console.log(html, env);
```

## Credits

motes-md uses the following packages:

- [markdown-it](https://www.npmjs.com/packages/markdown-it)
- [markdown-it-abbr](https://www.npmjs.com/packages/markdown-it-abbr)
- [markdown-it-anchor](https://www.npmjs.com/packages/markdown-it-anchor)
- [markdown-it-attrs](https://www.npmjs.com/packages/markdown-it-attrs)
- [markdown-it-block-embed](https://www.npmjs.com/packages/markdown-it-block-embed)
- [markdown-it-block-image](https://www.npmjs.com/packages/markdown-it-block-image)
- [markdown-it-center-text](https://www.npmjs.com/packages/markdown-it-center-text)
- [markdown-it-checkbox](https://www.npmjs.com/packages/markdown-it-checkbox)
- [markdown-it-container](https://www.npmjs.com/packages/markdown-it-container)
- [markdown-it-deflist](https://www.npmjs.com/packages/markdown-it-deflist)
- [markdown-it-emoji](https://www.npmjs.com/packages/markdown-it-emoji)
- [markdown-it-expand-tabs](https://www.npmjs.com/packages/markdown-it-expand-tabs)
- [markdown-it-footnote](https://www.npmjs.com/packages/markdown-it-footnote)
- [markdown-it-hashmention](https://www.npmjs.com/packages/markdown-it-hashmention)
- [markdown-it-highlighted](https://www.npmjs.com/packages/markdown-it-highlighted)
- [markdown-it-highlightjs](https://www.npmjs.com/packages/markdown-it-highlightjs)
- [markdown-it-imsize](https://www.npmjs.com/packages/markdown-it-imsize)
- [markdown-it-ins](https://www.npmjs.com/packages/markdown-it-ins)
- [markdown-it-mark](https://www.npmjs.com/packages/markdown-it-mark)
- [markdown-it-math](https://www.npmjs.com/packages/markdown-it-math)
- [markdown-it-playground](https://www.npmjs.com/packages/markdown-it-playground)
- [markdown-it-smartarrows](https://www.npmjs.com/packages/markdown-it-smartarrows)
- [markdown-it-sub](https://www.npmjs.com/packages/markdown-it-sub)
- [markdown-it-sup](https://www.npmjs.com/packages/markdown-it-sup)
- [markdown-it-table-of-contents](https://www.npmjs.com/packages/markdown-it-table-of-contents)
- [markdown-it-task-checkbox](https://www.npmjs.com/packages/markdown-it-task-checkbox)
- [markdown-it-title](https://www.npmjs.com/packages/markdown-it-title)
- [markdown-it-underline](https://www.npmjs.com/packages/markdown-it-underline)

## License

[MIT License](LICENSE)
