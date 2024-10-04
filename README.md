This is from [piazzai/cvless](https://github.com/piazzai/cvless).

Had some trouble settting this up as I never touched any Ruby and apparently it does not mix well with MacOS.

For my future self or whoever has the same issue:

- Clone the repo
- Init your own repo (username.github.io)
- `copy -r cvless/demo username.github.io`

Use `docker compose up` to change and test locally on your Mac

Do not forget to update the theme in the _\_config.yml_

- `remote_theme: piazzai/cvless` for Github Pages/builds
- `theme: cvless` for Docker(testing locally)

Use this [website](https://favicon.io) to update your favicon
