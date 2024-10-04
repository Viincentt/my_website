This is from piazzai/cvless.

Had some trouble settting this up as I never touched any Ruby and apparently it does not mix well with MacOS.

For my future self or whoever has the same issue:
  - Clone the repo
  - Init your own repo (username.github.io)
  - copy -r cvless/demo username.github.io
  - In _\_config.yml_ change `theme: cvless` to `remote_theme: piazzai/cvless`. This is to pass the Github Pages build.
