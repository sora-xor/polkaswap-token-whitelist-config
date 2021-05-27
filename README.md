# polkaswap-token-whitelist-config
This repository is managed by Terraform!

## Welcome to the Polkaswap Whitelisted Token Configuration Repository!

This repository contains the file in which all the whitelisted (safe) tokens are presented.
Whitelisted tokens do not show possible scam notification before swapping and also have their own icons instead of the default grey one.

### If you want your token to be whitelisted

The team can review your request for whitelisting your token in Polkaswap.
For that: 

1. Follow the link to see the file: https://github.com/sora-xor/polkaswap-token-whitelist-config/blob/e4d85072859b9d575e4de211f5b3b0286f05984d/whitelist.json
1. Clone the repository (or use the GitHub interface) to make changes to the file.
1. Add the necessary information: 
	1. "symbol": the symbol of the token. For example, "VAL".
    1. "name": name of the token. For example, "SORA Validator Token"
    1. "address": contract address in the ERC-20 network in the "0x..." format
    1. "decimals": number of numbers on the right from the decimal point
    1. "icon": icon of the token in SVG
1. Create a PR into this repository by adding lines to the file, representing your token
     > If some of the questions in the template are not replied to (except for the optional one), we will not be able to review your request. 
