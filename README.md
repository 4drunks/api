# 4Drunks API

[![Website](https://img.shields.io/website?url=https%3A%2F%2Ffordrunks.herokuapp.com%2F)](https://fordrunks.herokuapp.com/)
[![Production - Push](https://github.com/4drunks/api/actions/workflows/production-push.yml/badge.svg)](https://github.com/4drunks/api/actions/workflows/production-push.yml)
[![GitHub package.json dependency version (prod)](https://img.shields.io/github/package-json/dependency-version/4drunks/api/@adonisjs/core)](https://adonisjs.com/)
[![GitHub top language](https://img.shields.io/github/languages/top/4drunks/api)](https://github.com/4drunks/api/search?l=typescript)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![GitHub](https://img.shields.io/github/license/4drunks/api)](https://github.com/4drunks/api/blob/prod/LICENSE)

## How to use

```sh
git clone https://github.com/4drunks/api.git
cd api
npm install
cp .env.example .env
node ace generate:key # Update APP_KEY in .env
# Update database in .env
node ace migration:run
npm run dev
```
