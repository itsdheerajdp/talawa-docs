[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Organization/pinnedPosts](../README.md) / pinnedPosts

# Variable: pinnedPosts

\> `const` **pinnedPosts**: [`OrganizationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/OrganizationResolvers.md)\[`"pinnedPosts"`\]

Resolver function for the `pinnedPosts` field of an `Organization`.

This function retrieves the posts that are pinned by a specific organization.

## Param

The parent object representing the organization. It contains information about the organization, including the IDs of the posts that are pinned.

## See

 - Post - The Post model used to interact with the posts collection in the database.
 - OrganizationResolvers - The type definition for the resolvers of the Organization fields.

## Defined in

[src/resolvers/Organization/pinnedPosts.ts:18](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/Organization/pinnedPosts.ts#L18)