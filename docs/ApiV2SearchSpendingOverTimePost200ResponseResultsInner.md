
# ApiV2SearchSpendingOverTimePost200ResponseResultsInner


## Properties

Name | Type
------------ | -------------
`timePeriod` | [ApiV2SearchSpendingOverTimePost200ResponseResultsInnerTimePeriod](ApiV2SearchSpendingOverTimePost200ResponseResultsInnerTimePeriod.md)
`aggregatedAmount` | number
`contractObligations` | number
`loanObligations` | number
`idvObligations` | number
`grantObligations` | number
`directObligations` | number
`otherObligations` | number
`totalOutlays` | number
`contractOutlays` | number
`loanOutlays` | number
`idvOutlays` | number
`grantOutlays` | number
`directOutlays` | number
`otherOutlays` | number

## Example

```typescript
import type { ApiV2SearchSpendingOverTimePost200ResponseResultsInner } from ''

// TODO: Update the object below with actual values
const example = {
  "timePeriod": null,
  "aggregatedAmount": null,
  "contractObligations": null,
  "loanObligations": null,
  "idvObligations": null,
  "grantObligations": null,
  "directObligations": null,
  "otherObligations": null,
  "totalOutlays": null,
  "contractOutlays": null,
  "loanOutlays": null,
  "idvOutlays": null,
  "grantOutlays": null,
  "directOutlays": null,
  "otherOutlays": null,
} satisfies ApiV2SearchSpendingOverTimePost200ResponseResultsInner

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2SearchSpendingOverTimePost200ResponseResultsInner
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


