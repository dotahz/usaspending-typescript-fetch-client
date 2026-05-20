
# ApiV2SearchSpendingByGeographyPost200Response


## Properties

Name | Type
------------ | -------------
`scope` | string
`geoLayer` | string
`spendingLevel` | string
`results` | [Array&lt;ApiV2SearchSpendingByGeographyPost200ResponseResultsInner&gt;](ApiV2SearchSpendingByGeographyPost200ResponseResultsInner.md)
`messages` | Array&lt;string | null&gt;

## Example

```typescript
import type { ApiV2SearchSpendingByGeographyPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "scope": null,
  "geoLayer": null,
  "spendingLevel": null,
  "results": null,
  "messages": null,
} satisfies ApiV2SearchSpendingByGeographyPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2SearchSpendingByGeographyPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


