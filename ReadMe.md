# Hackernews example code

## Dev instructions

- pull repo
- npm install
- npm run dev

## Deployment instructions

Easiest way to deploy the code base is through [Zeit's Now ](https://zeit.co)

- npm i -g now@latest
- make sure your in the project dir and run "now" in the terminal and this will take you through the steps needed

I have already hosted the project [here](https://hackernews-test.madebyjonny.now.sh)

### Manual instructions

Push code to destination and run, or if you have a CI process these steps will need to be taken.

- npm install
- npm run build
- npm run start

## Tests

#### Run unit tests

- npm run test

#### Run coverage

- npm run test:coverage
