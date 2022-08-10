
<h1 align="center">
  malaa website
</h1>

## 🚀 Quick start

1.  **Create a Gatsby site.**


    Create a new Gatsby site using the hello-world starter 

    ```shell
    $ gatsby new Project_Name https://github.com/gatsbyjs/gatsby-starter-hello-world

    $cd Project_Name/
    ```
1.  **Install Tailwind CSS.**

    Using npm, install tailwindcss and its peer dependencies, as well as gatsby-plugin-postcss. 

    ```shell
    $ npm install -D tailwindcss postcss autoprefixer gatsby-plugin-postcss
    #run the init command to generate both
    $ npx tailwindcss init -p
    ```
1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    gatsby develop
    ```


## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a the project.

    .
    ├── src
       ├── components
          ├── common
              ├── Navigation.js
              ├── Footer.js
          ├── layouts
              ├── Home.js
              ├── About.js
              ├── Blog.js
          ├── container
        ├── pages
          ├── index.js
          ├── 404.js
          ├── 500.js
        ├── assets 
          ├── styles
             ├── global.css
          ├── icons
          ├── images
          ├── fonts
    ├── gatsby-config.js
    ├── tailwind.config.js
    

1.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

1.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.com/docs/reference/config-files/gatsby-config/) for more detail).

1.  **`tailwind.config.js`**: This file is used to configure the generated classes by Tailwind. We already configured the Tailwind using the config file to provide sensible defaults for a web app.






