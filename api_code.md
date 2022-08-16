### Success Methods
| Method | Status code | Description |
|---|---|---|
|ok|200|Successful get, patch (return a JSON object)|
|created|201|Successful post (return a JSON object)|
|noContent|204|Successful delete|

### Error Status

| Method | Status code | Description |
|---|---|---|
|unauthorized|401|Not authenticated|
|invalid|403|Authenticated, but no permissions|
|notFound|404|Not Found|
|invalid|422|Validation|

### Extra methods

| Method | Status code | Description |
|---|---|---|
|accepted|202|Successful post, delete, path - async|
|badRequest|400|The request could not be understood by the server due to malformed syntax|
|paymentRequired|402|Payment required|
