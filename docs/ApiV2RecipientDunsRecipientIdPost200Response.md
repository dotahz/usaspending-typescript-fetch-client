
# ApiV2RecipientDunsRecipientIdPost200Response


## Properties

Name | Type
------------ | -------------
`name` | string
`alternateNames` | Array&lt;string&gt;
`duns` | string
`uei` | string
`recipientId` | string
`parents` | [Array&lt;ApiV2RecipientDunsRecipientIdPost200ResponseParentsInner&gt;](ApiV2RecipientDunsRecipientIdPost200ResponseParentsInner.md)
`parentName` | string
`parentDuns` | string
`parentId` | string
`parentUei` | string
`location` | [ApiV2RecipientDunsRecipientIdPost200ResponseLocation](ApiV2RecipientDunsRecipientIdPost200ResponseLocation.md)
`businessTypes` | Array&lt;string&gt;
`totalTransactionAmount` | number
`totalTransactions` | number
`totalFaceValueLoanAmount` | number
`totalFaceValueLoanTransactions` | number
`recipientLevel` | string

## Example

```typescript
import type { ApiV2RecipientDunsRecipientIdPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "name": null,
  "alternateNames": null,
  "duns": null,
  "uei": null,
  "recipientId": null,
  "parents": null,
  "parentName": null,
  "parentDuns": null,
  "parentId": null,
  "parentUei": null,
  "location": null,
  "businessTypes": null,
  "totalTransactionAmount": null,
  "totalTransactions": null,
  "totalFaceValueLoanAmount": null,
  "totalFaceValueLoanTransactions": null,
  "recipientLevel": null,
} satisfies ApiV2RecipientDunsRecipientIdPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2RecipientDunsRecipientIdPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


