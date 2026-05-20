
# ApiV2SearchSpendingByTransactionPost200Response


## Properties

Name | Type
------------ | -------------
`results` | [Array&lt;ApiV2SearchSpendingByTransactionPost200ResponseResultsInner&gt;](ApiV2SearchSpendingByTransactionPost200ResponseResultsInner.md)
`pageMetadata` | [ApiV2AwardsFundingPost200ResponsePageMetadata](ApiV2AwardsFundingPost200ResponsePageMetadata.md)
`limit` | number

## Example

```typescript
import type { ApiV2SearchSpendingByTransactionPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "results": null,
  "pageMetadata": null,
  "limit": null,
} satisfies ApiV2SearchSpendingByTransactionPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2SearchSpendingByTransactionPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


