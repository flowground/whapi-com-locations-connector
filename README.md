# ![LOGO](logo.png) Locations **flow**ground Connector

## Description

A generated **flow**ground connector for the Locations API (version 2.0).

Generated from: https://api.apis.guru/v2/specs/whapi.com/locations/2.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:53+03:00

## API Description

The Locations API is a collection of methods that support geographical information. The first method is an address lookup service for UK addresses. This service can be used to provide a new customer with a list of possible addresses from which they can populate a registration form.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Retrieves a list of addresses when supplied with a house number or name and a postcode. It is generally used during customer registration to provide a list of possible addresses from where the customer can select their own address details.

*Tags:* `Locations`

#### Input Parameters
* `houseNum` - _required_ - House number or name of the address.
* `postCode` - _required_ - Postcode of the address, no spaces required.

### Retrieves a list of countries and its currencies.

*Tags:* `Locations`

### Retrieves the specified country and its currency.

*Tags:* `Locations`

#### Input Parameters
* `countryCode` - _required_ - Code of the country

### Retreives the list of currencies.

*Tags:* `Locations`

### Retreives the specified currency.

*Tags:* `Locations`

#### Input Parameters
* `currencyCode` - _required_ - Code of the currency

## License

**flow**ground :- Telekom iPaaS / whapi-com-locations-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
