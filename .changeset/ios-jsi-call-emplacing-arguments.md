---
'expo-modules-jsi': patch
---

[iOS] Add `JavaScriptFunction.call(argumentCount:emplacing:)` and `call(argumentCount:returning:emplacing:)`, and public `JavaScriptValuesBuffer.emplace` methods, to call a JavaScript function with any `JavaScriptEncodable` arguments, and fill the values of `JavaScriptValuesBuffer.allocate(in:capacity:)` with `undefined`.
