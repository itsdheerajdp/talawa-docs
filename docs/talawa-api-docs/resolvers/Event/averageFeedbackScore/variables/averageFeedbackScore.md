[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Event/averageFeedbackScore](../README.md) / averageFeedbackScore

# Variable: averageFeedbackScore

\> `const` **averageFeedbackScore**: [`EventResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/EventResolvers.md)\[`"averageFeedbackScore"`\]

Resolver function for the `averageFeedbackScore` field of an `Event`.

This function calculates the average feedback score for a specific event.

## Param

The parent object representing the event. It contains information about the event, including the ID of the feedback associated with it.

## See

 - Feedback - The Feedback model used to interact with the feedback collection in the database.
 - EventResolvers - The type definition for the resolvers of the Event fields.

## Defined in

[src/resolvers/Event/averageFeedbackScore.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/Event/averageFeedbackScore.ts#L16)