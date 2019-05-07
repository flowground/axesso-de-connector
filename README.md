# ![LOGO](logo.png) Axesso Api **flow**ground Connector

## Description

A generated **flow**ground connector for the Axesso Api API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/axesso.de/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:37:04+03:00

## API Description

Use this api to fetch information to Amazon products and more.

## Authorization

This API does not require authorization.

## Actions

### request buy recommendations to a given product

*Tags:* `amz`

#### Input Parameters
* `url` - _required_ - The url of the requested product.

### lookup product information

*Tags:* `amz`

#### Input Parameters
* `url` - _required_ - The url of the requested product.
* `size` - _optional_ - Size parameter if available.

### fetch results auf a keyword search on Amazon

*Tags:* `amz`

#### Input Parameters
* `keyword` - _required_ - keyword to search
* `domainCode` - _required_ - domain for the search
* `sortBy` - _optional_ - sort option
* `numberOfProducts` - _optional_ - number of the results (max 20)

### request available sort options to use in keyword search

*Tags:* `amz`

## License

**flow**ground :- Telekom iPaaS / axesso-de-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
