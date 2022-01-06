# Eleventy Starter
Eleventy generated static site, managed through Forestry and hosted on GitHub Pages.

## How to setup

### GitHub

The site's code is stored on GitHub and it will also be hosted there. To get this working, follow these steps:

1. Get a GitHub account
1. Fork this starter site
1. Enable workflows on the site (disabled by default by Github for security reasons after a fork). Also for pruner workflow.
1. If not going to use own domain name, need to rename repo to "username.github.io" so that it is served from the the root and not "https://username.github.io/repo-name" 
1. Setup Github pages
    1. If deploying to username.github.io => branch = "gh-pages", folder = "root"
    1. If deploying to custom domain? It seems like the above should always work.
1. Run the Eleventy Build workflow
1. Wait two minutes
1. Go to "https://username.github.io/" and check the site has been built and you can browse it.
1. It should look like this: (image of site) 

You're all set. Congratulations!

### Forestry

Once you have the site being hosted on GitHub Pages, you should add Forestry. This enables you to make some configuration changes (eg theming) and to edit and create content in a user friendly manner. Follow these steps:

1. Get a forestry account
1. Create site using 11ty and GitHub
1. Point forestry to the forked site, repo "username.github.io", master branch 
1. Mark all setup steps as done (no need to configure anything) and mark setup as complete.
1. Forestry "Deploy admin" in Settings in order to have domain/admin working otherwise it uses the wrong site id. So don't need the admin folder in the starter site
4. Edit file in data folder to setup site name and URL.

Happy blogging!

## ToDos
1. Set eleventy build action to run nightly by default?
1. Anything else?

## Done
1. DONE Basic theming
1. DONE Figure out tokens - build can't run using the forked token - using github token so no need to setup personal one.
1. DONE Look into default GH pages (ie username.github.io) so that those without a domain name can get started immediately
1. DONE Look into Forestry "auto setup"
    1. DONE Basic pots and pages are done
    1. DONE This should include some navigation menus (using eleventy navigation)
        1. This would mean a pages template with fields for navigation menu order
        1. No parent - only for simple one level menus as this is a simple site!
