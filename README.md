# @miciula/counters

Package with two counters `Counter` and `DecreasingCounter` constructors.

## Installation

```
npm install @miciula/counters

```

## Usage

To run demo app clone this repo and simply run:

```
npm instal
```

```
npm start
```

## API

every counter gets one argument - selector of element to be rendered in.
Countrer should be initialized after creation by calling `.init()` method

```javascript
import { Counter, DecreasingCounter } from '@miciula/counters'

const counter1 = new Counter ('.counter-1')
counter1.init()

const counter2 = new DecreasingCounter ('.counter-2')
counter2.init()
```