
# ApiV2ReportingAgenciesToptierCodeOverviewPost200ResponseResultsInner


## Properties

Name | Type
------------ | -------------
`fiscalYear` | number
`fiscalPeriod` | number
`currentTotalBudgetAuthorityAmount` | number
`totalBudgetaryResources` | number
`percentOfTotalBudgetaryResources` | number
`recentPublicationDate` | string
`recentPublicationDateCertified` | boolean
`tasAccountDiscrepanciesTotals` | [Array&lt;ApiV2ReportingAgenciesOverviewPost200ResponseResultsInnerTasAccountDiscrepanciesTotalsInner&gt;](ApiV2ReportingAgenciesOverviewPost200ResponseResultsInnerTasAccountDiscrepanciesTotalsInner.md)
`obligationDifference` | number
`unlinkedContractAwardCount` | number
`unlinkedAssistanceAwardCount` | number
`assuranceStatementUrl` | string

## Example

```typescript
import type { ApiV2ReportingAgenciesToptierCodeOverviewPost200ResponseResultsInner } from ''

// TODO: Update the object below with actual values
const example = {
  "fiscalYear": null,
  "fiscalPeriod": null,
  "currentTotalBudgetAuthorityAmount": null,
  "totalBudgetaryResources": null,
  "percentOfTotalBudgetaryResources": null,
  "recentPublicationDate": null,
  "recentPublicationDateCertified": null,
  "tasAccountDiscrepanciesTotals": null,
  "obligationDifference": null,
  "unlinkedContractAwardCount": null,
  "unlinkedAssistanceAwardCount": null,
  "assuranceStatementUrl": null,
} satisfies ApiV2ReportingAgenciesToptierCodeOverviewPost200ResponseResultsInner

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2ReportingAgenciesToptierCodeOverviewPost200ResponseResultsInner
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


