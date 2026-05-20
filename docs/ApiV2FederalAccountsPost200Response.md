
# ApiV2FederalAccountsPost200Response


## Properties

Name | Type
------------ | -------------
`previous` | number
`count` | number
`limit` | number
`hasNext` | boolean
`page` | number
`hasPrevious` | boolean
`next` | number
`fy` | string
`results` | [Array&lt;ApiV2FederalAccountsPost200ResponseResultsInner&gt;](ApiV2FederalAccountsPost200ResponseResultsInner.md)

## Example

```typescript
import type { ApiV2FederalAccountsPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "previous": null,
  "count": null,
  "limit": null,
  "hasNext": null,
  "page": null,
  "hasPrevious": null,
  "next": null,
  "fy": null,
  "results": null,
} satisfies ApiV2FederalAccountsPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2FederalAccountsPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


