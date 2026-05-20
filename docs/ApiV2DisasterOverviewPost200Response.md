
# ApiV2DisasterOverviewPost200Response


## Properties

Name | Type
------------ | -------------
`funding` | [Array&lt;ApiV2DisasterOverviewPost200ResponseFundingInner&gt;](ApiV2DisasterOverviewPost200ResponseFundingInner.md)
`totalBudgetAuthority` | number
`spending` | [ApiV2DisasterOverviewPost200ResponseSpending](ApiV2DisasterOverviewPost200ResponseSpending.md)
`additional` | object

## Example

```typescript
import type { ApiV2DisasterOverviewPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "funding": null,
  "totalBudgetAuthority": null,
  "spending": null,
  "additional": null,
} satisfies ApiV2DisasterOverviewPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2DisasterOverviewPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


