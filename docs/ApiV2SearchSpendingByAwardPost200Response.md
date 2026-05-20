
# ApiV2SearchSpendingByAwardPost200Response


## Properties

Name | Type
------------ | -------------
`spendingLevel` | string
`limit` | number
`results` | [Array&lt;ApiV2SearchSpendingByAwardPost200ResponseResultsInner&gt;](ApiV2SearchSpendingByAwardPost200ResponseResultsInner.md)
`pageMetadata` | [ApiV2SearchSpendingByAwardPost200ResponsePageMetadata](ApiV2SearchSpendingByAwardPost200ResponsePageMetadata.md)
`messages` | Array&lt;string | null&gt;

## Example

```typescript
import type { ApiV2SearchSpendingByAwardPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "spendingLevel": null,
  "limit": null,
  "results": null,
  "pageMetadata": null,
  "messages": null,
} satisfies ApiV2SearchSpendingByAwardPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2SearchSpendingByAwardPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


