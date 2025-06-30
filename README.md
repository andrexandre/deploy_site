# deploy_site

Simple template to deploy static files fast

## Usage

> I use [render](https://render.com) but this should work for any hosting platform

1. Put your static files in a folder called [dist](dist) (Ex: Compiling using a npm script)

2. Configure your hosting platform to deploy each time a commit in the deploy branch is commited

3. If everything is set up correctly, when you run `npm run deploy`, your site will be updated after some minutes
