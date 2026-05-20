
# ApiV2RecipientStateFipsPost200Response


## Properties

Name | Type
------------ | -------------
`name` | string
`code` | string
`fips` | string
`type` | string
`population` | number
`popYear` | number
`medianHouseholdIncome` | number
`mhiYear` | number
`totalPrimeAmount` | number
`totalPrimeAwards` | number
`totalFaceValueLoanAmount` | number
`totalFaceValueLoanPrimeAwards` | number
`awardAmountPerCapita` | number
`totalOutlays` | number

## Example

```typescript
import type { ApiV2RecipientStateFipsPost200Response } from ''

// TODO: Update the object below with actual values
const example = {
  "name": null,
  "code": null,
  "fips": null,
  "type": null,
  "population": null,
  "popYear": null,
  "medianHouseholdIncome": null,
  "mhiYear": null,
  "totalPrimeAmount": null,
  "totalPrimeAwards": null,
  "totalFaceValueLoanAmount": null,
  "totalFaceValueLoanPrimeAwards": null,
  "awardAmountPerCapita": null,
  "totalOutlays": null,
} satisfies ApiV2RecipientStateFipsPost200Response

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2RecipientStateFipsPost200Response
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


