## Setup

3. Choose your CI: Depending on your preference you can use github actions (recommended) or [Travis ci](https://travis-ci.com).
   - Github actions: Change your NUR repo name and optionally add a cachix name in [.github/workflows/build.yml](./.github/workflows/build.yml) and change the cron timer
     to a random value as described in the file
5. Change your travis and cachix names on the README template section and delete
   the rest
6. [Add yourself to NUR](https://github.com/nix-community/NUR#how-to-add-your-own-repository)

## README template

# nur-packages

**My personal [NUR](https://github.com/nix-community/NUR) repository**

<!-- Remove this if you don't use github actions -->
![Build and populate cache](https://github.com/<YOUR-GITHUB-USER>/nur-packages/workflows/Build%20and%20populate%20cache/badge.svg)

<!--
Uncomment this if you use travis:

[![Build Status](https://travis-ci.com/<YOUR_TRAVIS_USERNAME>/nur-packages.svg?branch=master)](https://travis-ci.com/<YOUR_TRAVIS_USERNAME>/nur-packages)
-->
[![Cachix Cache](https://img.shields.io/badge/cachix-<YOUR_CACHIX_CACHE_NAME>-blue.svg)](https://<YOUR_CACHIX_CACHE_NAME>.cachix.org)

