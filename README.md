# API Extractor Test

```bash
npm install
npm run build
api-extractor run
```

Result:

```
(Verbose) Writing: ...\api-extractor-react\dist\api-bug.api.json
(Verbose) The API signature is up to date: temp/api-bug.api.ts
(Verbose) The "mainDtsRollupPath" is: api.d.ts
Error: Program Bug: The symbol ReactNode is being imported after it was already registered as non-imported
```
