![cover](./images/cover.svg)

# Formatting
**Đây là bôi đậm**
*In nghiêng*
~~Gạch ngang~~
Một đoạn văn `thông thường`
> Đây là một `quotation`

# Table
| #   | Title 1   | Title 2   | Title 2 |
| --- | --------- | --------- | ------: |
| 1   | Content 1 | Content 2 |       2 |
| 2   | Content 1 | Content 2 |       2 |
| 3   | Content 1 | Content 2 |       2 |
| 4   | Content 1 | Content 2 |       2 |

# Code stype

```php
#php
echo 1
```

```sql
--sql
select * from table where abc = 1 and bcd = 'hello'
```

```js
//js
console.log(111)
console.log("Hello")
```

# Image
![![](2026-05-01-13-02-43.png)](image.png)

# Chart
## Mermaid

```mermaid
---
title: Bank example
---
classDiagram
    class BankAccount
    BankAccount : +String owner
    BankAccount : +Bigdecimal balance
    BankAccount : +deposit(amount)
    BankAccount : +withdrawal(amount)
```

## PlantUML

```plantuml
@startuml
:User: --> (Use)
"Main Admin" as Admin
"Use the application" as (Use)
Admin --> (Admin the application)
@enduml
```

# Calculation Formula

$y=x^2$

# Import file
