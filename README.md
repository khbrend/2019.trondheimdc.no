# 2019.trondheimdc.no

This is the repository for 2019.trondheimdc.no. It is a react application.

## Setup

You need a relatively new version of node.js. Anything above 6.0 should work.

    git clone git@github.com:TrondheimDeveloperConference/2019.trondheimdc.no.git
    cd 2019.trondheimdc.no
    npm i
    
## Technologies

- Webpack for bundling
- React w/ JSX for views
- Babel to transpile to ES5
- LESS (with postcss and autoprefixer) for styles
    

## Development

Run in watch mode:

    npm start
    
## Deployment

Everything is automatic. The `develop` branch is automatically deployed to https://test.trondheimdc.no
and `master` is automatically deployed to https://2019.trondheimdc.no. Push to `develop` (or a separate
branch if you would rather do that) and create a pull request from `develop` to `master` when you want
to deploy to production.
