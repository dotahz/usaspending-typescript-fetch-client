
# ApiV2AgencyAwardsCountPost200ResponsePageMetadata

Information used for pagination of results.

## Properties

Name | Type
------------ | -------------
`limit` | number
`page` | number
`next` | number
`previous` | number
`hasNext` | boolean
`hasPrevious` | boolean
`total` | number

## Example

```typescript
import type { ApiV2AgencyAwardsCountPost200ResponsePageMetadata } from ''

// TODO: Update the object below with actual values
const example = {
  "limit": null,
  "page": null,
  "next": null,
  "previous": null,
  "hasNext": null,
  "hasPrevious": null,
  "total": null,
} satisfies ApiV2AgencyAwardsCountPost200ResponsePageMetadata

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AgencyAwardsCountPost200ResponsePageMetadata
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


