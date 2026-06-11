# ChitMeo.DevTool

A collection of useful developer tools built with .NET.

## Overview

**ChitMeo.DevTool** is an open-source toolbox designed for developers and IT professionals. It provides a set of lightweight, offline-friendly utilities commonly used during software development.

The goal of this project is not only to create a practical toolbox but also to explore modern .NET application architecture, modular design, and plugin-based extensibility.

---

## Features

### JWT Tool (Initial Release)

Inspired by jwt.io.

#### Decode JWT

* Parse JWT Header
* Parse JWT Payload
* Display claims in formatted JSON
* Validate JWT structure

#### Encode JWT

* Create JWT tokens
* Support custom payload
* Support custom header
* Sign using HMAC algorithms

  * HS256
  * HS384
  * HS512

#### Validation

* Verify token signature
* Display expiration information
* Display issued-at information

---

## Roadmap

### Phase 1

* [x] JWT Decoder
* [x] JWT Encoder
* [ ] JWT Signature Verification

### Phase 2

* [ ] GUID Generator
* [ ] Base64 Encoder / Decoder
* [ ] JSON Formatter
* [ ] Hash Generator

### Phase 3

* [ ] Regex Tester
* [ ] Timestamp Converter
* [ ] URL Encoder / Decoder
* [ ] SQL Formatter

### Phase 4

* [ ] Plugin Architecture
* [ ] Dynamic Tool Loading
* [ ] Extension SDK

### Phase 5

Advanced Developer Tools

* [ ] Redis Explorer
* [ ] MongoDB ObjectId Parser
* [ ] HTTP Request Builder
* [ ] REST API Tester
* [ ] S3 Browser

---

## Technology Stack

* .NET 9
* C#
* Blazor (planned)
* Dependency Injection
* Modular Architecture

---

## Project Structure

```text
src/
├── ChitMeo.DevTool
├── ChitMeo.DevTool.Core
├── ChitMeo.DevTool.Shared
└── ChitMeo.DevTool.Tools.Jwt
```

The project is designed to support modular tools in the future.

Each tool can be developed independently and registered through a common contract.

---

## Screenshots

Coming soon.

---

## Running Locally

```bash
git clone https://github.com/chitmeo/devtool.git

cd devtool

dotnet restore

dotnet run
```

---

## Why This Project?

Most developers frequently use online tools such as:

* jwt.io
* jsonformatter.org
* regex101.com
* base64decode.org

This project aims to bring these utilities together into a single .NET application while serving as a learning platform for:

* Clean Architecture
* Modular Monolith
* Plugin Architecture
* Dependency Injection
* Reflection
* Cross-platform UI Development

---

## Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to open an issue or submit a pull request.

---

## License

MIT License
