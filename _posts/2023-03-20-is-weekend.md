---
title: Check if given date is weekend
layout: base
categories: 
- Check if given date is weekend
excerpt_separator: <!--more-->
---
### is_weekend(date_time_in_isoformat_or_dto)

&emsp; This function takes input datetime in iso format and returns whether the given date is weekend or not

<!--more-->

###### input

```shell
>>> import datetime
>>> from mechanics_utility_functions import is_weekend
>>> print(is_weekend(datetime.datetime.strptime("2023-03-20", "%Y-%m-%d")))
>>> print(is_weekend(datetime.datetime.strptime("2023-03-18", "%Y-%m-%d"))) 
```

###### output

```shell
False
True
```
