---
title: test126
---
<SwmSnippet path="/scripts/flow/convertDecimalToBinary.js" line="2">

---

This code snippet converts a decimal number <SwmToken path="/scripts/flow/convertDecimalToBinary.js" pos="2:4:4" line-data="function convertToBinary(x) {">`x`</SwmToken> to its binary representation. It does this by repeatedly dividing <SwmToken path="/scripts/flow/convertDecimalToBinary.js" pos="2:4:4" line-data="function convertToBinary(x) {">`x`</SwmToken> by 2 and keeping track of the remainders. The binary representation is constructed by multiplying each remainder by a power of 10 and adding them up. The process is logged step by step, including the quotient and remainder at each step, and the resulting binary number is displayed at the end.

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
