# Practice with TypeScript

## Prerequisites: 

NodeJS
TypeScript

## Start 

1. to compile file:
```
tsc app.ts
```
2. to watch 
```
tsc app.ts --watch
```
or
```
tsc app.ts -w
```


OR for every tsx file
Once
```
tsx --init
```
Then every time
```
tsx
```
```
tsx -w
```

If you want to exclude file from compiling:
in tsconfig.json add to "exclude": ["name of file"]