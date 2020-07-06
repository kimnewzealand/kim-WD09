# JAMStacking exercise

This exercise used the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/) to create a build a static website with JavaScript, CSS and HTML.

## Set up Environment

- First install the Gatsby CLI

> The Gatsby CLI tool lets you quickly create new Gatsby-powered sites and run commands for developing Gatsby sites. It is a published npm package.

`npm install -g gatsby-cli`

- Create this new GitHub repo called `kim-WD09`.

- Create a new site from a starter in the terminal:

`gatsby new [SITE_DIRECTORY_NAME] [URL_OF_STARTER_GITHUB_REPO]`

This line creates a new folder called [SITE_DIRECTORY_NAME]  with a boilerplate containing the following file structure: 

.  
├── node_modules  
├── src  
├── .gitignore  
├── .prettierrc  
├── gatsby-browser.js  
├── gatsby-config.js  
├── gatsby-node.js  
├── gatsby-ssr.js  
├── LICENSE  
├── package-lock.json  
├── package.json  
└── README.md  

Alternatively  leave this last URL empty to use the [gatsby-starter-default](https://github.com/gatsbyjs/gatsby-starter-default).

For this exercise I used this [Gatsby starter with Netlify CMS and Bulma styling](https://www.gatsbyjs.org/starters/netlify-templates/gatsby-starter-netlify-cms/).

- Install the [Netlify CLI](https://github.com/netlify/cli) to deploy the site:

`npm install netlify-cli -g`

## Gatsby Website Development


- Change directory to the starter folder

- Enter Gatsby development mode

`gatsby develop`

- View site locally in `http://localhost:8000/`

- Open code editor such as VS Code.

## Gatsby Styling

Some Gatsby sites use traditional `.css` stylesheets or CSS in JS libraries. 

Gatsby also works with component scoped CSS for working with React.

A [CSS Module](https://github.com/css-modules/css-modules) 
>is a CSS file in which all class names and animation names are scoped locally by default.

In this started there are starter components in the folder with `all.sass` stylesheet:

.  
├── src  ── components  

Layout components are found in the pages folder:

.  
├── src  ── pages 

## Site Deployment

A static site can be deployed using [Netlify](https://www.gatsbyjs.org/tutorial/blog-netlify-cms-tutorial/)