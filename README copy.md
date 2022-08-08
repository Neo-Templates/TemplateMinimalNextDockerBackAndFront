This is a [Next.js](https://nextjs.org/) template project based on minimals.cc project 
adaptated with docker

## Quick Start

First, run the development server:
```bash
$ npm i
$ npm run dev
```

Open promo page [http://localhost:8081](http://localhost:8081) with your browser to see the result.
Open desktop page

# Deployment

##

## Heroku

```bash
$ heroku login -i
$ heroku container:login
$ heroku container:push web -a softline-linkedin
$ heroku container:release web -a softline-linkedin
```

Log of server:
```bash
$ heroku logs --tail -a  softline-linkedin
```