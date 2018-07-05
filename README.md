# Maynard XC Website

Based on the Ghost blogging platform.

blog contains the ghost blogging platform
theme is the custom ghost theme

local compose file builds both and starts a docker container
running ghost

GHOST_CLI_VERSION 1.5.2
GHOST_VERSION 1.21.4

### To run the blog
> docker-compose up to run container

### To run the content
> cd theme
> npm install
> gulp

* shft-F5 may be required to reload the content changes



## Tagging of Posts

### Quotes

A quote tag
No title
Put quote sayers name in underscores, _John Smith_

# TODO
* Create navigation menu
  - course map
  - press, photos, quotes, etc
* Main menu to show most recent of echo type
* Calendar integration
* logging in
* link to photo site
* more recent press
* more photos?  Can read from gallery?



# Issues
* need to restart after changing handlebars
* how to store sql database
