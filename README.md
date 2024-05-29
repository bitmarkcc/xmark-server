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
Bitcoin: 1D7z9u3Z7aCASUwQbk4XzDjPo3FLQqt4LX

Bitmark: bQm13PDK2PKuL4UZgmreDds8KEfi4Bm1f7
