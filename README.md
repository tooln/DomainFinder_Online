# DomainHarvester 🚀

**DomainHarvester** is a powerful bug bounty tool designed to extract domains from text, generate links to verify domain availability, and produce commands to identify unregistered domains. Whether you're a bug bounty hunter, penetration tester, or cybersecurity enthusiast, DomainHarvester streamlines your workflow and helps you uncover valuable targets.

---

## Features ✨

- **Domain Extraction**: Automatically identifies and extracts domains from any given text.
- **Link Generation**: Creates direct links to check domain availability on platforms like GoDaddy.
- **Command Generation**: Generates commands to check domain registration status (e.g., `host` commands).
- **User-Friendly Interface**: Simple and intuitive design for seamless usage.
- **Cross-Platform**: Works on any device with a modern web browser.

---

## How It Works 🛠️

1. **Paste Your Text**: Input any text containing domains (e.g., HTTP responses, logs, or reports).
2. **Extract Domains**: Click "Extract Domains" to identify all valid domains.
3. **Generate Links**: Automatically generates links to check domain availability.
4. **Generate Commands**: Produces commands to verify domain registration status.
5. **Copy Results**: Easily copy extracted domains, links, or commands to your clipboard.

---

## Installation 💻

DomainHarvester is a web-based tool, so no installation is required! Simply open the tool in your browser and start using it.

### Local Setup (Optional)
If you want to run DomainHarvester locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DomainHarvester.git
   ```
2. Navigate to the project directory:
   ```bash
   cd DomainHarvester
   ```
3. Open `index.html` in your browser:
   ```bash
   open index.html  # macOS/Linux
   start index.html # Windows
   ```

---

## Usage 🚦

1. **Input Text**: Paste your text into the input box.
2. **Extract Domains**: Click the "Extract Domains" button to identify domains.
3. **Copy Links**: Use the "Copy All Links" button to copy GoDaddy links for domain availability checks.
4. **Generate Commands**: Click "Generate Commands" to create `host` commands for checking domain registration.
5. **Copy Commands**: Use the "Copy Commands" button to copy the generated commands to your clipboard.

---

## Example 🖥️

### Input Text:
```
Check these domains: dev-790973.oktapreview.com, *.oktacdn.com, login.okta.com, https://POLICYHUB-W16.policyhubadfs.com.
```

### Extracted Domains:
- oktapreview.com
- oktacdn.com
- login.okta.com
- policyhubadfs.com

### Generated Links:
- https://www.godaddy.com/en-in/domainsearch/find?domainToCheck=oktapreview.com
- https://www.godaddy.com/en-in/domainsearch/find?domainToCheck=oktacdn.com
- https://www.godaddy.com/en-in/domainsearch/find?domainToCheck=login.okta.com
- https://www.godaddy.com/en-in/domainsearch/find?domainToCheck=policyhubadfs.com

### Generated Commands:
```bash
host oktapreview.com | grep "NXDOMAIN"
host oktacdn.com | grep "NXDOMAIN"
host login.okta.com | grep "NXDOMAIN"
host policyhubadfs.com | grep "NXDOMAIN"
```

---

## Contributing 🤝

We welcome contributions! If you'd like to improve DomainHarvester, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## Credits 🙌

- Developed by **Professor the Hunter**.
- Inspired by the needs of bug bounty hunters and cybersecurity professionals.
- Powered by **Professor Software Solutions**.

---

## Support 💬

If you have any questions, suggestions, or issues, feel free to open an issue on GitHub or contact us at **bughuntar@gmail.com**.

---

Happy Hunting! 🎯
```

---

### Key Features of the README:
1. **Professional and Clean Layout**: Easy to read and navigate.
2. **Detailed Sections**: Covers features, installation, usage, examples, and more.
3. **Contributing Guide**: Encourages community involvement.
4. **License and Credits**: Adds professionalism and transparency.
5. **Support Section**: Provides a way for users to reach out for help.
