# Tailwind Vue

## Starting a project and adding Tailwind

- Spun up a basic Vue 3 project which included PostCSS by default by running `vue create hello-world`

- Added the necessary packages by using `npm install tailwindcss postcss autoprefixer --save-dev`

- Followed the Tailwind guidelines and created a `postcss.config.js` file with the necessary information

- Created a `tailwind.css` file in `assets` and added `tailwind base, components and utilities`

- Ran `npx tailwindcss init` to create the tailwind config file

- Imported Tailwind into `App.vue`

- Ran `npm run serve`

- Everything is shit

- Had to run `npm uninstall tailwindcss postcss autoprefixer` and `npm install tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9` because Vue 3 doesn't have it's shit together

- It worked!
