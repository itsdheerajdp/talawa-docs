[**talawa-api**](../../../../../README.md) • **Docs**

***

[talawa-api](../../../../../modules.md) / [helpers/event/updateEventHelpers/updateSingleEvent](../README.md) / updateSingleEvent

# Function: updateSingleEvent()

\> **updateSingleEvent**(`args`, `event`, `session`): `Promise`\<[`InterfaceEvent`](../../../../../models/Event/interfaces/InterfaceEvent.md)\>

This function updates a single non-recurring event.

## Parameters

• **args**: [`MutationUpdateEventArgs`](../../../../../types/generatedGraphQLTypes/type-aliases/MutationUpdateEventArgs.md)

the arguments provided for the updateEvent mutation.

• **event**: [`InterfaceEvent`](../../../../../models/Event/interfaces/InterfaceEvent.md)

the single event to be updated.

• **session**: `ClientSession`

## Returns

`Promise`\<[`InterfaceEvent`](../../../../../models/Event/interfaces/InterfaceEvent.md)\>

The updated event.

## Remarks

The following steps are followed:
1. If the single event is made recurring with this update:
  - get the appropriate data to create the baseRecurringEvent and recurring event instances.
  - generate the instances with createRecurringEvent function.
  - remove the current event and its associations as a new series has been created.
2. If it's still a non-recurring event:
  - just perform a regular update.

## Defined in

[src/helpers/event/updateEventHelpers/updateSingleEvent.ts:28](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/helpers/event/updateEventHelpers/updateSingleEvent.ts#L28)