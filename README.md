![](https://github.com/efrencodes/efrencodes/blob/master/assets/repos/next-typescript-base.png)

### 🎯 Used technologies:

-   Next.JS
-   TypeScript
-   Eslint
-   Prettier
-   [Module CSS](https://nextjs.org/docs/basic-features/built-in-css-support)
-   [Config of Typescript](https://github.com/efrencodes/next-typescript-base/blob/master/.eslintrc.js)
-   [Config of Prettier](https://github.com/efrencodes/next-typescript-base/blob/master/prettier.config.js)

### ⚙️ How To Use

To clone and run this application, you'll need **GIT** and **NodeJS** (which comes with npm) installed on your computer. From your command line:

```bash
  # Clone this repository
  $ git clone https://github.com/efrencodes/next-typescript-base.git

  # Go into the repository
  $ cd next-typescript-base

  # Install dependencies
  $ npm install

  # Run the app
  $ npm run start

  # Open in browser
  # http://localhost:3005/
```

### 🎨 Format code with Prettier

```bash
  # Format code
  $ npm run format

  # output
> next-typescript-base@0.1.0 format
> prettier --write '{*.tsx,*.js,*.css,pages/**/*,styles/**/*.{tsx,css,js}}'

pages/_app.tsx 14ms
pages/api/hello.js 10ms
pages/index.tsx 16ms
styles/globals.css 17ms
styles/Home.module.css 10ms
```

### 🚩 Lint project

```bash
  # Lint
  $ npm run lint
```

### 🚀 Deployment

To deploy this project run

```bash
  # Build
  $ npm run build
```
