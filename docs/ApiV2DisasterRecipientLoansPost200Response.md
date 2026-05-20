
# ApiV2DisasterRecipientLoansPost200Response


## Properties

Name | Type
------------ | -------------
`totals` | [ApiV2DisasterRecipientLoansPost200ResponseTotals](ApiV2DisasterRecipientLoansPost200ResponseTotals.md)
`results` | [Array&lt;ApiV2DisasterRecipientLoansPost200ResponseResultsInner&gt;](ApiV2DisasterRecipientLoansPost200ResponseResultsInner.md)
`pageMetadata` | [ApiV2DisasterAgencyLoansPost200ResponsePageMetadata](ApiV2DisasterAgencyLoansPost200ResponsePageMetadata.md)

## Example

```typescript
import type { ApiV2DisasterRecipientLoansPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "totals": null,
  "results": null,
  "pageMetadata": null,
} satisfies ApiV2DisasterRecipientLoansPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2DisasterRecipientLoansPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


