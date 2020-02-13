# travis-deploy-boilerplate
Boilerplate repo for deploying static sites to Amazon S3 via TravisCI 🤙

### You will need:
- A GitHub Access Token (used to push a copy of the compiled static site to `static` branch, optional)
- An AWS ID
- An AWS secret key
- 2 AWS buckets (`production` and `staging`)
- TravisCI Account

### This repo includes:
- A template `README.md` for your static site's repo
- A template `travis.yml file` for building, testing, and deployment
- A template `Rakefile` for testing your site
- A template `Gemfile` with sample dependencies.
