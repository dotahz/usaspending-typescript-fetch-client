
# ApiV2ReferencesSubmissionPeriodsPost200ResponseAvailablePeriodsInner


## Properties

Name | Type
------------ | -------------
`periodStartDate` | string
`periodEndDate` | string
`submissionStartDate` | string
`submissionDueDate` | string
`certificationDueDate` | string
`submissionRevealDate` | string
`submissionFiscalYear` | number
`submissionFiscalQuarter` | number
`submissionFiscalMonth` | number
`isQuarter` | boolean

## Example

```typescript
import type { ApiV2ReferencesSubmissionPeriodsPost200ResponseAvailablePeriodsInner } from ''

// TODO: Update the object below with actual values
const example = {
  "periodStartDate": null,
  "periodEndDate": null,
  "submissionStartDate": null,
  "submissionDueDate": null,
  "certificationDueDate": null,
  "submissionRevealDate": null,
  "submissionFiscalYear": null,
  "submissionFiscalQuarter": null,
  "submissionFiscalMonth": null,
  "isQuarter": null,
} satisfies ApiV2ReferencesSubmissionPeriodsPost200ResponseAvailablePeriodsInner

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2ReferencesSubmissionPeriodsPost200ResponseAvailablePeriodsInner
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


