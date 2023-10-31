# Shopping_cart web application using React.js with TypeScript
In this project, I try to implement a fully functional Shopping cart using React.js, typescript, and Bootstrap.


# Features
Add, remove, and update products in the cart.\
Calculate and display the total price.\
A responsive user interface with a modern design.\
Built with React, TypeScript, and Tailwind CSS for maintainability and scalability.
# Demo
![image](https://github.com/KhushbuNavdiwala/Shopping_cart/assets/77695748/31dcd9a4-3a20-4036-a76a-83aabf16ff54)

![image](https://github.com/KhushbuNavdiwala/Shopping_cart/assets/77695748/43694e5e-e3f4-450a-86e0-5058f027ef28)

![image](https://github.com/KhushbuNavdiwala/Shopping_cart/assets/77695748/3370325b-2523-444f-a642-00c5ca477a6b)



# React + TypeScript + Vite

## Available Scripts

In the project directory, you can run:

### `npm run dev`


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
