Hugo-Glitch Template
====================

This project is a [Hugo](https://gohugo.io/) template for [Glitch](https://glitch.com/).

>`Hugo`: a framework for creating blogs, portfolios, and product sites.
>`Glitch`: a platform for quickly building and hosting web apps. 

This project lets you quickly set up a blog. Checkout the live demo of this project [here](https://hugo-template.glitch.me/)

How to Use
----------

This project is hosted on Glitch. It may be easyiest to Remix it from there. Otherwise, you can make a new Glitch project, and run `git clone https://github.com/strawstack/hugo-glitch.git` from the Glitch console then start at step two below:

1. `Remix` this project on Glitch. Link: https://glitch.com/~hugo-template
2. Get your site's URL from `Share > Live App > Copy`.
3. Replace the `baseURL` in `config.toml` with your site's URL.
4. Open `Tools > Logs > Console`.
5. Run `cd hugo-glitch` in the console.

Note, if you can't see files in the Glitch at any point during this process, run the command `refresh` in the Glitch console.

Hugo Files
----------

From the `hugo-glitch` directory, you can edit the files that make up the site. Here are some common files you may want to edit:

>`content/posts/*.md`: Edit these files to affect the content inside blog posts
>`config.toml`: Edit this file to affect the site name, description, and menus

Hugo Commands
-------------

From the `hugo-glitch` directory, run these commands:

- `./hugo`: build the site. Once build, visit your site's URL to view the site.
- `./hugo new content/post_name.md`: to create a new post. `post_name` is the name of the new post.
