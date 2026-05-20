
# ApiV2FederalAccountsAccountNumberPost200Response


## Properties

Name | Type
------------ | -------------
`fiscalYear` | number
`id` | number
`agencyIdentifier` | string
`mainAccountCode` | string
`federalAccountCode` | string
`accountTitle` | string
`parentAgencyToptierCode` | string
`parentAgencyName` | string
`bureauName` | string
`bureauSlug` | string
`totalObligatedAmount` | number
`totalGrossOutlayAmount` | number
`totalBudgetaryResources` | number
`children` | [Array&lt;ApiV2FederalAccountsAccountNumberPost200ResponseChildrenInner&gt;](ApiV2FederalAccountsAccountNumberPost200ResponseChildrenInner.md)

## Example

```typescript
import type { ApiV2FederalAccountsAccountNumberPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "fiscalYear": null,
  "id": null,
  "agencyIdentifier": null,
  "mainAccountCode": null,
  "federalAccountCode": null,
  "accountTitle": null,
  "parentAgencyToptierCode": null,
  "parentAgencyName": null,
  "bureauName": null,
  "bureauSlug": null,
  "totalObligatedAmount": null,
  "totalGrossOutlayAmount": null,
  "totalBudgetaryResources": null,
  "children": null,
} satisfies ApiV2FederalAccountsAccountNumberPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2FederalAccountsAccountNumberPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


