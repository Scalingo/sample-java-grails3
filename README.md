# Sample Application using Java and Grails 3

This sample is running on: https://java-grails3.is-easy-on-scalingo.com/

## Running Locally

First, you need to have a working grails environment: http://docs.grails.org/latest/guide/gettingStarted.html#requirements

Then, simply execute:

```shell
grails run-app
```

## Deploy via Git

Create an application on https://scalingo.com, then:

```shell
scalingo -a my-app git-setup
git push scalingo master
```

And that's it!

## Deploy via One-Click

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy)
