This package only contains type declaration of locales for use in Node and JavaScript Intl methods.

## Example of use:

```typescript
import type { Locales } from 'locales-ts/types'

interface ExampleBeautifulInterface {
  locale: Locales
}
```

Fragment:

```typescript
export type Locales =
  | 'ar'
  | 'ar-AE'
  | 'ar-BH'
  | 'ar-DZ'
  ...
```

## Install

```
npm install locales-ts

```
