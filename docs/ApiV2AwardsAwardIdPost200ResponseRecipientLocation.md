
# ApiV2AwardsAwardIdPost200ResponseRecipientLocation

The recipient\'s location

## Properties

Name | Type
------------ | -------------
`addressLine1` | string
`addressLine2` | string
`addressLine3` | string
`foreignProvince` | string
`cityName` | string
`countyCode` | string
`countyName` | string
`stateCode` | string
`stateName` | string
`zip5` | string
`zip4` | string
`foreignPostalCode` | string
`countryName` | string
`locationCountryCode` | string
`congressionalCode` | string

## Example

```typescript
import type { ApiV2AwardsAwardIdPost200ResponseRecipientLocation } from ''

// TODO: Update the object below with actual values
const example = {
  "addressLine1": null,
  "addressLine2": null,
  "addressLine3": null,
  "foreignProvince": null,
  "cityName": null,
  "countyCode": null,
  "countyName": null,
  "stateCode": null,
  "stateName": null,
  "zip5": null,
  "zip4": null,
  "foreignPostalCode": null,
  "countryName": null,
  "locationCountryCode": null,
  "congressionalCode": null,
} satisfies ApiV2AwardsAwardIdPost200ResponseRecipientLocation

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AwardsAwardIdPost200ResponseRecipientLocation
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


