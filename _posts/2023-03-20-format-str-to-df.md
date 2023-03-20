---
title: Convert string to datetime object
layout: base
excerpt_separator: <!--more-->
categories: 
- Date Manipulation
---
### format_str_to_df(s)
&emsp; It takes an input as a datetime string in "%Y-%m-%d" format and converts it into a datetime object.
<!--more-->
##### input:
```python
>>> from mechanics import format_str_to_df
>>> format_str_to_df("2023-03-20")
```
##### output
```python
datetime.datetime(2023, 3, 20, 0, 0)
```