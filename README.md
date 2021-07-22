# polkaswap-token-whitelist-config

## Welcome to the Polkaswap Whitelisted Token Configuration Repository!

This repository contains the file in which all the whitelisted (safe) tokens are presented.
Whitelisted tokens do not show possible scam notification before swapping and also have their own icons instead of the default grey one.

### If you want your token to be whitelisted

Your request for whitelisting your token in Polkaswap can be reviewed in this repository.
For that: 

1. The whitelist is in `whitelist.json`
1. Clone the repository (or use the GitHub interface) to make changes to `whitelist.json`.
1. Add the necessary information: 
	1. "symbol": the symbol of the token. For example, "VAL".
    1. "name": name of the token. For example, "SORA Validator Token"
    1. "address": contract address in the ERC-20 network in the "0x..." format
    1. "decimals": number of numbers on the right from the decimal point
    1. "icon": icon of the token in SVG
1. Create a PR into this repository by adding lines to the file, representing your token
     > If some of the questions in the template are not replied to (except for the optional one), it will not be possible to review your request. 
