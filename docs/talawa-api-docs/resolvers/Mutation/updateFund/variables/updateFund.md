[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/updateFund](../README.md) / updateFund

# Variable: updateFund

\> `const` **updateFund**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"updateFund"`\]

This function enables to update an organization specific fund.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists.
2. If the Fund of the organization exists.
3. If the organization exists.
4.If the user is authorized to update the fund.
5. If the fund already exists with the same name.

## Defined in

[src/resolvers/Mutation/updateFund.ts:33](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/Mutation/updateFund.ts#L33)