---
title: Group Dm Add Recipient
category: Channel
order: 24
---

# `groupDmAddRecipient`

```php
$client->channel->groupDmAddRecipient($parameters);
```

## Description

Adds a recipient to a Group DM using their access token

## Parameters


Name | Type | Required | Default
--- | --- | --- | ---
access_token | string | false | *null*
nick | string | false | *null*
channel.id | snowflake | true | *null*
user.id | snowflake | true | *null*

## Response

Possibly No Response
