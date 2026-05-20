
# ApiV2AwardsAwardIdPost200ResponseParentAward

`null` if the idv has no parent

## Properties

Name | Type
------------ | -------------
`agencyId` | number
`agencyName` | string
`agencySlug` | string
`subAgencyId` | string
`subAgencyName` | string
`awardId` | number
`generatedUniqueAwardId` | string
`idvTypeDescription` | string
`multipleOrSingleAwDesc` | string
`piid` | string
`typeOfIdcDescription` | string

## Example

```typescript
import type { ApiV2AwardsAwardIdPost200ResponseParentAward } from ''

// TODO: Update the object below with actual values
const example = {
  "agencyId": null,
  "agencyName": null,
  "agencySlug": null,
  "subAgencyId": null,
  "subAgencyName": null,
  "awardId": null,
  "generatedUniqueAwardId": null,
  "idvTypeDescription": null,
  "multipleOrSingleAwDesc": null,
  "piid": null,
  "typeOfIdcDescription": null,
} satisfies ApiV2AwardsAwardIdPost200ResponseParentAward

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ApiV2AwardsAwardIdPost200ResponseParentAward
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


