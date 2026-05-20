
# ApiV2AgencyToptierCodeBudgetFunctionPost200Response


## Properties

Name | Type
------------ | -------------
`toptierCode` | string
`fiscalYear` | number
`pageMetadata` | [ApiV2AgencyToptierCodeBudgetFunctionPost200ResponsePageMetadata](ApiV2AgencyToptierCodeBudgetFunctionPost200ResponsePageMetadata.md)
`results` | [Array&lt;ApiV2AgencyToptierCodeBudgetFunctionPost200ResponseResultsInner&gt;](ApiV2AgencyToptierCodeBudgetFunctionPost200ResponseResultsInner.md)
`messages` | Array&lt;string&gt;

## Example

```typescript
import type { ApiV2AgencyToptierCodeBudgetFunctionPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "toptierCode": null,
  "fiscalYear": null,
  "pageMetadata": null,
  "results": null,
  "messages": null,
} satisfies ApiV2AgencyToptierCodeBudgetFunctionPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AgencyToptierCodeBudgetFunctionPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


