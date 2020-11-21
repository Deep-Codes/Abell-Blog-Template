# Hello, Abell!

{{ Abell.meta.$createdAt.toDateString() }}

A JavaScript based static-site-generator to help you create JSON, Markdown, or static-data based websites with minimal setup in a syntax you almost already know. Built on top of [abelljs/abell-renderer](https://github.com/abelljs/abell-renderer)

**Documentation:**

## 📖 &nbsp; Create Abell Project

```sh
npx create-abell-app my-blog
cd my-blog
npm run dev
```

Check out https://abelljs.org for complete documentation.

### 🕐 Changelog

Changelogs are maintained in [CHANGELOG.md](https://github.com/abelljs/abell/blob/main/CHANGELOG.md)

### 🤗 Local Installation & Contributing

Fork [abelljs/abell](https://github.com/abelljs/abell), Then follow these commands

```sh
git clone https://github.com/:github-username/abell # Get a copy of the codebase in your codebase
cd abell
npm install # Installs all the dependencies
npm link # This command will add the current directory to global packages.
cd examples/main # Directory `examples` has sample abell projects.
abell build # command to build project or
abell serve # command to start dev server.
```

We would love to have contributions! The contributing guidelines along with local setup guide is mentioned in [CONTRIBUTING.md](CONTRIBUTING.md)
