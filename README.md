# xmark-server
Server for Xmark (marking X posts on the Bitmark blockchain)

Requirements:
- nodejs>=20, npm (npm install -g rettiwt-api)
- a working X/Twitter account (Follow the rettiwt command line instructions for getting the api key)
- python3 with the modules imported by the script in cgi-bin (these modules should come as default)
- web server using python3 scripts as CGI
- Bitmark node from the akrmn/bitmark lm branch: https://github.com/akrmn2021/bitmark/tree/lm
- Setup your bitmark.conf
  ```
  rpcuser=yourRpcUserName
  rpcpassword=yourRpcPassword
  server=1
  listen=1
  txindex=1
  ```
- Start bitmarkd and web server with a valid HTTPS certificate

# Donate
BTC: bc1q0795vnddk099je8pp98uqckjlwzamm5t3hdfmz
Bitmark: bE28ZG3FpoGnyxobDFiybjJsQHUb9mLygb
XMR: 84qp8nTgei5RrjFzXW3KP3MoFmvh8CcRUBzuGtLpRE2PNr7W3nR7KpU3vxBuRNjHhfcLe8FoXGPzDhyPQk6kHmbb6Fuu3KQ
