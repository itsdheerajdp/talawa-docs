[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [utilities/graphQLConnection/getCommonGraphQLConnectionSort](../README.md) / getCommonGraphQLConnectionSort

# Function: getCommonGraphQLConnectionSort()

> **getCommonGraphQLConnectionSort**(`__namedParameters`): `CommmonGraphQLConnectionSort`

This function is used to get an object containing common mongoose sorting logic.

## Parameters

• **\_\_namedParameters**

• **\_\_namedParameters.direction**: [`GraphQLConnectionTraversalDirection`](../../type-aliases/GraphQLConnectionTraversalDirection.md)

## Returns

`CommmonGraphQLConnectionSort`

## Remarks

Here are a few assumptions this function makes which are common to most of the
graphQL connections.

The entity that has the latest creation datetime must appear at the top of the connection. This
means the default sorting logic would be sorting in descending order by the time of creation of
an entity, and if two or more entities have the same time of creation sorting in descending order
by the primary key of the entity. MongoDB object ids are lexographically sortable all on their own
because they contain information about both the creation time and primary key for the document.

Therefore, this function only returns sorting logic for sorting by the object id of a mongoDB
document.

## Example

```ts
const sort = getCommonGraphQLConnectionSort({
  direction: "BACKWARD"
 });
const objectList = await User.find().sort(sort).limit(10);
```

## Defined in

[src/utilities/graphQLConnection/getCommonGraphQLConnectionSort.ts:34](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/utilities/graphQLConnection/getCommonGraphQLConnectionSort.ts#L34)
