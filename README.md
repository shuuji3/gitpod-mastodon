# Gitpod Mastodon

Forked from the upstream GitLab repository: https://gitlab.com/acefed/gitpod-mastodon/-/tree/main

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#GITTAG=main/https://gitlab.com/acefed/gitpod-mastodon)
## Usage for the frontend development

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#GITTAG=main/https://gitlab.com/acefed/gitpod-mastodon)

- Edit frontend codes
- Run the build command for`yarn build:production`
- Restart the web server with the command:
  ```shell
  RAILS_ENV=production BIND=0.0.0.0 PORT=8080 RAILS_SERVE_STATIC_FILES=true bundle exec puma -C config/puma.rb
  ```

TODO: `development` build

## Fedibaird

https://gitlab.com/acefed/gitpod-mastodon/-/tree/fedibird

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#GITTAG=fedibird/https://gitlab.com/acefed/gitpod-mastodon/-/tree/fedibird)

## Documentation (only in Japanese?)

https://acefed.gitlab.io/gitpod-mastodon
