## Hamburger API documentation

## Order process overview

```mermaid
  graph TD;
  A((Start))-->B[New order]
  B-->AB{Choose food}
  AB-->C[Hamburger]
  C-->D{Choose bun}
  D-->E{Choose patty}
  E-->F{Choose size}
  F-->G{Choose doneness}
  G-->H{Choose toppings}
  H-->I{Choose sauces}
  I-->J{Choose side dish}
  J-->K{Choose size}
  K-->L{Choose drink}
  L-->M{Choose size}
  M-->N((End))
```


## Overview

### GET- retrieve the bill
### POST- submit the order

Table exmaple from the good docs:

The {product} APIs use the following standard HTTP response codes:

| Status code | Message           | Description   |
|-------------|-------------------|---------------|
| `200 OK`    | Request succeeds. | {description} |
|             |                   |               |
|             |                   |               |
