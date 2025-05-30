---
{
  "title": "TO_DAYS",
  "language": "en"
}
---

<!-- 
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->


## Description
Date calculation function, which is used to convert a date into a day value, that is, to calculate the total number of days from December 31, 0 AD (the base date) to the specified date.

## Syntax

```sql
TO_DAYS(<datetime_or_date_value>)
```

## Required parameters
| Parameter                  | Description                       |
|----------------------------|-----------------------------------|
| `<datetime_or_date_value>` | `datetime` or `date` type date-time |


## Example

Query how many days are there since October 7, 2007
```sql
select to_days('2007-10-07');
```
```text
+---------------------------------------+
| to_days(cast('2007-10-07' as DATEV2)) |
+---------------------------------------+
|                                733321 |
+---------------------------------------+
```

```sql
select to_days('2007-10-07 10:03:09');
```
```text
+------------------------------------------------+
| to_days(cast('2007-10-07 10:03:09' as DATEV2)) |
+------------------------------------------------+
|                                         733321 |
+------------------------------------------------+
```
