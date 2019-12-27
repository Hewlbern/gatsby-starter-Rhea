
<h1 align="center">
  Rhea Landing Page
</h1>


Playful and Colorful One-Page portfolio featuring Parallax effects and animations. Using the Gatsby Theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara).


## ✨ Features

- Theme UI-based theming
- react-spring parallax effect
- CSS Animations on Shapes


## 📝 Using and modifying this code

**Important Note:** Please read the guide [Shadowing in Gatsby Themes](https://www.gatsbyjs.org/docs/themes/shadowing/) to understand how to customize the underlying theme!

Have a look at the theme's README and files to see what options are available and how you can shadow the various components including Theme UI. Generally speaking you will want to place your files into `src/@lekoarts/gatsby-theme-cara/` to shadow/override files. The Theme UI config can be configured by shadowing its files in `src/gatsby-plugin-theme-ui/`.

### Changing content

The content of this project is defined in four `.mdx` files inside the theme's `sections` folder. You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx`. This starter has overriden the `intro.mdx` file as an example. Place the other files in the same `src/@lekoarts/gatsby-theme-cara/sections/` folder.

You have to use the `<ProjectCard />` component inside `projects.mdx` to display the cards. Example:

```md

### Change your `static` folder

The `static` folder contains the icons, social media images and robots.txt. Don't forget to change these files, too!

- **For most developers, I recommend starting with the [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to Gatsby's documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Reference Guides_ and _Gatsby API_ sections in the sidebar.