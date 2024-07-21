---
id: installing-a-dependency
title: Installing a Dependency
---

The generated project includes React and ReactDOM as dependencies. It also includes a set of scripts used by Create React App as a development dependency. You may install other dependencies (for example, React Router) with `npm`:

```sh
npx create-react-app ecommerce-website
cd ecommerce-website
npm start
```

Alternatively you may use `yarn`:

```sh
yarn add react-router-dom
```

This works for any library, not only `react-router-dom`.
