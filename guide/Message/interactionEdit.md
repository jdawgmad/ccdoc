# $interactionEdit
Edit a previously sent interaction with `$interactionReply`

#### Usage: `$interactionEdit[New Message;message id (optional, default is previously sent message)]`
<br/>
::: warning Just like $interactionreply, this function only works for interaction. 
Don't use it in exec or other triggertypes.
:::
<br/>
::: details Example
```
$interactionreply[Hello world!;yes]
$wait[2s]
$interactionedit[Bye World!]
```
![](https://cdn.discordapp.com/attachments/914682255346118687/937862286767435796/Screenshot_20220131210759.jpg)
:::

##### Function Difficultly: <Badge type="tip" text="Easy" vertical="middle" /> 
###### Tags: <Badge type="tip" text="interaction" vertical="middle" /> <Badge type="tip" text="edit" vertical="middle" /> <Badge type="tip" text="ephemeral" vertical="middle" /> <Badge type="tip" text="reply" vertical="middle" /> <Badge type="message" text="edit" vertical="middle" />