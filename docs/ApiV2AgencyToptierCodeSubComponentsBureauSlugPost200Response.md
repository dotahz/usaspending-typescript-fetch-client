
# ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200Response


## Properties

Name | Type
------------ | -------------
`toptierCode` | string
`bureauSlug` | string
`fiscalYear` | number
`totals` | [ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200ResponseTotals](ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200ResponseTotals.md)
`pageMetadata` | [ApiV2AgencyToptierCodeDefCodePost200ResponsePageMetadata](ApiV2AgencyToptierCodeDefCodePost200ResponsePageMetadata.md)
`results` | [Array&lt;ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200ResponseResultsInner&gt;](ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200ResponseResultsInner.md)
`messages` | Array&lt;string&gt;

## Example

```typescript
import type { ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "toptierCode": null,
  "bureauSlug": null,
  "fiscalYear": null,
  "totals": null,
  "pageMetadata": null,
  "results": null,
  "messages": null,
} satisfies ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AgencyToptierCodeSubComponentsBureauSlugPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


