# `@novicedev7291/streak-counter` - a basic streak counter
A typescript implementation of duolingo and meant for browser only (localstorage)

## Install

```shell
yarn add @novicedev7291/streak-counter
```
or

```shell
npm install @novicedev7291/streak-counter
```

## Usage
```typescript
import {streakCounter} from "@novicedev7291/streak-counter";

const today = new Date();
const streak = streakCounter(localStorage, today);
// streak returns an object
// {
//      currentCount: 1,
//      lastLoginDate: "11/10/2022",
//      startDate: "11/10/2022"
// }
```
