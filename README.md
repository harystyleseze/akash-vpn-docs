# 📚 Akash VPN Docs

This is the official documentation site for **Akash VPN**, built with [Docusaurus](https://docusaurus.io/) — a modern static site generator.

> Akash VPN is a decentralized VPN powered by the [Akash Network](https://akash.network). Private, censorship-resistant, and crypto-friendly.

---

## 🚀 Getting Started

### 📦 Installation

Install project dependencies:

```bash
yarn
````

### 🛠️ Local Development

To start the development server:

```bash
yarn start
```

This opens a browser at `http://localhost:3000`. Edits to Markdown files or components will hot-reload automatically.

---

## 🏗️ Building the Site

Generate the static site into the `build/` directory:

```bash
yarn build
```

You can serve it locally or deploy it using Docker or GitHub Pages.

---

## ☁️ Deployment Options

### 🐳 Deploy to Akash (recommended)

Build a Docker image and deploy the site using Akash's decentralized compute network.

You can use a `Dockerfile` and `deploy.yaml` to containerize and push to an Akash provider.

Example:

```bash
docker build -t akash-vpn-docs .
```

### 🐙 GitHub Pages

For GitHub Pages deployment:

**Using SSH:**

```bash
USE_SSH=true yarn deploy
```

**Without SSH:**

```bash
GIT_USER=<your-github-username> yarn deploy
```

This deploys to the `gh-pages` branch.

---

## 📁 Project Structure

* `docs/` - Markdown files for docs (e.g. `faq.md`, `intro.md`)
* `src/` - Custom React components and CSS
* `sidebars.ts` - Sidebar structure for docs
* `docusaurus.config.ts` - Global site config

---

## 🙌 Contributing

We welcome community contributions!

1. Fork the repo
2. Make changes in a new branch
3. Open a Pull Request with a clear description

See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for full guidelines.

---

## 📬 Support

* [Akash Discord](https://discord.gg/JKGjJUHB)
* [Akash Network Website](https://akash.network)

---

## 🛡️ License

MIT
