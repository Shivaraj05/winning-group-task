# cypress-project
A sample cypress project

## install all dependencies from the root directory
npm install

## Format the prject - 
`npm run format`

## To run tests -
`npm run test`

## I have used `cypress-parallel` package to run tests in parallel - 
`npm run test:parallel`

## Report generator -
I have used `mochawesome,mochawesome-merge,mochawesome-report-generator` for generating reports and merging all different spec report into single one.
After tests are run the html reports are generated at `cypress/reports/mochareports`

## Running in Selenium Moon session -
I tried this to follow the instruction given at `https://aerokube.com/moon/latest/#cypress`, but could not achieve fully.
