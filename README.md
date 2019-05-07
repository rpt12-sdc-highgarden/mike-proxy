# Project Name

> The proxy server for Goodreads' proxy. **Renders Description, Author, and Review modules via `bundle.js` files running on each service and loaded directly in index.html**

## Related Projects

> These services will need to be setup (either locally or remotely) to run the proxy

  - https://github.com/rpt12-knightrider/jb-service
  - https://github.com/rpt12-knightrider/mj-service
  - https://github.com/rpt12-knightrider/sm-service

## Table of Contents

1. [Usage](#Usage)
2. [Requirements](#requirements)
3. [API Endpoint](#api%20endpoint)

## Usage

> For setup, please follow this pattern:

1. `npm install`
2. ensure `index.html` script tags at bottom are pointed to the correct three `bundle.js` files on remote services. **Skipping this step will result in the proxy not working**
3. `npm start`
4. Navigate to [localhost:3000](http://localhost:3000)

