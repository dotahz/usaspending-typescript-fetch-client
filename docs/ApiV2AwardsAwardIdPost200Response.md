
# ApiV2AwardsAwardIdPost200Response


## Properties

Name | Type
------------ | -------------
`id` | number
`category` | string
`type` | string
`typeDescription` | string
`generatedUniqueAwardId` | string
`piid` | string
`description` | string
`totalObligation` | number
`baseExercisedOptions` | number
`baseAndAllOptions` | number
`dateSigned` | string
`subawardCount` | number
`totalSubawardAmount` | number
`awardingAgency` | [ApiV2AwardsAwardIdPost200ResponseAwardingAgency](ApiV2AwardsAwardIdPost200ResponseAwardingAgency.md)
`fundingAgency` | [ApiV2AwardsAwardIdPost200ResponseFundingAgency](ApiV2AwardsAwardIdPost200ResponseFundingAgency.md)
`recipient` | [ApiV2AwardsAwardIdPost200ResponseRecipient](ApiV2AwardsAwardIdPost200ResponseRecipient.md)
`periodOfPerformance` | [ApiV2AwardsAwardIdPost200ResponsePeriodOfPerformance](ApiV2AwardsAwardIdPost200ResponsePeriodOfPerformance.md)
`placeOfPerformance` | [ApiV2AwardsAwardIdPost200ResponsePlaceOfPerformance](ApiV2AwardsAwardIdPost200ResponsePlaceOfPerformance.md)
`latestTransactionContractData` | [ApiV2AwardsAwardIdPost200ResponseLatestTransactionContractData](ApiV2AwardsAwardIdPost200ResponseLatestTransactionContractData.md)
`executiveDetails` | [ApiV2AwardsAwardIdPost200ResponseExecutiveDetails](ApiV2AwardsAwardIdPost200ResponseExecutiveDetails.md)
`parentAward` | [ApiV2AwardsAwardIdPost200ResponseParentAward](ApiV2AwardsAwardIdPost200ResponseParentAward.md)
`naicsHierarchy` | [ApiV2AwardsAwardIdPost200ResponseNaicsHierarchy](ApiV2AwardsAwardIdPost200ResponseNaicsHierarchy.md)
`pscHierarchy` | [ApiV2AwardsAwardIdPost200ResponsePscHierarchy](ApiV2AwardsAwardIdPost200ResponsePscHierarchy.md)
`totalAccountOutlay` | number
`totalAccountObligation` | number
`accountObligationsByDefc` | [Array&lt;ApiV2AwardsAwardIdPost200ResponseAccountObligationsByDefcInner&gt;](ApiV2AwardsAwardIdPost200ResponseAccountObligationsByDefcInner.md)
`accountOutlaysByDefc` | [Array&lt;ApiV2AwardsAwardIdPost200ResponseAccountObligationsByDefcInner&gt;](ApiV2AwardsAwardIdPost200ResponseAccountObligationsByDefcInner.md)
`totalOutlay` | number

## Example

```typescript
import type { ApiV2AwardsAwardIdPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "category": null,
  "type": null,
  "typeDescription": null,
  "generatedUniqueAwardId": null,
  "piid": null,
  "description": null,
  "totalObligation": null,
  "baseExercisedOptions": null,
  "baseAndAllOptions": null,
  "dateSigned": null,
  "subawardCount": null,
  "totalSubawardAmount": null,
  "awardingAgency": null,
  "fundingAgency": null,
  "recipient": null,
  "periodOfPerformance": null,
  "placeOfPerformance": null,
  "latestTransactionContractData": null,
  "executiveDetails": null,
  "parentAward": null,
  "naicsHierarchy": null,
  "pscHierarchy": null,
  "totalAccountOutlay": null,
  "totalAccountObligation": null,
  "accountObligationsByDefc": null,
  "accountOutlaysByDefc": null,
  "totalOutlay": null,
} satisfies ApiV2AwardsAwardIdPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AwardsAwardIdPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


