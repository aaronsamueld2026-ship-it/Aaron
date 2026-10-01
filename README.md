# Aaron Career Map

An interactive, responsive static page presenting the education, professional experience, leadership, and research described in Aaron's CV.

## Run locally

Open `index.html` in a browser, or serve this directory with any static file server, for example:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy to Netlify

This repository is ready for Netlify's Git-based deployment:

1. Import the GitHub repository in Netlify.
2. Leave the build command empty.
3. Set the publish directory to `.`.

`netlify.toml` already sets the publish directory and basic response headers. There is no build step or package install.
