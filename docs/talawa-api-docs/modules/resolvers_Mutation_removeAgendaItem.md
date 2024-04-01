[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Mutation/removeAgendaItem

# Module: resolvers/Mutation/removeAgendaItem

## Table of contents

### Variables

- [removeAgendaItem](resolvers_Mutation_removeAgendaItem.md#removeagendaitem)

## Variables

### removeAgendaItem

• `Const` **removeAgendaItem**: [`MutationResolvers`](types_generatedGraphQLTypes.md#mutationresolvers)[``"removeAgendaItem"``]

This function removes an agenda item.

**`Param`**

parent of the current request

**`Param`**

payload provided with the request

**`Param`**

context of the entire application

**`Throws`**

NotFoundError if the user or agenda item is not found

**`Throws`**

UnauthorizedError if the user is not the creator of the agenda item

#### Defined in

[src/resolvers/Mutation/removeAgendaItem.ts:20](https://github.com/PalisadoesFoundation/talawa-api/blob/e5f7a9d/src/resolvers/Mutation/removeAgendaItem.ts#L20)