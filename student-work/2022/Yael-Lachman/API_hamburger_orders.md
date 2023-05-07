## Hamburger API documentation

## The process of ordering a hamburger

```mermaid
  graph TD;
  A((Start))-->B[New order]
  B-->C{Choose a food}
  C-->D[Hamburger]
  D-->E{Choose a bun}
  E-->F[White]
  E-->G[Whole wheat]
  E-->H[Spelt]
  E-->I[Gluten free]
  F-->J{Choose a patty}
  G-->J
  H-->J
  I-->J
  J-->K[Beef]
  J-->L[Beyond]
  J-->M[Portobello]
  J-->N[Soya]
  K-->O{Choose a size}
  L-->O
  M-->O
  N-->O
  O-->P[150g]
  O-->Q[300g]
  O-->R[450g]
  P-->S{Choose doneness}
  Q-->S
  R-->S
  S-->T[Well-done]
  S-->U[Medium]
  S-->V[Rare]
  T-->W{Choose toppings}
  U-->W
  V-->W
  W-->X[Lettuce]
  W-->Y[Tomato]
  W-->Z[White cabbage]
  W-->AA[Red cabbage]
  W-->AB[Fried onions]
  W-->AC[Raw onions]
  X-->BA{Choose another dressing?}
  BA-->BB[Yes]
  BB-->W
  BA-->BC[No]
  BC-->AD{Choose a sauce}
  Y-->BA
  Z-->BA
  AA-->BA
  AB-->BA
  AC-->BA
  AD-->AE[Ketchup]
  AD-->AF[Mustard]
  AD-->AG[BBQ]
  AD-->AH[Garlic Mayonnaise]
  AD-->AI[Teriyaki]
  AD-->AJ[Thousand Island]
  AD-->AK[Honey Mustard]
  AD-->AL[Sweet Chilli]
  AD-->AM[Sweet & Sour]
  AE-->AN{Choose another sauce?}
  AN-->AO[Yes]
  AO-->AD
  AN-->AP[No]
  AP-->AQ{Choose another item?}
  AQ-->AR[Yes]
  AR-->AS[No]<----END
  AR-->AT{Choose item type}
  AT-->AU[Side dish]
  AT-->AV[Drink]
  AU-->AW[Chips]
  AU-->AX[Sweet potato chips]
  AU-->AY[Onion rings]
  AU-->AZ[Potato croquettes]
  AU-->AAA[Home fries]
  AU-->AAB[Salad]
  AU-->AAC[Coleslaw]
  AV-->AAD[Coke/ Coke Zero]
  AV-->AAE[Fanta/ Fanta Zero]
  AV-->AAF[Capri Sun]
  AV-->AAG[Apple Cider]
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
