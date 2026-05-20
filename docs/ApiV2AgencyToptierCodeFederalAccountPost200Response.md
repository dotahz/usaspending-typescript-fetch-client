
# ApiV2AgencyToptierCodeFederalAccountPost200Response


## Properties

Name | Type
------------ | -------------
`toptierCode` | string
`fiscalYear` | number
`pageMetadata` | [ApiV2AgencyToptierCodeDefCodePost200ResponsePageMetadata](ApiV2AgencyToptierCodeDefCodePost200ResponsePageMetadata.md)
`totals` | [ApiV2AgencyToptierCodeDefCodePost200ResponseTotals](ApiV2AgencyToptierCodeDefCodePost200ResponseTotals.md)
`results` | [Array&lt;ApiV2AgencyToptierCodeFederalAccountPost200ResponseResultsInner&gt;](ApiV2AgencyToptierCodeFederalAccountPost200ResponseResultsInner.md)
`messages` | Array&lt;string&gt;

## Example

```typescript
import type { ApiV2AgencyToptierCodeFederalAccountPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "toptierCode": null,
  "fiscalYear": null,
  "pageMetadata": null,
  "totals": null,
  "results": null,
  "messages": null,
} satisfies ApiV2AgencyToptierCodeFederalAccountPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AgencyToptierCodeFederalAccountPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


