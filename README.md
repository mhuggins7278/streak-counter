#  `@mhuggins7278/streak-counter` - a basic streak counter


This is a  basic streak counter - inspired by Duoling - written in Tsypscript and meand for the browser (uses `localStorage`)


## Install
```shell
pnpm add @mhuggins7278/streak-counter
npm install @mhuggins7278/streak-counter

```

## Usage

```js
import {streakCounter} from '@mhuggins7278/streak-counter'

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns and object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021"
//    startDate: "11/11/2021"
//  }

```
