# Protractor/CodeceptJS Example Project
Test booking.com site functionality using Protractor and CodeceptJS in style "from user's perspective" for demonstration purposes 

## Prerequisites
* **node.js >= 4.2.6**;
* **NPM >= 4.2.0**

## Installation
1. Install dependencies: 
```
npm install
```

```
npm install -g protractor@^5.0.0
```
2. Install `selenium-standalone server`:
```
npm install selenium-standalone@latest -g 
```
```
selenium-standalone install
```

## Run 

### Integration tests
1. Run npm scripts:

1.1. start `selenium-standalone server`:
```
npm run server
```
1.2. in new bash instance start `codeceptjs` test run:
```
npm run e2e
```