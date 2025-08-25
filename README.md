# Platformatic Runtime API

This is a generated [Platformatic Runtime](https://docs.platformatic.dev/docs/runtime/overview) application.

## Requirements

Platformatic supports macOS, Linux and Windows ([WSL](https://docs.microsoft.com/windows/wsl/) recommended).
You'll need to have [Node.js](https://nodejs.org/) >= v18.8.0 or >= v20.6.0

## Setup

1. Install dependencies:

```bash
npm install
```

## Usage

Run the API with:

```bash
npm start
```

## Adding a Service

Adding a new service to this project is as simple as running `create-platformatic` again, like so:

```
npx create-platformatic
```


## Setup steps
### Vite app setup (Vite 7)
```bash
npm create vite@latest

> npx
> create-vite

│
◇  Project name:
│  app
│
◇  Select a framework:
│  React
│
◇  Select a variant:
│  TypeScript
│
◇  Scaffolding project in /Users/aditya.subramani/dev/app...
│
└  Done. Now run:

  cd app
  npm install
  npm run dev
```

### Platformatic/Watt setup
```bash
Hello Aditya Subramanian, welcome to Watt 2.74.3!
? This folder seems to already contain a Node.js application. Do you want to wrap into Watt? no
? Where would you like to create your project? watt-vite7-repro
? Which package manager do you want to use? npm
? Which kind of service do you want to create? @platformatic/db
✔ Installing @platformatic/db@^2.74.3 using npm ...
? What is the name of the service? server
? What is the connection string? sqlite://./db.sqlite
? Do you want to create default migrations? no
? Do you want to create another service? yes
? Which kind of service do you want to create? @platformatic/vite
✔ Installing @platformatic/vite using npm ...
? What is the name of the service? app
? Where is your application located? ../app
? Do you want to import or copy your application? copy
? Do you want to create another service? yes
? Which kind of service do you want to create? @platformatic/composer
✔ Installing @platformatic/composer@^2.74.3 using npm ...
? What is the name of the service? composer
? Do you want to create another service? no
? Which service should be exposed? composer
? Do you want to use TypeScript? yes
? What port do you want to use? 3042
```
