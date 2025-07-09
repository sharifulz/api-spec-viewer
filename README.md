# API Spec Viewer

A simple and intuitive developer-friendly UI to view and explore your API specification using [Stoplight Elements](https://docs.stoplight.io/docs/elements/b074dc47b2826-elements-configuration-options).

This project serves your OpenAPI specification via a clean, interactive web interface built using HTML and Stoplight's web components.

## 🔗 Live Demo

You can access the deployed version here:  
➡️ https://sharifulz.github.io/api-spec-viewer

## 🚀 Features

- Developer-friendly UI for OpenAPI / Swagger spec
- No backend required — fully static and frontend-only
- Responsive and lightweight
- Supports both `.json` and `.yaml` API spec files
- Powered by Stoplight Elements web components

## 📁 Project Structure

```
api-spec-viewer/
├── index.html             # Main HTML file that loads the API viewer
├── api-spec.json          # Your OpenAPI spec file (can also be YAML)
├── .github/workflows/     # Optional GitHub Actions deployment setup
└── README.txt             # Project documentation
```

## Genreate HASH password (SHA-256) from here:
https://www.onlinewebtoolkit.com/hash-generator

## ⚙️ Configuration

This project uses Stoplight Elements' `<elements-api>` component. You can configure it in the `index.html` like this:

```html
<elements-api
  apiDescriptionDocument="api-spec.json"
  router="hash"
/>
```

For more configuration options, see the official Stoplight Elements docs:  
➡️ https://docs.stoplight.io/docs/elements/b074dc47b2826-elements-configuration-options

## 🛠 Deployment

This project is deployed using **GitHub Pages** from the `main` branch. Make sure your `index.html` and `api-spec.json` are in the root directory or configured correctly in `index.html`.

Steps:
1. Commit and push your changes to the repository.
2. Enable GitHub Pages from the repository settings (`main` branch → root).
3. Visit the live URL to see your API viewer.

## 🧪 Example Spec

You can replace `api-spec.json` with your own OpenAPI specification. Supported formats:
- JSON (`.json`)
- YAML (`.yaml`)

---

Feel free to fork or clone this project and customize it for your own API documentation needs.

## 📜 License

This project is open-sourced under the [MIT License](LICENSE).
