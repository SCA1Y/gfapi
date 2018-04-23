# GFAPI

Node.js API bindings and sample code create Gameflip listings for Steam items
* [REST API documentation](https://gameflip.github.io/gfapi)
* [Node.js GFAPI Bindings](https://gameflip.github.io/gfapi/gfapi/0.1.1/GfApi.html)
* Node.js Sample Code
  * [Steam Bulk Listing](https://gameflip.github.io/gfapi/samples/bulk_listing.html)
  * [Rocket League Listing](https://gameflip.github.io/gfapi/samples/rl_listing.html)
  * [Search Listing](https://gameflip.github.io/gfapi/samples/search_listing.html)

### API Key and OTP secret

To get the API Key and secret, contact Gameflip support.
During Beta, API Keys are only being given out to select customers.

### 1. Install [NodeJS v8.x LTS](https://nodejs.org)

### 2. Download sample code
```
  git clone https://github.com/gameflip/gfapi.git
```

### 3. Install dependencies and generate docs
```
  cd gfapi
  npm install
  npm run-script docs
```

### 4. Run Sample Code
```
  export GFAPI_KEY=<my_api_key>
  export GFAPI_SECRET=<my_api_secret>
  node src/samples/bulk_listing.js
```

### 5. For your own project, you just install gfapi npm
```
npm install 'gameflip/gfapi'
```
