[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/updateAgendaCategory](../README.md) / updateAgendaCategory

# Variable: updateAgendaCategory

> `const` **updateAgendaCategory**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"updateAgendaCategory"`\]

This is a resolver function for the GraphQL mutation 'updateAgendaCategory'.

This resolver updates an existing agenda category based on the provided ID.
It checks if the user has the necessary permissions to update the agenda category.

## Param

The parent object, not used in this resolver.

## Param

The input arguments for the mutation.

## Param

The context object containing user information.

## Throws

`NotFoundError` If the agenda category or user is not found.

## Throws

`UnauthorizedError` If the user does not have the required permissions.

## Throws

`InternalServerError` For other potential issues during agenda category update.

## Defined in

[src/resolvers/Mutation/updateAgendaCategory.ts:36](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/updateAgendaCategory.ts#L36)
