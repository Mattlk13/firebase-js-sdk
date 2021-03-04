<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/messaging](./messaging.md) &gt; [deleteToken](./messaging.deletetoken.md)

## deleteToken() function

Deletes the registration token associated with this messaging instance and unsubscribes the messaging instance from the push subscription.

<b>Signature:</b>

```typescript
export declare function deleteToken(messaging: FirebaseMessaging): Promise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  messaging | [FirebaseMessaging](./messaging.firebasemessaging.md) | the messaging instance. |

<b>Returns:</b>

Promise&lt;boolean&gt;

The promise resolves when the token has been successfully deleted.
