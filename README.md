# Author: haotruong.dev

### Follow me

[![Official website](https://img.shields.io/badge/Code%20by-haotruong-informational?style=flat&logo=rubyonrails)](https://www.haotruong.dev)
[![Facebook](https://img.shields.io/badge/facebook-send%20message-1DA1F2?style=flat&logo=facebook&logoColor=ffffff)](https://www.facebook.com/haotv03)

# Kanji: Using Rails for API Applications

> Information Project

![](https://img.shields.io/badge/Ruby-3.2.2-informational?style=plastic&logo=ruby&logoColor=%23CC342D)
![](https://img.shields.io/badge/Rails-7.1.3.2-informational?style=plastic&logo=rubyonrails&logoColor=%23D30001)

## Getting Started

> Config environment

```sh
  cp .env.example .env
```

> Rails サーバー起動：

```sh
  docker compose build
  docker compose up
```

> Rails サーバーの操作

```sh
  docker compose exec web bash

  # Create database
  rails db:create

  # Migrate database
  rails db:migrate

  # Install gem
  bundle install

  # Check convention
  bundle exec rubocop

  # Check Unit test
  bundle exec rspec
```

## Docs API

```sh
  {{host}}/api/docs/index.html
```

## Sidekiq Status

```sh
  {{host}}/sidekiq
```
