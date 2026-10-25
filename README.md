# Neuronode QuikDB

The deployed Node.js backend and static build for Neuronode, an interactive data-structures and algorithms learning project.

Neuronode explains common problems in plain language, provides examples and hints, and supports JavaScript, Python and Java starter code. The current problem set focuses on array and hashing patterns.

## Features

- Plain-language explanations and analogies
- Worked examples and constraints
- Progressive hints
- Public and hidden test cases
- Starter code in JavaScript, Python and Java
- Optional AI-assisted learning routes when a provider key is configured

## Run locally

```bash
npm install
npm run dev
```

For the production command:

```bash
npm start
```

Create a `.env` file if you are testing an AI-powered route:

```env
ANTHROPIC_API_KEY=your_key
```

Do not commit API keys.

## Stack

Node.js, Express, JavaScript and Anthropic's SDK.
