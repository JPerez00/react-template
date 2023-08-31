![Site Image](/public/landing-page.png)

# React App Template

This is a very simple React template with TypeScript & Tailwind.CSS installed, just to simplify the process of creating new apps and saving time instead of manually typing all the steps listed below.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Steps followed during the setup:

Created A React App project with TypeScript:

```bash
npx create-react-app my-app --template typescript
```

Or

```bash
yarn create react-app my-app --template typescript
```

Installed tailwindcss via npm, and then ran the init command to generate your tailwind.config.js file:


```bash
npm install -D tailwindcss
```

```bash
npx tailwindcss init
```

Added the paths to all of your template files in your tailwind.config.js file.

```bash
content: ["./src/**/*.{js,jsx,ts,tsx}",],
```

Added the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Available Scripts

In the project directory, you can run:

```bash
npm start
```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

```bash
npm test
```

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

```bash
npm run build
```

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

```bash
npm run eject
```

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
