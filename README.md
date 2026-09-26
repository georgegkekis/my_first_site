# my_first_site

A simple static website created as a web development and deployment exercise.

The site takes text entered by the user and converts it to uppercase.

## Technology

* HTML
* CSS
* Vanilla JavaScript

The site is completely static. All text conversion happens client-side in the browser using JavaScript.

## Prerequisites

Python 3 is used to run a simple local HTTP server.

Check that Python is installed:

```bash
python3 --version
```

## Run Locally

From the project directory, run:

```bash
python3 -m http.server 8000
```

Then access the site at:

http://localhost:8000/

The Python HTTP server serves the files from the current directory. `index.html` is automatically served when accessing the root URL.

## Current Functionality

Enter text into the text box and click **Convert**.

The text is converted to uppercase using JavaScript.

## Project Structure

```text
my_first_site/
├── index.html
└── README.md
```

## TODO

* Create a Playwright test
* Create unit tests
