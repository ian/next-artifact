# next-artifact

Build-time artifact generation for Next.js + Vercel

## Inspiration

@todo

## Installation

### 1. Install the repository in your nextjs project:

`yarn add next-artifact`

### 2. Change your build command to include artifact cacheing

`package.json`

```

{
  "scripts": {
    "build": "next build && artifacts cache",
  }
}
```

### 3. Access your artifacts during runtime

@todo

`pages/api/endpoint.js`

```
import artifact from "next-artifact"

export default async (req, res) => {
  ...
}

```
