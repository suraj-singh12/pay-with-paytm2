# Suraj Singh
# Paytm Payment Gateway
## generate key from https://dashboard.paytm.com/


>> Accept request at `http://localhost:4100/callback` (later update with live url (where application is hosted))

>> CallBack to `http://localhost:4100/viewBooking?status=${_results.STATUS}&ORDERID=${_results.ORDERID}&date=${_results.TXNDATE}&bank=${_results.BANKNAME}` (later update with live url where api is hosted : heroku)

## How To Use

### Clone the repo to Local
```bash
git clone https://github.com/suraj-singh12/pay-with-paytm.git
```

## Configure the config.js
1. Create api keys from paytm dashboard : https://dashboard.paytm.com/

2. copy the keys and replace all the values in `config.js` file.

> Documentation: https://business.paytm.com/docs/getting-started/

> paytm-payment-gateway-api-documentation

### Install Dependencies
```npm
npm install
```

## Run 
```npm
npm start
```
> Go to localhost url and proceed after filling in details.

> You will receive the details of payment in the terminal window itself, and also on the redirect (last) page.
