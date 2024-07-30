[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/AgendaSection/createdBy](../README.md) / createdBy

# Variable: createdBy

\> `const` **createdBy**: [`AgendaSectionResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/AgendaSectionResolvers.md)\[`"createdBy"`\]

Resolver function for the `createdBy` field of an `AgendaSection`.

This function retrieves the user who created a specific agenda section.

## Param

The parent object representing the agenda section. It contains information about the agenda section, including the ID of the user who created it.

## See

 - User - The User model used to interact with the users collection in the database.
 - AgendaSectionResolvers - The type definition for the resolvers of the AgendaSection fields.

## Defined in

[src/resolvers/AgendaSection/createdBy.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/AgendaSection/createdBy.ts#L16)