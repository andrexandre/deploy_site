# deploy_site

Simple template to deploy static files fast

## Usage

1. Click on the top right button `Use this template` -> `Create a new repository` -> Check `Include all branches` -> `Create repository`

> I use [render](https://render.com) but this should work for any hosting platform

2. After cloning, put your static files in a folder called [dist](dist) (Ex: Compiling using a npm script)

3. Configure your hosting platform to deploy each time there's a new commit in the deploy branch

4. If everything is set up correctly, when you run `npm run deploy`, your site will be updated after some minutes
