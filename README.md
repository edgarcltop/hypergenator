# Hypergenator

A TypeScript-based React application with AWS Lambda functions, forked from.

## 🚀 Overview

Hypergenator is a modern web application that combines a TypeScript React frontend with serverless AWS Lambda functions, deployed on Netlify. This project maintains full TypeScript support both on the client-side and in the Lambda functions.


## 🛠️ Tech Stack

- **Frontend**: React with TypeScript
- **Backend**: AWS Lambda functions with TypeScript
- **Build Tool**: Create React App
- **Deployment**: Netlify
- **Package Manager**: Yarn
- **Languages**:
  - TypeScript (51.7%)
  - HTML (28.4%)
  - CSS (15.1%)
  - JavaScript (4.8%)

## ⚙️ Prerequisites

- Node.js (version 14 or higher)
- Yarn package manager
- Netlify CLI (optional, for local development)

## 🏃‍♂️ Getting Started

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd hypergenator

yarn install

yarn build

Lambda Development
The Lambda functions are located in the src/lambda directory and are written in TypeScript. They are automatically built and deployed with your Netlify application.
```


## 🌐 Deployment
This project is configured for seamless deployment on Netlify:

The netlify.toml file contains all deployment configuration

Lambda functions are automatically built and deployed

Continuous deployment is set up through Netlify


## 🔧 Configuration
TypeScript Configuration
tsconfig.json - TypeScript compiler options

Supports both client-side and server-side TypeScript

Babel Configuration
.babelrc - Babel transpilation settings

## 📦 Dependencies
Key dependencies include:

React

TypeScript

Netlify Lambda

Babel for transpilation

For a complete list, check the package.json file.

## 🎯 Features
Full TypeScript Support: Type-safe code both frontend and backend

Serverless Architecture: AWS Lambda functions for backend logic

Modern React: Latest React patterns with TypeScript

Netlify Optimized: Pre-configured for Netlify deployment

Local Development: Hot reloading and local Lambda testing

