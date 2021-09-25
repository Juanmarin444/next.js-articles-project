# Next.js Article Project

## Next.js

- Next.js is a React frontend development web framework created by Vercel.
- It enables functionality such as server-side rendering and static site generation

## Server-side rendering

- Next.js allows the first page load to be rendered by the server
- It is great for SEO and performance

## Benefits

- Super easy page routing
- API routes
- Out of the box typescript and sass
- Static site generation using the script (next export)
- Easy deployment

## Generating a new project

- You can generate new projects by using ( npx create-next-app name-of-your-app )
- Things like web-pack and babel are still being used in the background

## Public folder

- Everything in the public folder is accessible from the browser

## Styles folder

- Global CSS file is global to the entire project
- You can also have specific CSS files for each of your components or pages

## Components folder

- Creating a components folder will be to store components that are not intended to be pages
- Components like buttons, navbars or headers
- It's also convention for all pages to be lowercase and components to be uppercase

## Custom Documents

- A custom `Document` is commonly used to augment your application's `<html>` and `<body>` tags.
- This is necessary because Next.js pages skip the definition of the surrounding document's markup.

## Data Fetching

- Next.js provides **special functions** we can use to **fetch data** and **pass it into** our
  page as props
- The functions can be added above or below your components
- There are three different methods you can use to fetch data
  - getStaticProps: Allows to fetch at build time
  - getServerSideProps: Fetches data on every request (It can be a little slower)
  - getStaticPaths: Dynamically generates paths based on the data being fetched
