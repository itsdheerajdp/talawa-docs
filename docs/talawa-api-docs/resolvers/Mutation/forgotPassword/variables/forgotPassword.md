[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/forgotPassword](../README.md) / forgotPassword

# Variable: forgotPassword

> `const` **forgotPassword**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"forgotPassword"`\]

This function enables a user to restore password.

## Param

parent of current request

## Param

payload provided with the request

## Remarks

The following tasks are done:
1. Extracts email and otp out of otpToken.
2. Compares otpToken and otp.
3. Checks whether otp is valid.
4. Updates password field for user's document with email === email.

## Defined in

[src/resolvers/Mutation/forgotPassword.ts:23](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/forgotPassword.ts#L23)
