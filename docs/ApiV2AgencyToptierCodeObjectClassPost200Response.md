
# ApiV2AgencyToptierCodeObjectClassPost200Response


## Properties

Name | Type
------------ | -------------
`toptierCode` | string
`fiscalYear` | number
`pageMetadata` | [ApiV2AgencyAwardsCountPost200ResponsePageMetadata](ApiV2AgencyAwardsCountPost200ResponsePageMetadata.md)
`totals` | [ApiV2AgencyToptierCodeObjectClassPost200ResponseTotals](ApiV2AgencyToptierCodeObjectClassPost200ResponseTotals.md)
`results` | [Array&lt;ApiV2AgencyToptierCodeBudgetFunctionPost200ResponseResultsInnerChildrenInner&gt;](ApiV2AgencyToptierCodeBudgetFunctionPost200ResponseResultsInnerChildrenInner.md)
`messages` | Array&lt;string&gt;

## Example

```typescript
import type { ApiV2AgencyToptierCodeObjectClassPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "toptierCode": null,
  "fiscalYear": null,
  "pageMetadata": null,
  "totals": null,
  "results": null,
  "messages": null,
} satisfies ApiV2AgencyToptierCodeObjectClassPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AgencyToptierCodeObjectClassPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


