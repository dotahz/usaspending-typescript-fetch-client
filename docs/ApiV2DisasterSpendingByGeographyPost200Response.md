
# ApiV2DisasterSpendingByGeographyPost200Response


## Properties

Name | Type
------------ | -------------
`geoLayer` | string
`scope` | string
`spendingType` | string
`results` | [Array&lt;ApiV2DisasterSpendingByGeographyPost200ResponseResultsInner&gt;](ApiV2DisasterSpendingByGeographyPost200ResponseResultsInner.md)

## Example

```typescript
import type { ApiV2DisasterSpendingByGeographyPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "geoLayer": null,
  "scope": null,
  "spendingType": null,
  "results": null,
} satisfies ApiV2DisasterSpendingByGeographyPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2DisasterSpendingByGeographyPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


