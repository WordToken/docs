# Authentication

> To authorize, use this code:


```shell
# With shell, you can just pass the correct header with each request
curl "https://api.wordtoken.com/interlocutors"
  -H "Authorization: api_key"
```

```javascript
const wordToken = require('wordtoken')('api_key');

wordToken.interlocutors;
```

> Make sure to replace `api_key` with your generated API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

-- Token should be revokable, resetted, generated.

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>