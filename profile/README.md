<p align="center">
  <a href="https://clerk.com?utm_source=github&utm_medium=clerk_types" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./logo_dark.jpg" height="64">
      <img src="./logo.jpg" height="64">
    </picture>
  </a>
  <br />
  <h1 align="center">SSE Editor</h1>
</p>

<div align="center">

[Changelog](https://github.com/sse-editor/editor/blob/master/CHANGELOG.md)
·
[Report a Bug](https://github.com/sse-editor/editor/issues/new?assignees=&labels=needs-triage)
·
[Community](https://github.com/sse-editor/community)
</div>

---

SSE Editor.js is a block-styled editor that outputs clean data in JSON format. It is designed to be extensible and pluggable, allowing developers to create custom blocks and integrate with various back-end systems. With a focus on user experience, SSE Editor.js provides a simple and intuitive interface for content creation.

##  Table Of Content
- [Features](#features)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Plugins](#plugins)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Block-based Editing**: Create content in blocks, allowing for flexible layouts and easy rearrangement.
- **Clean Data Output**: Outputs data in a structured JSON format, making it easy to store and manipulate.
- **Extensible**: Easily add custom blocks and tools to fit your specific needs.
- **Rich Text Editing**: Supports various formatting options, including headings, lists, images, and more.
- **Cross-Platform**: Works seamlessly across different devices and browsers.

## Getting Started

1. **Include SSE Editor.js in your project**: You can install SSE Editor.js via npm or include it directly in your HTML.

```bash
npm install @sse-editor/editor.js -D
# or
yarn add @sse-editor/editor.js
# or
pnpm add @sse-editor/editor.js
```

Or include it via CDN:

```html
```

2. **Initialize SSE Editor.js**:

```js
const editor = new SSEEditor({
    holder: 'sse_editorjs',
    tools: {
        header: Header,
        list: List,
        image: SimpleImage,
        // Add other tools here
    },
    onReady: () => {
        console.log('Editor.js is ready to use!');
    },
    onChange: () => {
        console.log('Content changed!');
    }
});
```

3. **Save Data**: To save the data, you can use the `save` method:

```js
editor.save().then((outputData) => {
    console.log('Data saved: ', outputData);
}).catch((error) => {
    console.log('Saving failed: ', error);
});
```

## Documentation

> Uploading Soon

## Plugins

> Uploading Soon

## Examples

> Uploading Soon

## Contributing

We welcome contributions to Editor! If you would like to contribute, please follow these steps:

1. Fork the repository. ([Repo](https://github.com/sse-editor/editor))
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please make sure to follow our [Code of Conduct](https://github.com/sse-editor/editor/blob/master/CODE_OF_CONDUCT.md) and Contributing Guidelines.

## License

SSE Editor.js is licensed under the MIT License. See the [LICENSE](https://github.com/sse-editor/editor/blob/master/LICENSE) file for more information.

## Contact

For questions, suggestions, or feedback, please reach out to us:

- [Github](https://github.com/sse-editor/community)

Thank you for using SSE Editor!