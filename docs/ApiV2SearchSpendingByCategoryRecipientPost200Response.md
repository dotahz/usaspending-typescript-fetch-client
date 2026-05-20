
# ApiV2SearchSpendingByCategoryRecipientPost200Response


## Properties

Name | Type
------------ | -------------
`category` | string
`spendingLevel` | string
`results` | [Array&lt;ApiV2SearchSpendingByCategoryRecipientPost200ResponseResultsInner&gt;](ApiV2SearchSpendingByCategoryRecipientPost200ResponseResultsInner.md)
`limit` | number
`pageMetadata` | [ApiV2SearchSpendingByCategoryPost200ResponsePageMetadata](ApiV2SearchSpendingByCategoryPost200ResponsePageMetadata.md)
`messages` | Array&lt;string | null&gt;

## Example

```typescript
import type { ApiV2SearchSpendingByCategoryRecipientPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "category": null,
  "spendingLevel": null,
  "results": null,
  "limit": null,
  "pageMetadata": null,
  "messages": null,
} satisfies ApiV2SearchSpendingByCategoryRecipientPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2SearchSpendingByCategoryRecipientPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


