[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/DirectChatMessage/directChatMessageBelongsTo](../README.md) / directChatMessageBelongsTo

# Variable: directChatMessageBelongsTo

> `const` **directChatMessageBelongsTo**: [`DirectChatMessageResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/DirectChatMessageResolvers.md)\[`"directChatMessageBelongsTo"`\]

Resolver function for the `directChatMessageBelongsTo` field of a `DirectChatMessage`.

This function retrieves the direct chat to which a specific direct chat message belongs.

## Param

The parent object representing the direct chat message. It contains information about the direct chat message, including the ID of the direct chat to which it belongs.

## See

 - DirectChat - The DirectChat model used to interact with the direct chats collection in the database.
 - DirectChatMessageResolvers - The type definition for the resolvers of the DirectChatMessage fields.

## Defined in

[src/resolvers/DirectChatMessage/directChatMessageBelongsTo.ts:18](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/DirectChatMessage/directChatMessageBelongsTo.ts#L18)
