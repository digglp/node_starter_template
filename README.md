

# My TypeScript Node Console App

Scaffolding for a basic node app with typescript, eslint, jest

## Prerequisites

Before you get started, ensure you have the following installed on your machine:

- Node.js: [Download and Install Node.js](https://nodejs.org/)

## Getting Started

1. Clone this repository (or download and extract the ZIP file):

`
   git clone https://github.com/digglp/node_starter_template.git
   cd node_starter_template/source
`
2. Install project dependencies

`
   npm install
`

3. Execute the typescript code

`
   npx ts-node src/application/ConsoleApplication.ts
`

4. Run tests

`
   npm run test
`

5. Compile the typescript

`
   npm run build
`

This will do a lint check, remove the old build, copy any non ts-files, and use tsc to build the javascript in the dist folder.