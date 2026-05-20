
# ApiV2AgencyToptierCodePost200Response


## Properties

Name | Type
------------ | -------------
`fiscalYear` | number
`toptierCode` | string
`name` | string
`abbreviation` | string
`agencyId` | number
`iconFilename` | string
`mission` | string
`website` | string
`congressionalJustificationUrl` | string
`aboutAgencyData` | string
`subtierAgencyCount` | number
`defCodes` | [Array&lt;ApiV2AgencyToptierCodePost200ResponseDefCodesInner&gt;](ApiV2AgencyToptierCodePost200ResponseDefCodesInner.md)
`messages` | Array&lt;string&gt;

## Example

```typescript
import type { ApiV2AgencyToptierCodePost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "fiscalYear": null,
  "toptierCode": null,
  "name": null,
  "abbreviation": null,
  "agencyId": null,
  "iconFilename": null,
  "mission": null,
  "website": null,
  "congressionalJustificationUrl": null,
  "aboutAgencyData": null,
  "subtierAgencyCount": null,
  "defCodes": null,
  "messages": null,
} satisfies ApiV2AgencyToptierCodePost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AgencyToptierCodePost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


