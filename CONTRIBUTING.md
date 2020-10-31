# Contributing to Keyboard CSS

🙏 I would ❤️ for you to contribute to Keyboard CSS and help make it even better than it is today!

## Developing

Start by cloning the project and installing all dependencies:

```bash
git clone https://github.com/shhdharmen/keyboard-css.git
cd keyboard-css
npm i
```

Run the playground app:

```bash
npm start
```

## Building

Building and publishing is done through semantic-release and github actions. You can check the flow at [release.yml](./.github/workflows/release.yml).

<!-- markdownlint-disable -->
## <a name="rules"></a> Coding Rules
<!-- markdownlint-restore -->

To ensure consistency throughout the source code, keep these rules in mind as you are working:

- All features or bug fixes **must be tested** by one or more specs (unit-tests).
- All public API methods **must be documented**.

<!-- markdownlint-disable -->
## <a name="commit"></a> Commit Message Guidelines
<!-- markdownlint-restore -->

We have very precise rules over how our git commit messages can be formatted. This leads to **more
readable messages** that are easy to follow when looking through the **project history**. But also,
we use the git commit messages to **generate the Inspector changelog**.

### Commit Message Format

Each commit message consists of a **header**, a **body** and a **footer**. The header has a special
format that includes a **type**, a **scope** and a **subject**:

```bash
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

The **header** is mandatory and the **scope** of the header is optional.

Any line of the commit message cannot be longer 100 characters! This allows the message to be easier
to read on GitHub as well as in various git tools.

The footer should contain a [closing reference to an issue](https://help.github.com/articles/closing-issues-via-commit-messages/) if any.

Samples: (even more [samples](https://github.com/angular/angular/commits/master))

```bash
docs(changelog): update changelog to beta.5
```

```bash
fix(release): need to depend on latest rxjs and zone.js

The version in our package.json gets copied to the one we publish, and users need the latest of these.
```
