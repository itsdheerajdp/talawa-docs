[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [utilities/createSampleOrganizationUtil](../README.md) / generatePostData

# Function: generatePostData()

\> **generatePostData**(`users`, `organizationId`): `Promise`\<[`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md) & `Document`\<`any`, `any`, [`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md)\>\>

Generates post data for a given list of users and organization.

## Parameters

• **users**: [`InterfaceUser`](../../../models/User/interfaces/InterfaceUser.md)[]

The list of users associated with the post

• **organizationId**: `string`

The ID of the organization the post belongs to

## Returns

`Promise`\<[`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md) & `Document`\<`any`, `any`, [`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md)\>\>

A promise that resolves to the created post

## Defined in

[src/utilities/createSampleOrganizationUtil.ts:151](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/utilities/createSampleOrganizationUtil.ts#L151)