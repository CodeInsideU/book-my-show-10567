# Book-My-Show-10567

Built clone of BookMyShow ticket booking site using Javascript, React.js, Node.js and MovieDB API.
This website is used to purchase movie tickets. It displays the most recent theatrical releases and allows users to purchase tickets.

## API Reference

#### Get all items

```http
  GET /movie
```

| Parameter | Type     | Description                      |
| :-------- | :------- | :------------------------------- |
| `api_key` | `string` | 43f249322f1bb49e1dafd4e1d14d2b72 |

#### Get item

```http
  GET /movie/popular
```

| Parameter | Type     | Description |
| :-------- | :------- | :---------- |
| `id`      | `string` | popular     |

```http
  GET /movie/top_rated
```

| Parameter | Type     | Description |
| :-------- | :------- | :---------- |
| `id`      | `string` | top_rated   |

```http
  GET /movie/upcoming
```

| Parameter | Type     | Description |
| :-------- | :------- | :---------- |
| `id`      | `string` | upcoming    |

```http
  GET /movie/{movie_id}/credits
```

| Parameter | Type     | Description        |
| :-------- | :------- | :----------------- |
| `id`      | `string` | {movie_id}/credits |

```http
  GET /movie/{movie_id}/similar
```

| Parameter | Type     | Description        |
| :-------- | :------- | :----------------- |
| `id`      | `string` | {movie_id}/similar |

```http
  GET /movie/{movie_id}/recommendations
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id`      | `string` | {movie_id}/recommendations |

```http
  GET /movie/{movie_id}
```

| Parameter | Type     | Description       |
| :-------- | :------- | :---------------- |
| `id`      | `string` | /movie/{movie_id} |

### API Documentation link

https://developers.themoviedb.org/3/getting-started/introduction

## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```

Install create-react-app with npx

```bash
  npx install create-react-app
```

Install react-router-dom with npm

```bash
  npm install react-router-dom
```

Install tailwindcss via npm, and create your tailwind.config.js file.

```bash
  npm install -D tailwindcss
  npx tailwindcss init
```

Add the paths to all of your template files in your tailwind.config.js file.

```bash
  /** @type {import('tailwindcss').Config} */
  module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.

```bash
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
}
```

## Appendix

### Components

Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML.

- Cast_Component
- EntertainmentCard_Component
- Arrow_Component
- HeroCarousel_Component
- MovieHero_Component
- MovieInfo_Component
- MovieNavbar_Component
- Navbar_Component
- Payment_Component
- PlayFilters_Component
- Poster_Component
- PosterSlider_Component

### Context

Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

- Movie_Context

### Layout

The Layout component is a component that you create to provide common elements across all of your pages.

- Default.layout
- Movie.layout

### Pages

A page component uses other components to assemble the page like lego blocks.

- Home_page
- Movie_page
- Play_page

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
