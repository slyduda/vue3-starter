# vue3-starter
A starter guide for instantiating a Vue3 project.

I am using this to document the steps necessary to getting Vue3 up and running with Tailwind. 

This can be tricky as Vue3 is new and there are still bugs around extensions and support for it is still in its early stages.

To start, make sure that you are running the latest version of Node. At the current time of writing this that is `v15.3.0`.

If you have a version of Node running and you are finding it difficult upgrading, the easiest thing to do is to install a node version manager - either n, nvm, or nvm-windows. These installations are very light weight and should not cause many issues. 

To check to make sure that you are running the latest version of Node use the following command:

````
node --version
````

Also just make sure to update your npm to the latest version with

````
npm update
````

To get started in Vite, all we have to do is run 

````
npm init vite-app <project-name>
````

Then, we just have to go into our project folder, install our dependencies, and then run our app with the following commands

````
cd <project-name>
npm install
npm run dev
````

````
npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9
npx tailwindcss-cli@latest build -o tailwind.css
````
