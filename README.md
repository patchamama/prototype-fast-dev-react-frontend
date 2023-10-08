# Prototype of frontend (react) to a fast develop

## Develop

### Install React

```
npm create vite@latest . --template react
npm install
```

#### The application is started as follows

```
npm run dev
```

Runs the app in the development mode.\
Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

_If there is errors with modules, maybe reinstall all the modules: `rm -rf node_modules/ && npm i`_

### Install extra libraries

#### To fetch data can be used axios

```
npm install axios
```

#### To validate type of data in JS (See more details)[https://fullstackopen.com/en/part5/props_children_and_proptypes#prop-types]

```
npm install prop-types
```

#### To ESlint (See more details)[https://fullstackopen.com/en/part5/props_children_and_proptypes#e-slint]

```
npm install --save-dev eslint-plugin-jest
```

#### To Testing (See more details)[https://fullstackopen.com/en/part5/testing_react_apps#rendering-the-component-for-tests]

```
npm install --save-dev @testing-library/react @testing-library/jest-dom jest-environment-jsdom @babel/preset-env @babel/preset-react      @testing-library/user-event
```

#### End to end testing with Cypress (See more details)[https://fullstackopen.com/en/part5/end_to_end_testing#cypress]

```
npm install --save-dev cypress
npm install eslint-plugin-cypress --save-dev
```

_Execute the test with: `npm run cypress:open`_

#### Available Scripts

In the project directory, you can run:

```
npm test
```

## Deployment

```
npm run build
```
