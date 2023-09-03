# BAP SDK

A comprehensive NodeJS + React Native SDK, empowering developers to efficiently create Beckn-enabled consumer-facing applications (BAPs) using a streamlined boilerplate codebase. The SDK takes care of Beckn's backend code, allowing developers to prioritize UI/UX enhancements and simplify the overall development process.

**Application:** The SDK not only manages the backend code but also offers a pre-designed UI template. This eliminates the need for users to start their applications from scratch. They can make modifications to the provided UI, while the SDK handles the backend intricacies. This approach lets developers focus sharply on refining UI and UX, thus streamlining the development process.

## Features
- CLI based tool for initialisation 
- Boilerplate UI Templates
- Backend SDK Code
- Search use case for 2 domains
- Sorting as per rating use case

## Tech Stack
**Client:** React Native, Expo, Axios

**Server:** Node.js, Beckn Protocol

**Tools:** Postman

## Folder Structure

```bash
├── templates/
│   ├── BAP-Education/   # Boilerplate for education
│   ├── BAP-Mobility/    # Boilerplate for mobility
│   └── BAP-Retail/      # Boilerplate for retail
├── index.js             # sdk entry point for initialisation 
├── outputDirectory.js   # sdk output file
└── package.json
```

## Project Architecture
The workflow of the project goes as

## Run Locally

**Clone the project**
```bash
  git clone https://github.com/sandeepB3/bap-sdk.git
```

**Open bap-sdk folder in your terminal and run**
```bash
  sudo npm install -g
```

**Open a new folder in which you want to create your project and run**
```bash
  bap-sdk
```
Choose the required prompts provided by the CLI tool. This will setup a template project in your current folder, which can be modified by users.
