---
description: LineHeight

next:
  text: Link
  link: /extensions/Link/index.md
---

## Usage

```tsx
import { LineHeight } from 'reactjs-tiptap-editor'; // [!code ++]

const extensions = [
  ...,
  // Import Extensions Here
  LineHeight // [!code ++]
];
```

## Options

### lineHeights

Type: `string[]`\
Default: `['100%', '115%', '150%', '200%', '250%', '300%']`

```js
import { DEFAULT_LINE_HEIGHT_LIST, LineHeight } from 'reactjs-tiptap-editor';

FontSize.configure({
  LineHeight: [
    // Use default line height list
    ...DEFAULT_LINE_HEIGHT_LIST,
    '1',
    '1.5',
    '2',
    '2.5'
  ]
})
```
