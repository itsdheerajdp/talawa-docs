[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/updateFundCampaignPledge](../README.md) / updateFundraisingCampaignPledge

# Variable: updateFundraisingCampaignPledge

> `const` **updateFundraisingCampaignPledge**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"updateFundraisingCampaignPledge"`\]

This function enables to update a fundraising campaign pledge.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists.
2. If the FundraisingCampaignPledge exists.
3. If the user has made the pledge.
4. If the start date is valid.
5. If the end date is valid.

## Defined in

[src/resolvers/Mutation/updateFundCampaignPledge.ts:32](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/updateFundCampaignPledge.ts#L32)
