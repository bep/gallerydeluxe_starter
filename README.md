[![Netlify Status](https://api.netlify.com/api/v1/badges/fe020ffb-29ff-409c-905b-6f00175091d0/deploy-status)](https://app.netlify.com/sites/gallerydeluxe/deploys)

This is a starter project for the [Gallery Deluxe](https://github.com/bep/gallerydeluxe) Hugo Module. You need [Hugo](https://gohugo.io/getting-started/installing/) and [Go](https://go.dev/dl/) to run this project.

1. Click on use "Use this template" and give your new GitHub project a suitable name.
1. Edit `go.mod` and replace the path with your new GitHub project's path[^1]. 
1. Edit `config.toml` etc. to match your setup and replace the images inside `content/images` with your own.
1. Add your custom logo in [layouts/partials/logo.html](layouts/partials/logo.html)

This starter projects can be previewd at [gallerydeluxe.netlify.app](https://gallerydeluxe.netlify.app/). A bigger gallery can be found at [staticbattery.com](https://staticbattery.com/).

**Note:** This isn't a _theme_; it's meant to be used as a standalone Hugo project. You can edit/add/move files in this project as you please.

## Update theme

Run `hugo mod get -u` to update to a newer version of Gallery Deluxe if one exists.

[^1]: I wish GitHub's template project feature had support for variable replacements.
