# Introduction

The KPN SenML library helps you create and parse [senml documents](https://tools.ietf.org/html/draft-ietf-core-senml-13)
in both json and cbor format.

The mentions of `Base64.h` have been replaced with `MyBase64.h` in `senml_binary_actuator.cpp` and `senml_helpers.cpp`.

# key features

- Object oriented design.
- built in support for [senml's unit registry](https://tools.ietf.org/html/draft-ietf-core-senml-12#section-12.1)
- extensible for new data types
- makes use of (but doesn't restrict to) KPN's predefined list of record names.
- direct support to read/write in json and cbor format.
- automatically adjusts record data with respect to base time, base value & base sum.

Please visit our [docs site](https://kpn-iot.github.io/senml-c-library) for more info.

