# wp-polly

Sound streaming server with Amazon Polly and WP REST API.

## dependencies

- Git
- Node.js
- direnv

## get started

```shell
$ git clone https://github.com/kamataryo/wp-polly
$ cd wp-polly
$ npm install

$ direnv edit .
export AWS_DEFAULT_PROFILE=myprofile
export AWS_PROFILE=$AWS_DEFAULT_PROFILE

$ npm start
```
