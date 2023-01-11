# Zirco TypeScript config

Usage in tsconfig (no Yarn Plug 'n Play support):

```json
{
    "extends": "./node_modules/@zirco-lang/ts-config/tsconfig.json",
    "include": ["./src/*", "./src/**/*"],
    "exclude": ["./node_modules/"]
}
```