# STRELOK

A reconnaissance automation toolkit built for bug bounty hunters and pentesters. STRELOK combines battle-tested CLI tools with AI analysis to make your recon process faster and more effective.

## What is this?

STRELOK automates your recon workflow by chaining together tools like Subfinder, Httprobe, Httpx, and Nuclei. Once the data is collected, a conversational AI helps analyze the results and suggests what to try next.

## Features

- **Automation Pipeline**: Runs subdomain discovery, service probing, HTTP analysis, and vuln scanning in sequence
- **AI Analysis**: Uses LLMs to help make sense of your scan results
- **Modular Design**: Each tool runs in its own microservice for easy maintenance and scaling
- **Clean UI**: Simple frontend built with React and Tailwind
- **Background Tasks**: Celery and Redis handle the heavy lifting in the background

## Current Status

This is a work in progress! I'm actively developing the core functionality and refining the architecture. Expect things to change as the project evolves.

---

*Feedback and contributions welcome!*
