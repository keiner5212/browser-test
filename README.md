# Browser Test

This project aims to test web pages using Playwright in various browsers easily, allowing you to check if your page is compatible with the latest browsers. It provides a straightforward setup and commands to run tests in Chrome, Firefox, and Safari.

## Why is Browser Compatibility Important?

Browser compatibility ensures that your web application works seamlessly across different web browsers. Users may access your website using various browsers, and inconsistencies or errors in one browser can lead to a poor user experience and even loss of users. By testing your web application across multiple browsers, you can identify and fix compatibility issues, ensuring a smooth and consistent experience for all users.

## Features

-   **Cross-browser testing**: Easily test your web application in Chrome, Firefox, and Safari.
-   **Simple setup**: Quickly install dependencies and run tests with minimal configuration.
-   **Headed mode**: Tests run in headed mode, allowing you to see the browser interactions.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

-   [Node.js](https://nodejs.org/) (v14 or higher recommended)
-   [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/keiner5212/browser-test.git
    cd browser-test
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

### Running Tests

You can run tests in different browsers using the provided npm scripts.

#### Test in Chrome

```bash
npm run test:chrome
```

#### Test in Firefox

```bash
npm run test:firefox
```

#### Test in Safari

```bash
npm run test:safari
```

### Test

`note`: Check the test filein the `tests` folder to change the URL to whatever you want to test.

## Contributing

Contributions are welcome! If you have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgements

-   [Playwright](https://playwright.dev/) for providing a robust framework for browser automation.
