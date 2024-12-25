# rswag-example

## Required

- VSCode
- DevContainer

## Getting Started

Run DevContainer

```sh
cd app

rails db:create
rails db:migrate
rails db:seed

# run test
bundle exec rspec spec/requests/todos_spec.rb

# generate api document
rails rswag
```

Show API Document

http://127.0.0.1:3000/api-docs/index.html

Execute API

http://127.0.0.1:3000/api/v1/todos
http://127.0.0.1:3000/api/v1/todos/1
