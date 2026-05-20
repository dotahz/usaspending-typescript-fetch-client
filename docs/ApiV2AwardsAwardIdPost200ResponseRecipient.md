
# ApiV2AwardsAwardIdPost200ResponseRecipient


## Properties

Name | Type
------------ | -------------
`recipientName` | string
`recipientHash` | string
`recipientUei` | string
`recipientUniqueId` | string
`parentRecipientName` | string
`parentRecipientHash` | string
`parentRecipientUei` | string
`parentRecipientUniqueId` | string
`location` | [ApiV2AwardsAwardIdPost200ResponseRecipientLocation](ApiV2AwardsAwardIdPost200ResponseRecipientLocation.md)
`businessCategories` | Array&lt;string | null&gt;

## Example

```typescript
import type { ApiV2AwardsAwardIdPost200ResponseRecipient } from ''

// TODO: Update the object below with actual values
const example = {
  "recipientName": null,
  "recipientHash": null,
  "recipientUei": null,
  "recipientUniqueId": null,
  "parentRecipientName": null,
  "parentRecipientHash": null,
  "parentRecipientUei": null,
  "parentRecipientUniqueId": null,
  "location": null,
  "businessCategories": null,
} satisfies ApiV2AwardsAwardIdPost200ResponseRecipient

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AwardsAwardIdPost200ResponseRecipient
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


