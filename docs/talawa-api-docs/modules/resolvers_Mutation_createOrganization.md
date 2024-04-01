[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Mutation/createOrganization

# Module: resolvers/Mutation/createOrganization

## Table of contents

### Variables

- [createOrganization](resolvers_Mutation_createOrganization.md#createorganization)

## Variables

### createOrganization

• `Const` **createOrganization**: [`MutationResolvers`](types_generatedGraphQLTypes.md#mutationresolvers)[``"createOrganization"``]

This function enables to create an organization.

**`Param`**

parent of current request

**`Param`**

payload provided with the request

**`Param`**

context of entire application

**`Remarks`**

The following checks are done:
1. If the user exists
2. If the user has appUserProfile

#### Defined in

[src/resolvers/Mutation/createOrganization.ts:33](https://github.com/PalisadoesFoundation/talawa-api/blob/e5f7a9d/src/resolvers/Mutation/createOrganization.ts#L33)