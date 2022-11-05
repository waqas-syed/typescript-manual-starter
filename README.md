# typescript-manual-starter
Boilerplate for manually setting up a NodeJS project that uses TypeScript.

TypeScript code is run directly without waiting for it to be compiled using `ts-node` and changes are watched by `nodemon`.

## Run project for local development
Starts ts-node which allows us to to run TypeScript directly without having to compile it. This process icalled cold Reloading.
`npm run start:dev`

## Build for production
Clean the destination build folder `build` and emit new code.
`npm run build`

## Production Startup Command
This will clean the `build` folder, compile the code to JS for production and run the Javascript compiled from TypeScript.
`npm run start`


Credit: https://khalilstemmler.com/blogs/typescript/node-starter-project/