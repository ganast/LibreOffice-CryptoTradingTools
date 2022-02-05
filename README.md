# LibreOffice Crypto Trading Tools

LibreOffice macros, templates, etc., for cryptocurrency trading spreadsheets

NOTE: This is a very early version, nothing here yet except for some functions
for fetching trading pair prices from certain exchanges!

## Usage and more information

Format as number, not as currency (since the equivalency is determined by the
paired specified, not by the system's locale or currency cell formats).

Kraken (https://docs.kraken.com/rest/#operation/getTradableAssetPairs)

=VALUE(GETKRAKENASKPRICEFORPAIR("XRPEUR"))

Coinbase (https://developers.coinbase.com/api/v2#get-spot-price)

=VALUE(GETCOINBASEV2SPOTPRICEFORPAIR("SNX-EUR"))

etc.

(more providers and services to come)

License
-------

Licensed under the MIT License as described in LICENSE.

*Copyright (c) 2022 George Anastassakis (ganast@ganast.com)*
