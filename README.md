# PRATICE

## install tsc 
install ts to global 

ts instal link https://www.typescriptlang.org/download]

```bash
npm install typescript -g
```
check ts exist 
```bash
❯ tsc -v
Version 5.1.6 
```
generate tsc config

```bash
tsc --init

❯ tree
.
├── README.md
├── index.js
├── index.ts
└── tsconfig.json
```
## tsconfig

```json
{
  "rootDir": "./src",
  "outDir": "./dist",
  "allowJs": true,
   "sourceMap": true
}
```

設定完後的架構
```bash
❯ tree
.
├── README.md
├── dist
│   ├── index.js
│   └── index.js.map
├── src
│   └── index.ts
└── tsconfig.json

3 directories, 5 files
```