
# ApiV2AutocompleteGlossaryPost200Response


## Properties

Name | Type
------------ | -------------
`results` | Array&lt;string&gt;
`count` | number
`searchText` | string
`matchedTerms` | [Array&lt;ApiV2AutocompleteGlossaryPost200ResponseMatchedTermsInner&gt;](ApiV2AutocompleteGlossaryPost200ResponseMatchedTermsInner.md)

## Example

```typescript
import type { ApiV2AutocompleteGlossaryPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "results": null,
  "count": null,
  "searchText": null,
  "matchedTerms": null,
} satisfies ApiV2AutocompleteGlossaryPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AutocompleteGlossaryPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


