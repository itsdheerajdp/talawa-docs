[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/UserFamily/users](../README.md) / users

# Variable: users

\> `const` **users**: [`UserFamilyResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/UserFamilyResolvers.md)\[`"users"`\]

Resolver function for the `users` field of a `UserFamily`.

This function retrieves the users who are part of a specific user family.

## Param

The parent object representing the user family. It contains information about the user family, including the IDs of the users who are part of it.

## See

 - User - The User model used to interact with the users collection in the database.
 - UserFamilyResolvers - The type definition for the resolvers of the UserFamily fields.

## Defined in

[src/resolvers/UserFamily/users.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/UserFamily/users.ts#L16)