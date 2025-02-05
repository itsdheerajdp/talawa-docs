[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [setup/MongoDB](../README.md) / checkExistingMongoDB

# Function: checkExistingMongoDB()

> **checkExistingMongoDB**(): `Promise`\<`string` \| `null`\>

The `checkExistingMongoDB` function checks for an existing MongoDB URL in the environment variables and attempts to establish a connection.

It performs the following steps:
1. Retrieves the MongoDB URL from the environment variables.
2. If no URL is found, it immediately returns null.
3. If a URL is found, it attempts to establish a connection using the `checkConnection` function.
   - If the connection is successful (i.e., `checkConnection` returns true), it returns the URL.
   - If the connection fails (i.e., `checkConnection` returns false), it returns null.

This function is used during the initial setup process to check if a valid MongoDB connection can be made with the existing URL in the environment variables.

## Returns

`Promise`\<`string` \| `null`\>

A promise that resolves to a string (if a connection could be made to the existing URL) or null (if no existing URL or connection could not be made).

## Defined in

[src/setup/MongoDB.ts:17](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/setup/MongoDB.ts#L17)
