# Fly + TypeScript + Express

Repository for the [Deploying a TypeScript Express application to Fly](https://technotrampoline.com/articles/deploying-a-typescript-express-application-to-fly/) article.

Running the container image locally:




* Installing Fly: https://fly.io/docs/getting-started/installing-flyctl/
* Log in to Fly: https://fly.io/docs/getting-started/log-in-to-fly/
* Based on: https://fly.io/docs/getting-started/dockerfile/

* 

Make sure the service's `internal_port` (8080 by default) inside the fly.toml file matches the port exposed by your docker image.

* `fly deploy` to deploy your application
* `fly open` to open your application
* 

