---
title: Convert datetime object to string
layout: base
excerpt_separator: <!--more-->
categories: 
- Date Manipulation
---
### format_df_to_str(d)
&emsp; It takes an input as a datetime object and converts it into a datetime string in ''%Y-%m-%d’' format.
<!--more-->
##### input
```python
>>> import datetime
>>> from mechanics import format_df_to_str
>>> print(format_df_to_str(datetime.datetime.now()))
```
##### output
```python
2023-03-20
```