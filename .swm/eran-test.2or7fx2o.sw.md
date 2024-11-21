---
title: eran test
---
<SwmSnippet path="/fixtures/dom/src/toWarnDev.js" line="140">

---

this is snippet with empty line

```javascript

        let errorMessage;
        if (expectedMessages.length === 0) {
          errorMessage =
            'Unexpected warning recorded: ' +
            this.utils.printReceived(normalizedMessage);
        } else if (expectedMessages.length === 1) {
          errorMessage =
            'Unexpected warning recorded: ' +
            jestDiff(expectedMessages[0], normalizedMessage);
        } else {
          errorMessage =
            'Unexpected warning recorded: ' +
            jestDiff(expectedMessages, [normalizedMessage]);
        }
```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBcmVhY3QlM0ElM0FJZGl0WWVnZXJTd2ltbQ==" repo-name="react"><sup>Powered by [Swimm](https://staging.swimm.cloud/)</sup></SwmMeta>
