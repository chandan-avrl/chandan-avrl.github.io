---
title: Convert Python objects into a json string
layout: base
excerpt_separator: <!--more-->
categories: 
- Convert Python objects into a json string
---
### ujson_dumps(d, pretty_print=False)
&emsp; This function converts a subset of convertible Python objects into a json string.
<!--more-->
###### input
```shell
>>> from mechanics import ujson_dumps 
>>> ujson_dumps({"key_a": "value_a", "key_b": "value_b"})
```
###### output
```shell
'{"key_a": "value_a", "key_b": "value_b"}'
```