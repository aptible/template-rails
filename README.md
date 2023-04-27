<br>
<img src="https://user-images.githubusercontent.com/4295811/226700092-ffbd0c01-dba1-4880-8b77-a4d26e6228f0.svg"  width="64">

# Rails on Aptible

This is a variation of the [Rails](https://rubyonrails.org/) [Getting Started](https://guides.rubyonrails.org/v4.2.7/getting_started.html) example on [Aptible](https://aptible.com).

The app in this repo is deployed live [here](https://app-52710.on-aptible.com/).

[![Deploy on Aptible](https://app.aptible.com/deploy-on-aptible.svg)](https://app.aptible.com/create)

[Detailed docs](https://www.aptible.com/docs/ruby-quickstart)

## Configuration

The only thing the user needs to do is create and set `PRODUCTION_SECRET_KEY` environment variable during onboarding flow. The below command should generate
a secret you can use in that step.

```bash
rails secret
```

If you already created the app and just want to apply an environment variable, you can use our cli tool:

```bash
aptible config:set --app "$APP_HANDLE" PRODUCTION_SECRET_KEY="xxx"
```
