# weelnk

## Install

`composer create-project carc1n0gen/weelnk path/to/install`

`cd path/to/install && composer install`

### Environment Variables

For development it's good enough to just copy the example .env file and modify it as needed

`cp .env.example .env`

In production you should set real environment variables for the process.  The .env.example contains the required variables.

### Migrations

`php cli migrate`