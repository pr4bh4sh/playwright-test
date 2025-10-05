# Playwright Test Project

This repository contains automated browser tests using [Playwright](https://playwright.dev/).

## Project Structure

- `playwright.config.ts`: Playwright configuration file.
- `tests/`: Directory containing test specs.
- `.github/workflows/playwright.yml`: GitHub Actions workflow for CI.
- `.gitignore`: Files and folders to ignore in git.
- `package.json`: Project dependencies and scripts.

## Getting Started

### Install dependencies

```sh
npm install
```

### Run tests

```sh
npx playwright test
```

### View HTML report

After running tests, open the generated report:

```sh
npx playwright show-report
```

## Continuous Integration

Tests are automatically run on push and pull requests via GitHub Actions ([.github/workflows/playwright.yml](.github/workflows/playwright.yml)).

## Example Test

See [`tests/example.spec.ts`](tests/example.spec.ts) for sample Playwright tests.

## Resources

- [Playwright Documentation](https://playwright.dev/docs/intro)
