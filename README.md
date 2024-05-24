# Rust API client for usps-addresses-sdk

The Addresses API validates and corrects address information, eliminating errors, improving package delivery service and package pricing. This suite of APIs provides different utilities for addressing components. The ZIP Code&#8482; lookup finds valid ZIP Code&#8482; for a City and State.  The City/State lookup provides the valid cities and states for a provided ZIP Code&#8482;.  The Address Standardization API validates and standardizes USPS&#174; domestic addresses, city and state names, and ZIP Code&#8482; in accordance with USPS&#174; addressing standards.  The USPS&#174; address standard includes the ZIP + 4&#174;, signifying a USPS&#174; delivery point, given a street address, a city and a state. 


## Overview

This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [openapi-spec](https://openapis.org) from a remote server, you can easily generate an API client.

- API version: 3.0.2
- Package version: 3.0.2
- Generator version: 7.6.0
- Build package: `org.openapitools.codegen.languages.RustClientCodegen`

## Installation

Put the package under your project folder in a directory named `usps-addresses-sdk` and add the following to `Cargo.toml` under `[dependencies]`:

```
usps-addresses-sdk = { path = "./usps-addresses-sdk" }
```

## Documentation for API Endpoints

All URIs are relative to *https://api.usps.com/addresses/v3*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*ResourcesApi* | [**get_address**](docs/ResourcesApi.md#get_address) | **GET** /address | Returns the best standardized address for a given address.
*ResourcesApi* | [**get_city_state**](docs/ResourcesApi.md#get_city_state) | **GET** /city-state | Returns the city and state for a given ZIP Code
*ResourcesApi* | [**get_zip_code**](docs/ResourcesApi.md#get_zip_code) | **GET** /zipcode | Returns the ZIP Code for a given address.


## Documentation For Models

 - [Address](docs/Address.md)
 - [AddressAdditionalInfo](docs/AddressAdditionalInfo.md)
 - [AddressCorrectionsInner](docs/AddressCorrectionsInner.md)
 - [AddressMatchesInner](docs/AddressMatchesInner.md)
 - [AddressResponse](docs/AddressResponse.md)
 - [CityAndState](docs/CityAndState.md)
 - [CityStateResponse](docs/CityStateResponse.md)
 - [DomesticAddress](docs/DomesticAddress.md)
 - [ErrorMessage](docs/ErrorMessage.md)
 - [ErrorMessageError](docs/ErrorMessageError.md)
 - [ErrorMessageErrorErrors](docs/ErrorMessageErrorErrors.md)
 - [ErrorMessageErrorSource](docs/ErrorMessageErrorSource.md)
 - [ZipCodeResponse](docs/ZipCodeResponse.md)


To get access to the crate's generated documentation, use:

```
cargo doc --open
```

## Author

APISupport@usps.gov

