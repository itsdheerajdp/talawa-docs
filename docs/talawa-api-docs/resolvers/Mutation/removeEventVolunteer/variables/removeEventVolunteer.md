[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/removeEventVolunteer](../README.md) / removeEventVolunteer

# Variable: removeEventVolunteer

> `const` **removeEventVolunteer**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"removeEventVolunteer"`\]

This function enables to remove an Event Volunteer.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the current user exists
2. If the Event volunteer to be removed exists.
3. If the current user is leader of the corresponding event volunteer group.

## Defined in

[src/resolvers/Mutation/removeEventVolunteer.ts:25](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/removeEventVolunteer.ts#L25)
