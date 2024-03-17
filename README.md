# Gitpod Mastodon

Forked from the upstream GitLab repository: https://gitlab.com/acefed/gitpod-mastodon/-/tree/main

## Open in GitPod

### Latest `main` branch

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#GITTAG=main/https://github.com/shuuji3/gitpod-mastodon)

(https://gitpod.io/#GITTAG=main/https://github.com/shuuji3/gitpod-mastodon)

### `v4.2.8`

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#GITTAG=v4.2.8/main/https://github.com/shuuji3/gitpod-mastodon)

https://gitpod.io/new/#GITTAG=v4.2.8/https://github.com/shuuji3/gitpod-mastodon

## Usage for the frontend development

- Login username is `admin@<domain-name>` and pass can be found in the terminal tab
  - Example:
    ```shell  
    $ echo "E-mail address: admin@$(gp url 8080 | cut -d/ -f3)"
    E-mail address: admin@8080-shuuji3-gitpodmastodon-l0ypezodb7f.ws-us110.gitpod.io
    $ RAILS_ENV=development bin/tootctl accounts modify admin --reset-password
    OK
    New password: 5501eb0609b07c404cb9e38b4a19a1f4
    ```
- Edit frontend codes
- Run the build command for`yarn build:production`
- Restart the web server with the command:
  ```shell
  RAILS_ENV=production BIND=0.0.0.0 PORT=8080 RAILS_SERVE_STATIC_FILES=true bundle exec puma -C config/puma.rb
  ```

## Original Documentation (only in Japanese?)

https://acefed.gitlab.io/gitpod-mastodon
