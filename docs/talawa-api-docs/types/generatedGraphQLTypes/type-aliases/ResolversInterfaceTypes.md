[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / ResolversInterfaceTypes

# Type Alias: ResolversInterfaceTypes\<_RefType\>

\> **ResolversInterfaceTypes**\<`_RefType`\>: `object`

Mapping of interface types

## Type Parameters

• **_RefType** *extends* `Record`\<`string`, `unknown`\>

## Type declaration

### ConnectionPageInfo

\> **ConnectionPageInfo**: [`DefaultConnectionPageInfo`](DefaultConnectionPageInfo.md)

### Error

\> **Error**: [`MemberNotFoundError`](MemberNotFoundError.md) \| [`OrganizationMemberNotFoundError`](OrganizationMemberNotFoundError.md) \| [`OrganizationNotFoundError`](OrganizationNotFoundError.md) \| [`PostNotFoundError`](PostNotFoundError.md) \| [`UnauthenticatedError`](UnauthenticatedError.md) \| [`UnauthorizedError`](UnauthorizedError.md) \| [`UserNotAuthorizedAdminError`](UserNotAuthorizedAdminError.md) \| [`UserNotAuthorizedError`](UserNotAuthorizedError.md) \| [`UserNotFoundError`](UserNotFoundError.md)

### FieldError

\> **FieldError**: [`InvalidCursor`](InvalidCursor.md) \| [`MaximumLengthError`](MaximumLengthError.md) \| [`MaximumValueError`](MaximumValueError.md) \| [`MinimumLengthError`](MinimumLengthError.md) \| [`MinimumValueError`](MinimumValueError.md)

## Defined in

[src/types/generatedGraphQLTypes.ts:3243](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/types/generatedGraphQLTypes.ts#L3243)