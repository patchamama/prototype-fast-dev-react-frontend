# Prototype of frontend (react) to a fast develop

## Develop

### Install React

```
npm create vite@latest . --template react
npm install
```

### The application is started as follows

```
npm run dev
```

Runs the app in the development mode.\
Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### If there is errors with modules, maybe reinstall all the modules

```
rm -rf node_modules/ && npm i
```

### To de fetch data can be used axios

```
npm install axios
```

### Validate type of data in JS (See more details)[https://fullstackopen.com/en/part5/props_children_and_proptypes#prop-types]

```
npm install prop-types
```

### ESlint (See more details)[https://fullstackopen.com/en/part5/props_children_and_proptypes#e-slint]

```
npm install --save-dev eslint-plugin-jest
```

#### Available Scripts

In the project directory, you can run:

```
npm test
```

## Deployment

```
npm run build
```
