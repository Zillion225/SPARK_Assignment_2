# Playwright Automation Project 🎭

This repository contains automated end-to-end tests built with [Playwright](https://playwright.dev/).

---

## 🚀 Getting Started

### 1. Prerequisites
- **Node.js**: Version 18 or higher.
- **npm**: Comes with Node.js.

### 2. Installation
Clone the repository and install the dependencies:

```bash
# Clone this repository
git clone <your-repository-url>

# Go into the repository
cd <project-folder-name>

# Install dependencies
npm install

```

### 3. Install Browsers

Playwright requires specific browser binaries to run tests:

```bash
npx playwright install

```

---

## 🛠 Running Tests

You can run your tests using the following commands:

| Description | Command |
| --- | --- |
| **Run all tests (Headless)** | `npx playwright test` |
| **Run tests in UI Mode** | `npx playwright test --ui` |
| **Run in Headed mode** | `npx playwright test --headed` |
| **Run a specific test file** | `npx playwright test tests/example.spec.ts` |
| **Debug tests** | `npx playwright test --debug` |

---

## 📊 Test Reports

After the tests run, an HTML report is generated. To view it, run:

```bash
npx playwright show-report

```

If a test fails, the report will include screenshots, videos, and trace files to help you debug.

---

## 📂 Project Structure

* `tests/`: Directory where all test files are located.
* `playwright.config.ts`: Main configuration file for Playwright.
* `test-results/`: Folder created after tests run to store screenshots/videos.
* `package.json`: Project dependencies and scripts.

---

## 💡 Useful Tips

* **Codegen**: Generate tests by recording your actions: `npx playwright codegen`
* **Tracing**: If a test fails in CI, use the [Playwright Trace Viewer](https://trace.playwright.dev/) to inspect the failure.

```

**Was that easier to copy?** If you still have trouble, let me know and I can try providing it in smaller chunks for you!

```
