# 4Drunks API

[![Production](https://img.shields.io/website?label=Production&url=https%3A%2F%2Ffordrunks.herokuapp.com%2F)](https://fordrunks.herokuapp.com/)
[![QA](https://img.shields.io/website?label=QA&url=https%3A%2F%2Ffordrunks-qa.herokuapp.com%2F)](https://fordrunks-qa.herokuapp.com/)
[![GitHub package.json dependency version (prod)](https://img.shields.io/github/package-json/dependency-version/4drunks/api/@adonisjs/core)](https://adonisjs.com/)
[![GitHub top language](https://img.shields.io/github/languages/top/4drunks/api)](https://github.com/4drunks/api/search?l=typescript)
[![GitHub contributors](https://img.shields.io/github/contributors-anon/4drunks/api)](https://github.com/4drunks/api/graphs/contributors)
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
