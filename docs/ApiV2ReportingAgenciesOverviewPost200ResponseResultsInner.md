
# ApiV2ReportingAgenciesOverviewPost200ResponseResultsInner


## Properties

Name | Type
------------ | -------------
`agencyName` | string
`abbreviation` | string
`toptierCode` | string
`agencyId` | number
`currentTotalBudgetAuthorityAmount` | number
`recentPublicationDate` | string
`recentPublicationDateCertified` | boolean
`tasAccountDiscrepanciesTotals` | [Array&lt;ApiV2ReportingAgenciesOverviewPost200ResponseResultsInnerTasAccountDiscrepanciesTotalsInner&gt;](ApiV2ReportingAgenciesOverviewPost200ResponseResultsInnerTasAccountDiscrepanciesTotalsInner.md)
`obligationDifference` | number
`unlinkedContractAwardCount` | number
`unlinkedAssistanceAwardCount` | number
`assuranceStatementUrl` | string

## Example

```typescript
import type { ApiV2ReportingAgenciesOverviewPost200ResponseResultsInner } from ''

// TODO: Update the object below with actual values
const example = {
  "agencyName": null,
  "abbreviation": null,
  "toptierCode": null,
  "agencyId": null,
  "currentTotalBudgetAuthorityAmount": null,
  "recentPublicationDate": null,
  "recentPublicationDateCertified": null,
  "tasAccountDiscrepanciesTotals": null,
  "obligationDifference": null,
  "unlinkedContractAwardCount": null,
  "unlinkedAssistanceAwardCount": null,
  "assuranceStatementUrl": null,
} satisfies ApiV2ReportingAgenciesOverviewPost200ResponseResultsInner

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2ReportingAgenciesOverviewPost200ResponseResultsInner
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


