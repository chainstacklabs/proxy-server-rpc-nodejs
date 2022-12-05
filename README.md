# Node RPC proxy server

This project shows how to protect your RPC URL by creating a back-end server where you store the endpoint. Then, when you click the button to check the balance, the front end will send a request to the back-end server using the `eth_getBalance` method via the `web3.js` library. 

## Quickstart

1. Clone the repo.
1. Edit the `.env.sample` file to include your node RPC URL key and rename it to `.env`.
1. Install  dependencies:

```sh
npm install
```
4. Run page in dev mode with:

```sh
npm run dev
```
The page is now running in `http://localhost:5000/`. Open it in your browser to see it. 

1. Insert the address you want to query in the input field.
1. Click **Check balance** to send a request to your RPC node and retrieve the address' balance.

If you check the source code from the browser, you won't be able to find the API key used! 