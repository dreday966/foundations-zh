## Test
```
npm install
npm run build
npm test
```
#### 测试 case 1 'Chrome type error test'
#### 测试 case 2 'Firefox type error test'
## Lint
```
npm install
npm run build
npm run format
```
## Format
```
npm install
npm run build
npm run format
```
## pre-commit
```
npm install
```
commit前会运行Format, Test, Lint。

## CI
./github/workflows/nodejs.yml 配置了github的CI Action。push会自动运行test lint。

## rxjs

AutocompleteController.ts是rxjs笔试的代码。

