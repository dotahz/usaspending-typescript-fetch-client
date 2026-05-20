
# ApiV2ReportingAgenciesPublishDatesPost200ResponseResultsInner


## Properties

Name | Type
------------ | -------------
`agencyName` | string
`abbreviation` | string
`toptierCode` | string
`currentTotalBudgetAuthorityAmount` | number
`periods` | [Array&lt;ApiV2ReportingAgenciesPublishDatesPost200ResponseResultsInnerPeriodsInner&gt;](ApiV2ReportingAgenciesPublishDatesPost200ResponseResultsInnerPeriodsInner.md)

## Example

```typescript
import type { ApiV2ReportingAgenciesPublishDatesPost200ResponseResultsInner } from ''

// TODO: Update the object below with actual values
const example = {
  "agencyName": null,
  "abbreviation": null,
  "toptierCode": null,
  "currentTotalBudgetAuthorityAmount": null,
  "periods": null,
} satisfies ApiV2ReportingAgenciesPublishDatesPost200ResponseResultsInner

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2ReportingAgenciesPublishDatesPost200ResponseResultsInner
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


