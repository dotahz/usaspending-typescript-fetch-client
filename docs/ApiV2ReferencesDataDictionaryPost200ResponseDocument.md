
# ApiV2ReferencesDataDictionaryPost200ResponseDocument


## Properties

Name | Type
------------ | -------------
`metadata` | [ApiV2ReferencesDataDictionaryPost200ResponseDocumentMetadata](ApiV2ReferencesDataDictionaryPost200ResponseDocumentMetadata.md)
`sections` | [Array&lt;ApiV2ReferencesDataDictionaryPost200ResponseDocumentSectionsInner&gt;](ApiV2ReferencesDataDictionaryPost200ResponseDocumentSectionsInner.md)
`headers` | [Array&lt;ApiV2ReferencesDataDictionaryPost200ResponseDocumentHeadersInner&gt;](ApiV2ReferencesDataDictionaryPost200ResponseDocumentHeadersInner.md)
`rows` | Array&lt;Array&lt;string | null&gt;&gt;

## Example

```typescript
import type { ApiV2ReferencesDataDictionaryPost200ResponseDocument } from ''

// TODO: Update the object below with actual values
const example = {
  "metadata": null,
  "sections": null,
  "headers": null,
  "rows": null,
} satisfies ApiV2ReferencesDataDictionaryPost200ResponseDocument

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2ReferencesDataDictionaryPost200ResponseDocument
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


