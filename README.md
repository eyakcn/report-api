# Report API

Based on Quasar and Kotlin

## Getting started

Currently 2 instrumentation methods can be chosen through the `method` property: `agent` and `aot`. To run them:

```
gradle -Pmethod=agent run
gradle -Pmethod=agent test
gradle -Pmethod=aot run
gradle -Pmethod=aot test
```
