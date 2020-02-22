Pubnotes
========

This repo contains notes and thoughts on software, design, and life. It's a public repo of my thoughts on a variety of subjects that didn't make sense for a full blown article or post either because there's not enough complexity or the inspiration is close enough to copyrighted work that it would feel cheap to republish it as my own work.

Table of Contents
-----------------

- [Home](./README.md)
- [Software Development Philosophy](./software-development-philosophy.md)

Instructions for Making Additions
---------------------------------

Install `remark-lint` for linting and `markserv` for serving:

```bash
npm install
```

### Remark-Lint

This will run a bunch of linter rules over markdown files in the directory

```bash
npm run lint
```

### Markserv

To run the `markserv` CLI:

```bash
# Default
npm run markserv

# Pass arguments:
npm run markserv -- [arguments]
```

To run `readme` and view the README.md file in this directory:

```bash
npm run readme
```

For more details about Markserv: [](https://github.com/markserv/markserv)
