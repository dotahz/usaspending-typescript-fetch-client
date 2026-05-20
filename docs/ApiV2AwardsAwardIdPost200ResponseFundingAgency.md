
# ApiV2AwardsAwardIdPost200ResponseFundingAgency


## Properties

Name | Type
------------ | -------------
`id` | number
`hasAgencyPage` | boolean
`toptierAgency` | [ApiV2AwardsAwardIdPost200ResponseAwardingAgencyToptierAgency](ApiV2AwardsAwardIdPost200ResponseAwardingAgencyToptierAgency.md)
`subtierAgency` | [ApiV2AwardsAwardIdPost200ResponseAwardingAgencySubtierAgency](ApiV2AwardsAwardIdPost200ResponseAwardingAgencySubtierAgency.md)
`officeAgencyName` | string

## Example

```typescript
import type { ApiV2AwardsAwardIdPost200ResponseFundingAgency } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "hasAgencyPage": null,
  "toptierAgency": null,
  "subtierAgency": null,
  "officeAgencyName": null,
} satisfies ApiV2AwardsAwardIdPost200ResponseFundingAgency

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AwardsAwardIdPost200ResponseFundingAgency
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


