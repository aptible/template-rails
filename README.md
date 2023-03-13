# README

This is a variation of the [Rails](https://rubyonrails.org/) [Getting Started](https://guides.rubyonrails.org/v4.2.7/getting_started.html) example on [Aptible](https://aptible.com).

The app in this repo is deployed at [https://app-52710.on-aptible.com](https://app-52710.on-aptible.com).

## Deployment

1. Clone or fork the repository: `https://github.com/aptible/template-rails.git`
2. Create an App on Aptible with: `aptible apps:create $APP_HANDLE` 
3. Push this repository to the Aptible [Git Remote](https://deploy-docs.aptible.com/docs/git-remote):
`git remote add aptible "$GIT_REMOTE"`
`git push aptible main`
4. Create a default endpoint for the `CMD` service.

That's it! Your web service will be live on your Endpoint URL as soon as the build finishes.
