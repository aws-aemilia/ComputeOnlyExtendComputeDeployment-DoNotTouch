# Express Compute

## What is this repo?

- Express server in `./src`, deployed as compute app and served from the root `/` URL path
- Deploy manifest found in `./deploy-manifest.json`
- There's a `postbuild` script that copies all built assets to the `.amplify-hosting` folder and conforms the output to the deployment specification.