# @onix/config

Shared TypeScript presets for Onix projects.

## Install

```bash
npm i -D @onix/config
```

## Usage

Set `extends` in your `tsconfig.json`:

### Base

```json
{
  "extends": "@onix/config/tsconfig.base"
}
```

### React (Vite)

```json
{
  "extends": "@onix/config/tsconfig.reactjs"
}
```

### Next.js

```json
{
  "extends": "@onix/config/tsconfig.nextjs"
}
```

### Node.js

```json
{
  "extends": "@onix/config/tsconfig.node"
}
```

### NestJS

```json
{
  "extends": "@onix/config/tsconfig.nestjs"
}
```
