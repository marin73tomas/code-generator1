# Install & Start

#### Install nodejs

First, check if you already have node and npm installed. To check if you have Node.js installed, run this command in your terminal:

```bash
node -v
```

To confirm that you have npm installed you can run this command in your terminal:

```bash
npm -v
```

If node is not installed on your machine, you can go to the official nodejs.org website, and choose the version depending on your operating system:

- <a href="https://nodejs.org/en/download/" target="_blank">Install node.js and npm on Windows, Linux or Mac OSX</a>

#### Check the npm version

npm is a separate project from Node.js, and tends to update more frequently. As a result, even if you’ve just downloaded Node.js (and therefore npm), you’ll probably need to update your npm. Luckily, npm knows how to update itself! To update your npm, type this into your terminal:

```bash
npm install --global npm@latest
```

### Features

## Build prod

```bash
yarn build
```

#### Installing Yarn (recommended)

i personally recommend Yarn as we it is a better package manager than npm. If you want to use Yarn, keep in mind that you should not mix the 2. You either use Yarn or Npm in a project, never both.

```bash
npm install --global yarn
```

## 📦 Dependencies installation

To configure and start installing project dependencies, run one of the following
commands:

```bash
# using npm v7
npm install --legacy-peer-deps

# using yarn
yarn install
```

## 🔃 Run a development server

To start the development server, run one of the following commands:

```bash
# using npm v7
npm run dev

# using yarn
yarn dev
```

