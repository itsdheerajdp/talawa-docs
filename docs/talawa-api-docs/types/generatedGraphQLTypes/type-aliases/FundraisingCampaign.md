[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / FundraisingCampaign

# Type Alias: FundraisingCampaign

> **FundraisingCampaign**: `object`

## Type declaration

### \_\_typename?

> `optional` **\_\_typename**: `"FundraisingCampaign"`

### \_id

> **\_id**: [`Scalars`](Scalars.md)\[`"ID"`\]\[`"output"`\]

### createdAt

> **createdAt**: [`Scalars`](Scalars.md)\[`"DateTime"`\]\[`"output"`\]

### currency

> **currency**: [`Currency`](Currency.md)

### endDate

> **endDate**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

### fundId

> **fundId**: [`Fund`](Fund.md)

### fundingGoal

> **fundingGoal**: [`Scalars`](Scalars.md)\[`"Float"`\]\[`"output"`\]

### name

> **name**: [`Scalars`](Scalars.md)\[`"String"`\]\[`"output"`\]

### organizationId

> **organizationId**: [`Organization`](Organization.md)

### pledges?

> `optional` **pledges**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`FundraisingCampaignPledge`](FundraisingCampaignPledge.md)\>[]\>

### startDate

> **startDate**: [`Scalars`](Scalars.md)\[`"Date"`\]\[`"output"`\]

### updatedAt

> **updatedAt**: [`Scalars`](Scalars.md)\[`"DateTime"`\]\[`"output"`\]

## Defined in

[src/types/generatedGraphQLTypes.ts:962](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/types/generatedGraphQLTypes.ts#L962)
