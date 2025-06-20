# react-pdf-highlighter-sp2

Set of React components for PDF annotation (forked from [react-pdf-highlighter](https://github.com/agentcooper/react-pdf-highlighter)).

Fork reasons:

- PDF.js version 4.4.168 is not compatible with iOS < 16.4.
- Using PDF.js version 3.11.174 because it is the latest version that is compatible with React 18 and iOS < 16.4.

Features:

- Built on top of PDF.js
- Text and image highlights
- Popover text for highlights
- Scroll to highlights

## Importing CSS

The bundled CSS include the CSS for pdfjs.

```tsx
import "react-pdf-highlighter-sp2/dist/style.css";
```

## Example

See demo https://agentcooper.github.io/react-pdf-highlighter/.

To run the example app locally:

```bash
npm install
npm start
```

## Install

```bash
npm install react-pdf-highlighter-sp2
```

## How to use

See [`./example/src/App.tsx`](https://github.com/sergeysmetannikov2/react-pdf-highlighter-sp2/blob/main/example/src/App.tsx) for the React component API example.
