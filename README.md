# deploy_site

Simple template to deploy static files fast

## Usage

1. Click on the top right button `Use this template` -> `Create a new repository` -> Check `Include all branches` -> `Create repository`

2. After cloning, put your static files in the folder [dist](dist)

3. Configure your hosting platform (ex: [gh pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-from-a-branch)) to deploy each time there's a new commit in the deploy branch

4. If everything is set up correctly, when you run `npm run deploy`, your site will be updated after some minutes
