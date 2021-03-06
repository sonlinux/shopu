# Shopu Storefront

![1 copy 2x](https://user-images.githubusercontent.com/5421321/47798207-30aeea00-dd28-11e8-9398-3d8426836a83.png)

_**Note:** This project is beta quality. We don't advise using it in production._

A GraphQL-powered, PWA, single-page application storefront for [shopu](https://github.com/devsbranch/shopu/).

## Features
- Headless ecommerce storefront built with [GraphQL](https://graphql.org/), [Apollo Client](https://www.apollographql.com/client), [React](https://reactjs.org/) and [Typescript](https://www.typescriptlang.org/)
- Offline mode (beta)
- shopu GraphQL API integration
- Single-page application experience
- [Braintree Payment Gateway](https://www.braintreepayments.com/) integration

## Demo

See the [public demo](http://shopu.com) of shopu Storefront!

Or launch the demo on a free Heroku instance. Note that you have to set the `BACKEND_URL` environment to point to the shopu instance.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js 10.0+ 
- A running instance of shopu.

    To run the storefront, you have to set the `BACKEND_URL` environment to point to the Saleor instance. If you are running Saleor locally with the default settings, set `BACKEND_URL` to: `http://localhost:8000/`.

### Installing

Clone the repository:

```
git clone git@github.com:mirumee/shopu-storefront.git
```

Enter the project directory:

```
cd shopu-storefront
```

Install NPM dependencies:

```
npm i
```

Run the development server:

```
npm start
```

Go to `http://localhost:3000` to access the storefront.


**Note:** Offline mode doesn't currently work on the development server (run with `npm start`), which is a known issue in [sw-precache-webpack-plugin](https://github.com/goldhand/sw-precache-webpack-plugin#webpack-dev-server-support) and will be fixed in future releases.


## License

This project is licensed under the BSD-3-Clause License - see the [LICENSE.md](LICENSE.md) file for details


#### Crafted with ❤️ by [Mirumee Software](http://mirumee.com)
hello@mirumee.com
