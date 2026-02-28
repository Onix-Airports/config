# @onixairports/config

Shared TypeScript presets for Onix projects.

## Install

```bash
npm i -D @onixairports/config
```

## Usage

Set `extends` in your `tsconfig.json`:

### Base

```json
{
  "extends": "@onixairports/config/tsconfig.base"
}
```

### React (Vite)

```json
{
  "extends": "@onixairports/config/tsconfig.reactjs"
}
```

### Next.js

```json
{
  "extends": "@onixairports/config/tsconfig.nextjs"
}
```

### Node.js

```json
{
  "extends": "@onixairports/config/tsconfig.node"
}
```

### NestJS

```json
{
  "extends": "@onixairports/config/tsconfig.nestjs"
}
```

## Automated releases

This package is configured with Semantic Release and GitHub Actions.

- Workflow: `.github/workflows/release.yml`
- Config: `.releaserc.json`
- Trigger: pushes to `main`

### Required GitHub secret

Create `NPM_TOKEN` in your repository secrets using an npm granular access token with publish permission for `@onixairports/config`.

### Conventional commits

Semantic Release uses commit messages to decide version bumps:

- `fix:` -> patch
- `feat:` -> minor
- `feat!:` or `BREAKING CHANGE:` -> major
```
