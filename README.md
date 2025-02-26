a simple wrapper for the try catch method in typescript

## Installation

```bash
npm install try-catch-wrapper-ts
```

## Usage

```ts
import { tryCatch } from "try-catch-wrapper-ts";

const { data, error } = await tryCatch(someFunction());
```