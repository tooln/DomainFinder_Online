# DomainFinder Tool

A simple web-based tool that allows you to extract domain names from text, generate domain check commands with `grep "NXDOMAIN"`, and copy the results to the clipboard. It's useful for bulk domain lookup or checking for DNS errors.

## Features

- **Extract Domains**: Paste text containing URLs, and the tool will extract the domains.
- **Generate Domain Commands**: Create shell commands for each domain in the format `host <domain> | grep "NXDOMAIN"`.
- **Copy Links**: Copy all the generated domain links to your clipboard.
- **Copy Commands**: Copy all generated commands to your clipboard.

---

## How to Use

### 1. Extract Domains
- Paste any text containing URLs into the textarea.
- Click the **"Extract Domains"** button to extract valid domains from the text.
- The domains will be displayed as clickable links with a GoDaddy domain search URL.

### 2. Generate Domain Check Commands
- After extracting the domains, click the **"Generate Commands"** button.
- The tool will generate the following format for each domain:
  ```
  host domain1.com | grep "NXDOMAIN"
  host domain2.com | grep "NXDOMAIN"
  host domain3.com | grep "NXDOMAIN"
  ```
- These commands can be used in a shell to check DNS resolution errors (NXDOMAIN).

### 3. Copy Links or Commands to Clipboard
- You can click the **"Copy All Links"** button to copy all extracted links to your clipboard.
- Click the **"Copy Commands"** button to copy all generated `host <domain> | grep "NXDOMAIN"` commands to your clipboard.

---

## Installation

You don't need to install anything to use this tool, as it runs directly in your web browser. Simply:

1. Clone the repository or download the HTML file.
2. Open the `index.html` file in your preferred web browser.

For advanced users, you can set up a local server to run this tool, but it's not required.

---

## Technologies Used

- **HTML5**: Structure and content.
- **CSS3**: Styling for the user interface.
- **JavaScript**: Functionality for extracting domains, generating commands, and handling clipboard operations.


## Contact

For any questions or support, feel free to open an issue or reach out to the project maintainer at [bughuntar@gmail.com](mailto:bughuntar@gmail.com)
