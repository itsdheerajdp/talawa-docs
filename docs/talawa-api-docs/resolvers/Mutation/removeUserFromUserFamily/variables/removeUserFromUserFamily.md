[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/removeUserFromUserFamily](../README.md) / removeUserFromUserFamily

# Variable: removeUserFromUserFamily

> `const` **removeUserFromUserFamily**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"removeUserFromUserFamily"`\]

This function enables to remove a user from group chat.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire publication

## Remarks

The following checks are done:
1. If the family exists.
2. If the user to be removed is member of the organisation.
3. If the user is admin of the family

## Defined in

[src/resolvers/Mutation/removeUserFromUserFamily.ts:29](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/removeUserFromUserFamily.ts#L29)
