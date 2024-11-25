
# Email Template

This project is a MailChimp-based email template built using [Eleventy](https://www.11ty.dev/) (11ty) and the Nunjucks templating language. Eleventy is used as a static site generator to compile HTML, making it easy to build and update this template.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Styling](#styling)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed.

## Installation

1. Clone this repository:
```bash
git clone https://github.com/fmvilas/mailing-template.git
```

2. Install dependencies:
```bash
npm install
```

## Usage

To develop, run the following command to start the Eleventy server:

```bash
npm  start
```

Eleventy will start a local server and automatically rebuild when files are changed. You can view your template at `http://localhost:8080`.

The compiled HTML template can be found at `src/_site/`. This folder can be zipped and uploaded as a MailChimp template using MailChimp's editor dashboard.

## Styling

Inline CSS is encouraged and common in this email template, as it works better between different email clients. Common CSS is placed in the `src/_includes/styles/css.njk` file and it gets included in the `head` of the email inside a `<style>` tag. MailChimp's editor will review this CSS later in the creation process and inline as much CSS rules as possible.

## Contributing

Feel free to open issues or submit pull requests. We welcome contributions to improve template quality and functionality.

## License

Distributed under the AGPLv3 License. See `LICENSE.md` for more information.
