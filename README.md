# Eleventy Starter
Eleventy generated static site.

## ToDos
1. Set eleventy build action to run nightly by default?
1. Anything else?

## Done
1. DONE Figure out tokens - build can't run using the forked token - using github token so no need to setup personal one.
1. DONE Look into default GH pages (ie username.github.io) so that those without a domain name can get started immediately
1. DONE Look into Forestry "auto setup"
    1. DONE Basic pots and pages are done
    1. DONE This should include some navigation menus (using eleventy navigation)
        1. This would mean a pages template with fields for navigation menu order
        1. No parent - only for simple one level menus as this is a simple site!

## How to setup
1. Get a GitHub account
1. Fork this starter site
1. Enable workflows on the site (disabled by default by Github for security reasons after a fork)
1. If not going to use own domain name, need to rename repo to "username.github.io" so that it is served from the the root and not "https://username.github.io/repo-name" 
1. Get a forestry account
1. Point forestry to the forked site
2. Forestry "Deploy admin" in Settings in order to have domain/admin working otherwise it uses the wrong site id. So don't need the admin folder in the starter site
3. Setup Github pages
    1. If deploying to username.github.io => branch = "gh-pages", folder = "root"
    1. If deploying to custom domain? It seems like the above should always work.
4. Edit metadata.js file using online editor?
