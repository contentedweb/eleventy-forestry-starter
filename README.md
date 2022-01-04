# Eleventy Starter
Eleventy generated static site.

## ToDos
1. Look into Forestry "auto setup"
    1. DONE Basic pots and pages are done
    1. This should include some navigation menus (using eleventy navigation)
        1. This would mean a pages template with fields for navigation menu order
        1. No parent - only for simple one level menus as this is a simple site!
        1. (Only needed for complex menus) Also means some CSS styling to deal with it.

## Done
1. DONE Figure out tokens - build can't run using the forked token - using github token so no need to setup personal one.
4. DONE Look into default GH pages (ie username.github.io) so that those without a domain name can get started immediately

## How to setup
1. Get a GitHub account
1. Fork this starter site
1. Enable workflows on the site (disabled by default by Github for security reasons after a fork)
1. If not going to use own domain name, need to rename repo to "username.github.io" so that it is served from the the root and not "https://username.github.io/repo-name" 
1. Get a forestry account
1. Point forestry to the forked site
3. Setup Github pages
2. Forestry "Deploy admin" in Settings in order to have domain/admin working otherwise it uses the wrong site id. So don't need the admin folder in the starter site
4. Edit metadata.js file using online editor?
5. Set eleventy build action to run nightly by default