# travis-deploy-boilerplate
Boilerplate repo for deploying static sites to Amazon S3 via TravisCI 🤙
https://wiki.library.columbia.edu/display/USGSERVICES/Set+up+static+site+deployment+to+s3

### You will need:
- A GitHub Access Token (used to push a copy of the compiled static site to `static` branch)
- An AWS ID
- An AWS secret key
- 2 AWS buckets (`production` and `staging`)

### This repo includes:
- A template `README.md` for your static site's repo
- A Template `travis.yml file` for building, testing, and deployment
- A template `Rakefile` for testing your site
- A template `Gemfile` with sample dependencies.
