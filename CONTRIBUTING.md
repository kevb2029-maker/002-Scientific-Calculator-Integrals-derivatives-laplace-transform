# Contributing

Thanks for taking an interest in improving this project. All contributions are welcome.

## Getting started

```bash
git clone https://github.com/kevb2029-maker/002-Scientific-Calculator-Integrals-derivatives-laplace-transform.git
cd 002-Scientific-Calculator-Integrals-derivatives-laplace-transform
open index.html
```

No build step. Edit `index.html` and refresh the browser.

## Ways to contribute

- **Bug reports** — open an issue with steps to reproduce, browser, and OS.
- **New Laplace patterns** — add entries to `lpTable` and the `laplaceOf()` / `invLaplaceOf()` functions in `index.html`.
- **New functions** — add buttons to the Functions or Symbols pad and wire them to `ins()` or `fn()`.
- **UI / accessibility** — keyboard navigation, screen reader support, mobile layout.
- **Tests** — there are none yet; a small test harness for the symbolic functions would be valuable.

## Pull request process

1. Fork the repo and create a branch: `git checkout -b feature/my-change`
2. Make your changes in `index.html` (or add new files if needed).
3. Test in at least one modern browser (Chrome, Firefox, or Safari).
4. Open a pull request with a clear description of what changed and why.

## Code style

- The project is intentionally a single HTML file. Keep it that way unless there is a strong reason to split.
- No build tools, no frameworks, no transpilation.
- Prefer small, focused changes. One feature or fix per PR.
- Comment only when the *why* is non-obvious.

## Reporting issues

Open a GitHub issue and include:
- What you expected to happen
- What actually happened
- The exact expression that caused the problem (if applicable)
- Browser and OS version

## License

By contributing you agree that your changes will be released under the [MIT License](LICENSE).
