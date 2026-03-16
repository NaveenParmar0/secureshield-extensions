# SecureShield Extensions 🛡️

[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![CodeQL](https://github.com/NaveenParmar0/secureshield-extensions/actions/workflows/codeql.yml/badge.svg)](https://github.com/NaveenParmar0/secureshield-extensions/actions/workflows/codeql.yml)

> **Developed by:** Naveen Parmar | [GitHub: NaveenParmar0](https://github.com/NaveenParmar0)

Hi! 👋 Welcome to **SecureShield Extensions**. I developed this project from scratch as my core cybersecurity engineering portfolio project. 

As a passionate fresher in cybersecurity, I wanted to build a modular, extensible framework that can perform robust Dynamic Application Security Testing (DAST). I wrote this suite of Java-based security add-ons to automate the detection of common web vulnerabilities. 

## 🚀 Key Features

- 🔍 **Active & Passive Scanners** — I engineered custom scan rules (`ascanrules`, `pscanrules`) to detect vulnerabilities like XSS, SQLi, and misconfigurations by analyzing HTTP requests/responses.
- 🕷️ **Spidering Engine** — Built an automated crawling application to map out target endpoints thoroughly.
- 🔐 **Authentication Flows** — Wrote modules to handle session management and automated auth testing.
- 🌐 **Modern API Testing** — Added support for scanning OpenAPI, GraphQL, gRPC, and SOAP endpoints.
- 🧪 **Fuzzing Capabilities** — Integrated advanced fuzzing mechanics with custom payload processing.
- 📊 **Automated Reporting** — Designed a reporting module to generate comprehensive findings summaries.

## 💻 Tech Stack
- **Language:** Java 17
- **Build Tool:** Gradle
- **Architecture:** Modular Add-on System
- **Concepts:** AST Parsing, Heuristic Analysis, Multi-threading, Network Interception

## ⚙️ Getting Started

I designed each security scanning module as its own project under the `addOns` directory.

Clone this repository and build the modules using Gradle:

```bash
git clone https://github.com/NaveenParmar0/secureshield-extensions.git
cd secureshield-extensions
./gradlew :addOns:<addon-name>:compileJava
```

Replace `<addon-name>` with the module you want to test (e.g., `ascanrules`, `spider`, `graphql`).

## Building

The add-ons are built with [Gradle], each add-on has its own project which is located under the `addOns` project/directory.

```bash
# Build a specific add-on
./gradlew :addOns:ascanrules:compileJava

# Run unit tests for a specific add-on
./gradlew :addOns:ascanrules:test
```

[Gradle]: https://gradle.org/
