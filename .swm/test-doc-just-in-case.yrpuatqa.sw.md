---
title: Test doc just in case
---
<SwmSnippet path="/scripts/flow/convertDecimalToBinary.js" line="2">

---

This code snippet `convertToBinary` converts a decimal number to its binary representation. It uses a while loop to repeatedly divide the input number by 2 and keep track of the remainder and quotient. The remainder is appended to the binary representation. The loop continues until the input number becomes 0. The binary representation is then printed to the console.

```javascript
function convertToBinary(x) {
    let bin = 0;
    let rem, i = 1, step = 1;
    while (x != 0) {
        rem = x % 2;
        console.log(
            `Step ${step++}: ${x}/2, Remainder = ${rem}, Quotient = ${parseInt(x/2)}`
        );
        x = parseInt(x / 2);
        bin = bin + rem * i;
        i = i * 10;
    }
    console.log(`Binary: ${bin}`);
}
```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBcmVhY3QlM0ElM0FJZGl0WWVnZXJTd2ltbQ==" repo-name="react"><sup>Powered by [Swimm](https://swimm-web-app.web.app/)</sup></SwmMeta>
