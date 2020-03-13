## Let's do this
![Cat]()<!-- .element data-src="https://media.giphy.com/media/CjmvTCZf2U3p09Cn0h/source.gif" width="400" style="border: 0; background: None; box-shadow: None;" -->


### Requirements Shopware 6
- Apache 2.2 or 2.4 
- PHP 7.2.0 or higher
- MySQL 5.7 or higher
- composer (brew install composer)
- local host: shopware.local


### Setup Shopware 6
```bash
git clone https://github.com/shopware/development sw6
cd sw6
bin/setup
```


### Shopware 6 Plugin Installation
- Download Repository [github.com/hubblecommerce/shopware6-api-plugin](https://github.com/hubblecommerce/shopware6-api-plugin)
- Place files in: custom/plugins/DmfApi
```bash
bin/console plugin:refresh
bin/console plugin:install --activate DmfApi
./psh.phar cache
```


### Requirements hubble
- Node.js (>=8.0.0)
- NPM (>=6.0.0)
- Code: [github.com/hubblecommerce](https://github.com/hubblecommerce/hubble-frontend-pwa)
- Shopware 6 Plugin
- Shopware 6 Access Key


### Setup hubble
```bash
git clone git@github.com:hubblecommerce/hubble-frontend
-pwa.git

cd hubble-frontend-pwa

cp .env_example .env

npm install 
```


### Get your Shopware Access Key
![Image of DMF]()<!-- .element data-src="assets/get-your-access-key.png" width="900" style="border: 0; background: None; box-shadow: None;" -->


### Configuration hubble
.env:
```bash
API_TYPE          = 'sw'
API_SW_ACCESS_KEY = 'ENTER_YOUR_ACCESS_KEY_HERE'
API_BASE_URL      = 'http://shopware.local'
```


### Start Application
```bash
# Dev Mode
npm run dev

# Prod Mode
npm run build
npm start
```
